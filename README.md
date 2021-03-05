# Input and Output

## Input / Output Operation
-------------------------------
When we say **Input**, it means to feed some data into a program. An input can be given in the form of a file or from the command line. C programming provides a set of built-in functions to read the given input and feed it to the program as per requirement.

When we say **Output**, it means to display some data on screen, printer, or in any file. C programming provides a set of built-in functions to output the data on the computer screen as well as to save it in text or binary files.

C language provide us console input/output functions. As the name says, the console input/output functions allow us to -
* Read the input from the keyboard by the user accessing the console.
* Display the output to the user at the console.

>Note : These input and output values could be of any primitive data type.

There are two kinds of console input/output functions -
* Formatted input/output functions.
* Unformatted input/output functions.

## Formatted I/O
------------------------- 
Formatted console input/output functions are used to take one or more inputs from the user at console and it also allows us to display one or multiple values in the output to the user at the console.

Some of the most important formatted console input/output functions are:

|Functions    |                                    Description                                                  |
|:-----------:|-------------------------------------------------------------------------------------------------|
|``scanf()``  |This function is used to read one or multiple inputs from the user at the console.               |
|``printf()`` |This function is used to display one or multiple values in the output to the user at the console.|

## Unformatted I/O
---------------------------
Unformatted console input/output functions are used to read a single input from the user at console and it also allows us to display the value in the output to the user at the console.


Some of the most important formatted console input/output functions are:

|Functions    |                                                Description                                                                |
|:-----------:|---------------------------------------------------------------------------------------------------------------------------|
|``getch()``  |Reads a single character from the user at the console, without echoing it.                                                 |
|``getche()`` |Reads a single character from the user at the console, and echoing it.                                                     |
|``getchar()``|Reads a single character from the user at the console, and echoing it, but needs an ``Enter`` key to be pressed at the end.|
|``gets()``   |Reads a single string entered by the user at the console.                                                                  |
|``puts()``   |Displays a single string's value at the console.                                                                           |
|``putch()``  |Displays a single character value at the console.                                                                          |
|``putchar()``|Displays a single character value at the console.                                                                          |



