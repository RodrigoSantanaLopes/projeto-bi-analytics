| Coluna                    | Tipo    | Descrição                                           |
| ------------------------- | ------- | --------------------------------------------------- |
| `id_pedido`               | Inteiro | Identificador do pedido                             |
| `data_pedido`             | Data    | Data em que o pedido foi realizado                  |
| `ano`                     | Inteiro | Ano do pedido                                       |
| `mes`                     | Inteiro | Mês do pedido                                       |
| `ano_mes`                 | Texto   | Ano e mês do pedido                                 |
| `cliente`                 | Texto   | Nome fictício do cliente                            |
| `vendedor`                | Texto   | Vendedor responsável                                |
| `regiao`                  | Texto   | Região da venda                                     |
| `categoria`               | Texto   | Categoria do produto                                |
| `produto`                 | Texto   | Produto vendido                                     |
| `canal`                   | Texto   | Canal de venda                                      |
| `status_pedido`           | Texto   | Situação final do pedido                            |
| `quantidade`              | Inteiro | Quantidade vendida                                  |
| `receita_bruta`           | Decimal | Receita antes dos ajustes                           |
| `receita_liquida`         | Decimal | Receita considerada após o status                   |
| `custo`                   | Decimal | Custo da operação                                   |
| `lucro`                   | Decimal | Receita líquida menos custo                         |
| `pedido_concluido`        | Inteiro | Variável alvo do modelo                             |
| `probabilidade_conclusao` | Decimal | Probabilidade prevista de conclusão                 |
| `risco_nao_conclusao`     | Decimal | Probabilidade prevista de cancelamento ou devolução |
| `classificacao_risco`     | Texto   | Baixo, médio ou alto risco                          |
