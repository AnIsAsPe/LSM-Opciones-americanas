# Evaluación de opciones americanas con LMS

El presente repositorio se refiere a un curso para evaluar opciones americanas utilizando el método de Mínimos Cuadrados Montecarlo o LSM, por sus siglas en inglés, impartido en colaboración con el [Colegio de Matemáticas Bourbaki](https://www.colegio-bourbaki.com/) 

La evaluación de la opción americana del azúcar, implementada en Python usando un notebook de Jupyter, comienza por la simulación Montecarlo de un proceso Browniano a partir del precio final de 2020 y la variación durante ese año. Los datos fueron obtenida del servicio Yahoo Finance  [Yahoo Finance](https://finance.yahoo.com/).

La simulación referida sirve para calcular escenarios de ganancias a obtener considerando el precio de ejercicio o *strike*.

Finalmente se construye una matriz de valor calculando la esperanza condicionada de la ganancia por mantener viva la opción en cada oportunidad de ejercicio a partir de una regresión polinomial por mínimos cuadrados.
