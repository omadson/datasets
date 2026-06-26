### Sleep Efficiency

**Fonte:** [https://www.kaggle.com/datasets/equilibriumm/sleep-efficiency](https://www.kaggle.com/datasets/equilibriumm/sleep-efficiency)

Este conjunto de dados contém informações sobre hábitos de sono, características demográficas e estilo de vida de diferentes indivíduos. O objetivo é analisar como fatores comportamentais e fisiológicos influenciam a qualidade do sono e desenvolver modelos capazes de prever a eficiência do sono.

- `ID`: identificador único do registro.
- `Age`: idade do indivíduo em anos.
- `Gender`: gênero do participante.
- `Bedtime`: horário em que o indivíduo foi para a cama.
- `Wakeup time`: horário em que o indivíduo acordou.
- `Sleep duration`: quantidade total de horas dormidas.
- `Sleep efficiency`: proporção entre o tempo efetivamente dormido e o tempo total passado na cama.
- `REM sleep percentage`: porcentagem do sono total passada na fase REM, associada a sonhos e consolidação da memória.
- `Deep sleep percentage`: porcentagem do sono total passada na fase de sono profundo, importante para recuperação física.
- `Light sleep percentage`: porcentagem do sono total passada na fase de sono leve.
- `Awakenings`: número de despertares durante o período de sono.
- `Caffeine consumption`: quantidade de cafeína consumida por dia.
- `Alcohol consumption`: quantidade de álcool consumida por dia.
- `Smoking status`: indica se o indivíduo é fumante ou não.
- `Exercise frequency`: frequência semanal de prática de atividades físicas.

A variável-alvo é `Sleep efficiency`, caracterizando um problema de **aprendizado supervisionado do tipo regressão**, cujo objetivo é prever a eficiência do sono a partir das demais variáveis disponíveis no conjunto de dados.
