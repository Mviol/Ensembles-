# Ensemble- Deep and Machine Learning
Um ensemble é uma abordagem em aprendizado de máquina onde vários modelos individuais são combinados para melhorar a performance geral e a capacidade de generalização. No contexto de Deep Learning e Machine Learning, existem várias técnicas de ensemble que podem ser aplicadas. Algumas delas são:

Bagging (Bootstrap Aggregating): Nesse método, vários modelos são treinados em diferentes subconjuntos dos dados de treinamento, criados por amostragem com reposição. Os resultados desses modelos são então agregados, muitas vezes por média ou votação, para fazer a predição final.

Boosting: Aqui, os modelos são treinados sequencialmente, onde cada modelo subsequente foca nos erros cometidos pelo modelo anterior. O objetivo é melhorar as áreas em que os modelos anteriores falharam.

Random Forests: Uma variação do bagging, onde a combinação de modelos é feita usando árvores de decisão. Cada árvore é treinada em um subconjunto aleatório dos dados e suas predições são combinadas para produzir a predição final.

Stacking: Nesse método, diferentes modelos são treinados e suas previsões se tornam a entrada para um meta-modelo que aprende como combinar essas previsões para gerar a saída final.

Voting: Consiste em combinar as previsões de vários modelos individuais por meio de votação (por exemplo, maioria).

Blending: Similar ao stacking, mas em vez de um meta-modelo, uma parte do conjunto de dados é retida como conjunto de validação para combinar as previsões dos modelos.

Machine Learning (Aprendizado de Máquina):
Machine Learning é uma subárea da inteligência artificial (IA) que se concentra no desenvolvimento de algoritmos e modelos que permitem que sistemas aprendam a partir de dados. Em vez de programar explicitamente regras, o objetivo é permitir que as máquinas aprendam padrões a partir dos dados para fazer previsões, tomar decisões ou executar tarefas específicas. Algoritmos de Machine Learning são categorizados em três principais tipos: aprendizado supervisionado, aprendizado não supervisionado e aprendizado por reforço.

Deep Learning (Aprendizado Profundo):
Deep Learning é uma subárea do Machine Learning que se concentra em algoritmos inspirados na estrutura e função do cérebro humano, conhecidos como redes neurais artificiais. Essas redes têm várias camadas (daí o termo "profundo") que processam informações de maneira hierárquica, permitindo a extração automática de recursos e padrões complexos dos dados. Deep Learning tem se destacado em tarefas como reconhecimento de imagem, processamento de linguagem natural, tradução automática e muito mais.

Diferenças entre Deep Learning e Machine Learning:
A principal diferença entre Deep Learning e Machine Learning está na complexidade das representações aprendidas. Enquanto o Machine Learning tradicional tende a depender mais de recursos humanos para extrair características dos dados, o Deep Learning tenta aprender essas características automaticamente, resultando em um processo mais automatizado e menos dependente de conhecimento especializado.


