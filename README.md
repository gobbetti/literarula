# 📚 LiterAlura

Projeto desenvolvido como desafio da plataforma **Alura** no curso de Java.

O **LiterAlura** é um catálogo de livros que permite buscar informações diretamente da API pública da **OpenLibrary**, armazenar os dados localmente em um banco de dados **SQLite** e consultar os livros e autores cadastrados.

## 🚀 Funcionalidades

- 🔍 Buscar livros por título na API OpenLibrary
- 💾 Salvar livros e autores no banco de dados local
- 📑 Listar todos os livros cadastrados
- 👨‍💻 Listar todos os autores cadastrados
- 🌎 Filtrar livros por idioma
- 🖥️ Interface via console (terminal)

## 🛠️ Tecnologias Utilizadas

- Java 17
- Maven
- SQLite (via JDBC)
- Gson (manipulação de JSON)
- OkHttp (requisições HTTP)

## 🗃️ Banco de Dados

O banco de dados é criado localmente no arquivo `literAlura.db` e armazena os seguintes dados:

- Livros (título, autores, idioma, ano de publicação)
- Autores (nome)

## 🔗 API Utilizada

- [OpenLibrary API](https://openlibrary.org/developers/api)

Exemplo de endpoint de busca:  
`https://openlibrary.org/search.json?title=harry+potter`

## 🎯 Como executar o projeto

1. **Clone o repositório:**
```bash
git clone https://github.com/Gobbetti/literAlura.git
