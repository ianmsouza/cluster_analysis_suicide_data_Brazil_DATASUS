# Projeto da disciplina de validação de modelos de clusterização - 24E4_3

## Índice
- [Sobre](#sobre)
- [Pré-requisitos](#pré-requisitos)
- [Objetivo](#objetivo)

## Sobre
Validação de modelos de clusterização em dados de suicídio no Brasil (2014 a 2018 do DATASUS). Utilizando KMeans, DBScan e medidas de similaridade.

## Pré-requisitos
Lista de pré-requisitos necessários para rodar o projeto:
- [Conda](https://www.anaconda.com/download)
- [Git](https://git-scm.com/downloads)
- [VsCode](https://code.visualstudio.com/download)
- Jupyter Notebook v7.0.8
- Python v3.12.4
- Anaconda v24.9.2 (Ambiente virtual chamado "infnet-24E4-2")

## Objetivo
Este projeto tem como objetivo analisar e agrupar dados de mortalidade por suicídio no Brasil entre 2014 e 2018, utilizando técnicas de clusterização para identificar padrões e tendências. O trabalho é dividido em quatro partes principais, descritas a seguir:

1. **Infraestrutura:** Configuração de ambiente Python local em Jupyter Notebook com dependências específicas registradas em um arquivo requirements.txt, garantindo reprodutibilidade do código.
2. **Escolha e preparação da Base de Dados:** Seleção e análise exploratória dos dados, visualização gráfica das variáveis, identificação da faixa dinâmica das dimensões e aplicação de técnicas de pré-processamento, como limpeza e normalização dos dados.
3. **Aplicação de Algoritmos de Clusterização:** Utilizar os algoritmos de K-Médias e DBScan para realizar o agrupamento dos dados. Determinar o número ótimo de clusters com base no índice de silhueta e outras métricas de validação. Comparar os resultados entre os dois algoritmos, destacando suas vantagens e limitações.
4. **Exploração de Medidas de Similaridade:** Investigar estratégias para medir a similaridade entre séries temporais, como correlação cruzada e Distância Dinâmica de Tempo (DTW). Indicar algoritmos apropriados para o agrupamento dessas séries e apresentar um caso de uso prático para a solução projetada.

Este trabalho visa aplicar técnicas de aprendizado não supervisionado para gerar insights sobre o desenvolvimento global e auxiliar em decisões estratégicas de alocação de recursos.
