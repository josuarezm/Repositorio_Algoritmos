## Información del Taller
***
Taller Algoritmos - Clase 9 
Integrantes:
	Camilo Andres Fierro Fierro
	Cristian Camilo Vargas Morales
	Fabian Leandro Lopez Gomez
	Isaac Zarate Reyes
	Jose Ignacio Suarez Montiel

##Descripición de Algoritmo
***

Se clonó el código que se encuentra en la siguiente dirección "Iterative searching in Binary Search Tree"
[[Wiki](https://www.geeksforgeeks.org/iterative-searching-binary-search-tree/)], 
y a partir de él, realizamos ciertas modificaciones para hacer aún más útil el código.

Se edito el código para crear el árbol a partir de las entradas de usuario:
	*Definir Raíz
	*Definir Cantidad de Nodos
	*Establecer los valores de los nodos.
	*Indicar búsqueda.

Además, el algoritmo es capaz de mostrar la ruta encontrada en el grafo ejemplo por medio de instrucciones de 
la posición en que se encuentra un nodo hijo respecto a su nodo padre.

Adicional, con la intención de representar el grafo y la ruta que se recorre al hacer una BST en el grafo, 
el algoritmo presenta una forma gráfica e intuitiva de visualizar el árbol almacenado acompañado una coloración 
por cada nodo que nos indica el recorrido al realizar una BST.

Se representa el árbol binario de forma horizontal, bajando niveles de izquierda a derecha; es decir, a la 
izquierda se encuentra el nodo raíz y nos vamos desplazando a la derecha a medida que vamos descendiendo en 
los respectivos niveles que posea el árbol binario.

	Blanco: Nodo NO visitado
	Amarillo: Nodo Visitado
	Verde: Nodo con Valor Buscado

En el caso en que no se encuentre el valor buscado dentro del árbol, no aparece ningún nodo de color verde.