# 🛫 Predição de Atrasos em Voos com Machine Learning

Este repositório contém um notebook interativo focado na prática de **análise exploratória de dados (EDA)** e **modelagem de classificação supervisionada**, utilizando Python e bibliotecas poderosas como `pandas`, `matplotlib`, `seaborn` e `scikit-learn`.

---

## 🎯 Objetivo do Projeto
O objetivo deste projeto é **prever a ocorrência de atrasos em voos** a partir de variáveis históricas, aplicando técnicas de análise de dados e aprendizado de máquina.

O estudo busca responder a questões como:
- Quais fatores mais influenciam atrasos?
- Qual modelo de machine learning tem melhor desempenho na predição?
- Como validar corretamente os modelos e interpretar os resultados?

Além disso, o projeto visa consolidar boas práticas em **ciência de dados aplicada à aviação**, incluindo:
- Análise exploratória de dados
- Pré-processamento e engenharia de atributos
- Balanceamento de classes
- Construção e avaliação de modelos supervisionados
- Comparação de algoritmos com métricas adequadas

---

## 🧪 Visão Geral do Notebook

### `modelo_atraso_voo.ipynb`
Este notebook aplica uma **pipeline completa de classificação supervisionada**, desde a leitura e transformação dos dados até a avaliação de diferentes modelos de machine learning.

#### Etapas do projeto:
- **Análise exploratória dos dados (EDA)**
  - Estatísticas descritivas
  - Distribuições e correlações
  - Identificação de padrões em atrasos
- **Pré-processamento**
  - Tratamento de valores ausentes
  - Normalização e encoding de variáveis
  - Seleção de features relevantes
- **Modelagem preditiva**
  - Algoritmos utilizados:
    - Regressão Logística
    - Decision Tree
    - Random Forest
    - Gradient Boosting
- **Validação de modelos**
  - Holdout e K-Fold Cross Validation
  - Ajuste de hiperparâmetros (GridSearchCV)
- **Métricas de avaliação**
  - Acurácia
  - Precisão
  - Recall
  - F1-Score
  - Curva ROC e AUC
  - Curva Precision-Recall e AP
- **Balanceamento de classes**
  - Oversampling (SMOTE)
  - Undersampling
- **Avaliação final**
  - Matriz de confusão
  - Interpretação dos resultados

---

## 🛠️ Tecnologias e Bibliotecas Utilizadas
- **Linguagem:** Python  
- **Manipulação e análise de dados:** Pandas, NumPy  
- **Visualização:** Matplotlib, Seaborn  
- **Machine Learning:** Scikit-learn, imbalanced-learn  

---

## 📌 Exemplos de Saída

### Classificação e Métricas (exemplo ilustrativo)

```
'Raiz do Erro Quadrático Médio': 23.2241
'Erro Absoluto Médio': 18.6127
'R2 Score': -0.0
 ```
---
```
MAE Scores: ['-11.074', '-11.303', '-11.056', '-11.145', '-11.174']
MAE Média: -11.151, Std: 0.088
----------------------------------------------------------------
RMSE Scores: ['-13.767', '-14.049', '-13.793', '-13.877', '-13.930']
RMSE Média: -13.883, Std: 0.101
----------------------------------------------------------------
R2 Scores: ['0.647', '0.624', '0.645', '0.641', '0.635']
R2 Média: 0.638, Std: 0.008
----------------------------------------------------------------
 ```
---
```
'Raiz do Erro Quadrático Médio': 13.2635
'Erro Absoluto Médio': 10.6731
'R2 Score': 0.6738
 ```
