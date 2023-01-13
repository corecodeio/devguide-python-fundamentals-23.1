# Average sales and commission

## Solution 😎

```python
Algoritmo averageSalesAndCommission
	Escribir "Write the total number of sales to enter:"
	leer amount_of_sales
	total_revenue = 0
	
	Para sale = 1 Hasta amount_of_sales Con Paso 1 Hacer
		Escribir "Write the value of the sale number: ",sale
		leer amount
		total_revenue = total_revenue + amount
	FinPara
	
	average = total_revenue / amount_of_sales 
	Imprimir 'The average sales is: ', average
	
	SI amount_of_sales < 5 Entonces
		Imprimir 'The commission received by the seller is: ', total_revenue * 0.10
	SiNo
		Imprimir 'The commission received by the seller is: ', total_revenue * 0.15
	FinSi
	
FinAlgoritmo
```

## Video Solution 📹

[Average sales and commission](https://edpuzzle.com/assignments/637d8f29f515dc413287dedc/watch)
