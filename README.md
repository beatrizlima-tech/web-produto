# 🛍️ Web Produto

![Angular](https://img.shields.io/badge/Angular-21-red?style=for-the-badge\&logo=angular)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge\&logo=typescript)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge\&logo=html5\&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge\&logo=css3\&logoColor=white)
![REST API](https://img.shields.io/badge/REST%20API-Integration-blue?style=for-the-badge)
![Build](https://img.shields.io/badge/build-passing-brightgreen?style=for-the-badge)
![License](https://img.shields.io/badge/license-MIT-lightgrey?style=for-the-badge)

---

# 📌 Sobre o projeto

O **Web Produto** é uma aplicação frontend desenvolvida com **Angular** para consulta de produtos, integrada a uma API REST desenvolvida com **Java** e **Spring Boot**.

O projeto foi criado com foco na prática de consumo de APIs REST, comunicação entre frontend e backend, utilização do **HttpClient** e construção de interfaces utilizando Angular.

---

# 🚀 Funcionalidades

* Pesquisa de produtos por nome
* Consumo de API REST utilizando HttpClient
* Consulta dinâmica de produtos
* Integração com backend Spring Boot
* Interface responsiva
* Exibição dos resultados retornados pela API

---

# 🧱 Tecnologias Utilizadas

* Angular
* TypeScript
* HTML5
* CSS3
* FormsModule
* HttpClient
* REST API

---

# 🏗️ Estrutura do Projeto

```text
src/

├── app
│   ├── app.html
│   ├── app.css
│   ├── app.ts
│   ├── app.config.ts
│   └── app.routes.ts
```

---

# 📊 Arquitetura

```text
Usuário
      │
      ▼
Web Produto (Angular)
      │
      ▼
HttpClient
      │
      ▼
Produtos API (Spring Boot)
      │
      ▼
PostgreSQL
```

---

# 🔗 Integração com Backend

Este frontend consome o endpoint:

```http
GET /api/v1/produtos/listar?nome={nome}
```

Projeto relacionado:

**Produtos API**

https://github.com/beatrizlima-tech/produtos-api

---

# ⚙️ Como Executar

## 1. Clonar o repositório

```bash
git clone https://github.com/beatrizlima-tech/web-produto.git
```

---

## 2. Instalar dependências

```bash
npm install
```

---

## 3. Executar a aplicação

```bash
ng serve
```

---

## 4. Acessar

```text
http://localhost:4200
```

Para que a aplicação funcione corretamente, a API backend deve estar em execução:

```text
http://localhost:8081
```

---

# 📚 Conceitos Aplicados

* Componentização
* Angular Standalone Components
* Two-Way Data Binding
* FormsModule
* HttpClient
* Consumo de APIs REST
* Integração Frontend e Backend
* Programação Assíncrona
* Organização de componentes

---

# 📌 Melhorias Futuras

* Exibir os produtos em tabela
* Implementar paginação
* Adicionar filtros avançados
* Criar tela de detalhes do produto
* Exibir mensagens de carregamento
* Melhorar tratamento de erros
* Criar testes automatizados
* Publicar a aplicação

---

# 👩‍💻 Autora

**Beatriz Lima de Oliveira**

🔗 GitHub

https://github.com/beatrizlima-tech

💼 LinkedIn

https://www.linkedin.com/in/beatrizlima-tech
