# Double and triple of a value

## Solution 😎

```python
// Receives arg by value and return its double
Funcion res <- calculate_double(num)
	res <- num * 2
FinFuncion

// Receives arg by value and return its triple
Funcion res <- calculate_triple(num)
	res <- num * 3
FinFuncion

Algoritmo double_and_triple
	Definir new_number Como Real
	Escribir "Enter the number to calculate its double and triple: "
	Leer new_number
	Escribir "Calling function calculate_double(passed by value)"
	Escribir "Double of ", new_number," is ", calculate_double(new_number)
	Escribir "Calling function calculate_triple(passed by value)"
	Escribir "Triple of ", new_number," is ", calculate_triple(new_number)
FinAlgoritmo
```

## Video Solution 📹

<iframe width="560" height="315" src="https://www.youtube.com/embed/9cFT-74EFPQ" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
