# Multiplication tables

## Solution 😎

```python
Algoritmo multiplicationTables
	Imprimir '======= Multiplication Tables ======='
	Imprimir 'Ingrese la tabla a calcular:'
	Leer tabla
	Imprimir '@ Tabla de ' + ConvertirATexto(tabla) + ' @'
	iterador <- 1 
	Mientras iterador <= 10 Hacer
		Imprimir ConvertirATexto(tabla) ' *  ' + ConvertirATexto(iterador) + ' = ' ConvertirATexto(tabla * iterador) 
		iterador <- iterador + 1
	Fin Mientras
FinAlgoritmo
```

## Video Solution 📹

<iframe width="560" height="315" src="https://www.youtube.com/embed/sflZBFlxWeg" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>