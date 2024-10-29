
# Priorização de Estoque de Produtos

Para realizar uma análise preditiva sobre o risco de ruptura de estoque dos produtos citados, levaremos em consideração a média de vendas diárias e os dias restantes antes do estoque acabar. A prioridade será dada com base no menor número de dias restantes para o estoque acabar, indicando maior urgência em reabastecimento, enquanto a sugestão de compra será projetada para manter o estoque por ao menos mais 30 dias, considerando a média atual de vendas diárias para cada produto.

Aqui está a lista atualizada, levando em consideração esses critérios:

| Produto | Nome | Estoque (unidades) | Média de Vendas Diárias | Dias para Acabar Estoque | Prioridade | Justificativa Top 3 | Sugestão de Compra |
|---------|------|--------------------|-------------------------|--------------------------|------------|---------------------|--------------------|
| 48      | GELATO FRUTBISS 1,5 L NIÑO TRUFADO | 162                | 17.88                   | 9.06                     | 1          | Maior média de vendas diárias e menor número de dias para acabar o estoque. | 526                |
| 50      | GELATO FRUTBISS 1,5 L CASTANHA CARAMELIZADA | 135                | 13.25                   | 10.19                    | 2          | Elevada média de vendas diárias associada a baixo estoque restante. | 364                |
| 47      | GELATO FRUTBISS 1,5 L TORTA DE LIMÃO | 82                 | 7.51                    | 10.92                    | 3          | Menos urgente, porém com bom volume de vendas diárias. | 208                |
| 49      | GELATO FRUTBISS 1,5 L NAPOLITANO TRÊS AMORES | 240                | 12.20                   | 19.68                    | 4          |  | 335                |
| 54      | GELATO FRUTBISS 1,5 L IOGURTE GREGO | 558                | 12.41                   | 44.97                    | 5          |  | 341                |
| 51      | GELATO FRUTBISS 1,5 L ABACAXI SUIÇO | 0                  | 13.08                   | 0.00                     | 6          |  | 361                |
| 52      | GELATO FRUTBISS 1,5 L BROWNIE | 0                  | 11.82                   | 0.00                     | 7          |  | 326                |
| 53      | GELATO FRUTBISS 1,5 L CHOCOLATE BELGA | 0                  | 11.17                   | 0.00                     | 8          |  | 308                |

### Justificativa e Sugestão de Compra para o Top 3:

- **GELATO FRUTBISS 1,5 L NIÑO TRUFADO**: Sendo o produto com a maior média de vendas diárias (17.88) e o menor tempo restante antes do esgotamento do estoque (9.06 dias), ele se classifica com a maior prioridade. Para manter um estoque confortável por mais 30 dias, seriam necessárias aproximadamente \(17.88 	imes 30 = 536\) unidades, considerando que já se possui 162, sugerimos a compra de 526.
  
- **GELATO FRUTBISS 1,5 L CASTANHA CARAMELIZADA**: Com uma média de vendas diárias de 13.25 e 10.19 dias restantes de estoque, está em segunda posição na prioridade. Para 30 dias adicionais, seriam necessários \(13.25 	imes 30 = 397.5\), aproximadamente 364 unidades novas, visto que parte do estoque ainda está disponível.
  
- **GELATO FRUTBISS 1,5 L TORTA DE LIMÃO**: Menor urgência em relação aos primeiros, mas ainda significativo com 7.51 vendas diárias e 10.92 dias de estoque. Para cobertura de mais 30 dias, \(7.51 	imes 30 = 225.3\), indicando a compra de cerca de 208 unidades.

### Explicação:

A sugestão de compra visa prolongar o estoque existente por pelo menos mais 30 dias, baseando-se na média diária de vendas para cada produto. A priorização considera tanto a rapidez com que o estoque atual deve se esgotar quanto a demanda diária de cada item, tentando mitigar o risco de ruptura de estoque e satisfazer a demanda do mercado de maneira eficiente.
