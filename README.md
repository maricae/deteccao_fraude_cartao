# Detecção de Fraude de Cartão de Crédito - Regressão Linear
O projeto tem como objetivo identificar transações fraudulentas no serviço de cartão de crédito de seus clientes utilizando algoritmo de regressão logística. Para isso, foi selecionado um conjunto de dados que contém transações efetuadas com cartões de crédito durante dois dias do mes de setembro de 2013 por titulares de cartões europeus. No total, foram 284.807 transações analisadas.

A base de dados contém apenas variáveis ​​de entrada numéricas que são o resultado de uma transformação PCA, sendo as variáveis V1, V2,… V28. As únicas variáveis que não foram transformadas são 'Time' e 'Amount'.

**Time**: segundos decorridos entre cada transação e a primeira transação no conjunto de dados.\
**Amount**: valor total da transação.\
**Class (variável resposta)**: assume valor 1 em caso de fraude e 0 caso contrário.

Além disso, por conta das questões de confidencialidade, não foi possível trazer os valores originais e nomes originais das variáveis.

Link para Base de Dados no Kaggle: https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud/data