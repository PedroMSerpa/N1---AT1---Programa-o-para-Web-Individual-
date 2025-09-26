Esse projeto faz parte da avaliação N1 – AT1 de Programação para Web. O objetivo é colocar em prática o que vimos em aula, desenvolvendo um protótipo de sistema web que simula o funcionamento de um carrinho de compras online.

A ideia é aplicar conceitos fundamentais como:

uso de variáveis (let, const e var),

operadores,

estruturas de controle,

manipulação do DOM,

funções e arrays.

O sistema foi pensado para ter as seguintes partes principais:

Página de Login

Uma tela simples de autenticação com usuário e senha.

Somente quem estiver logado poderá acessar o carrinho.

Carrinho de Compras

Existe um array com os produtos disponíveis (contendo nome, preço e código).

É possível buscar produtos dentro desse array.

O usuário pode adicionar produtos ao carrinho, que também é um array separado.

Também é possível remover produtos do carrinho.

Os itens adicionados (nome, quantidade e valor total) são exibidos diretamente no HTML usando manipulação do DOM.

Fechamento da Compra

Um botão finaliza a compra.

Ao clicar, o resumo do pedido aparece na tela (também via DOM).

Organização do Código

Cada operação (login, busca, adicionar, remover, listar, finalizar compra) foi feita dentro de funções próprias.

Arrays são usados como a principal estrutura de dados.

Existem variáveis globais (como os arrays de produtos e carrinho) e variáveis locais dentro das funções.

Toda atualização visual é feita com manipulação de elementos do DOM.

Interface

Botões foram usados para todas as principais ações (login, buscar, adicionar, remover, finalizar).

As mensagens e resultados são mostrados direto no navegador, não apenas no console.
