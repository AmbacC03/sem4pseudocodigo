```
Funcion monto <- CostoTotal(precio, IVA)
	
	Definir monto Como Real;
	Imprimir "Ingrese cantidad"
	Leer cantidad
	Si cantidad > 3000 Entonces
		monto = (cantidad + (cantidad/100* IVA) ) / 100*90
	SiNo
		monto = (cantidad + (cantidad/100*IVA) )
	FinSi
Fin Funcion

Algoritmo Preciototal
	Imprimir CostoTotal(5000,21)
FinAlgoritmo
```
