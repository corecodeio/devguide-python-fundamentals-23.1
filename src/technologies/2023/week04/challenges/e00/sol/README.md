# Ascending sort checker

## Solution 😎

```python
Algoritmo is_ascending_order
	Definir number,new_number Como Real;
	Definir is_sorted Como Logico;
	is_sorted = verdadero;
	number = 0;
	Mientras number>=0 Hacer
		Escribir 'Enter a new number';
		Leer new_number;
		Si new_number > 0 Entonces
			Si new_number<number Entonces
				is_sorted = falso;
			FinSi
		FinSi
		number = new_number;
	FinMientras
	Si is_sorted=verdadero Entonces
		Escribir 'The series is in ascending order';
	Sino
		Escribir 'The series is not in ascending order';
	FinSi
FinAlgoritmo
```

## Video Solution 📹

<iframe width="560" height="315" src="https://www.youtube.com/embed/i-Vc75vLso4" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
