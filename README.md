<div align="center">

# Análise Exploratória

Projeto 2 do curso "Fundamentos de Linguagem Python para Análise de Dados e Data Science" da Data Science Academy.

## Introdução

A análise exploratória de dados (EDA) é uma abordagem utilizada para resumir as principais características de um conjunto de dados, frequentemente com o auxílio de métodos visuais. O objetivo da EDA é entender a estrutura dos dados, identificar padrões, detectar anomalias, testar hipóteses e verificar suposições. Esse processo é essencial para preparar os dados para modelagem e para obter insights valiosos que possam orientar decisões e estratégias.

Foram elaboradas 10 perguntas para a realização deste projeto. A seguir, exploraremos cada uma delas.

## Pacotes

| Bibliotecas         | Explicação                      |
|---------------------|---------------------------------|
| Numpy / Pandas      | Para a manipulação dos dados.   |
| Matplotlib / Seaborn| Para a criação dos gráficos.    |
| Datetime            | Para manipular colunas do tipo data. |
| Math                | Para arredondar valores.        |

## Base de Dados Utilizada

| Base de dados | Local                                    |
|---------------|------------------------------------------|
| Dataset       | [Clique aqui](/dataset.csv) |
| Código Jupyter Notebook | [Clique aqui](/varejo.ipynb) |

![Modelo conceitual](./img/carregando%20base%20de%20dados.png)

## Análise Exploratória

Agora, vamos explorar uma série de perguntas que guiarão nossa análise exploratória de dados, acompanhadas das respectivas respostas potenciais.

### 1 - Qual a cidade com maior valor de venda de produtos da categoria 'Office Supplies'?

![Cidade com mais vendas](./img/Cidade_com_mais_vendas.png)

### 2 - Qual o total de vendas por data do pedido?

![Gráfico de vendas por data](./img/grafico1.png)

O gráfico solicitado atende à questão específica, porém, para melhor legibilidade, poderíamos aplicar filtros adicionais. Neste caso, optei por filtrar os dados pelo mês.

![Gráfico de vendas por mês](./img/grafico2png.png)

### 3 - Qual o total de vendas por estado?

![Gráfico de vendas por estado](./img/grafico3.png)

### 4 - Quais são as 10 cidades com maior total de vendas?

![Gráfico das 10 cidades com maior total de vendas](./img/grafico4.png)



### 5 -  Qual segmento teve o maior total de vendas? Desmostre o resultado através de um gráfico de pizza.

![Gráfico das 10 cidades com maior total de vendas](./img/grafico5pizza.png)


### 6 - Qual o total de vendas por segmento e por ano?


![Gráfico das 10 cidades com maior total de vendas](./img/grafico6segmento_vendas_ano.png)



## Pergunta de Negócio 7 (Desafio Nível Júnior):

Os  gestores  da  empresa  estão  considerando conceder  diferentes  faixas  de  descontos  e gostariam de fazer uma simulação com base na regra abaixo:

</div>

- Se o Valor_Venda for maior que 1000 recebe 15% de desconto.

- Se o Valor_Venda for menor que 1000 recebe 10% de desconto.Quantas Vendas Receberiam 15% de Desconto?

<div align="center">

![--](./img/per_negocio7.png)


### Pergunta de Negócio 8 (Desafio Nível Master):

Considere  Que  a  Empresa  Decida  Conceder  o  Desconto  de  15%  do  Item  Anterior.  Qual Seria a Média do Valor de Venda Antes e Depois do Desconto?

![--](./img/per_negocio8.png)




</div>
