# Análise de Churn de Clientes Bancários

Projeto de análise exploratória de dados com Python para entender o perfil dos clientes bancários e identificar padrões relacionados ao churn.

## Fonte dos Dados

**Este projeto tem finalidade exclusivamente educacional e de portfólio.**

Os dados utilizados neste projeto foram obtidos no **Maven Analytics Data Playground**.

Dataset: **Bank Customer Churn** 
Link: https://mavenanalytics.io/data-playground/bank-customer-churn 

Os dados originais não foram incluídos neste repositório. Para acessar a base completa, consulte a fonte oficial informada acima.

## Objetivo

Analisar dados de clientes bancários para identificar padrões relacionados ao cancelamento do serviço e gerar insights que possam apoiar possíveis estratégias de retenção.

## Perguntas de Negócio

1. Qual é o perfil geral dos clientes do banco?
2. Quais diferenças aparecem entre clientes que cancelaram e clientes que permaneceram?
3. O comportamento dos clientes muda entre Alemanha, França e Espanha?
4. Quais grupos de clientes parecem ter maior risco de churn?

## Ferramentas Utilizadas

- Python
- Pandas
- Plotly Express
- Jupyter Notebook

## Principais Insights

- A base possui uma taxa de churn de 20,37%, sendo 2.037 dos 10.000 clientes cancelaram o serviço.
- Clientes inativos tiveram uma taxa de cancelamento maior (27%) em comparação aos clientes ativos (14%).
- A Alemanha possui a maior taxa de churn entre os países analisados.
- Clientes que cancelaram possuem idade média maior do que os clientes que permaneceram.
- Clientes com 3 e 4 produtos apresentam as maiores taxas de churn, mas são grupos pequenos na base.
- Clientes com apenas 1 produto concentram o maior número de cancelamentos.

## Conclusão

A análise mostrou que alguns fatores possuem relação com o churn dos clientes, principalmente atividade do cliente, país, idade e quantidade de produtos contratados.

Clientes inativos, clientes da Alemanha, clientes com idade média maior e alguns perfis de produtos apresentaram maiores taxas de cancelamento. Também foi possível observar a diferença entre analisar taxas e quantidade de casos: clientes com 3 e 4 produtos possuem taxas de churn mais altas, enquanto clientes com apenas 1 produto representam o maior número de cancelamentos.

Com base nesses padrões, algumas ações poderiam ser investigadas pelo banco, como criar estratégias de reativação para clientes inativos, entender os motivos de cancelamento na Alemanha, avaliar a experiência de clientes com poucos produtos contratados e direcionar campanhas para clientes mais velhos com o objetivo de aumentar a retenção.

Como essa análise é exploratória, os resultados encontrados não indicam que esses fatores são as causas diretas do churn, mas ajudam a identificar grupos de clientes que podem receber uma análise mais aprofundada e possíveis estratégias de retenção.