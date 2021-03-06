# Evaluación de opciones americanas con LMS

La serie de precios del azucar, a partir de la cuale se calcula el precio de opciones américanas utilizando el método de Mínimos Cuadrados Montecarlo o LSM, acrónimo en inglés de Least Squares Montecarlo, fue obtenida del servicio Yahoo Finance  [Yahoo Finance](https://finance.yahoo.com/), el periodo de tiempo que abarca la serie corresponde al año 2020.

La evaluación de la opción parte de la simulación Montecarlo de un proceso Browniano de los precios del azúcar, tomando el precio final en 2020 y la variación durante ese año. Dicha simulación sirve para calcular escenarios de ganancias a obtener considerando el precio de ejercicio o *strike*.

Finalmente se construye una matriz de valor calculando la esperanza condicionada de la ganancia por mantener viva la opción en cada oportunidad de ejercicio a partir de una regresión polinomial por mínimos cuadrados.
