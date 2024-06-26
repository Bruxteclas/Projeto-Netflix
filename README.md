# Descobrindo os Segredos do Entretenimento na Netflix

## Visão Geral

Este projeto visa explorar padrões e tendências nos dados de filmes e programas de TV da Netflix, utilizando técnicas de ciência de dados e modelagem preditiva. Utilizamos um conjunto de dados detalhado disponível no Kaggle para entender melhor as preferências dos usuários e prever características de títulos como "Movie" ou "TV Show".

## Objetivos

O objetivo principal deste projeto é:

- Analisar e visualizar dados para identificar fatores que influenciam a popularidade de filmes e programas de TV na Netflix.
- Desenvolver um modelo de árvore de decisão para prever se um título é um "Movie" ou "TV Show" com base em características como duração, ano de lançamento e classificação de conteúdo.
- Validar o modelo e interpretar os resultados para oferecer insights acionáveis para a Netflix e seus criadores de conteúdo.

## Estrutura do Repositório

- **data/**: Contém o arquivo `netflix.csv` utilizado para análise.
- **notebooks/**: Notebooks Jupyter utilizados para análise exploratória, modelagem e visualizações.
- **scripts/**: Scripts Python auxiliares.
- **results/**: Resultados da análise, como gráficos e métricas de modelo.
- **README.md**: Este arquivo, fornecendo uma visão geral do projeto, sua estrutura e como reproduzir os resultados.

## Metodologia

1. **Coleta de Dados**: Utilizamos o conjunto de dados disponível no [Kaggle](https://www.kaggle.com/datasets/rahulvyasm/netflix-movies-and-tv-shows).
2. **Análise Exploratória**: Exploramos visualmente os dados para identificar padrões e correlações entre variáveis.
3. **Modelagem Preditiva**: Implementamos um modelo de árvore de decisão para classificar títulos como "Movie" ou "TV Show".
4. **Avaliação do Modelo**: Validamos o modelo usando validação cruzada e métricas de desempenho como precisão e recall.

## Resultados

Nossos resultados indicaram que o ano de lançamento e a classificação de conteúdo são indicadores significativos na distinção entre filmes e programas de TV na Netflix. Além disso, o modelo de árvore de decisão alcançou uma precisão notável na classificação de novos dados.

## Conclusões

Este projeto oferece insights valiosos para a Netflix e seus stakeholders, ajudando a melhorar recomendações de conteúdo e compreender melhor os hábitos de visualização dos usuários.

## Como Usar

Para reproduzir os resultados, siga estas etapas:

1. Clone este repositório.
2. Instale os requisitos listados no `requirements.txt`.
3. Execute os notebooks Jupyter na ordem indicada na pasta `notebooks/`.

## Contribuições

Contribuições são bem-vindas! Sinta-se à vontade para abrir issues ou pull requests para melhorias no código, correções ou sugestões adicionais.

## Licença

Este projeto é licenciado sob a [MIT License](LICENSE).
