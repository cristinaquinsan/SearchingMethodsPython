# SearchingMethodsPython
Se ha implementado dos colas, la primera myQueue y heuristicsQueue. 

myQueue se programó de manera de que se pueda hacer una búsqueda por ramificación y acotación, usando el path_cost para encontrar la ruta hasta el punto final con el camino más corto en distancia.
heuristicsQueue se programó de manera que se pueda hacer una búsqueda por ramificación y acotación por subestimación, por lo que necesitabamos obtener la heurística de cada punto respecto al final, sumándoselo al path_cost para encontrar la ruta óptima.

La diferencia entre B&B y B&B con subestimación es que gracias a la heurística del B&B con subestimación, encontramos el camino más rápido y sin tener que estar visitando tantos nodos como se haría en el B&B.
