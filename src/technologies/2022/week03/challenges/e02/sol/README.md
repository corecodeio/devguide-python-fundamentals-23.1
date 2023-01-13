# Simple calculator

## Solution 😎

```python
Algoritmo simpleCalcSegun
	Imprimir '======= Simple Calculator ======='
	Imprimir 'Ingrese primer numero'
	Leer n1
	Imprimir 'Ingrese segundo numero'
	Leer n2
	Imprimir 'Ingrese una operación: +,-,*,/'
	Leer op
	Si op == '+' | op == '-' | op == '*' | op == '/' Entonces
		Imprimir 'Procesando: ' + ConvertirATexto(n1) + ' ' + op + ' ' + ConvertirATexto(n2)
		Segun op Hacer
			'+':
				Imprimir 'Resultado: ' + ConvertirATexto(n1 + n2)
			'-':
				Imprimir 'Resultado: ' + ConvertirATexto(n1 - n2)
			'*':
				Imprimir 'Resultado: ' + ConvertirATexto(n1 * n2)
			'/':
				Imprimir 'Resultado: ' + ConvertirATexto(n1 / n2)
		Fin Segun
	SiNo
		Imprimir '⚠️ La operación no es valida'
	FinSi
FinAlgoritmo
```

## Video Solution 📹

[Simple calculator](TBA)
