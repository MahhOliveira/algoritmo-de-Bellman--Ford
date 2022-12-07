# algoritmo-de-Bellman--Ford
é um algoritmo de busca de caminho mínimo em um dígrafo ponderado, ou seja, cujas arestas tem peso, inclusive negarivo.O algoritmo de Dijkstra resolve o mesmo problema, em um tempo menor, porém exige que todas as arestas tenham pesos positivos . Portanto, o algoritmo de Bellman - Ford é normalmente usado apenas quando existem arestas de peso negativo.
O algoritmo de Bellman - Ford executa em tempo O(V X E) onde V é o número de vértices e E o número de arestas.

Pseudocódigo - Assim como o algoritmo de Dijkstra, o algoritmo de Bellman - Ford utiliza a técnica de relaxamento, ou seja, realiza sucessivas aproximações das distancias até finalmente chegar na solução. A principal diferença entre Dijkstra é utilizada uma fila de prioridades para selecionar os vértices a serem relaxados , enquanto o algoritmo de Bellman - Ford simplesmente relaxa todas as arestas.
