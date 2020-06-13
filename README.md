# Compiler_Design
Implementation of C compiler.

Home/Project_code/Phase1/... 

AST, SYMBOL TABLE, ERROR HANDLING, INPUT VALIDATION, CODE OPTIMISATION,TOKENS

#Execution Steps
1. lex program.l
2. yacc -d program_test.y
3. gcc lex.yy.c y.tab.c -ll
4. ./a.out

#Result
1. Token.txt contains list of tokens
2. icode.txt contains the intermediate code
3. out.txt contains Symbol Table
4. tree.txt contains Abstract Syntax Tree in POSTORDER
5. program.c contains the user input c program
6. optimisedicode.txt contains optimisation of intermediate code

****************************************************************************************************************************
****************************************************************************************************************************


Home/Project_code/Phase2/...

icg.txt contains intermediate code

target.py contains code to convert intermediate code to target code
#Execution Steps
1. python3 target.py

#Result 
target code will be generated acc to risc architecture.
and can be displayed on the terminal

 
