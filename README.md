# projeto-bi-analytics

# Projeto de Business Intelligence e Analytics

## 1. Sobre o projeto

Este projeto foi desenvolvido para a disciplina de Projeto em Business Intelligence e Analytics.

O trabalho apresenta uma solução completa de BI e Analytics para uma empresa fictícia que enfrenta dificuldades na tomada de decisão devido à baixa confiança nos dados apresentados.

A solução inclui a geração de uma base fictícia de vendas, tratamento dos dados, criação de indicadores no Power BI e desenvolvimento de um modelo preditivo para identificar pedidos com risco de cancelamento ou devolução.

## 2. Problema de negócio

A empresa possui dados de vendas, clientes, produtos, canais e regiões, mas enfrenta dificuldades para transformar essas informações em indicadores confiáveis.

Além disso, a empresa não possui uma forma de identificar antecipadamente pedidos com maior risco de não conclusão.

A pergunta principal do projeto é:

Como uma solução de Business Intelligence e Analytics pode melhorar a confiabilidade dos dados e apoiar a tomada de decisões estratégicas?

## 3. Objetivos

O objetivo geral é desenvolver uma solução de BI e Analytics que organize os dados, apresente indicadores gerenciais e identifique pedidos com maior risco de cancelamento ou devolução.

Os objetivos específicos são:

1. Criar uma base fictícia de vendas.
2. Limpar e organizar os dados.
3. Definir métricas de negócio.
4. Construir dashboards no Power BI.
5. Desenvolver um modelo de Regressão Logística.
6. Calcular o risco de não conclusão dos pedidos.
7. Disponibilizar os resultados em um repositório organizado.

## 4. Tecnologias utilizadas

Python

Google Colab

Pandas

NumPy

Scikit-learn

Matplotlib

Power BI

GitHub

Draw.io

## 5. Arquitetura da solução

A solução segue o seguinte fluxo:

Python

Geração da base fictícia

Limpeza e processamento dos dados

Arquivos CSV

Power BI

Dashboards e indicadores

Google Colab

Modelo de Regressão Logística

Previsão do risco de não conclusão

GitHub

Documentação e tomada de decisão

<img width="729" height="932" alt="image" src="https://github.com/user-attachments/assets/7393db21-1859-404a-abeb-8be08107e5e8" />

## 6. Base de dados

A base fictícia possui 2.500 registros de pedidos realizados entre janeiro e dezembro de 2025.

As principais informações disponíveis são:

Data do pedido

Cliente

Vendedor

Região

Categoria

Produto

Canal

Status do pedido

Quantidade

Receita

Custo

Lucro

Os pedidos podem apresentar os seguintes status:

Concluído

Cancelado

Devolvido

## 7. Indicadores do dashboard

Os principais indicadores desenvolvidos foram:

Receita total

Lucro total

Margem de lucro

Quantidade vendida

Total de pedidos

Pedidos concluídos

Taxa de conclusão

Ticket médio

Clientes únicos

Receita por região

Receita por categoria

Receita por canal

Evolução mensal da receita

Risco médio de não conclusão

Quantidade de pedidos de alto risco

## 8. Páginas do dashboard

O dashboard foi dividido nas seguintes páginas:

### Visão Executiva

Apresenta os principais indicadores financeiros e comerciais.

### Desempenho Comercial

Apresenta análises por região, categoria, canal, produto e vendedor.

### Análise Operacional

Apresenta pedidos concluídos, cancelados e devolvidos.

### Risco de Pedidos

Apresenta a probabilidade de não conclusão e os pedidos classificados como baixo, médio ou alto risco.

### Desempenho do Modelo

Apresenta as métricas de avaliação e as variáveis com maior influência no modelo.

## 9. Modelo preditivo

Foi utilizado um modelo de Regressão Logística para prever se um pedido será concluído.

A variável alvo foi criada da seguinte forma:

1 representa pedido concluído.

0 representa pedido cancelado ou devolvido.

As variáveis utilizadas no modelo foram:

Mês

Região

Categoria

Produto

Canal

Vendedor

Quantidade

Receita bruta

O modelo foi avaliado por meio das seguintes métricas:

Acurácia

Precisão

Recall

F1-score

ROC AUC

Matriz de confusão

## 10. Estrutura do repositório

```text
dados/
notebooks/
scripts/
dashboard/
documentacao/
apresentacao/
```

## 11. Como executar o projeto

1. Abra o notebook `01_geracao_base.ipynb`.
2. Execute as células para gerar a base fictícia.
3. Abra o notebook `02_modelo_risco_pedidos.ipynb`.
4. Execute o treinamento do modelo.
5. Gere os arquivos CSV de saída.
6. Abra o arquivo `projeto_bi.pbix`.
7. Atualize as fontes de dados, caso necessário.

## 12. Resultados

A solução permite acompanhar o desempenho comercial da empresa e identificar pedidos com maior risco de cancelamento ou devolução.

Os dashboards facilitam a comparação entre regiões, categorias, canais e vendedores.

O modelo preditivo adiciona uma camada de Analytics ao projeto, permitindo que a empresa priorize pedidos que exigem maior atenção.

## 13. Autor

Rodrigo Santana Lopes
