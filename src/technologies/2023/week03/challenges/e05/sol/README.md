# Simple calculator Do While

## Solution 😎

```python
Algoritmo simpleCalcDoWhile
	Imprimir '======= Simple Calculator ======='
	Repetir 
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

		Imprimir 'Deseas continuar con otra operacion ? Si / No'
		Leer continuar
	Hasta Que continuar == 'No' | continuar == 'no'
FinAlgoritmo
```

## Video Solution 📹

<iframe width="560" height="315" src="https://www.youtube.com/embed/AmPr3TYy374" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
