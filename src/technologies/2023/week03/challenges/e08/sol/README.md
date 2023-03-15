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

<iframe width="560" height="315" src="https://www.youtube.com/embed/L88RkxCNp7I" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
