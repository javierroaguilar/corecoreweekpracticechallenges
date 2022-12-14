# core code week 4 practice challenges

## Extra exercise
 
 ``` python
 
 //Encuentra el promedio de 10 numeros usando For
  Algoritmo Promedio10Numeros
	Imprimir "Por favor ingrese los 10 numeros de los que desee operar"
	r=0
	Para x = 9 Hasta 0 con paso -1 Hacer
		Leer n
		r= r+n
		x=x
	FinPara
	Imprimir "El promedio es " (r)/10
  FinAlgoritmo
``` 

## Challenge 1 - Program for sales calculator

Make a program that asks how many sales the seller had, Once the number of sales is entered, ask for the value of each sale until all are entered, then return as a result the average value of sales, and the commission that the seller will take, If the seller had more than 5 sales, his commission will be 15% of the total value of the sales, if he sold 5 or less, his commission will be only 10%.

 ``` python
	Algoritmo ComisionDeVentas
	Imprimir "Por favor ingrese el número de ventas que realizó en el mes"
	Leer total
	Para ventas=1 Hasta total Hacer
		Imprimir "Ingrese el valor de la venta " ventas
		Leer n
		r = n + r
	FinPara
	Imprimir "El promedio de ventas es " r/total
	Si total <= 5 Entonces
		Imprimir "La comisión de venta para el vendedor es de " r * 0.1
	Sino 
		Imprimir "La comisión de venta para el vendedor es de " r * 0.15
	FinSi
	FinAlgoritmo
	
 ``` 
 
 ## Challenge 2 - Contador Par o Impar
 
 Request a number from 1 to 50, if the number is not between those values, report the error and request it again until you get a valid number, then it shows on the screen all the numbers from 1 to that number, if the number is even it only shows the even numbers, if it is odd it only shows the odd ones.

 ``` python
 
 	Algoritmo ContadorImparOPar
	Imprimir "Ingrese un número entre 1-50"
	Leer n
	Si n<1 y n>50
	Repetir
		Imprimir "Error! Ingrese un número entre 1-50"
		Leer n
	Hasta Que n>0 y n<51 
	SIno 
		Si n%2=0 Entonces
			Para x<-0 Hasta n Hacer
				Imprimir x
				x= x+1
			FinPara
		sino 
			Para x<-1 Hasta n Hacer
				Imprimir x
				x= x+1
			FinPara
		FinSi
		Finsi
	Imprimir "Fin de programa"
	FinAlgoritmo

```

## Challenge 3 - Imprimir nombre

``` python

	Algoritmo NombreEnMayuscula
	Imprimir "Ingrese un nombre"
	Leer nombre
	Imprimir "Ingrese un apellido"
	Leer apellido
	Imprimir Mayusculas(SubCadena(nombre,1,1)) Minusculas(SubCadena(Nombre,2,longitud(nombre))) " " Mayusculas(SubCadena(apellido,1,1)) 				Minusculas(SubCadena(apellido,2,longitud(apellido)))
	FinAlgoritmo
``` 

## Challenge 4 - tirar dados

``` python

	Algoritmo Dados
	Definir azar1 Como Entero
	Definir azar2 Como Entero
	Para x=1 hasta 10 Con paso 1 Hacer
		azar1 = aleatorio(1,6)
		azar2 = aleatorio(1,6)
		Si azar1 = azar2 Entonces
			Imprimir azar1 " " azar2 " Los dados son iguales"
		sino 
			Imprimir azar1 " " azar2
		FinSi
	FinPara
	FinAlgoritmo
``` 
