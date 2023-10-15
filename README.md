# Análise de Rede Social com Python e NetworkX

Este repositório contém um projeto de análise de uma rede social utilizando Python e a biblioteca NetworkX. O trabalho envolveu a importação de dados, criação de uma rede, cálculo de métricas de rede e a detecção de comunidades.

## Conteúdo

1. [Introdução](#introdução)
2. [Requisitos](#requisitos)
3. [Importação de Dados](#importação-de-dados)
4. [Descrição](#descrição)
5. [Resultados](#resultados)
6. [Conclusões Finais](#conclusões-finais)

## Introdução

Neste projeto, analisamos uma rede social a partir de um conjunto de dados que descrevem as conexões entre os usuários. O objetivo era explorar a estrutura da rede e identificar comunidades de usuários que compartilham interesses em comum.

## Requisitos

- Python 3.x
- Bibliotecas: NetworkX, Matplotlib, e Pandas

## Importação de Dados

Os dados da rede social foram importados a partir de um arquivo de texto no formato "nó1 nó2". O arquivo continha informações sobre as conexões entre os usuários.
A rede social escolhida foi a do Facebook, um database de tamanho pequeno, com 4039 nós e 88234 arestas.

## Descrição

Utilizei a biblioteca NetworkX para criar um grafo direcionado a partir dos dados importados. Cada nó no grafo representava um usuário, e as arestas representavam as conexões entre eles.
Realizei uma análise exploratória da rede para calcular métricas como grau de entrada, grau de saída, centralidade, densidade e outros. Isso nos forneceu informações sobre a estrutura da rede.
Fiz o uso de um algoritmo de detecção de comunidades para agrupar os usuários em comunidades com base nas conexões. Cada comunidade foi atribuída a uma cor única.

## Resultados

O resultado final inclui a visualização da rede com as comunidades destacadas por cores. Cada comunidade foi analisada para identificar interesses em comum entre os usuários.

##Conclusões Finais: 

Pegando como exemplo qualquer uma das comunidades que podem ser mostradas (0 - 15), 
Poderiamos criar um fluxo de informação de caracteristicas somente a essa comunidade que possuem caracteristicas em comum 
Seja: compras, pontos de interesses: politica, economia, esportes. .

Graças a uma simples analise de um grafo fornecido pela conectividade entre usuarios da rede facebook. 

Tentei executar diferentes formas de layout no grafo que escolhi do facebook, contudo aparentemente por ser um grafo muito grande ele fica de maneira borrada
Ou seja, os nós permanecem muito unidos. 
