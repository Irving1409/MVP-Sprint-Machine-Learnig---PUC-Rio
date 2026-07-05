# 🚛 MVP - Machine Learning | Predição de Falhas no Sistema APS de Caminhões Scania

## 📌 Sobre o projeto

Este repositório contém o desenvolvimento do **MVP (Minimum Viable Project)** da disciplina de **Machine Learning** da **PUC-Rio**.

O objetivo do projeto foi desenvolver e comparar modelos de Machine Learning capazes de identificar falhas no sistema **APS (Air Pressure System)** de caminhões Scania, utilizando dados de sensores operacionais.

Todo o fluxo de desenvolvimento foi implementado seguindo as boas práticas de projetos de Machine Learning, contemplando desde a análise exploratória dos dados até a otimização de hiperparâmetros e avaliação final dos modelos.

---

## 🎯 Objetivo

Construir um modelo de classificação capaz de prever a ocorrência de falhas no sistema APS de caminhões Scania, auxiliando aplicações de manutenção preditiva e reduzindo o risco de falhas operacionais.

---

## 📂 Dataset

**APS Failure at Scania Trucks**

- Problema: Classificação Binária
- Variável alvo: `class`
- Classes:
  - `neg` → Equipamento sem falha no sistema APS
  - `pos` → Equipamento com falha no sistema APS

O conjunto de dados apresenta:

- 170 variáveis numéricas;
- forte desbalanceamento entre as classes;
- elevada quantidade de valores ausentes.

---

## 🔎 Etapas desenvolvidas

- Definição do problema
- Análise exploratória dos dados (EDA)
- Tratamento dos valores ausentes
- Pipeline de pré-processamento
- Comparação entre modelos
- Avaliação utilizando métricas apropriadas
- Otimização de hiperparâmetros com GridSearchCV
- Avaliação final utilizando conjunto de teste
- Discussão dos resultados

---

## 🤖 Modelos avaliados

- Baseline (Dummy Classifier)
- Regressão Logística
- Árvore de Decisão
- Random Forest

---

## 📈 Métricas utilizadas

Como o conjunto de dados é fortemente desbalanceado, a principal métrica utilizada foi:

- **F1-Score**

Também foram analisadas:

- Accuracy
- Precision
- Recall

---

## 🏆 Melhor modelo

O modelo **Random Forest** apresentou o melhor desempenho entre os modelos avaliados, sendo selecionado como modelo final após a etapa de otimização de hiperparâmetros.

---

## 🛠️ Tecnologias utilizadas

- Python
- Google Colab
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn

---

## 📁 Estrutura do repositório

```
📦 MVP-Sprint-Machine-Learning---PUC-Rio
│
├── MVP_Machine_Learning.ipynb
└── README.md
```

---

## 🎓 Projeto acadêmico

Este projeto foi desenvolvido como parte da avaliação da disciplina **Machine Learning** do curso de Pós-Graduação em **Ciência de Dados e Analytics** da **PUC-Rio**.

---

## 👨‍💻 Autor

**Irving Caetano**

GitHub:
https://github.com/Irving1409
