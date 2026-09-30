 Sistema de Cardápio e Pedidos

Um sistema web desenvolvido para facilitar o gerenciamento do cardápio e dos pedidos de um restaurante.

O projeto está sendo desenvolvido como parte da disciplina de Engenharia de Software, com foco na aplicação prática de conceitos de levantamento de requisitos, modelagem, desenvolvimento, testes e documentação de software.

 Objetivo

O sistema tem como objetivo fornecer uma solução simples para que o restaurante possa:

Gerenciar os produtos disponíveis no cardápio;

Organizar os produtos por categorias;

Permitir a realização de pedidos;

Acompanhar o status dos pedidos;

Controlar o acesso ao sistema por meio de autenticação.

 Funcionalidades
 Autenticação

O sistema possui um mecanismo de autenticação para controlar o acesso às funcionalidades administrativas.

Cadastro de usuário;

Login;

Logout;

Autenticação por token;

Proteção das páginas restritas.

 Cardápio

Permite o gerenciamento dos produtos oferecidos pelo restaurante.

Cadastrar produtos;

Editar produtos;

Remover produtos;

Visualizar produtos;

Definir nome e descrição;

Definir preço;

Organizar produtos por categoria;

Ativar ou desativar produtos.

Exemplo:

Cardápio
│
├── Hambúrgueres
│   ├── X-Burger
│   └── X-Salada
│
├── Porções
│   ├── Batata Frita
│   └── Nuggets
│
└── Bebidas
    ├── Refrigerante
    └── Suco

 Pedidos

Permite realizar e acompanhar pedidos utilizando os produtos disponíveis no cardápio.

Criar pedido;

Adicionar produtos ao pedido;

Alterar quantidade;

Remover produtos do pedido;

Visualizar os itens do pedido;

Calcular o valor total;

Adicionar observações;

Acompanhar o status do pedido.

 Status do Pedido

Os pedidos poderão possuir diferentes estados:

PENDENTE
   ↓
EM PREPARO
   ↓
PRONTO
   ↓
FINALIZADO

 Equipe

Projeto desenvolvido por uma equipe de 5 estudantes de Engenharia de Software.

Integrante	Área
Integrante 1	Backend
Integrante 2	Frontend
Integrante 3	Banco de Dados
Integrante 4	Testes e Documentação
Integrante 5	Integração / Desenvolvimento

