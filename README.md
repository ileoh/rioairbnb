

- a. Como foi a definição da sua estratégia de modelagem?

Foi feita toda uma análise de preprocessamento dos dados e engenharia de features, para criação de novas variáveis que possibilitam em uma modelagem melhor

- b. Como foi definida a função de custo utilizada?

Foi definido a RMSE -  Root mean squared error

- c. Qual foi o critério utilizado na seleção do modelo final?

Realizei alguns testes com modelos simples (regressão linear e arvores), porém, decidi escolher o XGBoost pela eficiência do algoritmo em boosting e por conseguir lidar de forma robusta com diferentes tipos de problemas

- d. Qual foi o critério utilizado para validação do modelo?
Por que escolheu utilizar este método?

Foi utilizado a validação cruzada pelo k-fold, onde todas as entradas no conjunto de dados de treinamento original são usadas para treinamento e validação. Como o XGBoost suporta a validaçao cruzada k-fold pelo método cv, foi utilizado ele.

- e. Quais evidências você possui de que seu modelo é
suficientemente bom?

Validação cruzada, r2, RMSE
