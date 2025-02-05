## *Sistema de Reserva de Quartos de Hotel*

Este projeto é um sistema web desenvolvido para realizar a gestão de reservas de quartos em um hotel. O sistema permite que os usuários realizem reservas, visualizem quartos disponíveis e gerenciem os detalhes de suas estadias. O objetivo do projeto é proporcionar uma plataforma simples e funcional para a administração de reservas e informações de hóspedes, integrando uma API RESTful para facilitar o acesso ao sistema por meio de requisições HTTP.

### *Tecnologias Utilizadas*

- *Java*: Linguagem de programação principal utilizada para o desenvolvimento do sistema.
- *Spring Framework*: Framework para criação da aplicação web, fornecendo infraestrutura para o desenvolvimento de APIs RESTful, além de facilitar a configuração e o gerenciamento de dependências.
  - *Spring Boot*: Usado para criar uma aplicação autossuficiente, simplificando a configuração do Spring.
  - *Spring Data JPA*: Facilita a integração com o banco de dados, permitindo realizar operações no banco de dados de forma eficiente usando o JPA (Java Persistence API).
  - *Spring Web*: Usado para criar a camada de controle de requisições HTTP (REST Controllers).
- *PostgreSQL*: Banco de dados relacional utilizado para armazenar as informações de reservas, hóspedes e quartos.
- *JPA (Java Persistence API)*: Interface para mapear objetos Java para tabelas de um banco de dados relacional, facilitando as operações de CRUD (Create, Read, Update, Delete).
- *Maven*: Ferramenta de automação de construção usada para gerenciar dependências e construir o projeto.
- *Lombok*: Biblioteca para reduzir o código boilerplate, criando automaticamente getters, setters, construtores e outros métodos com anotações simples.
- *Postman*: Ferramenta usada para testar as APIs RESTful do projeto de maneira fácil e rápida.
- *GitHub*: Plataforma para versionamento de código, onde o projeto é hospedado e gerenciado.

### *Possíveis Tecnologias Úteis (Opcionais):*
- *Docker*: Facilita rodar o banco de dados sem instalação manual, usando contêineres.
- *Swagger*: Gera documentação automática da API, facilitando a visualização e testes.

---

### *Funcionalidades*

- *Cadastro de Hóspedes*: Adicionar, editar e excluir informações de hóspedes.
- *Gestão de Quartos*: Visualizar e atualizar a disponibilidade de quartos.
- *Reservas*: Criar e visualizar reservas feitas pelos hóspedes.
- *API RESTful*: Endpoint para interagir com o sistema via requisições HTTP (GET, POST, PUT, DELETE).
  
### *Como Rodar o Projeto*

1. Clone o repositório:
   bash
   git clone https://github.com/LuisH07/sistema-de-reserva-de-quartos-poo.git
   

2. Entre na pasta do projeto:
   bash
   cd sistema-de-reserva-de-quartos-poo
   

3. Execute a aplicação:
   Se estiver usando *Maven*, execute o comando:
   bash
   mvn spring-boot:run
   
   Ou, se preferir, use a IDE *IntelliJ IDEA* para rodar o projeto.

4. Acesse a aplicação em http://localhost:8080.
