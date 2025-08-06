# 📊 TelecomX - Parte 2: Predição de Evasão de Clientes

Este projeto é a **segunda etapa** do desafio **TelecomX**, onde o objetivo é desenvolver modelos preditivos capazes de identificar clientes com maior probabilidade de cancelar seus serviços (**evasão/churn**).

O trabalho foi conduzido no **Google Colab** utilizando Python e bibliotecas de análise de dados e machine learning.

---

## 🎯 Objetivo
- Analisar dados tratados da TelecomX (Parte 1 do desafio).
- Construir modelos preditivos para prever a evasão de clientes.
- Interpretar os resultados e gerar **insights estratégicos** para retenção.

---

## 🛠 Tecnologias e Bibliotecas Utilizadas
- **Linguagem:** Python 3
- **Análise de Dados:** Pandas, NumPy
- **Visualização:** Matplotlib, Seaborn, Plotly (opcional)
- **Machine Learning:** Scikit-learn, Imbalanced-learn (SMOTE)
- **Modelos:** Regressão Logística, Random Forest

---

## 📌 Etapas do Projeto
1. **Carregamento dos dados tratados** (CSV gerado na Parte 1).
2. **Análise exploratória inicial**:
   - Matriz de correlação
   - Boxplot, scatter plot e histograma da evasão
   - Resumo estatístico (`describe`)
3. **Pré-processamento**:
   - Remoção de colunas irrelevantes
   - Encoding (One-Hot) de variáveis categóricas
   - Imputação de valores nulos
   - Balanceamento das classes (SMOTE)
   - Normalização (StandardScaler)
4. **Modelagem**:
   - Treinamento de **Regressão Logística** (modelo sensível à escala)
   - Treinamento de **Random Forest** (modelo não sensível à escala)
5. **Avaliação dos modelos**:
   - Accuracy, Precision, Recall, F1-score
   - Matriz de confusão
   - Curva ROC e AUC
6. **Interpretação**:
   - Importância das variáveis (Random Forest)
   - Comparação de métricas entre modelos
7. **Conclusão estratégica** e recomendações para retenção.

---

## 📊 Principais Resultados
- **Random Forest** apresentou melhor desempenho geral.
- Principais fatores relacionados à evasão:
  - Tempo de contrato
  - Tipo de contrato
  - Total gasto
  - Método de pagamento
- O SMOTE foi eficaz para corrigir o desbalanceamento de classes.
- Insights geraram recomendações para reduzir churn e aumentar retenção.

---

## 🚀 Como Executar o Projeto
1. Faça o download do arquivo **`TelecomX_II.ipynb`**.
2. Abra o [Google Colab](https://colab.research.google.com/).
3. Faça upload do notebook e do arquivo **`telecomx_tratado.csv`**.
4. Execute as células na ordem.
5. Analise os gráficos, métricas e conclusões.

---

## 📌 Autor
Projeto desenvolvido como parte do **Desafio TelecomX - Parte 2**, seguindo as melhores práticas de análise e modelagem preditiva.
