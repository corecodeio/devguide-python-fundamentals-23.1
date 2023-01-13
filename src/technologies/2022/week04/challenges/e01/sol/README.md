# Even or odd

## Solution 😎

```python
Algoritmo EvenOrOdd
	Repetir
		Escribir "write a number between 1 and 50"
		leer num
		SI  num < 1  | num > 50 Entonces
			Imprimir 'invalid number'
		FinSi
	Mientras Que num < 1  | num > 50
	
	par =  num % 2 = 0
	
	Para count=1 Hasta num Con Paso 1 Hacer
		SI count % 2 = 0 & par Entonces
			Imprimir count
		FinSi
		SI count % 2 = 1 & ~(par) Entonces
			Imprimir count
		FinSi
	FinPara
FinAlgoritmo
```

## Video Solution 📹

[Even or odd](https://edpuzzle.com/assignments/637d8f5676dec54118c42ce9/watch)
