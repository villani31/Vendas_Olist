# Projeto Analise de dados Vendas Olist

<p align="center">
  <img src="https://image.freepik.com/vetores-gratis/grupo-de-analistas-trabalhando-em-graficos_1262-21249.jpg?w=740" alt="Projeto"height=400px >
</p>

Esse projeto é uma iniciativa da [Stack Tecnologia](https://stacktecnologias.com.br/), que criou o **Stack Labs**, um desavio em equipe simulando uma empresa real, com objetivo de fazer uma analise completa da **Olist**.

**Olist** é uma statup Brasileira que atua no segmento de e-commerce, sobretudo por meio de marketplace, conecta pequenas empresas de todo o Brasil, esses comerciantes podem vender seus produtos através da **Lojas Olist**, e enviá-los diretamente para os clientes usando os parceiros de logística **Olist**.

## Membros da Squad

* Bruno Barbosa Medeiros - [Linkedin](https://www.linkedin.com/in/bruno-medeiros-75305a107/)
* Paulo Sergio da Silva Júnior - [Linkedin](https://www.linkedin.com/in/paulosilvajr/)
* Thiago Villani - [Linkedin](https://www.linkedin.com/in/thiagovillani)
* Janize Castilho - 

## Objetivo do Projeto

Fazer uma analise completa dos dados disponibilizado públicamente no [Kaggle](https://www.kaggle.com/olistbr/brazilian-ecommerce), entendimento de como funciona a distribuição das vendas, criando um Dashboard com as analises feitas.

Nesse projeto passamos por todas as estapas de um projeto de dados, o squad foi divido com as seguintes funções:

* Gerente de Projetos
* Engenheiro de Dados
* Analista de Dados
* Cientista de Dados

## Tecnologias utilizada

* Docker
* Airflow
* Python
* Minio(S3)
* Mysql
* Jupyter Notebook
* Plotly

## Arquitetura da solução

Ambiente de Engenharia de Dados, criado de forma **On-Premises**. Containers gerado para o projeto utilizando **Docker-compose**:

* Airflow(e dependencias)
* Mysql
* Spark
* Jupyter-notebook
* Minio

<p align="center">
  <img src="https://github.com/villani31/Vendas_Olist/blob/main/imagens/arquitetura-solucao.png" alt="Arquitetura"height=400px >
</p>

<p align="center">
  <img src="https://github.com/villani31/Vendas_Olist/blob/main/imagens/airflow01.png" alt="Airflow"height=400px >
</p>

<p align="center">
  <img src="https://github.com/villani31/Vendas_Olist/blob/main/imagens/airflow02.png" alt="Airflow"height=400px >
</p>

## Análise Exploratória dos Dados

Foi feito uma análise geral dos dados, com o objetivo de entendimento, limpeza dos dados, criado um novo dataset consolidado, e gerar insights para identificar padrões:

[Clique aqui para acesso ao Notebook completo.](https://github.com/villani31/Vendas_Olist/blob/main/Analise_De_Dados_Olist.ipynb)

## Gerado alguns Insights

### Resumo da análise:
* Pedidos entregue com sucesso - 94320
* Forma de pagamento mais utilizada é cartão de crédito - 70481
* Categoria de produto mais vendido (cama_mesa_banho) - 10542
* Clientes que mais compra, são do estado de São Paulo - 44%
* Pedidos por dia, pico de - 1200
* Valor médio de transação - R$ 107,07
* Valor médio de frete - R$ 15,75

<p align="center">
  <img src="https://github.com/villani31/Vendas_Olist/blob/main/imagens/categoria_produtos.png" alt="Categoria_Produtos"height=400px >
</p>

<p align="center">
  <img src="https://github.com/villani31/Vendas_Olist/blob/main/imagens/clientes_estado.png" alt="Clientes_estado"height=400px >
</p>

<p align="center">
  <img src="https://github.com/villani31/Vendas_Olist/blob/main/imagens/distribuicao_forma_pagamento.png" alt="Forma_Pagamento"height=400px >
</p>

<p align="center">
  <img src="https://github.com/villani31/Vendas_Olist/blob/main/imagens/metodo_pagamento.png" alt="Metodo_pagamento"height=400px >
</p>

<p align="center">
  <img src="https://github.com/villani31/Vendas_Olist/blob/main/imagens/pedidos_dia.png" alt="Pedido_dia"height=400px >
</p>

<p align="center">
  <img src="https://github.com/villani31/Vendas_Olist/blob/main/imagens/pedidos_mes.png" alt="Pedido_mes"height=400px >
</p>

<p align="center">
  <img src="https://github.com/villani31/Vendas_Olist/blob/main/imagens/status_pedidos.png" alt="Status_pedido"height=400px >
</p>

<p align="center">
  <img src="https://github.com/villani31/Vendas_Olist/blob/main/imagens/valor_medio.png" alt="Valor_medio"height=400px >
</p>

## Dashboard final com Plotly

Após análise geral feita, criado um Dashboard utilizando ferramenta **Chart-Studio** da [Cloud Plotly](https://plotly.com/).

Plotly é uma biblioteca de visualização de dados do Python, e que permite a criação e publicação de gráficos interativos, bonitos e de altíssima qualidade.

[Clique aqui](https://plotly.com/~iamthiagovillani/15/untitled-dashboard/) para acessar o **Dashboard**.

<p align="center">
  <img src="https://github.com/villani31/Vendas_Olist/blob/main/imagens/dashboard-olist_3.png" alt="Dashboard"height=400px >
</p>

## Machine Learning
#### Perguntas de negocios a serem respondidas???

* Qual a previsão de vendas, considerando o Estado do Cliente?
* Qual a previsão de vendas, considerando a Categoria do Produto?
* Qual a previsão de vendas, considerando o valor dos produtos?


## Informações

Projeto ainda não foi concluído totalmente, a faze de Machine Learning ainda não foi finalizada totalmente.
  
**Links:**
* [LinkedIn](https://www.linkedin.com/in/thiagovillani)
* [Portfólio de Projetos](https://github.com/villani31/Data_Science)
