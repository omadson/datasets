### FIPE 2022

**Fonte:** [https://www.kaggle.com/datasets/vagnerbessa/average-car-prices-bazil](https://www.kaggle.com/datasets/vagnerbessa/average-car-prices-bazil)

Este conjunto de dados contém preços médios de veículos segundo a tabela FIPE em 2022, com informações de marca, modelo, combustível, câmbio, motor e ano do modelo. Ele pode ser usado para estudar a precificação de veículos no mercado brasileiro.

- `year_of_reference`: ano de referência da tabela.
- `month_of_reference`: mês de referência da tabela.
- `fipe_code`: código FIPE.
- `authentication`: código de autenticação.
- `brand`: marca do veículo.
- `model`: modelo do veículo.
- `fuel`: combustível.
- `gear`: tipo de câmbio.
- `engine_size`: tamanho do motor.
- `year_model`: ano do modelo.
- `avg_price_brl`: preço médio em reais.
- `age_years`: idade do veículo em anos.

A variável-alvo é `avg_price_brl`, caracterizando um problema de **aprendizado supervisionado do tipo regressão**.
