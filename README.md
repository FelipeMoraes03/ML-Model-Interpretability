# ML-Model-Interpretability

Este projeto visa empregar métodos de interpretabilidade em modelos de machine learning para compreender as decisões tomadas por esses modelos.

### Conjunto de Dados

O conjunto de dados utilizado consiste em asteroides classificados como **Perigosos** e **Não Perigosos** para a Terra. O conjunto de dados pode ser encontrado [aqui](https://www.kaggle.com/datasets/sameepvani/nasa-nearest-earth-objects).

### Modelos Utilizados

Foram desenvolvidos dois modelos distintos para a classificação dos asteroides:
- **KNN (K-Nearest Neighbors)**
- **Random Forest**

### Técnicas de Interpretabilidade

Foram aplicadas as seguintes técnicas para interpretar cada um dos modelos mencionados acima:

- **PFI (Permutation Feature Importance)**: Esta técnica avalia a importância de cada feature no modelo, medindo como a acurácia do modelo é afetada pela permutação aleatória das features.
  
- **PDP (Partial Dependence Display)**: O PDP mostra como uma fature específica afeta as previsões do modelo, mantendo outras features fixas.

- **LIME**: Local Interpretable Model-agnostic Explanations é uma técnica que explica as previsões de um modelo complexo ao aproximar localmente o modelo com um modelo linear.

Além disso, a confiabilidade de cada modelo foi avaliada com a criação de um **Modelo Assessor** e a análise de uma **Matriz de Confusão**.