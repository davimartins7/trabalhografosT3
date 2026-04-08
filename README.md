# Eulerização de Dígrafos Ponderados - Padrão ALGS4

## Descrição do Projeto

Este trabalho apresenta a análise e eulerização de um **dígrafo ponderado**, utilizando os conceitos de **Caminho Euleriano** e **Ciclo Euleriano**.  

O objetivo principal foi identificar vértices desbalanceados em um grafo direcionado e aplicar um processo de **balanceamento das arestas**, permitindo a construção de um **circuito euleriano**, onde cada aresta é percorrida exatamente uma vez e o percurso retorna ao vértice inicial.

Toda a implementação segue o **padrão da biblioteca ALGS4**, amplamente utilizada no estudo de **Algoritmos e Estruturas de Dados**, garantindo organização, clareza e aderência às boas práticas acadêmicas.

---

## Conceitos Utilizados

- Grafos direcionados (Dígrafos)
- Grafos ponderados
- Grau de entrada e saída
- Caminho Euleriano
- Ciclo Euleriano
- Eulerização de grafos
- Balanceamento de vértices

---

## Problema Inicial

O grafo analisado inicialmente **não era euleriano**, pois possuía **quatro vértices desbalanceados**, impossibilitando a existência de um caminho ou ciclo euleriano.

Foi realizada a análise do **grau de entrada e saída de cada vértice**, identificando:

- vértices com **excesso de saída**
- vértices com **excesso de entrada**

---

## Solução Aplicada

Para resolver o problema, foi aplicado um processo de **eulerização**, que consiste em:

- adicionar novas arestas no grafo
- respeitar as direções
- considerar os pesos das arestas
- priorizar os caminhos de menor custo

Após o balanceamento das arestas, todos os vértices passaram a possuir:
grau de entrada = grau de saída


Com isso, o grafo passou a possuir um **Ciclo Euleriano válido**.

---

## Resultado

Após a eulerização:

- Todos os vértices ficaram balanceados
- Foi possível identificar um **Circuito Euleriano**
- Cada aresta pode ser percorrida **uma única vez**
- O percurso **retorna ao vértice inicial**

---

## Estrutura Utilizada

O trabalho foi desenvolvido seguindo o **padrão estrutural da biblioteca ALGS4**, incluindo:

- representação do grafo por **lista de adjacência**
- organização modular do código
- manipulação de arestas ponderadas
- análise de graus de vértices

Esse padrão é amplamente utilizado no ensino de **Algoritmos e Estruturas de Dados**, especialmente em cursos de Ciência da Computação e Engenharia de Software.

---

## Vídeo Explicativo

No vídeo abaixo é apresentada a explicação completa do trabalho, incluindo:

- análise do grafo inicial
- identificação dos vértices desbalanceados
- processo de eulerização
- resultado final

▶ **Link do vídeo:**  
https://youtu.be/IEgA7YTl6zc

---

## Autor
Grupo C: 
Davi Martins 
Paulo Afonso 
Isaac Coelho 

Trabalho acadêmico desenvolvido para a disciplina de **Grafos**, utilizando o padrão **ALGS4** para implementação e análise de grafos.
