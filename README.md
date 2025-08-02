# 📊 Análise de Evasão de Clientes (Churn) - TelecomX II

Este projeto tem como objetivo principal analisar os dados de clientes de uma empresa de telecomunicações para identificar os fatores que mais influenciam a evasão (churn). O trabalho foi desenvolvido para construir e avaliar modelos de Machine Learning capazes de prever quais clientes têm maior probabilidade de cancelar seus serviços, permitindo a implementação de estratégias de retenção proativas e direcionadas.

## 📈 Requisitos

- Python 3.x
- Pandas, NumPy, Seaborn, Matplotlib, Scikit-learn

> 📌 O projeto foi desenvolvido e executado no ambiente Google Colab.

## 🌐 Fonte de Dados
Os dados utilizados são carregados diretamente de um arquivo JSON hospedado no GitHub:

```
https://raw.githubusercontent.com/Raybarreto/Challenge3_TelecomX_II/refs/heads/main/dados_tratados.csv
```

## 📁 Estrutura do Projeto

- `Telecom_BR_II.ipynb` – Notebook principal contendo:
  - Pré-processamento dos dados
  - Análise exploratória e correlação
  - Modelagem preditiva (Regressão Logística, Random Forest, SVM)
  - Avaliação dos modelos
  - Interpretação dos resultados

## 🔍 Objetivos

- Detectar os principais fatores que levam à saída dos clientes.
- Construir modelos preditivos eficazes para prever a evasão.
- Propor estratégias de retenção baseadas nos insights obtidos.

## ⚙️ Técnicas Utilizadas

### 📌 Pré-processamento
- Remoção de colunas irrelevantes (`Id_cliente`)
- One-hot encoding para variáveis categóricas
- Normalização para modelos sensíveis à escala
- Tratamento de valores nulos

### 📌 Análise Exploratória
- Proporção de churn
- Correlação entre variáveis
- Boxplots para tempo de serviço e cobrança total vs. churn

### 📌 Modelagem
- **Regressão Logística** (melhor recall para evasão)
- **Random Forest**
- **SVM (linear)**

### 📌 Avaliação de Modelos
- Acurácia, Precisão, Recall, F1-score
- Matriz de Confusão
- Curva ROC e Precisão-Recall

## ✅ Principais Resultados

### 🔝 Variáveis com maior influência na evasão:
- **Tempo de serviço** (negativo)
- **Cobrança total**
- **Tipo de contrato**
- **Tipo de internet (Fibra ótica)**
- **Forma de pagamento (cheque eletrônico)**

### 🧠 Melhor modelo:
- **Regressão Logística** apresentou:
  - Acurácia: 80,6%
  - Recall (Evadiu): **53,6%** (melhor entre os modelos)
  - Alta interpretabilidade

## 🎯 Estratégias Recomendadas de Retenção

- **Incentivar contratos mais longos**
- **Promover pagamento automático por cartão**
- **Acompanhar de perto novos clientes (0–6 meses)**
- **Analisar e melhorar a experiência com internet por fibra**
- **Oferecer upgrade ou personalização para clientes com baixa cobrança total**


## 📬 Contato
Para dúvidas ou sugestões:
- Raylaine Barreto
- E-mail: raylainebarreto@outlook.com
- [LinkedIn](https://www.linkedin.com/in/raylaine-barreto)

