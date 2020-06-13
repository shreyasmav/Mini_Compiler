# Compiler_Design
Implementation of C compiler.

Home/Project_code/Phase1/... 

AST, SYMBOL TABLE, ERROR HANDLING, INPUT VALIDATION, CODE OPTIMISATION,TOKENS

#Execution Steps
lex program.l
yacc -d program_test.y
gcc lex.yy.c y.tab.c -ll
./a.out

#Result
Token.txt contains list of tokens
icode.txt contains the intermediate code
out.txt contains Symbol Table
tree.txt contains Abstract Syntax Tree in POSTORDER
program.c contains the user input c program
optimisedicode.txt contains optimisation of intermediate code

******************************************************************************************************************************
******************************************************************************************************************************


Home/Project_code/Phase2/...

icg.txt contains intermediate code

target.py contains code to convert intermediate code to target code
#Execution Steps
python3 target.py

#Result 
target code will be generated acc to risc architecture.
and can be displayed on the terminal

 
