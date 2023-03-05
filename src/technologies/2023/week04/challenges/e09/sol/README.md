# Reverse direction and size

## Solution 😎

```python
Funcion result <- ReverseDirectionAndSize (string)
	Definir result Como Caracter;
	result = "";
	Para count = Longitud(string) Hasta 0 Con Paso -1 Hacer
		letter = Subcadena(string,count,count);
		SI letter = Mayusculas(letter) Entonces
			letter = Minusculas(letter)
		SiNo
			letter = Mayusculas(letter)
		FinSi
		result = Concatenar(result, letter)
	FinPara
Fin Funcion

Algoritmo example_ReverseDirectionAndSize
	Imprimir ReverseDirectionAndSize("Hello")
FinAlgoritmo
```

## Video Solution 📹

[Reverse direction and size](https://edpuzzle.com/assignments/637ff1e7512ac4415e8b643b/watch)
