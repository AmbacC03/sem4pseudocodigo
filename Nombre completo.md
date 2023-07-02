```
Algoritmo NombreCompleto
	Escribir "Ingrese un nombre"
	Leer nombre
	Escribir "Ingrese un apellido"
	Leer apellido
	
	p1Nombre = Subcadena(nombre,0,1)
	p2Nombre = Subcadena(nombre,2,Longitud(nombre))
	nombreFinal = Mayusculas(p1Nombre) + Minusculas(p2Nombre)
	Imprimir nombreFinal 
	
	p1Apellido = Subcadena(apellido,0,1)
	p2Apellido = Subcadena(apellido,2,Longitud(apellido))
	apellidoFinal = Mayusculas(p1Apellido) + Minusculas(p2Apellido)
	Imprimir apellidoFinal
	
FinAlgoritmo

```
