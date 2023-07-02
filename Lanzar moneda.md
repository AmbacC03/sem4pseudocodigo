```
Algoritmo Lanzarmoneda
	
	Imprimir "--LANZAMIENTO DE MONEDA--"
	Escribir "Ingrese el primer nombre del jugador"
	Leer jugador1
	Escribir "Ingrese cuántas veces desea jugar"
	leer cantidad1
	Escribir "Ingresa el nombre del segundo jugador"
	leer jugador2
	Escribir "Ingresa la cantidad a jugar"
	leer cantidad2
	
	Si cantidad1 <= 0 | cantidad2 <= 0 Entonces
		Si cantidad1<= 0 & cantidad2 <= 0 Entonces
			Imprimir "Juego cancelado"
		SiNo
			Si cantidad1 <= 0 Entonces
				Imprimir "Jugador que gana: ", Mayusculas(jugador2), " cantidad ganada: 0"
			SiNo
				Imprimir "Jugador que gana: ", Mayusculas(jugador1), " cantidad ganada: 0"
			FinSi
		FinSi
	SiNo
		Si Aleatorio(1,2) = 1 Entonces
			Imprimir "Jugador que gana: ", Mayusculas(jugador1), " cantidad ganada: ", cantidad2
		SiNo
			Imprimir "Jugador que gana: ", Mayusculas(jugador2), " cantidad ganada: ", cantidad1
		FinSi
	FinSi
	
FinAlgoritmo
```
