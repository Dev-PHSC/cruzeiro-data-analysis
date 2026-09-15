# Cruzeiro Data Analysis

Projeto de Ciência de Dados aplicado ao Cruzeiro Esporte Clube.

## Sobre o projeto

Futebol sempre foi uma das minhas grandes paixões, e o Cruzeiro é o clube que dá sentido a essa paixão.

Sou estudante de Ciência da Computação e, durante a disciplina de Ciência de Dados, decidi unir meu interesse por futebol aos conhecimentos que estou desenvolvendo durante a graduação.

O **Cruzeiro Data Analysis** foi criado com três objetivos principais:

- praticar conceitos e ferramentas estudados em Ciência de Dados;
- desenvolver um projeto próprio para compor meu portfólio no GitHub;
- aprofundar meu conhecimento sobre o desempenho histórico do Cruzeiro por meio dos dados.

Ao longo do projeto, pretendo trabalhar com organização, tratamento, exploração, visualização e interpretação dos dados.

## Objetivos

O projeto pretende analisar o desempenho do Cruzeiro no Campeonato Brasileiro nas temporadas:

- 2003 até 2025

Esses dados serão utilizados para investigar diferentes aspectos do desempenho da equipe ao longo dos anos.

## Análises planejadas

### 1. Evolução histórica

Analisar a evolução do Cruzeiro ao longo das temporadas utilizando informações como:

- jogos disputados;
- vitórias, empates e derrotas;
- gols marcados e sofridos;
- saldo de gols;
- pontos;
- aproveitamento.

### 2. Desempenho como mandante e visitante

Comparar o desempenho do Cruzeiro jogando em casa e fora de casa.

Entre os indicadores analisados estarão:

- aproveitamento;
- gols por partida;
- número de vitórias;
- gols sofridos.

### 3. Jogadores mais decisivos

Analisar a participação dos jogadores utilizando informações como:

- gols;
- assistências;
- minutos jogados;
- participações em gols;
- desempenho por 90 minutos.

### 4. Desempenho contra adversários

Investigar o retrospecto do Cruzeiro contra diferentes clubes do Campeonato Brasileiro.

A análise poderá incluir:

- número de confrontos;
- vitórias;
- empates;
- derrotas;
- aproveitamento por adversário.

### 5. Fatores relacionados aos resultados

Investigar quais estatísticas de uma partida apresentam maior relação com vitórias, empates e derrotas.

Algumas variáveis que poderão ser estudadas:

- posse de bola;
- finalizações;
- finalizações no alvo;
- escanteios;
- gols marcados e sofridos.


## Perguntas de interesse

Ao longo do projeto, algumas das perguntas que pretendo investigar são:

- Como o desempenho do Cruzeiro evoluiu ao longo das temporadas?
- O desempenho como mandante é significativamente melhor do que como visitante?
- Quais jogadores tiveram maior impacto nos resultados?
- Contra quais adversários o Cruzeiro apresenta melhor ou pior retrospecto?
- Quais estatísticas de jogo estão mais associadas a vitórias?

## Tecnologias

O projeto utilizará principalmente:

- Python
- Pandas
- NumPy
- Matplotlib
- Jupyter Notebook

Outras ferramentas poderão ser incorporadas conforme o projeto evoluir.

## Estrutura do projeto

```text
cruzeiro-data-analysis/
│
├── data/
│   ├── raw/
│   └── processed/
│
├── notebooks/
│
├── src/
│
├── images/
│
├── README.md
├── requirements.txt
└── .gitignore
```

## Fonte dos dados

Os dados utilizados neste projeto foram obtidos a partir do [Brasileirao_Dataset](https://github.com/adaoduque/Brasileirao_Dataset).

O conjunto contém informações sobre partidas do Campeonato Brasileiro entre 2003 e 2025.
