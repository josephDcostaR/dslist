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

No momento, a utilização está disponível apenas através de ferramentas como o **Postman**, utilizando os seguintes **endpoints**:

---

### 🔹 `GET` → `/games`  
Retorna todos os jogos do banco de dados.

**Exemplo de resultado:**  
![get-1](https://github.com/user-attachments/assets/076f0e7a-9822-4715-9a45-7a29cfb41bb4)

---

### 🔹 `GET` → `/games/{id}`  
Retorna o jogo especificado na URL (ex.: ID `1`).

**Exemplo de resultado:**  
![get-2](https://github.com/user-attachments/assets/188a4dae-331c-4064-9a96-2c75ad435a63)

---

### 🔹 `GET` → `/lists`  
Retorna todas as listas de jogos.

**Exemplo de resultado:**  
![get-3](https://github.com/user-attachments/assets/f93242e4-8f1b-4ec9-90d3-866f789a5a15)

---

### 🔹 `GET` → `/lists/{id}/games`  
Retorna todos os jogos de uma lista específica (ex.: ID `2`).

**Exemplo de resultado:**  
![get-4](https://github.com/user-attachments/assets/b2bb073b-c16b-4e18-b6cf-140b6f8f07c2)

---

### 🔹 `POST` → `/lists/{id}/replacement`  
Realiza a troca de posição entre os jogos dentro da lista.

**Exemplo de resultado:**  

✅ Antes da troca:  
![post-1-antes](https://github.com/user-attachments/assets/ccbf2297-dd86-414f-b202-e963ecb11ffe)

✅ Troca de posições feita via Postman: 
![post-1-postman](https://github.com/user-attachments/assets/cec4f12e-8f18-43d9-ab14-c127ffaf4a7b)


✅ Resultado após a troca:  
![post-1-depois](https://github.com/user-attachments/assets/3d7f71cc-cf42-4981-a6cf-32b26fe9c7cf)

---



## 🚧 Em Andamento

Atualmente, o sistema está configurado apenas para o ambiente de **`application-test`**.  
Já existem perfis para **dev** e **prod**, mas ainda não realizo deploy em produção, seja por limitações de hardware ou por falta de conhecimento técnico — aspectos que estou estudando e pretendo dominar em breve.

---

### ✅ Próximas melhorias:

- Implementação de novas rotas e operações.
- Aprimoramento no tratamento de exceções e validações.
- Documentação da API utilizando **Swagger** (em desenvolvimento).

---


## 💡 Aprendizados

Este projeto tem sido uma excelente oportunidade para aprofundar meus conhecimentos em desenvolvimento backend com **Java** e **Spring Boot**.  

Pude evoluir na aplicação de práticas profissionais como a estruturação de projetos em camadas, modelagem com ORM, e integração com bancos de dados relacionais.  

Além disso, compreendi melhor como desenvolver APIs robustas utilizando **Spring**, com uma visão mais alinhada ao mercado de trabalho.

---

