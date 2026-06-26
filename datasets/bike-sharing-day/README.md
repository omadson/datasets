### Bike Sharing Day

**Fonte:** [https://www.kaggle.com/datasets/lakshmi25npathi/bike-sharing-dataset](https://www.kaggle.com/datasets/lakshmi25npathi/bike-sharing-dataset)

Este conjunto de dados reúne informações diárias de um sistema de compartilhamento de bicicletas, incluindo calendário, clima e quantidade de usuários casuais e registrados. Ele pode ser usado para estudar demanda diária por bicicletas.

- `instant`: identificador sequencial do registro.
- `dteday`: data da observação.
- `season`: estação do ano codificada.
- `yr`: ano codificado.
- `mnth`: mês.
- `holiday`: indica se o dia é feriado.
- `weekday`: dia da semana.
- `workingday`: indica se é dia útil.
- `weathersit`: condição climática codificada.
- `temp`: temperatura normalizada.
- `atemp`: sensação térmica normalizada.
- `hum`: umidade normalizada.
- `windspeed`: velocidade do vento normalizada.
- `casual`: número de usuários casuais.
- `registered`: número de usuários registrados.
- `cnt`: total de aluguéis de bicicletas.

A variável-alvo mais comum é `cnt`, caracterizando um problema de **aprendizado supervisionado do tipo regressão**.
