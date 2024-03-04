# Modelo de análise das métricas RFM

## Introdução
Uma empresa de e-commerce está buscando entender melhor o comportamento de seus clientes para personalizar as suas campanhas de marketing. Para isso, ela disponibilizou uma base de dados em csv contendo informações a sobre os clientes, produtos e transações realizadas entre os anos de 2010 e 2011.

## Objetivo do projeto

A partir da base de dados disponibilizada, o presente projeto tem como objetivo desenvolver um modelo de machine learning de Clusterização que permita analisar as métricas RFM destes clientes, agrupando-os os em clusters com base em seu comportamento de compra, identificando padrões e características comuns dentro destes grupos.

A partir disso, ainda é necessário explicar de que forma esta análise pode ser útil para a empresa, no intuito de segmentar seus clientes e personalizar campanhas de marketing, sugerindo ações possíveis para cada um dos grupos identificados.

## Sobre os dados

Os dados fornecidos possuem informações de transações de compras da empresa realizada em 38 países diferentes, com mais de 4.000 clientes únicos e mais de 540.000 transações.

Segue abaixo um descritivo do significado das informações presentes em cada coluna do dataset.

- InvoiceNo: Identificação da transação;
- StockCode: Código de estoque do produto;
- Description: Descrição do produto;
- Quantity: Quantidade de produtos por transação;
- InvoiceDate: Data da transação;
- UnitPrice: Preço unitário do produto;
- CustomerID: Identificação do cliente;
- Country: País de origem da transação.

## Bibliotecas utilizadas

Segue uma lista com as bibliotecas em Python utilizadas no desenvolvimento e resolução deste case.

- pandas
- numpy
- plotly
- matplotlib
- scikit-learn
- yellowbrick

## Deployment

Este projeto foi todo desenvolvido utilizando o VS CODE. Portanto, se torna necessário a instalação deste ou de algum outro interpretador de código para o seu correto funcionamento. Em seguida, foram instaladas as extensões do Python e Jupyter Notebook dentro do VS CODE.

OBS: Versão do Python utilizada no projeto = 3.11.5

### Instalação das bibliotecas utilizadas

Feita as instalações dos requisitos base acima, agora é necessário instalar as bibliotecas, listadas no arquivo 'requirements.txt', que foram utilizadas no desenvolvimento do projeto. Para isso, executa-se no terminal do VS CODE, o comando abaixo.

```bash

pip install -r requirements.txt

```

## Análise dos dados

