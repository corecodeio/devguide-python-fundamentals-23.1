# Greetings

## Solution 😎

```python
Algoritmo Greetings
	Imprimir '======= Greetings ======='
	Definir continuar Como Cadena
	Definir cantidadSaludos Como Entero
	cantidadSaludos <- 0
	continuar <- 'Si'
	Mientras continuar == 'Si' Hacer
		Imprimir 'Ingrese la hora actual (0-23):'
		Leer hora
		Si hora <= 12 Entonces
			Imprimir 'Buenas dias!'
		SiNo 
			Si hora <= 18 Entonces
				Imprimir 'Buenas tardes!'
			SiNo
				Imprimir 'Buenas noches!'
			Fin Si
		Fin Si

		cantidadSaludos <- cantidadSaludos + 1

		Imprimir 'Desea continuar ? Si/No'
		Leer continuar
	Fin Mientras

	Imprimir 'Cantidad de Saludos realizados: ' + ConvertirATexto(cantidadSaludos)
FinAlgoritmo
```

## Video Solution 📹

[Greetings](https://edpuzzle.com/assignments/638f74c3e1234e40e18f63ff/watch)
