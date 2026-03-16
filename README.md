# Arboles-ABB-y-B-
Sistema de gestion de 10000 estudiantes usando ABB y B+ arbol, ABB ofrece busquedas rapidas y listado jerarquico, mientras B+ garantiza el orden total y la eficiencia mediante hojas enlazadas. incluye una carga masiva aleatoria, es posible listar de 1000 en 1000 e ingresar un nuevo alumno 

En el arbol ABB
Su logica es con menores a la izquierda y mayores a la derecha por lo que se hizo con recursividad para buscar el vacio segun ID, en su busqueda es muy rapido porque en cada paso descartas la mitad del arbol, en su listado al usar la opcion 5 nos muestra en orden de profundidad lo que lo hace desordenado pero sigue la estructura

En el arbol B+

A diferencia del ABB, los datos reales estan en las hojas el balanceo a llegar al limite porque lo pusimos en orden 50, el arbol se rompe y crece hacia arriba solo manteniendose nivelado 

En su listado esta en el siguiente puntero, como todas las hojas estan conectadas. Es mucho mas facil seguirlo con una linea recta del id 0 al 10000 que lo hace mas eficiente en este caso para un listado en orden

Para ingresar los 10.000 estudiantes 

primero usamos random.shuffle en los ID antes de insertar para evitar que se haga una lista pesada y tenerlo siempre eficiente 

en su paginacion el sistema es el operador %1000 esto evita el truncado de python que al mostrarnos una lista con 10000 elementos muestre solo la mitad asi nos permite ir viendo de 1000 en 1000 y poder ver la lista completa.

Entonces, esto nos permite ver que las busquedas iondividuales ambas estructuras son muy buenas, pero para listados ordenados vimos la superioridad del arbol B+ gracias a su estructura de hojas enlazadas.
