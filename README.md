# Products API

## Descrição do Projeto
<p>API CRUD de produtos</p>

<h2 align="center">💻 Technologies</h2>
<div align="center" style="display: inline_block"><br>
  <img align = "center" src="https://img.shields.io/badge/.NET-5C2D91?style=for-the-badge&logo=.net&logoColor=white" />
  <img align = "center" src="https://img.shields.io/badge/Microsoft_SQL_Server-CC2927?style=for-the-badge&logo=microsoft-sql-server&logoColor=white" />
</div>
  
### Pré Requisitos
<p>Este projeto usa um banco de dados SQL Server, sua string de conexão deve ser colocada em "SqlServer" no arquivo appsettings.Development</p>
<p>Desenvolvido na versão .NET 8</p>

### Features

- [x] Cadastro de produtos
- [x] Consulta de produtos
- [x] Atualização de produtos
- [x] Exclusão de produtos


### Detalhes
<p>Foi desenvolvido apenas o back-end, os testes de requisição podem ser realizados em aplicativos como Postman ou Insomnia</p>

<br>
<h2 align="center">Exemplos de testes de requisição</h2>

### POST
<p>http://localhost:5038/products</p>
<p>Body: { "code": "5", "name": "Memory 8gb", "description": "memoria ram", "categoryId": 1, "tags": ["computer", "technologie"]}</p>

### GET
<p>http://localhost:5038/products/1</p>

### PUT
<p>http://localhost:5038/products/1</p>
<p>body: { "code": "8", "name": "Memory 16gb", "description": "memoria ram2", "categoryId": 1, "tags": ["computer2", "technologie2"]}</p>

### DELETE
<p>http://localhost:5038/products/1</p>

<h4 align="center"> Projeto Concluído </h4>
