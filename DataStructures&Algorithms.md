# Search Algorithms

## Prim's Algorithm

O algoritmo de Prim é um algoritmo guloso que encontra uma árvore geradora mínima para um grafo não direcionado ponderado. Isso significa que ele encontra um subconjunto de arestas que forma uma árvore abrangendo todos os vértices, de modo que o peso total de todas as arestas da árvore seja minimizado. O algoritmo opera construindo essa árvore um vértice de cada vez, a partir de um vértice inicial arbitrário, adicionando em cada passo a conexão de menor custo possível da árvore para outro vértice.

## Kruskal's Algorithm

O algoritmo de Kruskal é um procedimento popular na ciência da computação para encontrar árvores geradoras mínimas em um grafo, desenvolvido por Joseph Kruskal em 1956. O algoritmo funciona ordenando as arestas do grafo por seus pesos em ordem crescente. Em seguida, ele percorre cada aresta, adicionando-a à árvore geradora caso ela não forme um ciclo com as arestas já incluídas. Esse processo se repete até que todos os vértices do grafo estejam presentes na árvore. O algoritmo de Kruskal pertence à categoria dos algoritmos gulosos (*greedy algorithms*), pois busca encontrar o ótimo local em cada etapa, na expectativa de alcançar o ótimo global. Ele apresenta uma complexidade de tempo geral de O(E log E) ou O(E log V), em que E é o número de arestas e V é o número de vértices.

## Trie

Uma Trie — também chamada de árvore digital e, por vezes, de árvore de radix ou árvore de prefixos — é um tipo de árvore de busca utilizada para armazenar um conjunto dinâmico ou um array associativo, no qual as chaves são, geralmente, strings. Ao contrário das árvores de busca binária, nenhum nó da árvore armazena a chave a ele associada; em vez disso, sua posição na árvore define a chave com a qual está relacionado. Todos os descendentes de um determinado nó compartilham um prefixo comum da string associada a esse nó, e a raiz está associada à string vazia. Assim, uma Trie é uma forma de representar a recuperação (*retrieval*) de informações e constitui um tipo de estrutura de árvore empregada para essa finalidade. Cenários típicos de uso incluem o armazenamento de dicionários para texto preditivo ou preenchimento automático, como os encontrados em smartphones ou mecanismos de busca.
