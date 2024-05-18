# Movie Recommendation System

Este projeto é um modelo de Machine Learning de recomendação de filmes que também pode ser usado para músicas, livros e etc. 

Desenvolvido com Python, usando as bibliotecas `Pandas`, `scikit-learn` e `scipy`.

Você já deve ter reparado que ao avaliar um filme na sua platafor de streaming, você começa a receber recomendações de titulos semelhante, esse projeto é um exemplo desse sistema de recomendação.

Link dataset: https://www.kaggle.com/code/alyssonbispopereira/recomenda-o-de-filmes-ptbr/data

# Processo

- Análise exploratoria removendo valores nulos e colunas que não possuissem utilidades.
- Apenas usuários e filmes com mais de 999 avaliações foram mantidos.
- transformando o DataFrame em um PIVOT, definindo 0 para os valores nulos.
- Criando uma Matriz Sparsa com o PIVOT.
- Treinamento do modelo e recomendações

