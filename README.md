# PI-CESMAC

```plaintext
Inicio
    Constante PRECO_UNITARIO = 8.00
    Constante PRECO_ATACADO = 5.50
    Constante QUANTIDADE_ATACADO = 100

    Variável quantidade_sonhos
    Variável valor_total
    Variável preço_médio

    Escreva "Digite a quantidade de sonhos vendidos:"
    Leia quantidade_sonhos

    Se quantidade_sonhos >= QUANTIDADE_ATACADO Então
        valor_total <- quantidade_sonhos * PRECO_ATACADO
    Senão
        valor_total <- quantidade_sonhos * PRECO_UNITARIO
    FimSe

    preço_médio <- valor_total / quantidade_sonhos

    Escreva "Quantidade de sonhos vendidos: ", quantidade_sonhos
    Escreva "Preço médio por unidade: R$", preço_médio
    Escreva "Valor total vendido: R$", valor_total
Fim
