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
