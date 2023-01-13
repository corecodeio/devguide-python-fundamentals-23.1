# Simple calculator

## Solution 😎

```python
Algoritmo simpleCalc
	Imprimir '======= Simple Calculator ======='
	Imprimir 'Ingrese primer numero'
	Leer n1
	Imprimir 'Ingrese segundo numero'
	Leer n2
	Imprimir 'Ingrese una operación: +,-,*,/'
	Leer op
	Si op == '+' | op == '-' | op == '*' | op == '/' Entonces
		Imprimir 'Procesando: ' + ConvertirATexto(n1) + ' ' + op + ' ' + ConvertirATexto(n2)
		Si op == '+' Entonces
			Imprimir 'Resultado: ' + ConvertirATexto(n1 + n2)
		SiNo
			Si op == '-' Entonces
				Imprimir 'Resultado: ' + ConvertirATexto(n1 - n2)
			SiNo
				Si op == '*' Entonces
					Imprimir 'Resultado: ' + ConvertirATexto(n1 * n2)
				SiNo
					Imprimir  'Resultado: ' + ConvertirATexto(n1 / n2)
				FinSi
			FinSi
		FinSi
	SiNo
		Imprimir '⚠️ La operación no es valida'
	FinSi
FinAlgoritmo
```

## Video Solution 📹

[Simple calculator](https://edpuzzle.com/assignments/637c55ea8a59d7410fb361d7/watch)
