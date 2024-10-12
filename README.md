# Sistema de Gerenciamento de Biblioteca

Este projeto é um sistema simples de gerenciamento de uma biblioteca, utilizando um banco de dados SQLite. Ele permite o cadastro de autores, livros e o controle de empréstimos de livros.

## Estrutura do Banco de Dados

O banco de dados é composto pelas seguintes tabelas:

- **Autores**: Armazena informações sobre os autores, incluindo nome e nacionalidade.
- **Livros**: Armazena informações sobre os livros, incluindo título, autor, ano de publicação e gênero.
- **Empréstimos**: Registra os empréstimos de livros, incluindo o usuário que fez o empréstimo e as datas de empréstimo e devolução.

## Pré-requisitos

- Python 3.x
- Biblioteca `sqlite3` (já incluída na biblioteca padrão do Python)

## Como Usar

1. Clone o repositório:
   ```bash
   git clone https://github.com/seu-usuario/seu-repositorio.git
   cd seu-repositorio
