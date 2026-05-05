# Análise Exploratória de Dados - Spotfy Tracks Dataset

Este projeto é a entrega final da disciplina de Python Para Análise de Dados. O objetivo foi aplicar técnicaslimp de ETL, eza, qualidade de dados e Análise Exploratória (EDA) em um dataset real, cumprindo todos os requisitos obrigatórios como o uso das bibliotecas (pandas, numpy, matplotlib).

## Sobre o Dataset
O dataset escolhido foi o **Spotify Tracks Dataset**. Ele contém dados de mais de 114 mil faixas do Spotify, com características extraídas da própria API da plataforma.

## Fonte: [Kaggle - Spotify Tracks Dataset](https://www.kaggle.com/datasets/maharshipandya/-spotify-tracks-dataset?resource=download)
## Tamanho original: +114.000 linhas e 21 colunas.

## Estrutura do Projeto
projeto/
├── data/
│   ├── raw/                # Dataset original bruto baixado do Kaggle
│   └── processed/          # Dataset limpo após o pipeline de ETL
├── src/                    
│   ├── etl.py              # Script de limpeza, uso do numpy e transformação 
│   └── analise.py          # Script de perguntas de pesquisa e gráficos 
├── relatorio.pdf           # Relatório final com as conclusões 
├── README.md               # Instruções de execução do projeto
└── requirements.txt        # Bibliotecas necessárias

# omo executar o projeto

## Preparar os dados:
Baixe o arquivo CSV original no link do Kaggle citado acima.
Salve o arquivo dentro da pasta data/raw/ com o nome dataset.csv.

## Instalar dependências: 
Abrir o terminal na pasta principal do projeto e instale as bibliotecas obrigatórias:
pip install -r requirements.txt

## Executar o ETL e Limpeza
Rode o script de ETL.
Ele irá remover nulos, tratar duplicatas e utilizar Pandas e Numpy para derivar novas variáveis.

python src/etl.py

Após a execução, o arquivo dataset_clean.csv será gerado na pasta data/processed/.

## Executar a Análise
Rodar o script de análise para gerar as visualizações (gráficos).

python src/analise.py






