# Cadastro de Clientes

## 📌 Sobre o projeto

Este projeto consiste em um sistema simples de **cadastro de clientes**, desenvolvido utilizando HTML e PHP, com conexão a um banco de dados MySQL.

O formulário permite cadastrar o **nome** e o **e-mail** do cliente.

## 🛠️ Tecnologias utilizadas

* HTML
* PHP
* MySQL
* MySQLi

## ⚙️ Funcionamento

O usuário preenche o nome e o e-mail no formulário e clica em **Cadastrar**. Os dados são enviados pelo método `POST` e inseridos na tabela `clientes` do banco de dados `exercicio`.

Após a tentativa de cadastro, o sistema informa se o cliente foi cadastrado com sucesso ou se ocorreu algum erro.

## 🗄️ Banco de dados

O projeto utiliza o banco de dados:

```text
exercicio
```

E a tabela utilizada para o cadastro é:

```text
clientes
```

## ▶️ Como executar

1. Inicie o Apache e o MySQL.
2. Crie o banco de dados `exercicio`.
3. Certifique-se de que a tabela `clientes` esteja criada.
4. Coloque o arquivo `10_insercao.php` na pasta do servidor.
5. Acesse o arquivo pelo navegador.

## 🎯 Objetivo

Praticar a criação de formulários em HTML, o recebimento de dados com PHP e a inserção dessas informações em um banco de dados MySQL.
