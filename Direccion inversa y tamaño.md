```
	Funcion resultado <- Direccion_Inversay_Tamano (string)
		Definir resultado Como Caracter;
		resultado = " ";
		Para contar = Longitud(string) Hasta 0 Con Paso -1 Hacer
			carta = Subcadena(string,contar,contar);
			Si carta = Mayusculas(carta) Entonces
				carta = Minusculas(carta)
			SiNo
				carta = Mayusculas(carta)
			FinSi
			resultado = Concatenar(resultado, carta)
		FinPara
	Fin Funcion
	
	Algoritmo Inverso_direcciontamano
		Imprimir Direccion_Inversay_Tamano("aNgElicA")
FinAlgoritmo	
```
