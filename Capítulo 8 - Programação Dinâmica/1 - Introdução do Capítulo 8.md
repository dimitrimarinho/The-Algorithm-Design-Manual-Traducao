## Programação Dinâmica

Os problemas algorítmicos mais desafiadores envolvem a otimização, onde buscamos encontrar uma solução que maximize ou minimize alguma função. O vendedor viajante é um problema clássico de otimização, onde buscamos o caminho visitando todos os vértices de um grafo pelo custo total mínimo. Mas, como mostrado no Capítulo 1, é fácil propor "algoritmos" para resolver o TSP que geram soluções razoáveis, mas nem sempre estes algoritmos produzem o caminho de custo mínimo.

Algoritmos para problemas de otimização exigem prova de que eles sempre retornam a melhor solução possível. Algoritmos gulosos que tomam a melhor decisão local em cada etapa são tipicamente eficientes, mas geralmente não garantem a otimização global. Algoritmos de busca exaustiva que tentam todas as possibilidades e selecionam sempre as melhores produzem o melhor resultado, mas geralmente a um custo proibitivo em termos de complexidade de tempo.

A programação dinâmica combina o melhor dos dois mundos. Ela nos dá um jeito de projetar algoritmos personalizados que pesquisam sistematicamente todas as possibilidades (garantindo assim a correção) ao armazenar os resultados para evitar a recomputação (proporcionando assim eficiência). Ao armazenar as consequências de todas as decisões possíveis e usar esta informação de maneira sistemática, a quantidade total de trabalho é minimizada.

Uma vez que você tenha entendido, a programação dinâmica é provvelmente a técnica de projeto de algoritmo mais fácil de aplicar na prática. Na verdade, acho que os algoritmos de programação dinâmica são geralmente mais fáceis de reinventar do que tentar procurar em um livro. Dito isso, até você entender programação dinãmica, ela irá parecer como mágica. Você deve descobrir o truque antes de poder usá-lo.

A programação dinâmica é uma técnica para implementar eficientemente um algoritmo recursivo, armazenando resultados parciais. O truque é ver se o algoritmo recursivo ingênuo calcula os mesmos subproblemas repetidas vezes. Em caso afirmativo, armazenar a resposta para cada subproblema em uma tabela para procurar em vez de recalcular pode levar a um algoritmo eficiente. Comece com um algoritmo recursivo ou definição. Somente quando temos um algoritmo recursivo correto, nos preocupamos em acelerá-lo usando uma matriz de resultados.

A programação dinâmica é geralmente o método correto para problemas de otimização em objetos combinatórios que possuem uma ordem inerente da esquerda para direita entre os componentes. Os objetos da esquerda para direita incluem: cadeia de caracteres, árvores com raiz, polígonos, e sequências inteiras. A programação dinâmica é melhor aprendida estudando cuidadosamente os exemplos até que as coisas comecem a clicar. Apresentamos três histórias de guerra em que a programação dinâmica desempenhou o papel decisivo para demonstrar sua utilidade na prática.

# Nota da tradução

## Glossário

**TSP** - *Traveling Salesman Problem* ou Problema do Caixeiro Viajante (PCV) em português (PT-BR).

**Algoritmos de busca exaustiva** - Também conhecidos como Algoritmos de Força Bruta (*Brute Force Algorithm*)
