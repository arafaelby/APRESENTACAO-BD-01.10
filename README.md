# APRESENTACAO-BD-01.10
PROJETO DE BANCO DE DADOS

Relacionamentos:
cliente - pedido (1:n)

pedido - produto - pedido_produto(n:n)

categoria - produto(1:n)

produto - fornecedor - produto _fornecedor (n:n)

pedido - pagamento (1:1)

pedido - entrega (1:1)

funcionário - pedido (1:n)

pedido - devolução (1:n)

estoque - produto (1:n)

entrega - funcionário (1:n)

pagamento - metodo (1:n)

Tabelas em ordem:
1. cliente
( Lista de clientes )
2. funcionário
( Lista de funcionários )
3. fornecedor
( Lista dos fornecedores. Ex: um fornecedor da Nike, outro da Adidas)
4. categoria
 ( Lista de categorias dos produtos/sapatos. Ex: Bota, Tênis, Salto, Sapatilha)
5. produto
( Lista de todos os produtos )
6. fornecedor_produto
( Tabela relacional de fornecedores pra quais produtos )
7. estoque
( Contém as informações dos produtos, como quantidade )
8. pedido
( Lista dos clientes que fizeram pedidos )
9. pedido_produto
( Tabela relacional da lista dos produtos pedidos )
10. metodo
( Pix, cartão, dinheiro. É necessário escolher antes o método pra conseguir realizar o pagamento )
11. pagamento
( pagamento dos pedidos )
12. entrega
( entrega dos pedidos )
13. devolução
( Lista de pediddos em devolução )

