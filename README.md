# desenvolve01.github.io
Análise de Dados de Crédito com Python (Google Colab)
Este projeto tem como objetivo realizar uma análise exploratória de dados (EDA) aplicada a informações de clientes, utilizando Python e bibliotecas como Pandas, NumPy e Matplotlib. A análise é executada no ambiente do Google Colab, com upload de uma planilha .xlsx contendo os dados originais.

Funcionalidades implementadas:
Importação e limpeza de dados:
Leitura de uma aba específica da planilha Excel, remoção de duplicatas e conversão de colunas para tipos numéricos adequados.
Criação de estruturas de dados úteis:
Listas, tuplas e dicionários para organizar informações como clientes únicos, pontuações e valores por departamento.

Classificação de risco de crédito:
Uma função condicional foi implementada para classificar os clientes em níveis de risco (Baixo, Médio, Alto e Desconhecido) com base na pontuação de crédito.
Cálculo de estatísticas com NumPy:
Média e desvio padrão das pontuações de crédito.
Agrupamentos e agregações com Pandas:
Cálculo da média de pontuação por departamento e contagem de status dos clientes.
Visualizações gráficas com Matplotlib:
Gráfico de barras: distribuição dos clientes por nível de risco.
Gráfico de linhas: evolução da pontuação dos clientes ao longo do tempo.
Gráfico de dispersão: relação entre pontuação de crédito e valor da dívida.
Requisitos
Google Colab (ou ambiente com suporte a Jupyter Notebooks)
Python 3.x
Bibliotecas: pandas, numpy, matplotlib, openpyxl (para leitura de Excel)


