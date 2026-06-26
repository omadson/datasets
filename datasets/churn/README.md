### Churn

**Fonte:** [https://www.kaggle.com/datasets/saurabhbadole/bank-customer-churn-prediction-dataset](https://www.kaggle.com/datasets/saurabhbadole/bank-customer-churn-prediction-dataset)

Este conjunto de dados contém informações cadastrais e financeiras de clientes bancários, além de um indicador de saída do banco. O objetivo é prever churn de clientes a partir de características demográficas e de relacionamento.

- `RowNumber`: número sequencial da linha.
- `CustomerId`: identificador do cliente.
- `Surname`: sobrenome do cliente.
- `CreditScore`: pontuação de crédito.
- `Geography`: país do cliente.
- `Gender`: gênero do cliente.
- `Age`: idade do cliente.
- `Tenure`: tempo de relacionamento com o banco.
- `Balance`: saldo em conta.
- `NumOfProducts`: número de produtos contratados.
- `HasCrCard`: indica se o cliente possui cartão de crédito.
- `IsActiveMember`: indica se o cliente é ativo.
- `EstimatedSalary`: salário estimado.
- `Exited`: indica se o cliente deixou o banco.

A variável-alvo é `Exited`, caracterizando um problema de **aprendizado supervisionado do tipo classificação binária**.
