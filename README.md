# lexical_analyser
Lexical_Analyser is a C-based compiler design project that performs lexical analysis on source code files by identifying and classifying tokens such as keywords, identifiers, operators, symbols, constants, strings, and special characters.  The project reads input source code and breaks it into meaningful lexical tokens.


The project reads input source code and breaks it into meaningful lexical tokens, helping in the initial phase of compiler construction.

## Features

- Detects and classifies:
  - Keywords
  - Identifiers
  - Operators
  - Symbols
  - Special Characters
  - Integer and Floating Constants
  - Binary, Octal, and Hexadecimal Numbers
  - String Literals
  - Character Literals
- Handles invalid tokens and lexical errors
- Simple and efficient token parsing
- File-based input processing

## Technologies Used

- C Programming
- File Handling
- String Manipulation
- Compiler Design Concepts

## Compilation

```bash
gcc analyser.c lexical_analyser.c -o lexer
