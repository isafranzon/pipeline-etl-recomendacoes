# Pipeline ETL – Recomendações Personalizadas

Este projeto implementa um pipeline ETL (Extract, Transform, Load) para gerar recomendações personalizadas para clientes,
utilizando lógica inteligente baseada em regras de negócio.

O objetivo é demonstrar, de forma prática, os conceitos de extração de dados, transformação com critérios inteligentes
(simulando decisões que poderiam ser feitas por IA) e carregamento dos dados processados.

## Tecnologias Utilizadas

- Python
- Pandas
- Google Colab

## Pipeline ETL

### Extract
Os dados dos clientes são extraídos a partir de um arquivo CSV contendo informações como nome, faixa etária e interesse.

### Transform
As recomendações são geradas com base no perfil do cliente, considerando idade e interesse, utilizando regras de negócio
para personalizar a mensagem.

### Load
O dataset final, já com as recomendações, é salvo em um novo arquivo CSV para posterior uso ou análise.

## Contexto

Projeto desenvolvido como exercício prático do bootcamp Santander Dev Week 2023 da DIO.
