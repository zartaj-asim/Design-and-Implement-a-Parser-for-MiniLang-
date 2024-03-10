# Design-and-Implement-a-Parser-for-MiniLang-
This parser is designed to process and interpret the MiniLang programming language. 
MiniLang is a simple yet powerful language that supports basic arithmetic operations, variable assignments, if-else conditions, and print statements.

### Parser Type 
The parser is implemented as a top-down parser.

### Grammar Rules
The parser implements the grammar rules of MiniLang. Each rule corresponds to a specific construct in MiniLang, such as expressions, statements, and programs.

### Syntax Tree
The parser builds an abstract syntax tree (AST) representing the hierarchical structure of the source code. Each node in the tree corresponds to a language construct.


## Test Cases
- Case 1: Testing IF-Else Code
Tested the scanner's ability to tokenize a basic if-else code structure in MiniLang.
- Case 2: Testing != (not equal to) operator
Tested the scanner's handling of the != (not equal) operator within an if statement.
- Case 3: Testing Boolean Expression
Tested the scanner's ability to handle Boolean expressions within an if statement.
 
## Edge Cases
- Edge Case 1: Empty File
Input: An empty file.
- Edge Case 2: File with Only Whitespace
Input: File with only whitespace characters.
- Edge Case 3: File with Comments Only
Input: File with only comments.
- Edge Case 4: Long Identifier File
Input: File with a long identifier.
Identifier: a1234567890123456789012345678901234567890
Operator: =
Integer Literal: 42
 
