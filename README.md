# Predição de Doenças Cardíacas com Orange Data Mining
### Projeto – Fase 2: Ciência de Dados e Inteligência Artificial
**Autora:** Kaliope De Moraes Costa

---

## 📌 Descrição do Projeto

Este repositório contém o desenvolvimento completo de um processo de Ciência de Dados utilizando o Orange Data Mining.  
O objetivo é construir e avaliar modelos capazes de prever a presença de doença cardíaca com base em variáveis clínicas.

Arquivos incluídos:
- **heart_disease_orange_ready.csv** – dataset pronto para uso no Orange  
- **projeto_heart_disease.ows** – workflow completo contendo o fluxo do projeto  

---

## 📊 Exploração dos Dados (EDA)

Foram realizados:
- Verificação de valores faltantes  
- Análise descritiva das variáveis  
- Avaliação de distribuição  
- Detecção de outliers  
- Estatísticas descritivas gerais  

Principais achados:
- Não há valores nulos  
- Outliers em colesterol e pressão arterial  
- Target balanceado  
- Média de idade ≈ 54 anos  

---

## 🤖 Modelos Utilizados

### 1️⃣ Logistic Regression  
Modelo interpretável e baseline eficiente.

### 2️⃣ Random Forest  
Robusto, lida com variáveis complexas e reduz overfitting.

### 3️⃣ SVM  
Eficiente em dados tabulares, requer normalização.

---

## 🔧 Preparação dos Dados

- Seleção de colunas relevantes  
- Normalização de variáveis numéricas  
- Conversão automática de variáveis categóricas  
- Validação cruzada (5 folds)  

Widgets usados: Select Columns, Normalize, Data Sampler, Test & Score.

---

## 📈 Resultados dos Modelos

| Modelo | AUC | CA | F1 | Precisão | Recall | MCC |
|--------|------|------|------|-----------|---------|---------|
| Logistic Regression | **0.815** | **0.714** | **0.712** | **0.712** | **0.714** | **0.410** |
| Random Forest | 0.744 | 0.690 | 0.689 | 0.689 | 0.690 | 0.364 |
| SVM | 0.712 | 0.667 | 0.668 | 0.673 | 0.667 | 0.330 |

Conclusão: a Regressão Logística obteve o melhor desempenho geral.

---

## 📝 Reflexão e Lições Aprendidas

- Preparação dos dados é essencial  
- Métricas múltiplas trazem visão mais completa  
- Modelos simples podem superar modelos complexos  
- Orange facilita visualização e execução do pipeline  

---

## 📂 Arquivos Incluídos

- **heart_disease_orange_ready.csv**
- **projeto_heart_disease.ows**

---

## ▶️ Como Executar

1. Baixe os arquivos  
2. Abra o Orange  
3. Importe **projeto_heart_disease.ows**  
4. Garanta que o CSV esteja acessível  
5. Execute e visualize as métricas  

---

## 🔗 Repositório GitHub

https://github.com/KaliMoraes/heart_disease
