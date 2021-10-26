# **Relatório de Desenvolvimento do Trabalho Prático - Parte 4:**

## Análise Preditiva:

Nesta etapa do trabalho o grupo teve a ideia de treinar um modelo para a previsão das macroregiões de determinada cidade, assim criamos a correlação
entre as macroregiões do banco de "Dados de Vacinação" com as incidencias de casos de covid e obitos, do banco de "Dados de Covid".

Assim sendo, foi calculado a média de casos e óbitos agrupados por cidades, e estas, foram relacionadas com sua macroregião estabelecida na tabela "Dados Vacinação". Após
o preparo inicial dos dados, o grupo decidiu por utilizar a abordagem 1:4, onde 80% dos dados foram utilizados para treino, e 20% para teste, e o algoritmo escolhido foi o de Árvore
de decisão, importado da biblioteca sklearn.

## Resultados:

Após o teste com outros algoritmos, foi notado que o resultado apresentado pelo algoritmo de árvore de decisão foi o melhor, obtendo entre 95%~99% de acerto, e portanto
o grupo decidiu por mantê-lo.
