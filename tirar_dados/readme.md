Algoritmo throwDice

	Definir dice1, dice2 Como Entero
	Para count = 1 Hasta 10 Con Paso 1 Hacer
		dice1 = Aleatorio(1,6)
		dice2 = Aleatorio(1,6)
		SI dice1 = dice2 Entonces
			Imprimir dice1, " ", dice2, " the dice are the same"
		SiNo
			Imprimir dice1, " ", dice2
		FinSi
	FinPara
FinAlgoritmo
