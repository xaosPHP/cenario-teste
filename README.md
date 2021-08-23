# React Challenge

Este é um desafio para testar seus conhecimentos em JavaScript, React, Nex.JS e Styled Components.

Neste teste existem várias respostas corretas, pois o objetivo é avaliar a sua forma de codificação, e suas habilidades usando a tecnologia proposta.

## Obrigatoriedades

O uso de axios para consulta na API.

O Front-End deve utilizar styled components.

Utilizar técnicas de SSR para melhorar o desempenho de SEO da ferramenta.

## Sinta-se Livre

Para desenvolver o layout.

Criar Hooks personalizados.

Usar a criatividade para personalizar a ferramenta.


## Carrinho de Compras

Seu objetivo é montar um carrinho de compras simples, conforme o protótipo a seguir:

O layout deve ser como de um site de vendas convencional, com uma listagem de produtos, e um ícone de carrinho de compras no header do site.

O ícone do carrinho de compras deve exibir um dropdown com a quantidade de itens presente no carrinho.

## A tela de listagem de produtos deve:

- Listar todos os produtos;
- Usar SSR;
- Ao entrar no projeto, deve exibir os produtos na listagem com foto, título e preço formatado em reais;
- Ao clicar no produto da lista, deve exibir os detalhes de um produto individual;
- Permitir comprar
- Ao clicar em comprar, e o produto não estiver no carrinho, deve ser adicionado;
- Ao clicar em comprar, e o produto já existir no carrinho, deve ser incrementado em 1;
- Exibir resumo do carrinho
- Exibir no ícone do carrinho uma dropdown com quantidade de itens;
- Exibir ao lado do ícone, o valor total da compra;


## O carrinho deve:

- Permitir remover itens;
- Ao remover, liberar o estoque do produto;
- Permitir alterar a quantidade de um item;
- Ao clicar em aumentar, deve incrementar em 1;
- Ao clicar em diminuir, deve decrementar em 1;
- Ao incrementar, deve validar se o produto ainda possui estoque;
- Ao decrementar, deve liberar o estoque do produto;
- Não deve permitir o usuário informar quantidade zero;
- Exibir o somatório total dos itens incluídos;

## Serviço Rest

Criar o backend não é o foco deste teste, portanto está sendo disponibilizado um serviço Rest que deve ser utilizado para recuperar a lista de produtos do projeto.

Para rodar o serviço, é necessário instalar o json-server:

`yarn install -g json-server`

Após isso, rodar o comando: `json-server --watch rest-api/products.json`

Isso irá disponibilizar uma api REST rodando no endereço http://localhost:3000/products

Um produto específico pode ser acessado através da url http://localhost:3000/products/{id}