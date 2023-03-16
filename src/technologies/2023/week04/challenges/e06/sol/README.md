# Factorial (recursive)

## Solution 😎

```python
Funcion fact <- calculate_factorial(num)
	Definir fact Como Entero;
	Si num=1 Entonces
		fact <- 1;
	SiNo
		fact <- num * calculate_factorial(num-1);
	FinSi
FinFuncion

Algoritmo factorial
	Definir limit Como Entero;
	Escribir Sin Saltar "Factorial number to calculate:";
	Leer limit;
	Escribir "Factorial value is: ", calculate_factorial(limit);
FinAlgoritmo

```

## Video Solution 📹

<iframe width="560" height="315" src="https://www.youtube.com/embed/q6ZhWblyeaw" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
