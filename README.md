# APRESENTACAO-BD-01.10
PROJETO DE BANCO DE DADOS

Relacionamentos:
cliente - pedido (1:n)

pedido - produto - pedido_produto(n:n)

categoria - produto(1:n)

produto - fornecedor - fornecedor_produto (n:n)

pedido - pagamento (1:1)

pedido - entrega (1:1)

funcionário - pedido (1:n)

pedido - devolução (1:n)

estoque - produto (1:n)

funcionário - entrega (1:n)

Tabelas em ordem:
1. cliente
2. funcionário
3. fornecedor
4. estoque
5. categoria
6. produto
7. fornecedor_produto
8. pedido
9. pedido_produto
10. pagamento
11. entrega
12. devolução

