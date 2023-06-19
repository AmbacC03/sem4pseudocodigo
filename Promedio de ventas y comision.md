```
Algoritmo Ventasycomisiones_promedio
	Imprimir "Ingrese el numero total de ventas: "
	Leer num_ventas
	ventacompleta = 0
	
	Para venta = 1 hasta num_ventas Con Paso 1 Hacer
		Escribir "Ingrese el valor de cada venta: ", venta
		Leer num_ventas
		ventacompleta = ventacompleta + num_ventas
	FinPara
	
	promedio = ventacompleta / num_ventas
	Imprimir "La venta promedio es: ", promedio
	
	Si num_ventas < 5 Entonces
		Imprimir "La comision de ventas recibida es: ", ventacompleta * 0.10
	SiNo
		Imprimir "La comision recibida por el vendedor es: ", ventacompleta * 0.15
	FinSi
FinAlgoritmo

```
