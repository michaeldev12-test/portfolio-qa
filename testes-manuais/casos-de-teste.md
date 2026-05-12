#  Casos de Teste - Mercado Livre


# CT-01 - Busca de produto

## Objetivo
Validar se o usuário consegue pesquisar um produto no Mercado Livre.

## Passos
1. Entrar no site do Mercado Livre
2. Digitar "notebook" no campo de busca
3. Clicar em pesquisar

## Resultado esperado
O sistema deve exibir produtos relacionados à pesquisa.


# CT-02 - Login com senha inválida

## Objetivo
Validar comportamento do sistema ao inserir senha incorreta.

## Passos
1. Acessar tela de login
2. Inserir e-mail válido
3. Inserir senha incorreta
4. Clicar em entrar

## Resultado esperado
Sistema deve exibir mensagem de erro.


# CT-03 - Campo de busca vazio

## Objetivo
Validar comportamento da busca sem preenchimento.

## Passos
1. Entrar no Mercado Livre
2. Clicar em pesquisar sem digitar nada

## Resultado esperado
Sistema deve informar ao usuário que o campo está vazio ou redirecionar corretamente.
