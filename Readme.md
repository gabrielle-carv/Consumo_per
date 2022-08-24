# Consumo Doméstico _Per Capita_

## Descrição

O projeto tem como objetivo fazer uma breve análise do Consumo Doméstico Real _per capita_ no mundo. Será observado seu comportamento ao longo dos anos juntamente com algumas correlações. O trabalho seguirá o seguinte roteiro:

 1 - Ranking do consumo real *per capita*;
 
 2 - Mapa mundial de temperatura do consumo real *per capita*;
 
 3 - Evolução do consumo real *per capita*, por continente: De 2000 a 2019;
 
 4 - Taxa de crescimento do consumo real *per capita*, por continente, em forma de barras;
 
 5 - Correlação: Consumo Real *per capita* x Média de horas trabalhadas;
  
 6 - Correlação: Consumo Real *per capita* x Índice de capital humano;
 
 7 - Correlação: Consumo Real *per capita* x Índice de gini.
 
## Como Usar

Pode-se encontrar acima duas pastas, são elas `codg-base` e `pasta-auxiliar`, para realizar as sete etapas completas da análise é necessário que seja realizado o Download de ambas. Na pasta `cod-base`, encontra-se o código utilizado para tratar as tabelas e plotar os gráficos, é possível já fazer uma pré-visualização dos mesmos. Já na pasta `pasta-auxiliar`, tem um arquivo CSV com os dados do Índice de Gini no Brasil, que será utilizado em nossa última análise gráfica (Correlação: Consumo Real *per capita* x Índice de gini). Também possível realizar o Download do mesmo no site do [IPEAdata](http://www.ipeadata.gov.br/Default.aspx).

## Dados

Os dados utilizados no projeto são da Penn World Table (versão 10.0), liberados pela University of Groningen, e podem ser encontrado já tratados no site da [Basededados](https://basedosdados.org/). O foco foi examinar o consumo doméstico real _per capita_ a nível continental, e para isso foi utilizado tabelas com os nomes dos países em português e respectivamente o continente a quem pertence, cruzando com a tabela da PWT, ou seja foram filtradas a  `basedosdados.br_bd_diretorios_mundo.pais` e a `basedosdados.br_bd_diretorios_mundo.continente` e combinadas nas tabela  `basedosdados.nl_ug_pwt.microdados`. Para uma única análise também foi utilizado o Índice de Gini do Brasil, coletado no site do [IPEAdata](http://www.ipeadata.gov.br/Default.aspx).

## Análise Gráfica

### 1 - Ranking do consumo real *per capita*
A primeira visualização mostra um ranking do top 10 países com o maior consumo doméstico real _per capita_ para o ano de 2019. 

<div align="center">
<img src="https://user-images.githubusercontent.com/77730866/186523294-f8569349-843d-4a9b-ab54-7c7aa16bee43.png" width="500px" />
</div>

###  2 - Mapa mundial de temperatura do consumo real *per capita* 

A segunda visualização nos mostra um mapa mundial de temeperatura do consumo real *per capita*, relativo ao ano de 2019. É possível fazer uma localização geográfica do top 10. 

<div align="center">
<img src="https://user-images.githubusercontent.com/77730866/186526327-bbe7862c-c75a-4d2d-8cc0-b858f49b4b75.png" width="800px" />
</div>

###  3 - Evolução do consumo real *per capita*, por continente: De 2000 a 2019

O terceiro gráfico nos mostra, em relação aos continentes, o consumo doméstico real médio de cada ao longo dos anos. É válido ressaltar a queda acentuada após o ano de 2008 para os continentes da América do Norte e Europa, em que no contexto mundial havia estourado a bolha imobiliária americana.  

<div align="center">
<img src="https://user-images.githubusercontent.com/77730866/186526605-2b3c16d4-a2b9-4037-af65-5998fb77d9ef.png" width="900px" />
</div>

###  4 - Taxa de crescimento do consumo real *per capita*, por continente, em forma de barras

A quarta visualização nos dá uma ótica na margem dos anos sobre a taxa de crescimento do consumo real *per capita*, por continente, de 2018 para 2019. Podemos, com isso, reparar que apesar de historicamente o continente africano não se mostrar com um crescimento acentuado, conseguiu ter uma taxa de crescimento maior que a Oceania e América do Sul.

<div align="center">
<img src="https://user-images.githubusercontent.com/77730866/186526893-d3a4d6f8-44f1-43ba-b595-c091bfe12d9d.png" width="900px" />
</div>

###  5 - Correlação: Consumo Real *per capita* x Média de horas trabalhadas

O quinto gráfico nos mostra a correlação entre o consumo real *per capita* e a média de horas trabalhadas, entre os anos 2000-2019. É possível no código assistir a animação entre os anos. 

<div align="center">
<img src="https://user-images.githubusercontent.com/77730866/186527115-a8b743e7-3292-4bce-8327-34e3b13c885b.png" width="800px" />
</div>

###  6 - Correlação: Consumo Real *per capita* x Índice de capital humano

O sexto gráfico expõe a correlação entre o consumo real *per capita* e o índice de capital humano, entre os anos 2000-2019. É possível no código assistir a animação entre os anos.

<div align="center">
<img src="https://user-images.githubusercontent.com/77730866/186527327-fa9c4d23-fa26-40a7-98ff-f268a74d5a72.png" width="800px" />
</div>

###  7 - Correlação: Consumo Real *per capita* x Índice de gini

A sétima e última visualização é uma análise sobre o Brasil ao longo dos anos sobre a correlação entre o consumo real *per capita* e o Índice de Gini. Uma hipótese para o consumo doméstico real _per capita_ estar aumentando viria por consequência de um percentual pequeno da população. Para checar tal cenário foi feita análise gráfica. O Índice de Gini é um instrumento para medir o grau de concentração de renda, no qual o valor zero representa a situação de igualdade. Pode-se observar que ao longo dos anos o índice vem caindo, e o consumo aumentando, o que quebraria tal hipótese.

<div align="center">
<img src="https://user-images.githubusercontent.com/77730866/186527487-143fd4c4-8a9e-45b6-8d34-2cb52faf746f.png" width="900px" />
</div>



## Bibliotecas 

- Basedosdados
 
- Pandas 

- Matplotlib

- Seaborn 

- Plotly

- Os

