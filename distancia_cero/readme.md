Algoritmo distanceToZero

	Escribir "write a number"
	leer maxDistance
	Para count=1 Hasta 4 Con Paso 1 Hacer
		Escribir "write a number"
		leer num
		SI Abs(num) > Abs(maxDistance) Entonces
			maxDistance = num
		FinSi
	FinPara
	Imprimir Trunc(maxDistance)
FinAlgoritmo
