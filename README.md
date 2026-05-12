# KNN-MarketBasket

1. Extraiga la base de datos “wine-clustering.csv” y agréguela a un DataFrame en Python.

2. Mediante el algoritmo de K vecinos más cercanos determine el valor promedio de alcohol que tendrían los 5 vinos más parecidos a aquel con las características siguientes:

<img width="816" height="44" alt="image" src="https://github.com/user-attachments/assets/fb5e3369-aa5e-4dae-8a98-34b5ad45ef78" />

Asegúrese de detallar las concentraciones de alcohol de cada elemento que haya sido utilizado para obtener dicho valor promedio.

<img width="324" height="69" alt="image" src="https://github.com/user-attachments/assets/a2b5005e-b13e-4c53-aa9e-1e7a84edda75" />

4. Considere la lista de 11 compras desglosada de la manera siguiente:

<img width="543" height="202" alt="image" src="https://github.com/user-attachments/assets/8048724c-ef5f-4c78-a73f-dfc03a6d06c4" />

5. De acuerdo a la información anterior, se entiende que el primer ticket de compra de la lista consideró la adquisición de los siguientes productos:

bread   butter  wine  bananas  coffee  carrots

Modifica el código para que sea capaz de realizar un análisis mediante el algoritmo “Market basket” a dicha lista de compras con la finalidad de detectar patrones de consumo. Realice a continuación las conclusiones que sean pertinentes sobre sus resultados.

<img width="431" height="186" alt="image" src="https://github.com/user-attachments/assets/4bc341ec-0ec8-489d-803a-bf219990af8a" />

El análisis identificó conjuntos de productos que suelen comprarse juntos con frecuencia. 

Por ejemplo: El par {bread, butter} aparece de manera repetida en varias compras. El trío {beer, chips, milk} también aparece como combinación recurrente Las reglas con confidence > 0.7 y lift > 1 son las más relevantes, ya que indican relaciones más fuertes de compra conjunta. El análisis Market Basket permitió descubrir relaciones no triviales entre productos, revelando patrones de consumo que ayudan a entender mejor el comportamiento de compra. Estos resultados pueden ser utilizados para aumentar las ventas, mejorar la experiencia del cliente y diseñar estrategias de marketing más efectivas. 
