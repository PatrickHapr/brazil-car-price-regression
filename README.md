# Brazil Car Price Regression

Pipeline completo de Ciencia de Dados com EDA, visualizacao e modelagem de regressao para preco medio de veiculos no Brasil.

## Estrutura

- `notebooks/01_data_audit_eda.ipynb`
- `notebooks/02_exploratory_visualization.ipynb`
- `notebooks/03_regression_modeling.ipynb`
- `data/precos_carros_brasil.csv`

## Resultados numericos do processo

- Base tabular real com coluna alvo `avg_price_brl`
- Divisao treino/teste: `75% / 25%`
- Modelos testados: `RandomForestRegressor` e `XGBRegressor`

## Imagens do projeto

![Visao geral do pipeline](docs/pipeline.svg)
![Resumo numerico](docs/results-summary.svg)

## Reproducao local

1. `pip install -r requirements.txt`
2. Abrir e executar os notebooks em ordem numerica.
