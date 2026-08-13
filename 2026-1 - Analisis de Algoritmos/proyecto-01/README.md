# Propagacion de Malware en un Servidor mediante Grafos

Proyecto de Analisis de Algoritmos que simula la propagacion de malware entre un servidor Linux y un cliente Windows mediante un grafo dirigido y ponderado.

## Descripcion

El grafo integra 50 nodos y 86 aristas. Sus pesos representan probabilidades sinteticas de propagacion y el puente SSH conecta los nodos de ambas computadoras.

## Algoritmos y tecnologias

* Dijkstra adaptado para maximizar la probabilidad acumulada.
* Bellman-Ford adaptado para el mismo problema de optimizacion.
* Python, NetworkX, Tkinter, Matplotlib, CSV, `timeit`, `tracemalloc` y `unittest`.
* Comparacion empirica de tiempo, memoria, estabilidad, probabilidad y longitud de ruta.

## Repositorio oficial

[ueesaalg/aalg_act2_2p_ord1_26_grupo3](https://github.com/ueesaalg/aalg_act2_2p_ord1_26_grupo3)
