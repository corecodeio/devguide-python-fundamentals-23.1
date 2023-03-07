# Vowel counter

## Solution 😎

```python
Funcion res <- vowel_counter(text)
	Definir text_length Como Entero
	text_length = Longitud(text)
	
	Para i=0 Hasta text_length Hacer
		Segun Subcadena(text, i, i) Hacer
				"a", "e", "i", "o", "u":
					res = res + 1
		FinSegun
	FinPara
FinFuncion

Proceso vowel_counter_process
	Definir count Como Entero
	Definir text Como Caracter
	Escribir "Enter the text to count its vowels: "
	Leer text
	count = vowel_counter(text)
	Escribir "Vowels in passed text: ", count
FinProceso
```

## Video Solution 📹

[Vowel counter](https://drive.google.com/file/d/1x2ySkSQsGC4_PXPVPZhX3p1j_gqbvNAj/view?usp=share_link)
