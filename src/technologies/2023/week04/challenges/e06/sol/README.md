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

[Factorial](https://drive.google.com/file/d/1YSAJLK5XI-_OW9eKeeb7b32DnUqhkiIC/view?usp=share_link)
