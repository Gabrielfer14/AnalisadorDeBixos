# PROJETO DE ML - Classificação de Imagens de Gatos e Cachorros

## Descrição
Este projeto tem como objetivo comparar diferentes algoritmos de Machine Learning na classificação de imagens de **quatro datasets** distintos:  
- 2 raças diferentes de cães  
- 2 raças diferentes de gatos  

A análise envolve desde a preparação dos dados até a aplicação de **comitês de classificação** e técnicas de **redução de dimensionalidade (PCA)**.

---

## Objetivos
- Comparar a performance de diferentes algoritmos supervisionados.
- Analisar o impacto da redução de dimensionalidade na acurácia.
- Organizar e visualizar métricas para facilitar a tomada de decisão.

---

## Estrutura do Repositório
    /data → informações sobre datasets
    /notebooks → código separado por algoritmo
    /results → tabelas, gráficos e métricas finais


---

## Algoritmos Utilizados
- Naive Bayes (NB)
- Árvore de Decisão (AD)
- K-Nearest Neighbors (KNN)
- Multi-Layer Perceptron (MLP)
- Comitês de Classificação

---

## Técnicas Adicionais
- **PCA (Principal Component Analysis)** para redução de dimensionalidade.
- Avaliação de métricas como Accuracy, Precision, Recall e F1-Score.

## Requisitos
As principais bibliotecas usadas foram:
    -pandas
    -numpy
    -matplotlib
    -seaborn
    -scikit-learn