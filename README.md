# 🎮 Análise de Dados e Recomendação de Jogos

## 🎯 Objetivo

O projeto tem como objetivo realizar uma análise exploratória de dados (EDA) em um catálogo de jogos digitais, identificando padrões, tendências e comportamentos dentro do conjunto de dados.
Além disso, foi implementada uma função de recomendação simples, utilizando métricas estatísticas e similaridade de cosseno para sugerir jogos com base em características em comum — como preço, avaliações e nota média.

## 📚 Principais Aprendizados

Durante o desenvolvimento desse projeto, aprendi a importância de seguir um fluxo de análise bem estruturado — desde a limpeza dos dados até a visualização e interpretação dos resultados.
Alguns aprendizados que marcaram o processo:

- Entender como usar o Pandas para tratar valores ausentes e analisar distribuições.

- Criar gráficos informativos com o Matplotlib para visualizar dados reais.

- Aplicar conceitos estatísticos como média, mediana e desvio padrão para entender o comportamento dos jogos.

- Utilizar a similaridade do cosseno para construir uma base de recomendação simples e funcional.

- Integrar diferentes etapas de um projeto de dados dentro de um ambiente real de desenvolvimento (Google Colab e GitHub).

## Tecnologias Utilizadas

Linguagem: `Python`

### Bibliotecas:

`pandas` → manipulação e análise de dados

`numpy` → cálculos numéricos e estatísticos

`matplotlib` → geração de gráficos e visualizações

### Ferramentas:

`Google Colab` → ambiente de desenvolvimento em nuvem
`Git e GitHub` → controle de versão e publicação do código

### Principais Partes do Código

#### Análise Exploratória (EDA)

Nessa etapa, foi feita uma exploração completa do conjunto de dados: contagem de gêneros, análise por plataforma e ano de lançamento, além de cálculo de médias e medianas das variáveis numéricas.
O objetivo foi entender o comportamento geral dos jogos e visualizar padrões por meio de gráficos de distribuição.
Essa parte ajudou a identificar tendências como os anos com mais lançamentos e gêneros mais populares.

#### Função de Recomendação

A recomendação foi feita com base na similaridade do cosseno, uma técnica matemática que mede o quanto dois itens se parecem em termos de características numéricas.
Ao normalizar os dados (como preço, rating e número de reviews), foi possível calcular quais jogos possuem comportamentos semelhantes e sugeri-los como recomendações personalizadas.
Essa parte uniu estatística, álgebra linear e raciocínio analítico em uma aplicação prática — algo essencial em projetos de análise e ciência de dados.

## Considerações Finais

Esse projeto foi uma ótima oportunidade para colocar em prática conceitos de análise exploratória, estatística e recomendação, consolidando o uso do Python como principal ferramenta para transformar dados em informação.
Mais do que aprender bibliotecas, o foco foi entender como pensar como um analista de dados — explorando, comparando e descobrindo histórias escondidas nos números.