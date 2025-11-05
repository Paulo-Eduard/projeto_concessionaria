# Projeto Concessionária

Este projeto simula um sistema web para uma concessionária de carros, com funcionalidades separadas para compradores e vendedores, trazendo uma experiência mais próxima de um site real de vendas de automóveis.

## Objetivo

Criar uma aplicação funcional e visual, onde:

* Clientes podem se cadastrar, fazer login, visualizar carros disponíveis e realizar compras.
* Vendedores podem cadastrar novos carros, editar informações e gerenciar seus anúncios.

## Tecnologias Utilizadas

PHP
MySQL / MariaDB
HTML / CSS

## Banco de Dados

O banco de dados utilizado se chama `projeto1` e contém as seguintes tabelas:

* `clientes`: informações dos clientes (nome, email, senha, telefone, endereço, cidade, estado e data de nascimento).
* `vendedores`: informações dos vendedores (nome, email, senha, telefone, cidade e estado).
* `carros`: carros cadastrados pelos vendedores (modelo, marca, preço, imagem e referência ao vendedor).
* `compras`: registros de compras feitas pelos clientes, incluindo qual carro foi comprado, por qual cliente e o valor pago.

O script SQL já está fornecido para criar o banco e inserir dados de teste.

## Funcionalidades

Para o Comprador

* Cadastro e login de clientes
* Visualização de todos os carros disponíveis, com imagem, marca, modelo e preço
* Compra de carros

Para o Vendedor

* Cadastro e login de vendedores
* Adição de novos carros com imagem e preço
* Edição e exclusão de carros já cadastrados
* Gerenciamento completo de seus anúncios

## Como Rodar o Projeto

1. Crie o banco de dados `projeto1` no phpMyAdmin e rode o script SQL fornecido
2. Coloque os arquivos do projeto na pasta `htdocs` do XAMPP
3. Acesse `http://localhost/projeto1/index.php` no navegador
4. Para comprar um carro, faça login como cliente
5. Para adicionar ou gerenciar carros, faça login como vendedor
   

Espero que goste pretendo melhorar.
