# heart_disease
# Projeto de Ciência de Dados - Doença Cardíaca

Este repositório contém os arquivos utilizados para a **Fase 2 do Projeto de Ciência de Dados e Inteligência Artificial**, desenvolvido no **Orange Data Mining**.

## 📂 Arquivos incluídos

- `heart_disease_orange_ready.csv` → Conjunto de dados de doença cardíaca, preparado e limpo para utilização no Orange.  
- `projeto_heart_disease.ows` → Projeto do Orange Data Mining contendo o fluxo completo:
  - Leitura do dataset  
  - Exploração dos dados  
  - Preparação  
  - Treinamento com 3 algoritmos (Regressão Logística, Random Forest, Naive Bayes)  
  - Avaliação com **Test & Score** e **Matriz de Confusão**

## ▶️ Como abrir o projeto no Orange

1. Instale o [Orange Data Mining](https://orangedatamining.com/download/).  
2. Baixe este repositório ou os arquivos `.ows` e `.csv`.  
3. Abra o **Orange** e vá em:  
   - `File` → `Open Workflow`  
   - Selecione `projeto_heart_disease.ows`.  
4. Verifique se o dataset `heart_disease_orange_ready.csv` está no mesmo diretório do projeto, assim o Orange conseguirá carregar automaticamente os dados.

## 📊 Sobre o dataset

O dataset contém **14 colunas** referentes a informações clínicas dos pacientes e uma variável alvo:

- `DoencaCardiaca` → Coluna alvo (0 = não possui doença cardíaca, 1 = possui doença cardíaca)

Fonte original: [Kaggle - Heart Disease Dataset](https://www.kaggle.com/datasets/johnsmith88/heart-disease-dataset)

## 🧑‍💻 Equipe

Projeto desenvolvido por Kali Moraes como parte da disciplina de **Ciência de Dados e Inteligência Artificial**.
