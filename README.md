# Olist: Crescimento e Receita

Tech Challenge, Fase 1. Análise executiva da receita do e-commerce Olist (cerca de 100 mil pedidos, 2016 a 2018), na trilha **Crescimento e Receita**.

## Entregas

- Código: `Tech_Challenge_Olist_completo.ipynb`
- Apresentação: 
- Vídeo: https://youtu.be/gsQvaSTv9PA

## Principais resultados

- Receita de R$ 13,2 milhões em 96.478 pedidos entregues. Ticket médio de R$ 137,04 e mediana de R$ 86,57.
- Receita de jan–ago cresceu 141% de 2017 para 2018, mas estabilizou em cerca de R$ 0,91 milhão por mês em 2018.
- A receita é concentrada: 18 de 74 categorias geram 80%, e os 10% maiores vendedores geram 67%.
- O frete pesa 18,3% do preço em vendas entre estados, contra 13,0% no mesmo estado.
- Só 3% dos clientes compraram mais de uma vez.
- Previsão para set–dez/2018: cerca de R$ 4,2 milhões.

## Regras de negócio

- Receita é a soma do preço dos itens, sem frete.
- Só entram pedidos com status `delivered` e com pelo menos um item.
- Comparações mensais usam jan/2017 a ago/2018, porque 2016 e o fim de 2018 estão incompletos.

## Qualidade dos dados

Chaves duplicadas são checadas, as junções usam `validate=` e `assert`, e a receita dos itens é conferida contra a receita por pedido.

## Autor
Henzo Farina
