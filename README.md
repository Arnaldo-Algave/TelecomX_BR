📊 Telecom X — Análise de Churn de Clientes

Este projeto apresenta uma Análise Exploratória de Dados (EDA) focada na evasão de clientes (churn) em uma empresa fictícia de telecomunicações chamada Telecom X.

A proposta é utilizar ferramentas de análise de dados em Python para explorar o comportamento dos clientes, identificar possíveis fatores associados ao cancelamento e gerar insights que possam apoiar estratégias de retenção.

🧠 Visão Geral

A evasão de clientes é um desafio comum no setor de telecomunicações. Quando um cliente cancela o serviço, a empresa perde receita e precisa investir mais para conquistar novos clientes.

Neste projeto, os dados foram analisados com o objetivo de compreender melhor esse fenômeno e identificar padrões relacionados ao churn.

A análise foi desenvolvida utilizando Python e bibliotecas de ciência de dados, a partir de um conjunto de dados no formato JSON, simulando um cenário de consumo de dados via API.

🎯 Objetivos do Projeto

Aplicar técnicas de ETL (Extração, Transformação e Carga) em dados semiestruturados

Realizar uma Análise Exploratória de Dados (EDA) bem estruturada

Identificar fatores que podem influenciar o churn

Explorar variáveis relevantes para futuras análises preditivas

Desenvolver habilidades de análise e comunicação de insights

🗂️ Estrutura do Repositório
├── TelecomX_Data.json       # Conjunto de dados utilizado na análise
├── EDA_TelecomX_Churn.ipynb # Notebook com a análise exploratória
└── README.md                # Documentação do projeto
📘 Dados Utilizados

O conjunto de dados contém informações sobre clientes da empresa, incluindo:

características demográficas

tempo de permanência na empresa

serviços contratados

informações de faturamento

status de churn (cancelamento ou permanência)

Os dados estão no formato JSON, simulando um cenário de extração de dados via API.

🔍 Principais Análises

Durante a análise exploratória foram investigados alguns fatores importantes relacionados ao churn.

✔️ Tipo de contrato

Clientes com contratos mensais apresentam maior taxa de cancelamento quando comparados a clientes com contratos de longo prazo.

✔️ Tempo de permanência

Clientes com menor tempo de relacionamento com a empresa apresentam maior probabilidade de cancelar o serviço.

✔️ Serviços adicionais

Clientes que utilizam mais serviços adicionais tendem a apresentar menor taxa de churn, o que pode indicar maior engajamento com a empresa.

🛠️ Tecnologias Utilizadas

Python

Pandas

NumPy

Matplotlib

Jupyter Notebook

🚀 Possíveis Continuidade do Projeto

A análise exploratória abre espaço para etapas futuras, como:

criação de novas variáveis (feature engineering)

desenvolvimento de modelos de Machine Learning para previsão de churn

avaliação de modelos e interpretação dos resultados

👤 Autor

Arnaldo Algave
Link Projeto: https://github.com/Arnaldo-Algave/TelecomX_BR/new/main?filename=README.md

Projeto desenvolvido como parte de um exercício prático de análise de dados, com foco na aplicação de conceitos de EDA e interpretação de dados em um contexto de negócio.

💡 Este projeto tem caráter educacional e busca demonstrar o processo de exploração de dados e geração de insights em um problema comum do setor de telecomunicações.
