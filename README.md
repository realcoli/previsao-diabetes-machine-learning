# 🩺 Previsão de Diabetes com Machine Learning

🔗 [Abrir no Google Colab](https://colab.research.google.com/drive/1dYsvV-DaQcADoyiB5x0JN7OL134xgzyW?usp=sharing)

---

## 🎯 Objetivo

Desenvolver um modelo de Machine Learning capaz de prever a presença de diabetes em pacientes com base em dados clínicos.

---

## 🧠 Problema de Negócio

A identificação precoce de diabetes é essencial para prevenir complicações graves e reduzir custos no sistema de saúde.

Modelos preditivos podem auxiliar profissionais na tomada de decisão e no direcionamento de pacientes de risco.

---

## 📊 Principais Insights

- O modelo atingiu aproximadamente **78% de acurácia**
- A variável mais importante foi **glicose**, seguida por **IMC**
- O modelo tem mais dificuldade em identificar corretamente casos positivos (diabetes)
- Há presença de falsos negativos, o que pode ser crítico no contexto de saúde

---

## 📈 Variáveis mais relevantes

- Glucose (mais importante)
- BMI
- DiabetesPedigreeFunction
- Age

Essas variáveis estão diretamente relacionadas ao risco de diabetes, indicando que o modelo capturou padrões coerentes com a literatura médica.

---

## 📌 Aplicação Prática

O modelo pode ser utilizado para:

- Identificar pacientes com maior risco de diabetes
- Apoiar decisões médicas
- Priorizar exames e acompanhamento
- Reduzir diagnósticos tardios

---

## 🔍 Análise Realizada

- Análise inicial dos dados
- Tratamento de valores inconsistentes
- Separação entre variáveis preditoras e alvo
- Treinamento de modelo de Machine Learning
- Avaliação com métricas de classificação
- Análise de importância das variáveis

---

## ⚠️ Limitações

- O modelo apresenta dificuldade em identificar todos os casos positivos
- Possível desbalanceamento das classes
- Necessidade de ajustes para melhorar recall da classe positiva

---

## 🚀 Possíveis Melhorias

- Balanceamento de dados (SMOTE, undersampling)
- Ajuste de hiperparâmetros
- Teste com outros modelos (XGBoost, Logistic Regression)
- Feature engineering

---

## 👩‍💻 Autor

Renata  
🔗 https://github.com/realcoli
