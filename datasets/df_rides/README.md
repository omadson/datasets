### Bike Sharing Rides Brasília

**Fonte:** [https://www.kaggle.com/datasets/joseguilhermelopes/bike-sharing-system-in-brasilia-brazil](https://www.kaggle.com/datasets/joseguilhermelopes/bike-sharing-system-in-brasilia-brazil)

Este conjunto de dados contém viagens de um sistema de bicicletas compartilhadas em Brasília, com informações do usuário, datas, horários, estações de origem e destino, duração e atraso. Ele permite estudar padrões de mobilidade urbana.

- `user_gender`: gênero informado pelo usuário.
- `user_birthdate`: data de nascimento do usuário.
- `user_residence`: residência do usuário.
- `ride_date`: data da viagem.
- `time_start`: horário de início.
- `time_end`: horário de término.
- `station_start`: estação de origem.
- `station_end`: estação de destino.
- `ride_duration`: duração da viagem em minutos.
- `ride_late`: indica se houve atraso.

Uma variável-alvo possível é `ride_duration`, caracterizando um problema de **regressão**. Também é possível usar `ride_late` em um problema de **classificação binária**.
