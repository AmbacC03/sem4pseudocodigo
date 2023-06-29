```
Algoritmo numeropar_oimpar
	Repetir
		Escribir "Escribe un numero entre 1 y 50"
		Leer cifra
		Si cifra < 1 | cifra > 50 Entonces
			Imprimir "Numero invalido"
		FinSi
	Mientras Que cifra < 1 | cifra > 50
	
	par = cifra % 2 = 0 
	
	Para contador=1 Hasta cifra Con Paso 1 Hacer
		Si contador % 2 = 0 & par Entonces
			Imprimir contador
		FinSi
		Si contador % 2 = 1 & ~(par) Entonces
			Imprimir contador
		FinSi
	FinPara
FinAlgoritmo
```
