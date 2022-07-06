# hola-mundo
Mi primer repositorio en GitHub
SubProceso procesoUno(variable1 por Referencia)
	variable1 = variable1 + 5
	Escribir variable1
FinSubProceso
Proceso Por_Valor
	Definir num Como Entero
	num = 20
	procesoUno(num)
	Escribir "El valor de la variable num es: ", num
FinProceso
