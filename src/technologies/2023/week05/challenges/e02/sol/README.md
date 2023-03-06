# Sum of pairs

## Solution 😎

```python
Funcion result <- sumOfPairs ()
	Definir result Como Real;
	Definir suma Como Real;
	suma = 0;
	Repetir
		Escribir "write a number between 1 and 100"
		leer num
		SI  num < 1  | num > 100 Entonces
			Imprimir 'invalid number'
		SiNo
			SI num % 2 = 0
				suma = suma + num;
			FinSi
		FinSi
	Mientras Que num >= 1  & num  <= 100
	result = suma;
Fin Funcion

Algoritmo exampleSumOfPairs
	Imprimir sumOfPairs()
FinAlgoritmo
```

## Video Solution 📹

[Sum of pairs](https://edpuzzle.com/assignments/63a22597c8c6a941310bf8ff/watch)
