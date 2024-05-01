# Segmentação de Clientes

![Descrição da imagem](https://github.com/waltercrastobr/Segmentacao-Clientes/blob/main/img_segmentacao.png)

Este repositório contém uma análise de dados completa para a segmentação de clientes de um banco. O projeto utiliza uma [base](https://github.com/waltercrastobr/Segmentacao-Clientes/blob/main/Marketing_data.csv) de dados, disponível no [Kaggle](https://www.kaggle.com/arjunbhasin2013/ccdata), e segue uma abordagem de aprendizado supervisionado para classificação.

## Introdução

### Contexto do Projeto

Neste projeto, conduzi uma análise exploratória de dados (EDA) com o objetivo de extrair insights valiosos sobre o comportamento dos clientes de um banco em relação ao uso de cartão de crédito. Em seguida, desenvolvi um modelo preditivo utilizando o algoritmo K-means e PCA, com foco na segmentação dos clientes em grupos distintos. Essa segmentação permitirá ao banco otimizar seus ganhos financeiros por meio de campanhas de marketing personalizadas para cada grupo. Cada etapa do processo foi abordada detalhadamente, com a explicação das razões por trás de cada decisão tomada, visando garantir uma análise sólida e resultados significativos.

### Problema de Negócio

O banco deseja segmentar seus clientes em grupos distintos com base em seus padrões de uso de cartão de crédito. Isso permitirá ao banco direcionar campanhas de marketing mais eficazes e personalizadas para cada grupo, potencializando assim seus ganhos financeiros.

### Objetivos do Projeto

1. Realizar uma análise exploratória de dados para descobrir insights sobre os padrões dos clientes de um banco com base em seu comportamento de uso de cartão de crédito.
2. Segmentar os clientes em grupos distintos para potencializar os ganhos financeiros do banco por meio de campanhas personalizadas.
3. Abordar detalhadamente cada etapa do processo, explicando as razões por trás de cada decisão tomada.

### Benefícios Esperados

- Aumento dos ganhos financeiros do banco por meio de campanhas de marketing mais eficazes e direcionadas.
- Melhoria da experiência do cliente e da fidelização, devido às campanhas personalizadas.

## Bibliotecas Usadas

Abaixo estão as principais bibliotecas utilizadas neste projeto:

- pandas: Para manipulação de dados tabulares.
- numpy: Para operações matemáticas e manipulação de arrays.
- seaborn: Para visualização de dados estatísticos.
- matplotlib: Para criação de gráficos e visualizações.
- scikit-learn: Para construção e avaliação de modelos de machine learning.
- StandardScaler: Para padronização dos dados.
- PCA: Para redução de dimensionalidade.

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

## Notebooks

### [Análise Exploratória de Dados](https://github.com/waltercrastobr/Segmentacao-Clientes/blob/main/EDA_Segmentacao_Clientes.ipynb)

- **Objetivo:** 
  1. Realizar uma análise exploratória de dados para descobrir insights sobre os padrões dos clientes de um banco com base em seu comportamento de uso de cartão de crédito.
  2. Identificar padrões e tendências nos dados que possam ser úteis na segmentação dos clientes.
  3. Visualizar graficamente os principais insights obtidos na análise exploratória.
     
- **Resultados:**
  - Espera-se obter um entendimento maior dos dados e uma prévia segmentação dos clientes, permitindo ao banco direcionar campanhas de marketing mais eficazes e personalizadas. Isso pode resultar em um aumento significativo nos ganhos financeiros, além de melhorar a experiência do cliente e a fidelização.

### [Clusterização](https://github.com/waltercrastobr/Segmentacao-Clientes/blob/main/Clusterizacao_Segmentacao.ipynb)

- **Objetivo:** 
  1. Realizar uma redução de dimensionalidade utilizando PCA.
  2. Segmentar os dados em quatro clusters distintos.
  3. Interpretar os resultados da clusterização e identificar características comuns em cada grupo.
  4. Salvar a base clusterizada para a equipe de Marketing.
  5. Gerar um relatório de recomendações com base na análise feita.

- **Resultados:**
  - Espera-se obter uma segmentação clara dos dados em quatro clusters distintos, o que permitirá uma melhor compreensão dos padrões presentes nos dados e a identificação de possíveis insights e recomendações para tomada de decisões.


### Resultados

Como resultados, obtivemos a separação dos clientes em 4 grupos distintos, armazenados nessa [base](https://github.com/waltercrastobr/Segmentacao-Clientes/blob/main/cluster_ordenado.csv). E também foi gerado um relatório com os grupos ja divididos e recomendações para a equipe de marketing.

![Descrição da imagem](https://github.com/waltercrastobr/Segmentacao-Clientes/blob/main/img_clusterizacao.png)
