# Weather average

## Solution 😎

```python
Funcion celsius <- fahrenheitToCelsius (fahrenheit)
	Definir celsius Como Real;
	celsius = (fahrenheit - 32 ) / 1.8
Fin Funcion

Algoritmo exampleWeatherAverage
	count = 0;
	total = 0;
	Repetir
		Imprimir "select an option:";
		Imprimir "a. enter degrees celsius.";
		Imprimir "b. enter degrees fahrenheit.";
		Imprimir "x. go out.";
		leer option
		Si option = "a" | option = "b" Entonces
			leer degree
			count = count + 1;
		FinSi
		Si option = 'a' Entonces
			total = total + degree;
		FinSi
		Si option = 'b' Entonces
			total = total + fahrenheitToCelsius(degree);
		FinSi
	Mientras Que option = "a" | option = "b"
	Imprimir total / count;
FinAlgoritmo
```

## Video Solution 📹

[Weather average](https://edpuzzle.com/assignments/63a2260dc106be4132bd365a/watch)
