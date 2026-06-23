# Sistema de Gestão para Doceria 🍰

Projeto de modelagem e implementação de banco de dados relacional desenvolvido em MySQL para gerenciamento completo de uma doceria.

## Sobre o Projeto

Este projeto foi desenvolvido com o objetivo de aplicar conceitos de Banco de Dados, modelagem relacional e SQL através da criação de um sistema capaz de controlar clientes, produtos, estoque, pedidos e pagamentos.

A estrutura foi projetada para representar cenários reais de negócio, utilizando boas práticas de modelagem e integridade dos dados.

## Tecnologias Utilizadas

* MySQL
* SQL
* Modelagem Relacional

## Funcionalidades

### Gestão de Clientes

* Cadastro de clientes
* Controle de informações pessoais
* Gerenciamento de múltiplos endereços

### Catálogo de Produtos

* Categorias de produtos
* Cadastro de produtos
* Controle de disponibilidade

### Controle de Estoque

* Cadastro de ingredientes
* Controle de quantidade disponível
* Registro de movimentações de estoque
* Definição de estoque mínimo

### Produção

* Associação entre produtos e ingredientes
* Controle de receitas

### Pedidos

* Registro de pedidos
* Controle de status
* Entrega ou retirada
* Itens do pedido

### Pagamentos

* Controle de formas de pagamento
* Registro de transações
* Controle de status dos pagamentos

## Estrutura do Projeto

### doceria_ddl.sql

Script responsável pela criação do banco de dados, tabelas, relacionamentos, restrições e índices.

### doceria_dml.sql

Script para inserção e manipulação dos dados.

### doceria_queries.sql

Conjunto de consultas SQL para extração de informações e análise dos dados cadastrados.

## Conceitos Aplicados

* Chaves Primárias (PRIMARY KEY)
* Chaves Estrangeiras (FOREIGN KEY)
* Relacionamentos 1:N
* Relacionamentos N:N
* Integridade Referencial
* Índices para otimização de consultas
* Constraints
* Modelagem Relacional

## Objetivo

Desenvolver uma solução de banco de dados capaz de representar o funcionamento de uma doceria real, aplicando conceitos estudados em Engenharia de Software e Banco de Dados.

## Status

✅ Projeto acadêmico concluído.

## Autora

Anna Karolina Trindade dos Santos
Anny Beatris Serveriano 
Victor Hugo Lemes
Estudante de Engenharia de Software
