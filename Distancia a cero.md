```
Algoritmo Distancia_Cero
	
	Escribir "Escribe un numero"
	Leer MaximaDistancia
	
	Para contador = 1 Hasta 3 Con Paso 1 Hacer
		Escribir "Escribe un numero"
		Leer numero
		Si abs(numero) >abs(MaximaDistancia) Entonces
			MaximaDistancia = numero
		FinSi
	FinPara
	Imprimir Mayusculas("El numero mas lejos de cero es: ")
	Imprimir trunc(MaximaDistancia)
FinAlgoritmo

```
