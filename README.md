# Juridiq Full Stack Challenge

## Objetivo do Teste

Avaliar as habilidades básicas do candidato em desenvolvimento back-end utilizando Node.js.

## Instruções Gerais

- **Tecnologias:** Node.js com TypeScript.
- **Framework:** Fastify (opcional).
- **Ferramentas:** Git para versionamento de código.

## Tarefas

### 1. Configuração do Projeto

- Inicialize um novo projeto Node.js utilizando TypeScript.
- Configure as dependências necessárias.

### 2. Criação de uma API Simples

- **Entidade:** `Book`
  - **Campos:** `id` (string, UUID), `title` (string), `author` (string), `publishedYear` (number)
- **Endpoints:**
  - `POST /books`:Adiciona um novo livro.
  - `GET /books`: Lista todos os livros.

## Detalhamento dos Endpoints

### POST /books

- **Descrição:** Adiciona um novo livro.
- **Request Body:**
  ```json
  {
    "title": "string",
    "author": "string",
    "publishedYear": "number"
  }
  ```

### GET /books

- **Descrição:** Lista todos os livros.

##### BÔNUS:

- Descrição: Filtrar livros pelo `title`.

## Entrega

O candidato deve enviar o código fonte através de um repositório no GitHub, para o seguinte e-mail: contato@juridiq.com.br

O repositório deve conter um README.md com instruções básicas sobre como configurar e executar o projeto.
