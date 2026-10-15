# Machine Learning - Solucoes de Energias Renovaveis e Sustentaveis (SERS)

## Descricao
Este repositorio contem o projeto de analise de dados e aplicacao de modelos de Machine Learning desenvolvido para a disciplina de Solucoes de Energias Renovaveis e Sustentaveis (SERS), parte da grade do Bacharelado em Ciencia da Computacao da FIAP.

O objetivo principal deste estudo e prever e analisar a estabilidade de redes eletricas inteligentes (Smart Grids). Para isso, foi utilizado o dataset "Electrical Grid Stability Simulated Data", que simula o comportamento de sistemas com geracao e consumo descentralizados.

## Fonte dos Dados
Os dados analisados neste projeto foram extraidos do UCI Machine Learning Repository:
- Dataset: Electrical Grid Stability Simulated Data
- Link: https://archive.ics.uci.edu/dataset/471/electrical+grid+stability+simulated+data

O conjunto de dados apresenta variaveis preditivas como o tempo de reacao dos nos da rede (tau), potencia nominal (p) e elasticidade de preco (g), buscando prever a variavel alvo que indica a estabilidade ou instabilidade do sistema.

## Tecnologias e Bibliotecas Utilizadas
- Python 3.x
- Pandas e NumPy (Manipulacao e tratamento de dados)
- Scikit-Learn (Construcao, treinamento e avaliacao dos modelos de Machine Learning)
- Matplotlib e Seaborn (Visualizacao de dados e analise exploratoria)

## Estrutura do Repositorio
A organizacao dos arquivos reflete o pipeline classico de um projeto de Ciencia de Dados:

- /data: Diretorio destinado ao armazenamento do arquivo CSV original baixado da UCI e de possiveis bases tratadas.
- /notebooks: Cadernos interativos (Jupyter Notebooks) contendo a Analise Exploratoria de Dados (EDA) passo a passo.
- /src: Scripts em Python contendo as funcoes de pre-processamento, separacao de dados (train/test split) e treinamento dos algoritmos.
- /models: Modelos treinados e exportados para inferencias futuras.
