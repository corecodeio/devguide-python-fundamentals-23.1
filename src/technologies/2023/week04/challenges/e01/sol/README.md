# Count numbers by range

## Solution 😎

```python
Algoritmo count_numbers_by_range
	Definir input_quantity, negative_numbers_count, greater_than_sixty_count Como Entero;
	Definir range_0_numbers_count Como Entero;
	Definir X Como Real;
	negative_numbers_count = 0;
	greater_than_sixty_count = 0;
	range_0_numbers_count = 0;
	
	Escribir 'Enter the series of numbers to count (10) below...';
	Para input_quantity=1 Hasta 10 Hacer
		Leer X;
		Si X<0 Entonces
			negative_numbers_count = negative_numbers_count+1;
		FinSi
		Si X>60 Entonces
			greater_than_sixty_count = greater_than_sixty_count+1;
		FinSi
		Si X>=30 Y X<=50 Entonces
			range_0_numbers_count = range_0_numbers_count+1;
		FinSi
	FinPara
	Escribir 'Negative numbers: ', negative_numbers_count;
	Escribir 'Numbers > 60: ', greater_than_sixty_count;
	Escribir 'Numbers between 30 - 50: ', range_0_numbers_count;
FinAlgoritmo
```

## Video Solution 📹

[Count numbers by range](TODO: Video here)
