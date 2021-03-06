# **Relatório de Desenvolvimento do Trabalho Prático - Parte 1:**

## Obtenção dos Bancos de Dados:
#### Para obter os conjuntos de dados relacionados às informações da COVID-19 no Brasil, utilizamos dados fornecidos pela [brasil.io](https://brasil.io/dataset/covid19/files/), contendo um compilado diário informações das Secretarias Estaduais de Saúde. Entretanto, reduzimos esse conjunto de dados apenas às cidades de Minas Gerais com o propósito de dar um enfoque maior e produzir análises centradas nas macrorregiões de Minas Gerais, gerando um *Dataset* com dados desde o início da pandemia até o último mês de Julho (07/2021).

#### Relativo aos dados da vacinação no estado de Minas Gerais, utilizamos DataFrames oriundos de [Dados Abertos da Saúde de MG](https://coronavirus.saude.mg.gov.br/dadosabertos), em "Sistemas de Vacinação". Nesse Banco de Dados nós fizemos uma redução (subset) para utilizar apenas algumas colunas que nós julgamos mais relevantes e que de fato nos auxiliariam a obter informações importantes neste projeto. Essas decisões estão descritas mais a fundo no arquivo "DataPrep.ipynb"

## Nosso objetivo:

#### A nossa proposta, então, é aplicar posteriormente outras técnicas de *DataPreparation* para finalmente fazer o *join* desses Bancos de Dados para produzir as análises mais significativas acerca dos dados sobre vacinação, casos e óbitos em Minas Gerais e, posteriormente, elaborar *dashboards* que possibilitem um entendimento da nossa análise de maneira mais ao alto nível.