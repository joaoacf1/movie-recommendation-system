# Movie Recommendation System

Este projeto é um modelo de Machine Learning de recomendação de filmes que também pode ser adaptado para músicas, livros e outros produtos. Foi desenvolvido com Python, utilizando as bibliotecas `Pandas`, `scikit-learn` e `scipy`.

## Introdução

Você já deve ter reparado que, ao avaliar um filme na sua plataforma de streaming favorita, você começa a receber recomendações de títulos semelhantes. Este projeto é um exemplo de um sistema de recomendação que implementa essa funcionalidade.


Dataset: [Kaggle](https://www.kaggle.com/code/alyssonbispopereira/recomenda-o-de-filmes-ptbr/data).

## Processo

O processo de criação do modelo de recomendação inclui as seguintes etapas:

1. **Análise Exploratória de Dados (EDA)**:
    - Remoção de valores nulos.
    - Remoção de colunas que não possuem utilidade para o modelo.

2. **Filtragem de Dados**:
    - Apenas usuários e filmes com mais de 999 avaliações foram mantidos.

3. **Transformação dos Dados**:
    - Transformação do DataFrame em uma tabela PIVOT, definindo 0 para os valores nulos.
    - Criação de uma matriz esparsa com a tabela PIVOT.

4. **Treinamento do Modelo**:
    - Treinamento do modelo de recomendação

5. **Geração de Recomendações**:
    - Geração de recomendações de filmes com base nas preferências do usuário.
