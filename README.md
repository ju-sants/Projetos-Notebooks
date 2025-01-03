# Predição de Dias Atrasados na Produção Industrial

**Objetivo:**

Desenvolver uma solução para prever o número de dias atrasados na produção industrial, utilizando dados operacionais e administrativos. O objetivo é fornecer insights acionáveis que auxiliem na otimização de processos e na tomada de decisões estratégicas, reduzindo atrasos e melhorando a eficiência geral.

## Metodologia:

### **Preparação dos Dados:**

**Exploração:**

- Visualizações (histogramas, heatmaps, scatter plots) para correlações e tendências.
- Investigação de outliers e inconsistências.

**Limpeza:**

- Remoção de duplicatas e dados nulos.
- Identificação de variáveis irrelevantes.

**Feature Engineering:**

- Criação e padronização de variáveis críticas.

### **Modelagem Preditiva:**

**Divisão de Dados:**

- Conjuntos de treino e teste (80/20) com validação cruzada.

**Modelos:**

- Testes com Regressão Linear, Random Forest, Gradient Boosting e Redes Neurais.
- Avaliação via RMSE, MAE e R².

**Seleção:**

- Escolha baseada em desempenho estatístico e aplicabilidade.

### **Desenvolvimento de App Web:**

**Flask:**

- Implementação de um pequeno app web para facilitar o uso do modelo preditivo por stakeholders.
- Funcionalidades:
  - Upload de arquivos CSV contendo novos dados.
  - Visualização de previsões geradas pelo modelo em tempo real.
  - Relatórios resumidos dos resultados diretamente na interface.

**Integração:**

- Deployment do app para permitir acessibilidade e uso colaborativo.

### **Resultados:**

**Insights:**

- Identificação de variáveis-chave e comparação entre previsões e dados reais.

**Visualizações:**

- Gráficos de previsões e erros residuais.

### Tecnologias Utilizadas:

**Python:**

- **Pandas, NumPy:** Manipulação de dados.
- **Scikit-learn, XGBoost:** Modelagem.
- **Matplotlib, Seaborn:** Visualização.

**Flask:**

- Desenvolvimento do app web.

---


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

# Versionamento

O controle de versões está completamente na plataforma **_Google Colaboratory_**.

**Controle de versões:**

![image](https://github.com/user-attachments/assets/1dd10b32-edb0-4a65-b236-7a81abbda4f2)
