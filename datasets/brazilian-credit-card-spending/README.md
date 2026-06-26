### Brazilian Credit Card Spending

**Fonte:** [https://www.kaggle.com/datasets/sufyant/brazilian-real-bank-dataset](https://www.kaggle.com/datasets/sufyant/brazilian-real-bank-dataset)

Este conjunto de dados contém transações de cartão de crédito associadas a clientes brasileiros, com informações cadastrais, limite disponível, data da compra e segmento do estabelecimento. Ele é útil para análises de comportamento de consumo e segmentação.

- `id`: identificador do cliente ou conta.
- `safra_abertura`: período de abertura da conta.
- `cidade`: cidade do cliente.
- `estado`: estado do cliente.
- `idade`: idade do cliente.
- `sexo`: sexo do cliente.
- `limite_total`: limite total do cartão.
- `limite_disp`: limite disponível no momento do registro.
- `data`: data da transação.
- `valor`: valor da transação.
- `grupo_estabelecimento`: categoria do estabelecimento.
- `cidade_estabelecimento`: cidade do estabelecimento.
- `pais_estabelecimento`: país do estabelecimento.

Uma variável-alvo possível é `valor`, caracterizando um problema de **regressão** para estimar o valor das transações. O conjunto também pode ser usado em tarefas não supervisionadas de segmentação.
