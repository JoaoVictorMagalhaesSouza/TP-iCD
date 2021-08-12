# **Relatório de Desenvolvimento do Trabalho Prático - Parte 1:**

## Obtenção dos Bancos de Dados:
#### Para obter os conjuntos de dados relacionados à informações da COVID-19 no Brasil, utilizamos dados fornecidos pela [brasil.io](https://brasil.io/dataset/covid19/files/), contendo um compilado diário informações das Secretarias Estaduais de Saúde. Entretanto, reduzimos esse conjunto de dados apenas às cidades de Minas Gerais com o propósito de dar um enfoque maior e produzir análises centradas nas macrorregiões de Minas Gerais.

#### Relativo aos dados da vacinação no estado de Minas Gerais, utilizamos DataFrames oriundos de [Dados Abertos da Saúde de MG](https://coronavirus.saude.mg.gov.br/dadosabertos), em "Sistemas de Vacinação". Nesse Banco de Dados nós fizemos uma redução (subset) para utilizar apenas algumas colunas que nós julgamos mais relevantes e que de fato nos auxiliariam a obter informações importantes neste projeto. Essas decisões estão descritas mais a fundo no arquivo "DataPrep.ipynb"

## Nosso objetivo:

#### A nossa proposta, então, é utilizar esses Bancos de Dados para produzir análises significativas acerca dos dados sobre vacinação, casos e óbitos em Minas Gerais.