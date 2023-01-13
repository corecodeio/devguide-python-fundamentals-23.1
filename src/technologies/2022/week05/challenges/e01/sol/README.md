# Compare distances

## Solution 😎

```python
Funcion result <- compareDistances ()
	Definir result Como Logico;
	Definir negativeNumber, positiveNumber Como Real;
	negativeNumber = 0;
	positiveNumber = 0;
	Para count=1 Hasta 5 Con Paso 1 Hacer
		Escribir "write a number"
		leer num
		SI num > 0 Entonces
			positiveNumber = positiveNumber + num;
		SiNo
			negativeNumber = negativeNumber + num;
		FinSi
	FinPara
	result = positiveNumber > Abs(negativeNumber)
Fin Funcion

Algoritmo exampleCompareDistances
	Imprimir compareDistances()
FinAlgoritmo
```

## Video Solution 📹

[Compare distances](https://edpuzzle.com/assignments/63a2252460141141499cdee3/watch)
