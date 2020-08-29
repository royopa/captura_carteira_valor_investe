# captura_carteira_valor_investe

Utilitários para webscraping das Carteira Valor

https://valor.globo.com/valor-data/carteira-valor/

## Carteira Valor

A Carteira Valor é formada pelas 10 ações mais recomendadas pelas corretoras participantes, selecionadas a partir da indicação mensal de cinco papéis por instituição. Em caso de empate, prevalecem as ações com maior volume financeiro médio em bolsa, no período de 90 últimos dias úteis encerrado no fim de cada mês.

## Iniciando

Para iniciar o processo, inicie o seu jupyter, comando abaixo:

> cd [pasta_onde_baixei_o_projeto]

> jupyter notebook

## Capturando arquivos

A captura dos arquivos do site é realizada usando o selenium, através do notebook [captura_arquivos_carteira_valor.ipynb](captura_arquivos_carteira_valor.ipynb)

## Consolidando arquivos

Após a captura dos arquivos, eles são consolidados para facilitar a importação em arquivos csv na pasta [dados](dados). O notebook utilizado para essa tarefa é o [consolida_dados.ipynb](consolida_dados.ipynb)
