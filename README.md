# Exercícios de Data Science ⚽

Notebook de análise de dados de partidas de futebol, desenvolvido como atividade de Data Science. O trabalho explora estatísticas do conjunto de dados e apresenta gráficos e tabelas com Python.

## Análises

- Dados ausentes, tipos e estatísticas descritivas.
- Média de gols por partida em cada dia da semana.
- Capitães por equipe, formações e posse de bola.
- Classificação por pontos e público por equipe e partida.
- Visualizações com Matplotlib, Seaborn, Plotly e Dash.

## Como executar

1. Abra `Prova_Data_Science_N1.ipynb` no [Google Colab](https://colab.research.google.com/) ou no Jupyter.
2. Baixe o [arquivo matches.csv](https://raw.githubusercontent.com/mdietterle/repositorio_dados/main/matches.csv). No Colab, envie-o para `/content/matches.csv`; em outro ambiente, ajuste os caminhos nas células.
3. Instale as bibliotecas usadas no notebook: `pandas`, `numpy`, `matplotlib`, `seaborn`, `requests`, `beautifulsoup4`, `plotly` e `dash`.
4. Execute as células em ordem. Caso a primeira célula que utiliza `np` apresente erro, execute `import numpy as np` antes dela.

Algumas células dependem de serviços externos, dados disponíveis e compatibilidade de versões das bibliotecas. O notebook contém uma chave de API no código; ela deve ser revogada ou rotacionada caso ainda esteja ativa, e substituída por uma configuração privada antes do uso.

## Arquivo principal

- `Prova_Data_Science_N1.ipynb` — perguntas, código, análises e visualizações.
