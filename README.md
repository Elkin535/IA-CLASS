# IA-CLASS
trabajos elaborados en la clase de inteligencia artificial

Implementación de BFS y DFS en Python

Descripción
Este proyecto presenta la implementación de dos algoritmos fundamentales de búsqueda en grafos:
* BFS (Breadth First Search) – Búsqueda en anchura
* DFS (Depth First Search) – Búsqueda en profundidad

Ambos algoritmos permiten recorrer o explorar los nodos de un grafo siguiendo diferentes estrategias. Estos métodos son la base de muchos algoritmos más complejos utilizados en inteligencia artificial, redes, rutas de navegación y análisis de datos.
El proyecto fue desarrollado en Python utilizando Google Colab y posteriormente publicado en GitHub.

Objetivos del proyecto

* Implementar los algoritmos BFS y DFS en Python.
* Aplicarlos sobre un grafo pequeño representado mediante una estructura de datos.
* Comparar los resultados obtenidos entre ambos algoritmos.
* Analizar el camino recorrido y el uso de memoria de cada método.
----------------------------------------------------------------------------------------------------------------------------
1. Estructura del grafo
El grafo utilizado en el ejemplo está representado mediante un diccionario en Python:


//SE PUEDE VER EN EL REPOSITORIO COMO GRAFO VISUAL//

2. Representación en código:

grafo = {
    'A': ['B', 'C'],
    'B': ['D', 'E'],
    'C': ['F'],
    'D': [],
    'E': ['F'],
    'F': []
}
-----------------------------------------------------------------------------------------------------------------------------

Implementación de los algoritmos

* BFS (Breadth First Search)

El algoritmo BFS explora el grafo nivel por nivel, visitando primero todos los nodos vecinos antes de avanzar al siguiente nivel.
Utiliza una cola (Queue) para gestionar los nodos pendientes de explorar.

</> CODE PHYTON:
------------------
    from collections import deque

    def bfs(grafo, inicio):
        visitados = []
        cola = deque([inicio])
    
    while cola:
        nodo = cola.popleft()

        if nodo not in visitados:
            visitados.append(nodo)
            cola.extend(grafo[nodo])

    return visitados
--------------------

* DFS (Depth First Search)

El algoritmo DFS explora el grafo profundizando lo más posible antes de retroceder.
Normalmente se implementa utilizando recursión o una pila (Stack).

</> CODE PHYTON
---------------------------
    def dfs(grafo, inicio, visitados=None):
        if visitados is None:
            visitados = []

    visitados.append(inicio)

    for vecino in grafo[inicio]:
        if vecino not in visitados:
            dfs(grafo, vecino, visitados)

    return visitados
--------------------------

* Ejecución del programa
print("Recorrido BFS:", bfs(grafo, 'A'))
print("Recorrido DFS:", dfs(grafo, 'A'))

Resultado esperado

Recorrido BFS: ['A', 'B', 'C', 'D', 'E', 'F']
Recorrido DFS: ['A', 'B', 'D', 'E', 'F', 'C']

al ejecutar el codigo deberia de mostrar este resultado de como es el recorrido el grafo en BFS y DFS.

MUCHAS GRACIAS <3
