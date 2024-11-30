# Clusterização e análise de Segmentação de Clientes em um E-commerce (RFM)

**Objetivo:**

Este projeto visa identificar e segmentar os clientes de um e-commerce com base em seus comportamentos de compra. Utilizando técnicas de clusterização, buscamos agrupar os clientes em segmentos distintos, permitindo a criação de estratégias de marketing mais personalizadas e eficazes.

## Metodologia:

### **Análise e Preparação dos Dados:**

**Visualização:** Criação de gráficos (histogramas, boxplots, scatter plots) para entender a distribuição dos dados e identificar padrões.
**Análise Estatística:** Cálculo de estatísticas descritivas (média, mediana, desvio padrão) para cada variável.
**Investigação:** Investigação profunda de dados nulos, duplicados, outliers e anômalos no dataset.
**Limpeza:** Remoção de dados duplicados, tratamento de valores ausentes, outliers e anômalos.
**Criação da Tabela RFM:** Cálculo das métricas de Recência, Frequência e Monetário para cada cliente.
**Normalização:** Padronização dos dados para garantir comparabilidade entre as features.

### **Modelagem de Clusterização:**

**Algoritmos:** Aplicação de algoritmos como K-means, hierárquico, GaussianMixture, DBSCAN e MeanShift para agrupar os clientes.
**Avaliação:** Utilização de métricas como silhouette score, Davies Bouldin score, Calinski-Harabasz score, AIC, BIC, R² para avaliar a qualidade dos clusters.
**Seleção do Melhor Modelo:** A escolha do modelo se deu pela visão de negócio sobre as métricas performadas em cada algoritimo, que nem sempre que melhores, eram simultaneamente melhores para o negócio.

### **Interpretação dos Resultados:**

**Análise dos Clusters:** Análise das características de cada cluster para identificar os perfis de clientes.
**Visualização:** Criação de visualizações para facilitar a interpretação dos resultados (por exemplo, gráficos de dispersão em 3D).

### Tecnologias Utilizadas:

**Python:** Linguagem de programação principal.
**Pandas:** Manipulação e análise de dados.
**NumPy:** Computação numérica.
**Scikit-learn:** Algoritmos de machine learning.
**Matplotlib, Seaborn, Plotly:** Visualização de dados.
