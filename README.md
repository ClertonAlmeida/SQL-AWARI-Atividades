# Exercicios-SQL-AWARI

### Trabalhando com as funções de agregação do SQL

### Agrupando valores com o GROUP BY

### Os tipos de JOIN: Quais são e como usá-los! (SQL SERVER)


## Lista 01:
Queries:
Com a base de dados aberta, crie queries que:

1. selecione os dados da tabela de pagamentos onde só apareçam os tipos de pagamento “VOUCHER” e “BOLETO”.
2. retorne os campos da tabela de produtos e calcule o volume de cada produto em um novo campo.
3. retorne somente os reviews que não tem comentários.
4. retorne pedidos que foram feitos somente no ano de 2017.
5. encontre os clientes do estado de SP e que não morem na cidade de São Paulo.

## Lista 02:
Queries:
Com a base de dados aberta, crie queries que:

1. retorne a quantidade de itens vendidos em cada categoria por estado em que o cliente se encontra, mostrando somente categorias que tenham vendido uma quantidade de items acima de 1000.
2. mostre os 5 clientes (customer_id) que gastaram mais dinheiro em compras, qual foi o valor total de todas as compras deles, quantidade de compras, e valor médio gasto por compras. Ordene os mesmos por ordem decrescente pela média do valor de compra.
3. mostre o valor vendido total de cada vendedor (seller_id) em cada uma das categorias de produtos, somente retornando os vendedores que nesse somatório e agrupamento venderam mais de $1000. Desejamos ver a categoria do produto e os vendedores. Para cada uma dessas categorias, mostre seus valores de venda de forma decrescente.

## Lista 03:
Queries:
Com a base de dados aberta, crie queries que:

1. crie uma tabela analítica de todos os itens que foram vendidos, mostrando somente pedidos interestaduais. Queremos saber quantos dias os fornecedores demoram para postar o produto, se o produto chegou ou não no prazo.
2. retorne todos os pagamentos do cliente, com suas datas de aprovação, valor da compra e o valor total que o cliente já gastou em todas as suas compras, mostrando somente os clientes onde o valor da compra é diferente do valor total já gasto.
3. retorne as categorias válidas, suas somas totais dos valores de vendas, um ranqueamento de maior valor para menor valor junto com o somatório acumulado dos valores pela mesma regra do ranqueamento.

## Lista 04:
Crie queries que:

1. Crie uma view (SELLER_STATS) para mostrar por fornecedor, a quantidade de itens enviados, o tempo médio de postagem após a aprovação da compra, a quantidade total de pedidos de cada Fornecedor, note que trabalharemos na mesma query com 2 granularidades diferentes.
2. Queremos dar um cupom de 10% do valor da última compra do cliente. Porém os clientes elegíveis a este cupom devem ter feito uma compra anterior a última (a partir da data de aprovação do pedido) que tenha sido maior ou igual o valor da última compra. Crie uma querie que retorne os valores dos cupons para cada um dos clientes elegíveis.


## Fonte:
Todos os exercícios foram feitos com base em questões alaboradas pela AWARI:

Link: https://awari.com.br

Utilizando o dataset OLIST, retirado do kaggle.

Link: https://www.kaggle.com/olistbr/brazilian-ecommerce

Utilizei o DBBrowser para executar os comandos SQL

Link para download da ferramenta: https://sqlitebrowser.org/dl/
