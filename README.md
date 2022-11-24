# 0x11. C - printf

## Description

This printf project is a collaboration between Samuel Adebayo and Gerald Juwah. Who are Software Engineers studing at students of ALX school. This project involves a function named "\_printf" which would imitate the actual "printf" command located in the stdio.h library. This function contains some of the basic features and functions found in the man 3 of "printf".

What you would learn from this project:

- How to use git in a team setting
- Applying variadic functions to big projects
- The complexities of printf
- Managing a lot of flies and finding a good workflow

## Prototype

    int _printf(const char *format, ...);

## Usage

- Prints a string to the standard output, according to a given format
- All files were created and compiled on Ubuntu 14.04.4 LTS using GCC 4.8.4 with the command `gcc -Wall -Werror -Wextra pedantic *.c`
- Returns the number of characters in the output string on success, -1 otherwise
- Call it this way: `_printf("format string", arguments...)` where `format string` can contain conversion specifiers and flags, along with regular characters.
