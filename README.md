# Board de Tarefas com Java

## Descrição do Projeto
Este projeto é uma aplicação simples de um Board de Tarefas (também conhecido como To-Do List), construída utilizando Java e MySQL. O objetivo principal é permitir que os usuários criem, editem, marquem como concluídas e excluam tarefas em uma interface simples.

## Funcionalidades Principais
- **Cadastro de Tarefas:** O usuário pode criar novas tarefas, atribuindo título, descrição e data de vencimento.
- **Edição de Tarefas:** Permite que o usuário edite detalhes das tarefas cadastradas.
- **Marcação de Concluídas:** O usuário pode marcar tarefas como concluídas, facilitando o gerenciamento das atividades.
- **Exclusão de Tarefas:** O usuário tem a opção de excluir tarefas que não são mais necessárias.
- **Armazenamento de Dados:** Utiliza um banco de dados MySQL para armazenar todas as informações sobre as tarefas, garantindo persistência entre as execuções da aplicação.

## Tecnologias Utilizadas
- **Java:** Linguagem principal para a implementação da lógica de negócios e a interface da aplicação.
- **MySQL:** Banco de dados utilizado para armazenar as informações das tarefas.
- **JDBC (Java Database Connectivity):** Usado para estabelecer a conexão entre a aplicação Java e o banco de dados MySQL.
- **IDE IntelliJ IDEA:** Ambiente de desenvolvimento integrado utilizado para o desenvolvimento do projeto.

## Como Funciona
O projeto utiliza a arquitetura tradicional de conexão com banco de dados, onde as operações de CRUD (*Create, Read, Update, Delete*) são realizadas no banco de dados MySQL, permitindo que o usuário interaja com as tarefas de forma intuitiva. 

A conexão com o banco é feita através do JDBC, utilizando a string de conexão:
```java
jdbc:mysql://localhost:3306/board
```
onde `board` é o nome do banco de dados.

## Objetivo
O objetivo deste projeto é proporcionar uma compreensão prática de como integrar uma aplicação Java com um banco de dados MySQL, realizando operações básicas de manipulação de dados. 

É um exemplo de como sistemas de gerenciamento de tarefas podem ser desenvolvidos de forma simples e eficiente utilizando tecnologias de back-end.
