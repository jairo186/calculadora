# calculadora
de  tabular  importar  tabular
esco  = { 1 : ( lambda  x , y : x  +  y ), 2 : ( lambda  x , y : x  *  y ), 3 : ( lambda  x , y : x  /  y ), 4 : ( lambda  x , y : x  -  y )}

es  = [ 'Soma' , 'Multiplicação' , 'Divisão' , 'Subtração' ]

opc  =  int ( input ( "" "Escolha uma opção.
[1] Soma
[2] Multiplicação
[3] Divisão
[4] Subtração
===============
"" " ))
imprimir ( '===' , es [ opc  -  1 ], '===' )

num1  =  int ( input ( 'Numero 1:' ))
num2  =  int ( input ( 'Numero 2:' ))

a  =  esco [ opc ]
res  =  a ( num1 , num2 )
imprimir ( f'Resultado = [[[ { res } ]]] ' )
