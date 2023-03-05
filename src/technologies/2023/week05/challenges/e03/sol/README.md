# Mid point

## Solution 😎

```python
Funcion result <- midPoint (num1,num2)
	Si num1 > 0 Entonces
		Si num2 > 0 Entonces
			SI num1 > num2 Entonces
				result = num2 + ((num1 - num2) / 2); 
			SiNo
				result = num1 + ((num2 - num1) / 2);
			FinSi
		SiNo
			result = num1 - ( (num1 + Abs(num2))/2);
		FinSi
	SiNo
		SI num2 > 0 Entonces
			result = num1 + ( (num2 + Abs(num1))/2)	;
		SiNo
			SI Abs(num1) > Abs(num2) Entonces
				result = num1 + ((Abs(num1) - Abs(num2)) / 2); 
			SiNo
				result = num2 + ((Abs(num2) - Abs(num1)) / 2); 
			FinSi
		FinSi
	FinSi
	
Fin Funcion

Algoritmo exampleMidpPoint
	Imprimir midPoint(40,80)
	Imprimir midPoint(40,-80)
	Imprimir midPoint(50,50)
	Imprimir midPoint(-50,50)
FinAlgoritmo
```

## Video Solution 📹

[Mid point](https://edpuzzle.com/assignments/63a2256909d745415251605e/watch)
