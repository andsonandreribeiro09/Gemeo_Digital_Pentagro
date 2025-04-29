# Gemeo_Digital_Pentagro

# 🌾 Projeto Pentagro IA — Gêmeo Digital para Processos Industriais

Este projeto integra ciência de dados e machine learning para construir um **modelo preditivo em tempo real**, com foco na **otimização do processo de dosagem de cal e controle de pH** em ambientes industriais, utilizando os conceitos de **Gêmeo Digital**.

---

## 🎯 Objetivo

Desenvolver um sistema de previsão que:
- Antecipe, com **5 minutos de antecedência**, o valor de uma variável dependente crítica (ex: pH do material dosado).
- Responda em **milissegundos**, com **alta precisão (erro de 1% a 2%)**.
- Suporte decisões operacionais em tempo real por meio de visualizações e dashboards inteligentes.

---

## 🔍 Etapas do Projeto

### 1. 🔎 Análise Exploratória
- Estatísticas descritivas de variáveis sensoriais e operacionais.
- Visualização de distribuições, boxplots e correlações.
- Identificação de variáveis com alta influência sobre o pH.

### 2. 🧼 Pré-processamento de Dados
- Interpolação linear para valores ausentes.
- Remoção de **outliers** com base no intervalo interquartil (IQR).
- Padronização dos dados com **Z-Score**.
- Extração de **características temporais**.

### 3. 🤖 Modelagem Preditiva
- Algoritmos aplicados:
  - **Regressão Linear**
  - **AutoML (H2O AutoML)**
  - **XGBoost (Regressão)**
- Técnica de validação: **TimeSeriesSplit**, respeitando a ordem temporal dos dados.
- Métricas usadas: **MAE**, **RMSE**, **Tempo de Inferência**, **Erro Relativo (%)**.

### 4. 📊 Resultados
- Modelos com erro médio abaixo de **2%**.
- AutoML com melhor desempenho em termos de precisão e tempo.
- Visualização por dashboards com métricas de predição.

---

## 💡 Tecnologias Utilizadas

- Python, Pandas, NumPy
- Matplotlib, Seaborn, Plotly
- Scikit-learn, H2O.ai AutoML, XGBoost
- Flask (para deploy do dashboard)
- Jupyter Notebook

---

## 🚀 Deploy

- Aplicação web para visualização dos resultados hospedada localmente:


---

## 📬 Contato

**E-mail:** adwbemestardigitalavancado@gmail.com  
**Instagram:** [@ADW](https://www.instagram.com/adw)  
**Telefone:** (11) 98556-0057

---

## 🤝 Agradecimentos

Projeto desenvolvido por **ADW - Advanced Digital Wellbeing**  
Com o apoio de pesquisadores e engenheiros em IA para aplicações industriais.

---

**🔗 Em breve:** integração com Gêmeo Digital em tempo real e feedback automatizado para controle de processos.


