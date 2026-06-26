### Brazilian Temperature Timeseries

**Fonte:** [https://www.kaggle.com/datasets/volpatto/temperature-timeseries-for-some-brazilian-cities](https://www.kaggle.com/datasets/volpatto/temperature-timeseries-for-some-brazilian-cities)

Este conjunto de dados reúne séries temporais anuais de temperatura para diferentes cidades brasileiras. Cada arquivo representa uma estação/cidade e contém médias mensais, médias sazonais e média anual.

Arquivos incluídos:

- `station_belem.csv`
- `station_curitiba.csv`
- `station_fortaleza.csv`
- `station_goiania.csv`
- `station_macapa.csv`
- `station_manaus.csv`
- `station_recife.csv`
- `station_rio.csv`
- `station_salvador.csv`
- `station_sao_luiz.csv`
- `station_sao_paulo.csv`
- `station_vitoria.csv`

Colunas:

- `YEAR`: ano da observação.
- `JAN` a `DEC`: temperatura média mensal.
- `D-J-F`: média sazonal de dezembro, janeiro e fevereiro.
- `M-A-M`: média sazonal de março, abril e maio.
- `J-J-A`: média sazonal de junho, julho e agosto.
- `S-O-N`: média sazonal de setembro, outubro e novembro.
- `metANN`: média anual de temperatura.

A variável-alvo pode ser `metANN`, caracterizando um problema de **regressão em séries temporais** para previsão de temperatura média anual.
