# Desafio | Frontend Developer

Olá! Seja bem vindo ao teste para a vaga de **Frontend Developer Júnior**.

Preparamos um teste que abordará seus conhecimentos em **HTML**, **CSS** e **Javascript**.

---

## Sobre o desafio

O desafio consiste no desenvolvimento do *layout* de uma *landing page* com uma grade de produtos e um formulário de *newsletter*. Seu principal objetivo é transformar este *layout* em uma página funcional.

**Link do Mock do Layout**: https://xd.adobe.com/spec/4025e242-a495-4594-71d2-5fd89d774b57-3614

**Endpoint da API**: https://frontend-intern-challenge-api.iurykrieger.now.sh/products?page=1

### Sobre o Layout

Você terá que implementar o *layout* de acordo com o mock no link acima. O *mock* contém a estrutura do layout e todo o estilo da página.

É importante se ater aos detalhes de tamanho e espaçamento entre os elementos da página, construindo o HTML mais semântico possível.

### Comportamento:

Para preencher a página com as informações dos produtos, você terá que consultar esta **[API](https://frontend-intern-challenge-api.iurykrieger.now.sh/products?page=1)** de forma paginada, sendo que cada página consultada retornará as informações de **8 produtos** e um **link para a próxima página**.

Assim que obter os dados, você deverá implementar os seguintes pontos:

- Para cada **produto** retornado pela API, um **card de produto** com suas respectivas informações deve ser criado na grade de produtos;
- Ao clicar no botão **Ainda mais produtos aqui!** a próxima página da API deve ser consultada, gerando mais **8 produtos** na grade existente, abaixo dos produtos já carregados pela primeira requisição;
- Os formulários devem ter seus campos de *input* validados de acordo com o conteúdo (ex: O campo de email deve conter um email válido).

---

## Instruções

- Crie um repositório no seu github que irá conter o desenvolvimento do seu desafio;
- Faça *commits* ao longo do seu desenvolvimento, isso nos ajudará a entender sua linha de raciocínio;
- Faça **README.md** que contenha as informações de *setup* e a descrição do seu projeto;
- Suba um *live preview* do seu desafio em algum Github Pages no seu Github;
- Assim que concluir o seu desafio, envie o link do repositório e do live preview em nossa comunidade no Discord, no canal "Avaliação de Testes", e peça para o pessoal do Suporte Técnico avaliar o seu desafio.

---

## Dicas
> Não use frameworks (react, vue, angular, bootstrap), o objetivo aqui é usar HTML, CSS e JS puro;

> Crie uma estrutura de arquivos organizada para suas implementações;

> Construa o CSS de forma bem estruturada e em um arquivo separado;

> Evite poluir o escopo global do Javascript;

> Documente suas funções e seja o mais conciso possível ao escrever seu código;

> Seu README.md deve conter as instruções necessárias para qualquer pessoa fazer seu projeto funcionar;

> Your code will be better understood in English ;)

---

## Critérios de avaliação
- Commits significativos

- Arquitetura e organização do sistema

- Conhecimento de responsividade

- Modularidade e reusabilidade

- Boas práticas de programação

---

## Dúvidas
Em caso de dúvidas, consulte o Suporte Técnico em nossa comunidade do Discord.

---

**Boa sorte =]**
