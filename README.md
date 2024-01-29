***PrevDiabetes - Análise Exploratória e Modelo de Machine Learning***

**Sobre o Projeto**

O PrevDiabetes é um projeto acadêmico desenvolvido como parte de disciplinas relacionadas a backend, data science, inteligência artificial e teste de software na faculdade. Este projeto visa fornecer previsões sobre a probabilidade de diabetes com base em informações fornecidas pelos usuários. Aqui está uma visão geral das etapas realizadas na análise exploratória de dados (EDA) e na criação do modelo de machine learning.

📊 **Análise Exploratória de Dados (EDA)**

**Balanciamento dos Dados**

- Realizamos o balanço do conjunto de dados, garantindo que cada classe tenha uma quantidade mínima de exemplos.
  
**Tratamento de Dados Ausentes/Ruidosos**

- Não identificamos valores nulos ou dados ruidosos.
  
**Remoção de Duplicatas**

- Removemos registros duplicados no conjunto de dados.
  
**Estatísticas Descritivas Básicas**

- Calculamos estatísticas descritivas básicas para colunas numéricas, como média, mediana, desvio padrão, mínimo, máximo e quartis.
  
**Visualização de Dados**

- Utilizamos histogramas, boxplots e gráficos de barras para visualizar distribuições e relações entre variáveis.
  
**Análise de Correlação**

- Calculamos a matriz de correlação e exploramos correlações entre variáveis numéricas.
  
🤖**Modelo de Machine Learning**

**Pré-processamento e Treinamento do Modelo**

- Remoção de outliers usando Z-score.
- Pré-processamento com padronização e uso do RandomForestClassifier.
- Utilização de técnicas de subamostragem e sobreamostragem para lidar com desequilíbrio de classes.
- Otimização de hiperparâmetros com Grid Search.

**Avaliação do Modelo**

- Acurácia média ao longo de múltiplas execuções.
- Matriz de confusão, precision, recall e f1-score para avaliação detalhada.
- Visualização da importância das características no modelo.

🚀 **Resultados**

O modelo desenvolvido apresentou uma acurácia média de aproximadamente 93%, demonstrando uma boa capacidade de prever casos de diabetes. A análise exploratória permitiu compreender a distribuição das variáveis, identificar possíveis correlações e visualizar padrões nos dados.
