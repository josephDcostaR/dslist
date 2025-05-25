# 🎮 Intensivão de Java - DevSuperior

## 🚀 Projeto: DSList

O **DSList** é um sistema backend de uma **API para listagem de jogos**, desenvolvido durante o **Intensivão de Spring Boot** promovido pela **DevSuperior**.

---

## 🛠️ Tecnologias e Ferramentas Utilizadas

- **Java 21**  
- **Spring Boot**  
- **PostgreSQL**  
- **JPA (Java Persistence API)**  
- **H2 Database**  
- **UML (Unified Modeling Language)**  

---

## 📚 Descrição

Este projeto consiste na criação de uma **API RESTful** para o gerenciamento de uma lista de jogos, aplicando boas práticas de desenvolvimento com **Java** e **Spring Boot**, como:

- Estrutura em camadas (**Controller**, **Service**, **Repository**).  
- Modelagem de dados com **Entidades e ORM**.  
- Padrão **DTO** para transferência de dados.  
- **Database seeding** para inserção de dados iniciais.  
- Consumo via clientes **HTTP**.

---

## 🗂️ Modelo de Domínio DSList

![dslist-model](https://github.com/user-attachments/assets/d4b3d35e-e408-41eb-a565-e899af3430ee)

---

## ✅ Funcionalidades Implementadas

- Mapeamento de entidades com **JPA**.  
- Integração com bancos de dados **H2** e **PostgreSQL**.  
- Estrutura de projeto seguindo o padrão **Spring REST**.  
- Operações básicas com **GET** para listagem de dados.

---

## ▶️ Como Usar

No momento, a utilização está disponível apenas através de ferramentas como o **Postman**, com os seguintes **endpoints**:

- `GET` → [http://localhost:8080/games](http://localhost:8080/games) → Retorna todos os jogos do banco de dados.  
- `GET` → [http://localhost:8080/games/1](http://localhost:8080/games/1) → Retorna o jogo especificado na URL (ex.: ID 1).  
- `GET` → [http://localhost:8080/lists](http://localhost:8080/lists) → Retorna todas as listas de jogos.  
- `GET` → [http://localhost:8080/lists/2/games](http://localhost:8080/lists/2/games) → Retorna todos os jogos de uma lista específica (ex.: ID 2).  
- `POST` → [http://localhost:8080/lists/2/replacement](http://localhost:8080/lists/2/replacement) → Realiza a troca de posição entre os jogos dentro da lista.

---

## 🚧 Em Andamento

- Implementação de novas rotas e operações.  
- Melhorias no tratamento de exceções e validações.  
- Documentação da API utilizando **Swagger** (em desenvolvimento).

---

## 💡 Aprendizados

Este projeto tem sido uma excelente oportunidade para aprofundar meus conhecimentos em desenvolvimento backend com **Java** e **Spring Boot**.  

Pude evoluir na aplicação de práticas profissionais como a estruturação de projetos em camadas, modelagem com ORM, e integração com bancos de dados relacionais.  

Além disso, compreendi melhor como desenvolver APIs robustas utilizando **Spring**, com uma visão mais alinhada ao mercado de trabalho.

---

