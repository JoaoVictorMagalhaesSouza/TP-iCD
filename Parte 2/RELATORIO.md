# **Relatório de Desenvolvimento do Trabalho Prático - Parte 2:**

## Redução dos Bancos de Dados:
#### Os conjuntos de dados que nós obtivemos eram muito grandes para serem lidos em tempo e recursos hábeis pelos componentes do grupo (Parte 1). Dessa forma, nós utilizamos o Dicionário desses dados e pegamos apenas um subset das colunas que mais nos interessavam para essa aplicação. Dessa forma, tivemos uma redução de cerca de +- 7GB de Dados. Como nosso escopo é focado no estado de Minas Gerais, essa redução NÃO ACOMETERÁ NENHUMA INTERFERÊNCIA EM NOSSA ANÁLISE.

## Tratamento de valores NaN:    
#### Tanto no Banco de Dados de Casos e Mortes da COVID-19 quanto no Banco de Dados da Vacinação possuiam alguns registros com valores NaN em algumas colunas. Na nossa concepção, apenas excluir esses registros dos *Datasets* seria uma perda de informação lastimável e, dessa forma, decidimos tratar esses valores da seguinte forma: verficamos a coluna onde havia a ocorrência de NaN e, de acordo com a coluna, nós atribuimos um valor para aquele registro do tipo "Não especificado", "Não identificado", etc. Dessa forma, mantemos a essência do registro em si e, ainda assim, podemos fazer análises e obter métricas acerca dos dados faltantes.

## Mudança de tipos:
#### Realizando alguns testes iniciais e algumas operações com os dados, nos deparamos que alguns valores númericos estão tipados como string. Dessa forma, em algumas colunas como Número de Casos no Dia(16) e Números de Óbitos do Dia(17) nós convertemos o registro de string para numérico, com intuito de, posteriormente, poder somar esses dados e obter resultados de acordo com critérios como: por cidade, por macrorregião, por faixa etária, etc. 