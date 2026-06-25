# 🛍️ Web Produto

Frontend desenvolvido com Angular para consulta de produtos, consumindo uma API REST criada com Java e Spring Boot.

O projeto tem como objetivo praticar integração entre frontend e backend, utilizando Angular, TypeScript, Forms e HttpClient para realizar requisições HTTP.

---

## 🚀 Tecnologias Utilizadas

* Angular
* TypeScript
* HTML5
* CSS3
* FormsModule
* HttpClient
* API REST

---

## ✨ Funcionalidades

* Campo de busca por nome do produto
* Consulta de produtos em API REST
* Integração com backend Spring Boot
* Requisição HTTP GET com HttpClient
* Interface responsiva com CSS
* Exibição inicial dos resultados no console do navegador

---

## 🏗️ Arquitetura

```text id="7kjab1"
Web Produto (Angular)
        │
        ▼
Produtos API (Spring Boot)
        │
        ▼
PostgreSQL
```

---

## 🔗 Integração com Backend

Este frontend consome o endpoint de listagem da Produtos API:

```text id="in4gr8"
GET http://localhost:8081/api/v1/produtos/listar?nome={nomeProduto}
```

Projeto relacionado:

```text id="ejf5gh"
https://github.com/beatrizlima-tech/produtos-api
```

---

## 📂 Estrutura do Projeto

```text id="mcx53l"
src/
├── app/
│   ├── app.html
│   ├── app.css
│   ├── app.ts
│   ├── app.config.ts
│   └── app.routes.ts
```

---

## ▶️ Como Executar

### Pré-requisitos

* Node.js
* Angular CLI

### Clonar o projeto

```bash id="kik1r9"
git clone https://github.com/beatrizlima-tech/web-produto.git
```

### Instalar dependências

```bash id="vut6i5"
npm install
```

### Executar

```bash id="ewmb2r"
ng serve
```

A aplicação ficará disponível em:

```text id="xx36vj"
http://localhost:4200
```

Para a consulta funcionar, a API backend deve estar em execução:

```text id="y7umxa"
http://localhost:8081
```

---

## 📚 Objetivo

Este projeto foi desenvolvido para praticar a criação de interfaces com Angular e o consumo de APIs REST, reforçando conceitos de integração entre frontend e backend.

---

## 👩‍💻 Autora

**Beatriz Lima de Oliveira**

GitHub:
https://github.com/beatrizlima-tech
