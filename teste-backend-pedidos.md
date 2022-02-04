# Teste para vaga de Desenvolvedor Backend 
Por esse desafio, o desenvolvedor deverá mostrar ser capaz de desenvolver uma API RESTFul, para criar pedidos de uma lanchonete, e um painel administrativo para cadastrar os produtos e gerenciar os pedidos.

## Sobre o problema
O Sistema deverá contemplar os módulos: __Cliente__, __Produto__ e __Pedido__. Um __Pedido__ pertence a um __Cliente__ e um __Pedido__ contém vários __Produtos__.

A API será utilizada para o _client_ que irá realizar os pedidos. Nesse sentido, ela deverá conter _endpoints_ para que um __Cliente__ possa se cadastrar. Além de `criar`, `listar`, `ver` e `excluir` __Pedidos__ de um __Cliente__ específico. Obs.: Para evitar autenticação, o id do __Cliente__ pode ser usado como parâmetro para realizar essas ações.

O painel administrativo deve conter uma autenticação básica. E através dele deverá ser possível `listar` __Clientes__ e `listar` __Pedidos__, além de poder gerenciar os __Produtos__ da lanchonete..

Os campos para cada entidade serão:
- Cliente: `nome`, `email`, `telefone` e `endereço`;
- Produto: `nome` e `preço`;
- Pedido: `código do cliente`, `código do produto`, `data de criação` e `status do pedido`.

O __Pedido__ poderá conter os `status`: `Pendente`, `Em preparo`, `Em entrega`, `Entregue` e `Cancelado`.

## Requisitos
- Não poderá existir mais de um __Cliente__ com o mesmo `email` ou `telefone`;
- Todos os dados deverão ser validados;
- Um __Cliente__ não pode excluir um __Pedido__ criado por outro __Cliente__.

## Critérios de avaliação
- Profundidade de conhecimento do framework escolhido;
- Organização do código;
- Fidelidade aos requisitos;

## Instruções para entrega
- Seu código deverá ser versionado com Git e hospedado no GitHub;
- Crie um README.md explicando como solucionou o problema, como poderemos executar o projeto e outros pontos que achar necessário;
- Assim que concluir o seu desafio, envie o link do repositório e do live preview em nossa comunidade no Discord, no canal "Avaliação de Testes", e peça para o pessoal do Suporte Técnico avaliar o seu desafio.