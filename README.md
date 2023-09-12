# Exercício: Tratamento de Dados, Modelo PyCaret e API FastAPI Dockerizada

Este projeto demonstra uma solução completa que abrange o pré-processamento de dados, a criação de um modelo de aprendizado de máquina com PyCaret, o desenvolvimento de uma API usando FastAPI e a dockerização da aplicação.

# Solução

## 1. Tratamento de Dados
O primeiro passo é carregar os dados brutos e fazer o tratamento deles para torná-los adequados para o treinamento do modelo.
Realizamos operações como limpeza de dados ausentes, codificação de variáveis categóricas e normalização de atributos numéricos.
## 2. Modelo PyCaret

Utilizamos a biblioteca PyCaret para criar um pipeline de treinamento de modelo de regressão.
Realizamos a seleção automática de características, treinamento de vários modelos e seleção do melhor modelo com base em métricas de desempenho.

## 3. Desenvolvimento da API FastAPI
Utilizamos o framework FastAPI para criar uma API RESTful que expõe nosso modelo de regressão.
Criamos rotas para receber solicitações e retornar previsões com base nos dados de entrada.

## 4. Dockerização da Aplicação
Criamos um Dockerfile para empacotar nossa aplicação em um contêiner Docker.
Garantimos que todas as dependências e arquivos necessários estejam incluídos no contêiner.
A aplicação é configurada para ser executada dentro do contêiner.

