# MVP Análise de Dados e Boas Práticas

**Nome:** Fábio Henrique Neves Reis Ribeiro

## Dataset:

O dataset *Video Games Sales* é um conjunto de dados baixado do site *vgchartz.com*. Ele é composto apenas por jogos que venderam pelo menos 100 mil cópias.

[Video Game Sales](https://www.kaggle.com/datasets/gregorut/videogamesales?select=vgsales.csv)

## Colab

[Colab](https://github.com/fhnribeiro/mpv-puc-analise-dados-2/blob/main/MVP_Fabio_Ribeiro_v2__4052025000834_(40530010055_20250_01).ipynb)

## Descrição

O objetivo deste trabalho é tentar encontrar as relações dos jogos mais vendidos e como cada plataforma se comporta, se podemos categorizar os gêneros por mercados, plataformas ou pelo ano de lançamento.

## Hipoteses

1. O sucesso comercial de uma plataforma não depende apenas do número de jogos lançados.
2. O ciclo de vida dos consoles segue um padrão, com picos de produção e vendas nos primeiros anos após o lançamento.
3. O gênero dos jogos influencia significativamente o desempenho de vendas em diferentes regiões.

## Conclusão

A análise e o pré-processamento do dataset de vendas de jogos demonstram a importância de entender a estrutura dos dados antes da modelagem. O dataset, apesar de algumas limitações, permitiu identificar padrões de vendas por região, plataforma e gênero, além de mostrar a evolução do mercado ao longo dos anos.

As principais conclusões foram:

1. O mercado norte-americano e europeu possuem gostos semelhantes, enquanto o Japão apresenta preferências distintas, principalmente por RPGs e jogos casuais.
2. O PlayStation 2 se destaca como a plataforma de maior sucesso em vendas globais por título lançado.
3. A produção de jogos segue um ciclo de vida típico para cada console, com picos nos primeiros anos após o lançamento.
4. O tratamento de valores nulos e a remoção de outliers foram essenciais para garantir a qualidade das análises.

A análise exploratória revelou correlações importantes entre as regiões e a eficácia de visualizações como heatmaps e histogramas para distinguir padrões de vendas.

### Hipótese 1

O sucesso comercial de uma plataforma não depende apenas do número de jogos lançados, mas também do desempenho médio de vendas por título.

Verdadeiro, como vimos no gráfico de jogos produzidos x vendas, o DS foi o console com mais jogos produzidos, mas o Playstation 2 acabou sendo o console com maior vendar.

### Hipótese 2

O ciclo de vida dos consoles segue um padrão, com picos de produção e vendas nos primeiros anos após o lançamento.

Verdadeiro, como mostrado no mapa de calor e nos gráficos de produção por ano, a maioria dos consoles apresenta um aumento rápido no número de lançamentos e vendas logo após o lançamento, seguido de uma queda antes da chegada do sucessor. Isso indica um ciclo de vida típico para a maioria das plataformas.

### Hipótese 3

O gênero dos jogos influencia significativamente o desempenho de vendas em diferentes regiões.

Verdadeiro, conforme evidenciado pelos gráficos de vendas por gênero e região. América do Norte e Europa preferem gêneros como Action, Sports e Shooter, enquanto o Japão se destaca em RPG, Platform e Puzzle. Isso mostra que o perfil de consumo varia bastante entre os mercados, sendo fundamental considerar o gênero ao analisar o desempenho regional de vendas.