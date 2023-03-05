# Time Converter

## Solution 😎

```python
Funcion result <- timeConverter (number)
	Definir result Como Caracter;
	Definir days, hours, minutes, seconds Como Entero;
	seconds = number % 60;
	minutes = Trunc(number/60) % 60;
	hours = Trunc(number/3600) % 24;
	days = Trunc(number/86400);
	result = Concatenar('days: ', ConvertirATexto(days));
	result = Concatenar(result, ', hours: ');
	result = Concatenar(result, ConvertirATexto(hours));
	result = Concatenar(result, ', minutes: ');
	result = Concatenar(result, ConvertirATexto(minutes));
	result = Concatenar(result, ', and seconds: ');
	result = Concatenar(result, ConvertirATexto(seconds));
Fin Funcion

Algoritmo exampleTimeConverter
	Imprimir timeConverter(100000)
FinAlgoritmo
```

## Video Solution 📹

[Time Converter](https://edpuzzle.com/assignments/63a224ccc18444413606c5bf/watch)
