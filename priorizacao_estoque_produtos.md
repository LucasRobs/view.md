
# Priorização de Estoque de Produtos

Analisando os dados fornecidos, podemos estabelecer a prioridade de cada produto com base nos **dias_para_acabar_estoque**, considerando que produtos com menos dias para acabar o estoque têm maior urgência para reabastecimento, visando evitar rupturas. Além disso, deve-se considerar a **média de vendas diárias**, uma vez que produtos de alta rotatividade necessitam de atenção especial para não ocorrer falta.

Aqui está a lista atualizada, levando em consideração esses critérios:

| Produto | Nome | Estoque (unidades) | Média de Vendas Diárias | Dias para Acabar Estoque | Prioridade | Justificativa Top 3 |
|---------|------|--------------------|-------------------------|--------------------------|------------|---------------------|
| 48      | GELATO FRUTBISS 1,5 L NIÑO TRUFADO | 162                | 17.88                   | 9.06                     | 1          | Maior média de vendas diárias entre os produtos que possuem estoque, indicando alta rotatividade. |
| 50      | GELATO FRUTBISS 1,5 L CASTANHA CARAMELIZADA | 135                | 13.25                   | 10.19                    | 2          | Segundo menor número de dias para acabar o estoque, com uma média de vendas significativa. |
| 47      | GELATO FRUTBISS 1,5 L TORTA DE LIMÃO | 82                 | 7.51                    | 10.92                    | 3          | Terceiro menor número de dias para acabar o estoque, indicando necessidade de atenção para reabastecimento. |
| 49      | GELATO FRUTBISS 1,5 L NAPOLITANO TRÊS AMORES | 240                | 12.20                   | 19.68                    | 4          |  |
| 54      | GELATO FRUTBISS 1,5 L IOGURTE GREGO | 558                | 12.41                   | 44.97                    | 5          |  |
| 51      | GELATO FRUTBISS 1,5 L ABACAXI SUIÇO | 0                  | 13.08                   | 0.00                     | 6          |  |
| 52      | GELATO FRUTBISS 1,5 L BROWNIE | 0                  | 11.82                   | 0.00                     | 7          |  |
| 53      | GELATO FRUTBISS 1,5 L CHOCOLATE BELGA | 0                  | 11.17                   | 0.00                     | 8          |  |

### Produtos com Maior Prioridade

1. **GELATO FRUTBISS 1,5 L NIÑO TRUFADO**: Prioridade máxima devido à sua alta média de vendas diárias e ao menor número de dias restantes para acabar o estoque, indicando alto risco de ruptura.
2. **GELATO FRUTBISS 1,5 L CASTANHA CARAMELIZADA**: Segunda prioridade, considerando seu equilíbrio entre uma boa média diária de vendas e um baixo número de dias até o esgotamento do estoque.
3. **GELATO FRUTBISS 1,5 L TORTA DE LIMÃO**: Terceira prioridade, dado que possui menos dias restantes para acabar o estoque em comparação com as opções que têm um prazo mais extenso, embora sua média de vendas diárias seja menor.

Essa priorização permite focar no reabastecimento dos produtos mais críticos primeiro, mitigando riscos de ruptura de estoque e atendendo à demanda do mercado de forma eficiente.
