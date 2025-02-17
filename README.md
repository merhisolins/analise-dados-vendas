# Analise de Dadosde  Vendas


## Descrição:

O objetivo principal é identificar padrões que influenciam o sucesso de um jogo, utilizando informações como:

Avaliações de usuários e especialistas
Gêneros e plataformas (ex.: Xbox, PlayStation)
Classificações etárias ESRB (Entertainment Software Rating Board)
Dados históricos de vendas
Com base nesses padrões, o intuito é fornecer insights que auxiliem na elaboração de campanhas publicitárias e na previsão de possíveis sucessos.

Os dados analisados abrangem até o ano de 2016, simulando o planejamento de uma campanha para 2017. O foco é fortalecer habilidades de análise de dados e extração de insights para tomadas de decisão estratégicas no mercado de jogos.


## Conjunto de Dados:

Atualmente o conjunto de dados utilizado neste projeto inclui as seguintes colunas:

—Name (nome)

—Platform (plataforma)

—Year_of_Release (Ano de lançamento)

—Genre (gênero)

—NA_sales (vendas norte-americanas em milhões de USD)

—EU_sales (vendas na Europa em milhões de USD)

—JP_sales (vendas no Japão em milhões de USD)

—Other_sales (vendas em outros países em em milhões de USD)

—Critic_Score (Pontuação crítica) (máximo de 100)

—User_Score (Pontuação do usuário) (máximo de 10)

—Classificação (ESRB)

## Arquitetura e Tecnologias Utilizadas

Este projeto segue princípios de **arquitetura modular**, garantindo escalabilidade e reuso eficiente de código. A estrutura adota uma abordagem **camada por camada**, separando **dados, lógica de negócio e visualização**.

🔹 **Camada de Dados**: Tratamento e preparação dos dados com `Pandas` e `NumPy`.  
🔹 **Camada de Análise**: Aplicação de estatística descritiva, análise exploratória e testes de hipóteses.  
🔹 **Camada de Modelagem**: Implementação de técnicas de aprendizado de máquina para previsão de vendas.  
🔹 **Camada de Apresentação**: Geração de relatórios gráficos e dashboards interativos.

As principais tecnologias e bibliotecas utilizadas incluem:

- **Python 3.8+** – Linguagem base para análise e processamento de dados.
- **Pandas / NumPy** – Manipulação e tratamento de dados estruturados.
- **Matplotlib / Seaborn** – Criação de visualizações gráficas avançadas.
- **Scikit-Learn** – Modelos de machine learning para análise preditiva.
- **Jupyter Notebook** – Desenvolvimento e apresentação de insights.
