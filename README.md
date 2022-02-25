# C-parser

In this project, I developed concise context-free grammar for the C language. Given the C
program, the parser will try to check if the program follows the rules or not. In other words, it
checks for the syntactic correctness of the given C program. I used Lark parser in Python
to tokenise and parse the given code. The lark parser reads the grammar in EBNF (Extended
Backus-Naur Form) and provides us with the freedom to choose from a varied range of
parsing algorithms like CYK, Earley, LALR and so on to parse the code and generate its
respective parse-tree / Abstract Syntax Tree (AST).
