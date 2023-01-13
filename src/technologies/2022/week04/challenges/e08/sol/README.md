# Total price

## Solution 😎

```python
Funcion value <- TotalPrice (price, iva)
	Definir value Como Real;
	SI price > 3000 Entonces
		value = ( price + (price/100*iva) ) / 100*90
	SiNo
		value = ( price + (price/100*iva) )
	FinSi
Fin Funcion

Algoritmo example_TotalPrice
	Imprimir TotalPrice(5000,21)
FinAlgoritmo
```

## Video Solution 📹

[Total price](https://edpuzzle.com/assignments/637d8fbd4e8ff840ff1a64bb/watch)
