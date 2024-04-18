# Resolução do Capítulo 9 - Noções de Simulação

Este repositório contém, em Python, a resolução do Capítulo 9 (Estatística Básica de Wilton O. Bussab e Pedro A. Morettin - 9. ed). O capítulo aborda as principais noções iniciais de simulação computacional para a geração de valores aleatórios.


![Monte Carlo simulation]('https://j.gifs.com/qQ7BNp.gif')

 
### Geração de Valores Pseudoaleatórios
A simulação computacional é uma ferramenta poderosa para compreender e prever o comportamento de sistemas complexos. Um dos pilares da simulação é a capacidade de gerar números aleatórios que sigam distribuições específicas. Esse tópico não é um tópico simples da programação por ter uma natureza divergente à computação tradicional. Enquanto a programação é, em essência, a definição de processos por meio de algoritmos, a geração de números aleatórios tem como pressuposto um processo não determinístico.

### Modelos de Distribuição a partir de uma Uniforme (0,1)
Um dos conceitos mais importantes na geração de valores pseudoaleatórios é o de que **qualquer variável aleatória pode ser gerada a partir de uma distribuição uniforme entre 0 e 1**. A função de **distribuição acumulada inversa** possui a propriedade de levar valores entre zero e um aos valores da **distribuição acumulada**. Ou seja, os valores de um modelo de distribuição qualquer são mapeados uniformemente entre zero e um. Dessa forma, pode-se produzir um valor pseudoaleatório de qualquer distribuição. Este é o princípio da transformação inversa.

### Como Contribuir
Sinta-se à vontade para abrir uma issue ou enviar um pull request de novas possíveis formas de resolução ou para reportar erros. Vamos fazer nossa comunidade estatística crescer.

Todas as contribuições são bem-vindas!
