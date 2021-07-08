# Basic-Plotting
Basic plotting using Matplotlib in Python

Primero, se muestra un conjunto de datos dimensional, almacenado en una sola variable con valores únicos.
Luego, esos valores fueron almacenado como una sola estructura de datos en una matriz NumPy.
También se sacaron columnas selectivamente para enviarlas a otras funciones. 

Además, se hizo uso de patches de la bibliotecha matplotlib para añadir superposiciones gráficas a los gráficos. Con la intención de mostrar más claramente las características estadísticas del conjunto de datos en el gráfico: mostramos la desviación estándar y la representamos con una elipse. De esta forma, el centro de la elipse es la media y el ancho y el alto, la desviación estándar. 

Utilizamos una lista de comprensión donde la función "dists" determina la distancia entre cada elemento en el dataset y la media. 

Estandarizamos usando el tipo de sintaxis Numpy con una formula simple y luego trazamos el gráfico nuevamente para que funcione con el conjunto de datos normalizado.

