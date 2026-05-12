#  Relatório de Bugs - Mercado Livre


# BUG-01 - Campo aceita caracteres especiais na busca

## Descrição
O sistema permite busca com caracteres especiais sem apresentar validação.

## Passos para reproduzir
1. Entrar no Mercado Livre
2. Digitar "@@@@@"
3. Clicar em pesquisar

## Resultado atual
Sistema realiza busca normalmente.

## Resultado esperado
Sistema deveria validar caracteres inválidos.


# BUG-002 - Falta mensagem ao buscar produto inexistente

## Descrição
Sistema não informa claramente quando nenhum produto é encontrado.

## Resultado esperado
Sistema deve exibir mensagem amigável ao usuário.
