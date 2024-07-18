<h1 align="center"> 🥇 Teste: Campos Dealer 🚀 </h1>
  
## 💻 Projeto 

- Desenvolvimento de uma aplicação Fullstack para uma Loja, onde possui:
  - CRUD do cliente
  - CRUD do produto
  - CRUD da venda
- O padrão utilzado é o MVC.

<br>

## 🔎 Para Rodar

Necessário ter/instalar:
- Visual Studio
- Clonar o projeto
- .Net 8
- Microsoft.EntityFrameworkCore
- Microsoft.EntityFrameworkCore.Sqlite
  -   Esses dois últimos podem ser instalados através do gerenciador de pacotes NuGet. Essa opção (Manage NuGet Packages) aparece ao clicar com mouse direito no projeto da API por exemplo.

Ao rodar a aplicação, será gerado o banco de dados automáticamente na raíz do projeto.

<br>

## 🧐 Não consegui realizar

Teve alguns pontos no documento que foi passado que não consegui realizar. Pesquisei bastante todos eles para tentar entender e fazer funcionar:
- SQL Server
  - Falhou por conta dos dados do login na ConnectionString;
  - Por algum motivo não consigo logar no SQL Server, optei por usar o SQLite.
- React
  - Confesso que não sabia como adicionar o React no Blazor;
  - Mesmo assim, tentei fazer alguns procedimentos, mas estavam ficando uma gambiarra bem feia.
- EndPoints fornecidos
  - Esse eu tentei e testei de várias formas, pesquisei em todo lugar, mas não consegui fazer a requisição funcionar e trazer os dados corretamente.
- o CRUD de Venda
  - Tive problemas no VendaModel, pois não sabia o que fazer com as outras tabelas referenciadas. Se eu as iniciasse com "New", iria criar dados inconsistentes nas suas respectivas tabelas
  - Por conta desse problema, o CRUD de Venda inteiro não funciona pois não consigo adicionar uma Venda.
- Os outros dois CRUDS
  - Nesses ainda falta aplicar uma regra de negócio para quando deletar um produto que já esteja associado a uma venda por exemplo. No caso acho que o mais válido seria não deletar.
  - Teria que aplicar essa regra e mais algumas outras regras que pensei no Produto e no Cliente.

  São esses os problemas que tive. Demorei para resolver uns e outros realmente não achei solução.

<br>


## 🚀 Tecnologias

Este projeto foi desenvolvido utilizando:
- C#
- .Net 8
- Entity Framework Core
- SQLite
- Blazor (HTML)
- CSS (Bootstrap)
- JavaScript e Jquery
  
## Finalização ❤

Feito com ♥ por Mikael Sirqueira
