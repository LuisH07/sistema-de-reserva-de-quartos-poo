## *Sistema de Reserva de Quartos de Hotel*

Este projeto é um sistema web desenvolvido para realizar a gestão de reservas de quartos em um hotel. O sistema permite que os usuários realizem reservas, visualizem quartos disponíveis e gerenciem os detalhes de suas estadias. O objetivo do projeto é proporcionar uma plataforma simples e funcional para a administração de reservas e informações de hóspedes, integrando uma API RESTful para facilitar o acesso ao sistema por meio de requisições HTTP.


### *Tecnologias Utilizadas*

- **Planejamento e Controle de Versão**
  - *Git*: Para versionamento do código.
  - *GitHub*: Plataforma para hospedagem do repositório remoto e colaboração.
  
- **Desenvolvimento Back-end**
  - *Java*: Linguagem principal utilizada para o desenvolvimento do sistema.
  - *Spring Framework*: Framework para criação da aplicação web, fornecendo infraestrutura para o desenvolvimento de APIs RESTful e gerenciamento de dependências.
    - *Spring Boot*: Usado para criar uma aplicação autossuficiente, simplificando a configuração do Spring.
    - *Spring Data JPA*: Facilita a integração com o banco de dados, permitindo realizar operações de forma eficiente usando o JPA (Java Persistence API).
    - *Spring Web*: Usado para criar a camada de controle de requisições HTTP (REST Controllers).
    - *Spring Security*: Para autenticação e autorização de usuários.
    - *JWT (JSON Web Token)*: Para autenticação baseada em tokens.
  
- **Banco de Dados**
  - *PostgreSQL*: Banco de dados relacional utilizado para armazenar as informações de reservas, hóspedes e quartos.
  - *pgAdmin4*: Interface gráfica para gerenciamento do banco de dados PostgreSQL.
  
- **Testes Automatizados**
  - *JUnit*: Para criação de testes unitários.
  - *Mockito*: Para simular comportamentos de dependências e facilitar testes isolados.
  - *Spring Boot Test*: Para testes de integração dentro do Spring Framework.
  
- **Ferramentas de Testes de API**
  - *Postman*: Ferramenta usada para testar as APIs RESTful do projeto de maneira fácil e rápida.
  - *Swagger (Springdoc OpenAPI)*: Para documentação automática da API.
  
- **Gerenciamento de Dependências e Build**
  - *Maven*: Ferramenta de automação de construção usada para gerenciar dependências e compilar o projeto.
  - *Lombok*: Biblioteca para reduzir o código boilerplate, criando automaticamente getters, setters, construtores e outros métodos com anotações simples.
  
- **Implantação e Deploy**
  - *Render*: Plataforma de hospedagem para deploy de aplicações web e APIs.
  - *Docker*: Para criar contêineres e facilitar a implantação (opcional).
  - *GitHub Actions*: Para automação de deploy e CI/CD (opcional).

---

### *Funcionalidades*

- *Cadastro de Hóspedes*: Adicionar, editar e excluir informações de hóspedes.
- *Gestão de Quartos*: Visualizar e atualizar a disponibilidade de quartos.
- *Reservas*: Criar e visualizar reservas feitas pelos hóspedes.
- *API RESTful*: Endpoint para interagir com o sistema via requisições HTTP (GET, POST, PUT, DELETE).
  
Aqui está o trecho formatado em Markdown:


### Como Rodar o Projeto

### Como Rodar o Projeto

1. **Clone o repositório**:
   ```bash
   git clone https://github.com/LuisH07/sistema-de-reserva-de-quartos-poo.git


2. **Entre na pasta do projeto**:
   ```bash
   cd sistema-de-reserva-de-quartos-poo
   ```

3. **Execute a aplicação**:
   - Se estiver usando Maven, execute o comando:
     ```bash
     mvn spring-boot:run
     ```
   - Ou, se preferir, use a IDE **IntelliJ IDEA** para rodar o projeto.

4. **Acesse a aplicação** em:  
   [http://localhost:8080](http://localhost:8080)
