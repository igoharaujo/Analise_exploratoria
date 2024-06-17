<style>
    h2 {
        text-align: center;
    }
    h1 {
        text-align: center;
    }
    p {
        text-align: justify; /* Alinha o texto do parágrafo justificado */
    }
</style>

<h1> Análise Exploratória </h1>


<p>Projeto 2 do curso "Fundamentos de Linguagem Python para Análise de Dados e Data Science" da Data Science Academy.</p>


<h2>Introdução</h2>

<p>A análise exploratória de dados (EDA) é uma abordagem utilizada para resumir as principais características de um conjunto de dados, frequentemente com o auxílio de métodos visuais. O objetivo da EDA é entender a estrutura dos dados, identificar padrões, detectar anomalias, testar hipóteses e verificar suposições. Esse processo é essencial para preparar os dados para modelagem e para obter insights valiosos que possam orientar decisões e estratégias.</p>

<p>Foram elaboradas 10 perguntas para a realização deste projeto. A seguir, exploraremos cada uma delas.</p>


<h2>Pacotes</h2>

<div align=center>

|Bibliotecas              | Explicação                 |
|-------------------------|---------------------------|
|Numpy / Pandas           | - Para a manipução dos dados.|
|Matplotlib / Seaborn     | - Para a criação dos graficos|
|Datetime                 | - Para manipular colunas do tipo data|
|Math                     | - Para arredondar valores|



<h2>Base de Dados Utilizada</h2>

|Base de dados              | Local               |
|-------------------------|---------------------------|
|Dataset           |[Clique em mim](/Analise_exploratoria/dataset.csv)|
|Codigo jupyter notebook  |[Clique em mim](/Analise_exploratoria/varejo.ipynb)|

![Modelo conceitual](./img/carregando%20base%20de%20dados.png)

</div>


<h2>Análise Exploratoria</h2>

<p> Agora, vamos explorar uma série de perguntas que guiarão nossa análise exploratória de dados, acompanhadas das respectivas respostas potenciais. </p>

<h2> 1 - Qual a cidade com maior valor de venda de produtos da Categoria 'Office Supplies' </h2>


![Modelo conceitual](./img/Cidade_com_mais_vendas.png)


<h2> 2 - Qual o total de vendas por data do pedido? </h2>

![Modelo conceitual](./img/grafico1.png)

<p> O gráfico solicitado atende à questão específica, porém, para melhor legibilidade, poderíamos aplicar filtros adicionais. Neste caso, optei por filtrar os dados pelo mês. </p>

![Modelo conceitual](./img/grafico2png.png)

<h2> 3 - Qual o Total de Vendas por Estado? </h2>

![Modelo conceitual](./img/grafico3.png)

<h2> 4 - Quais São as 10 Cidades com Maior Total de Vendas? </h2>

![Modelo conceitual](./img/grafico4.png)