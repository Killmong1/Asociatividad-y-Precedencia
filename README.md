Elkin Benitez y Jose Gonzales

adjuntamos los tres ejercicios de los diferetes tipos de gramaticas para realizar el calculo matematico de diferentes operaciones matematicas
teniendo en cuenta que son archivos bison y flex, se ejecutan de la siguiente manera:

-> bison -d calculadora.y
-> flex calculadora.l
-> gcc -o calculadora calculadora.tab.c lex.yy.c -lfl -lm
-> ./calculadora
