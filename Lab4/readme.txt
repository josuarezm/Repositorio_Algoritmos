## Tabla de Contenido
1. [Información del proyecto]
2. [Cálculo de complejidad]

## Información del proyecto
***
Laboratorio 4
Algoritmos
Integrantes:
	Camilo Andres Fierro Fierro
	Cristian Camilo Vargas Morales
	Fabian Leandro Lopez Gomez
	Isaac Zarate Reyes
	Jose Ignacio Suarez Montiel


## Cálculo de complejidad
***
Para algoritmo de fuerza bruta:

# El algoritmo presenta una complejidad de O(n^2) (orden dado para el peor de los casos teniendo en cuenta que el while no solo recorre una si no dos variables ‘x’ y ‘y’)
x=-1000  #O(1) 
def brute_force(x):
    while x <= 1000:   #O(n) ->  orden para bucle  (iteración de x)
        y=(x**5 - 59*(x**4) + 35*(x**3) - 250*(x**2) + x - 70)  #O(n) -> orden para bucle (iteración de y)
        if y >= -40 and y<= 40:   #O(1) -> orden para condicional                                   
            print("la raiz es: {0:.6f}".format(x))
            return           
        x+=0.00001    
brute_force(x)           


Para el algoritmo voraz:

Debido al analisis del comportamiento del arbol de recursión se llega a la conclusión de que el  comportamiento es de orden O(N(log(N))
