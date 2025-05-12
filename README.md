# 📊 Atividade de Data Science - Compet 2025

#### Índice

<p align="center"> 
    <a href="#sobre-a-atividade">Sobre a Atividade</a> &nbsp;&nbsp; | &nbsp;&nbsp;
    <a href="#análise-dos-dados">Análise dos Dados</a> &nbsp;&nbsp; | &nbsp;&nbsp;
    <a href="#dashboard">Dashboard</a> &nbsp;&nbsp; | &nbsp;&nbsp; 
    <a href="#tecnologias-utilizadas">Tecnologias Utilizadas</a> &nbsp;&nbsp; | &nbsp;&nbsp;
    <a href="#autora">Autora</a> &nbsp;&nbsp; 
</p>

## Sobre a atividade

- Escolher um conjunto de dados disponível no portal do INEP; 
- Utilizar as bibliotecas Python;
- Aplicar técnicas de wrangling, selecionando atributos relevantes e realizando o tratamento de valores faltantes ou inconsistentes;
- Interpretar de forma sucinta as saídas de info() e describe(); 
- Usar operações de agregação como groupby;
- Gerar visualizações, exportar o conjunto de dado tratado para o Power BI, para a criação de um dashboard.

<br>

## Análise dos dados 

**Base de dados escolhida:** Adequação da formação docente (2024)

**Link:** https://www.gov.br/inep/pt-br/acesso-a-informacao/dados-abertos/indicadores-educacionais/adequacao-da-formacao-docente

#### Sobre a base de dados

A base tem por objetivo apresentar dados referentes ao percentual de docentes na Educação Infantil, Ensino Médio e EJA (Educação para Jovens e Adultos) por grupo de adequação da formação à disciplina que leciona. 

Sendo assim, foi possível observar que a formação docente adequada é mais experissiva nos Ensino Médio da EJA do que no Ensino Fundamental, além das redes federais se destacarem positivamente em relação as municipais e estaduais, onde se concentra mais docentes com formação inadequada ou fora de sua área de atuação. Foi interessante observar e fazer a análises, pois acreditei que o Ensino Médio EJA teria uma maior discrepância em relação ao Ensino Fundamental, refutando assim umas das minhas teses. Contudo a minha tese sobre a zona rural ser mais defasada em relação a zona urbana foi validada, destacando dores que permeiam a Educação de Jovens e Adultos no Brasil. 

#### Dicionário de dados

| **Variáveis** | **Descrição** | **Tipo** | 
|---------------|---------------| --------------- |
| GEO | Unidade Geográfica | Categórico |
| LOC | Categoria | Categórico | 
| DA | Dependência Administrativa | Categórico | 
| EJAFUNG1 | EJA - Ensino Fundamental - Grupo 1 | Numérico | 
| EJAFUNG2 | EJA - Ensino Fundamental - Grupo 2 | Numérico | 
| EJAFUNG3 | EJA - Ensino Fundamental - Grupo 3 | Numérico | 
| EJAFUNG4 | EJA - Ensino Fundamental - Grupo 4 | Numérico | 
| EJAFUNG5 | EJA - Ensino Fundamental - Grupo 5 | Numérico | 
| EJAMEDG1 | EJA - Ensino Médio - Grupo 1 | Numérico |
| EJAMEDG2 | EJA - Ensino Médio - Grupo 2 | Numérico |
| EJAMEDG3 | EJA - Ensino Médio - Grupo 3 | Numérico |
| EJAMEDG4 | EJA - Ensino Médio - Grupo 4 | Numérico |
| EJAMEDG5 | EJA - Ensino Médio - Grupo 5 | Numérico |


#### Perguntas que feitas a essa base de dados: 

A análise dos dados foi orientada a algumas perguntas como: 

- Em qual zona a EJA sofre uma maior discrepância entre a formação docente e a disciplina ensinada num total?

- Analisando separadamente, qual zona apresenta maior discrepância na formação docente para a EJA do Ensino Fundamental? E para a EJA do Ensino Médio?

- Em quais dependências admnistritativas há uma maior incidênica dessa discrepância em relação a EJA do Ensino Fundamental? E no Ensino Médio? 

- Há alguma relação entre a unidade geográfica e a localização em realação a EJA do Ensino Fundamental?  E no Ensino Médio? 

- Existe alguma correlação entre a unidade geográfica e a dependencia administrativa em relação à formação docente da EJA no Ensino Fundamental? E no Ensino Médio?

- Ao fazer uma comparação entre o Ensino Fundamental EJA e Ensino Médio EJA, qual podemos observar que há uma maior dispariadade?

- Qual região do Brasil apresenta a maior variação na formação dos docentes da EJA em termos de adequação (Grupos 1 a 5)?

- Qual grupo de formação docente (1, 2, 3, 4 e 5) concentra um maior percentual desses docentes, considerando a zona geográfica?

- Qual grupo de formação docente (Grupo 1, 2, 3, 4, 5) apresenta maior percentual de docentes na EJA, considerando a dependência administrativa?

- Comparando as regiões do Brasil, qual apresenta maior desigualdade na adequação da formação docente para a EJA?

## Dashboard

<p align="center">
    <p>Capa</p>
    <img src="https://i.imgur.com/gWEo9L8.png">
</p>
<p align="center">
    <p>Visão Geral</p>
    <img src="https://i.imgur.com/4enjcvR.png">
</p>
<p align="center">
    <p>Comparativo entre o Ensino Fundamental e Ensino Médio</p>
    <img src="https://i.imgur.com/n8URzui.png">
</p>
<p align="center">
    <p>Ensino Fundamental - EJA</p>
    <img src="https://i.imgur.com/mBZyBXL.png">
</p>
<p align="center">
    <p>Ensino Médio - EJA</p>
    <img src="https://i.imgur.com/QB3KycE.png">
</p>

## Tecnologias Utilizadas

- Pandas 
- Matplotlib
- Python

## Autora

#### Ruth Xavier 

- [Linkedin](https://www.linkedin.com/in/ruthxavier/)
- [Github](https://github.com/xavierruth)
- [Behance](https://www.behance.net/xavierruth)