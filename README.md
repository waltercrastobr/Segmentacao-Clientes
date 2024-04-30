# Segmentação de Clientes


<img src="" alt="Descrição da imagem">


Este repositório contém uma análise de dados completa para prever a probabilidade de um funcionário deixar uma empresa, com foco em estratégias de retenção de funcionários. O projeto utiliza uma [base](https://github.com/waltercrastobr/Analise-Churn/blob/main/Human_Resources.csv) de dados fictícia da IBM (International Business Machine Corporation), disponível no [Kaggle](https://www.kaggle.com/datasets/pavansubhasht/ibm-hr-analytics-attrition-dataset)
, e segue uma abordagem de aprendizado supervisionado para classificação. 

## Introdução

### Contexto do Projeto


### Problema de Negócio



### Objetivos do Projeto

1. 
2. 
3. 

### Benefícios Esperados

-
-
-
-



## Bibliotecas Usadas
Abaixo estão as principais bibliotecas utilizadas neste projeto:

- pandas: Para manipulação de dados tabulares.
- numpy: Para operações matemáticas e manipulação de arrays.
- seaborn: Para visualização de dados estatísticos.
- matplotlib: Para criação de gráficos e visualizações.
- scikit-learn: Para construção e avaliação de modelos de machine learning.

  
Além disso, foram utilizados os seguintes modelos de machine learning:

- K-means
- RandomForestClassifier


## Dicionários de Atributos
#### **Atributos Categóricos (object):**
- CUST_ID: Identificação do titular do cartão de crédito

#### **Atributos Numéricos (float64):**

- BALANCE: Valor do saldo restante na conta para fazer compras
- BALANCE_FREQUENCY: Frequência com que o saldo é atualizado
- PURCHASES: Valor total das compras feitas
- ONEOFF_PURCHASES: Valor máximo de compra em uma única vez
- INSTALLMENTS_PURCHASES: Valor total das compras parceladas
- CASH_ADVANCE: Valor do adiantamento em dinheiro dado pelo usuário
- PURCHASES_FREQUENCY: Frequência das compras
- ONEOFF_PURCHASES_FREQUENCY: Frequência das compras em uma única vez
- PURCHASES_INSTALLMENTS_FREQUENCY: Frequência das compras parceladas
- CASH_ADVANCE_FREQUENCY: Frequência do adiantamento em dinheiro
- CREDIT_LIMIT: Limite de crédito do cartão
- PAYMENTS: Valor total dos pagamentos feitos
- MINIMUM_PAYMENTS: Valor mínimo dos pagamentos feitos
- PRC_FULL_PAYMENT: Percentual de pagamento total feito pelo usuário

#### **Atributos Inteiros (int64):**

- CASH_ADVANCE_TRX: Número de transações de adiantamento em dinheiro
- PURCHASES_TRX: Número de transações de compras
- TENURE: Tempo de serviço do cartão de crédito para o usuário

# Notebooks

## [Análise Exploratória de Dados](https://github.com/waltercrastobr/Segmentacao-Clientes/blob/main/EDA_Segmentacao_Clientes.ipynb)
- **Objetivo:** 
  1. 
  2. 
  3. 
     
- **Resultados:**


## [Clusterização](https://github.com/waltercrastobr/Segmentacao-Clientes/blob/main/Clusterizacao_Segmentacao.ipynb)

- **Objetivo:** 
- **Passos:**
  1. 
  2. 
  3. 
 
- **Resultados:**
Foram inicialmente testados os modelos regressão logística e no random forest devido à sua capacidade com dados desbalanceados. Após avaliar seus desempenhos, outros modelos foram considerados para melhorar as métricas de recall e F1-score, cruciais na análise de churn. Além da regressão logística e do XGB, foram testados o AdaBoostClassifier, SVC, KNeighborsClassifier e GaussianNB. Os melhores resultados foram obtidos com a regressão logística e o XGB, levando a uma otimização desses modelos para maximizar seu desempenho.


## [Relatório de Recomendações](https://github.com/waltercrastobr/Analise-Churn/blob/main/relatorio_ganhos.pdf)
Em conclusão, o uso do modelo resultou em uma economia significativa de custos e tempo para a empresa, em comparação com o cenário sem o modelo. Em cinco meses, a diferença total foi de $2,983,440, considerando os custos de contratação (reposição dos 'churners') e o lucro acumulado. 
















