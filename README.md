# Sistema de Gerenciamento com Java Spring Boot

## 📖 Introdução
Este projeto é um sistema de gerenciamento desenvolvido com Java Spring Boot 3. O sistema permite realizar operações de CRUD (Criar, Ler, Atualizar e Excluir) para gerenciar informações sobre usuários, produtos, categorias e pedidos.

## 💻 Tecnologias Utilizadas
![Java](https://img.shields.io/badge/java-%23ED8B00.svg?style=for-the-badge&logo=openjdk&logoColor=white) ![Spring Boot](https://img.shields.io/badge/spring%20boot-6DB33F.svg?style=for-the-badge&logo=spring&logoColor=white) ![Postman](https://img.shields.io/badge/postman-FF6C37.svg?style=for-the-badge&logo=postman&logoColor=white) ![H2](https://img.shields.io/badge/h2-4A148C.svg?style=for-the-badge&logo=h2database&logoColor=white)

### Funcionalidades
- **CRUD de Usuários:** Adicionar, visualizar, atualizar e remover usuários.
- **CRUD de Produtos:** Gerenciar produtos com informações como nome, descrição e preço.
- **CRUD de Categorias:** Organizar produtos em categorias, permitindo a gestão de suas informações.
- **CRUD de Pedidos:** Criar e gerenciar pedidos, incluindo detalhes de pagamento e itens do pedido.
- **Consultas:** Consultar a lista de usuários, produtos, categorias e pedidos associados via API.
- **Teste de API:** Usar o Postman para interagir com as APIs de forma fácil e eficiente.
- **H2 Console:** Acessar o console H2 para visualização e manipulação direta do banco de dados.

## Como Configurar e Executar
Para configurar e executar o projeto:
1. **Configurar o Ambiente:**
   - Instale o [STS Eclipse](https://spring.io/tools) (Spring Tool Suite).
   - Clone o repositório do projeto em sua máquina local.

2. **Configurar o Banco de Dados:**
   - O projeto utiliza o H2 Database, que é um banco de dados em memória.
   - As configurações do H2 estão definidas no arquivo `application-test.properties`.

3. **Executar o Projeto:**
   - Abra o projeto no STS Eclipse.
   - Execute a classe principal do Spring Boot.
   - Acesse o H2 Console em `http://localhost:8080/h2-console` para interagir diretamente com o banco de dados.
   - Use o Postman para fazer requisições às APIs do sistema.


### Telas do Sistema
Aqui estão algumas telas principais do sistema:

![Postman](https://github.com/user-attachments/assets/5dcdcf9e-8b37-442e-9678-12ad5ced969d)  
*Interação com a API usando Postman*

![H2 Console](https://github.com/user-attachments/assets/9a640a06-4396-40ba-8b75-16b87dcac10d)  
*Console H2 para gerenciamento do banco de dados*

## 🛠️ API Endpoints
- **Usuários:**
  - `GET /users` - Lista todos os usuários.
  - `POST /users` - Cria um novo usuário.
  - `PUT /users/{id}` - Atualiza um usuário existente.
  - `DELETE /users/{id}` - Remove um usuário.

- **Produtos:**
  - `GET /products` - Lista todos os produtos.
  - `POST /products` - Cria um novo produto.
  - `PUT /products/{id}` - Atualiza um produto existente.
  - `DELETE /products/{id}` - Remove um produto.

- **Categorias:**
  - `GET /categories` - Lista todas as categorias.
  - `POST /categories` - Cria uma nova categoria.
  - `PUT /categories/{id}` - Atualiza uma categoria existente.
  - `DELETE /categories/{id}` - Remove uma categoria.
