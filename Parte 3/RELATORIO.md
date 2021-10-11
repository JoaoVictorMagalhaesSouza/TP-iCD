# **Relatório de Desenvolvimento do Trabalho Prático - Parte 3:**

## Análise Exploratória:
#### Nesta etapa, visamos manter um enfoque nas perguntas que havíamos levantado na Parte 1 deste projeto, juntamente com as sugestões dadas pelo professor. Dessa forma, visamos responder tais questões e, paralelamente, procurar correlacionar os atributos presentes nos atributos dos Bancos de Dados previamente preparados.

#### Ao passo que íamos desenvolvendo algumas análises, refatoramos algumas questões que não faziam muito sentido e/ou derivavam em alguma limitação de hardware para serem desenvolvidas, visto que os Bancos de Dados possuem um tamanho considerável. Além disso, adicionamos alguns tratamentos nos dados bem específicos que foram surgindo à medida em que "debulhavamos" os dados e fazíamos análises mais profundas.

#### Por fim, decidimos manter todos os resultados no próprio Notebook, visando evitar retrabalhos e que, além disso, no arquivo em questão fazemos algumas discussões pertinentes àqueles momentos de desenvolvimento e às questões envolvidas naquele determinado momento. Sendo assim, os resultados desta etapa são acessados mediante ao arquivo "TP-iCD.ipynb" neste diretório (Parte 3).

## Esclarecimentos Prévios:
#### Durante algumas análises, buscamos informações a nível municipal. Dessa forma, algumas vezes referenciamos, por exemplo, "Taxa de Novos Casos" como sendo uma proporção entre os números de Novos Casos e a População de cada cidade. Decidimos manter essa abordagem (Novos Casos/População) como forma de obter um mesmo dimensionamento analítico para todas as cidades de MG, de forma a não ter uma análise tão deturpada devido ao fato de diferentes tamanhos populacionais. Sendo assim, mesmo que duas cidades A e B tenham uma grande diferença entre os números de Novos Casos, a nossa análise leva em conta esses números em relação à população de seu próprio município.
