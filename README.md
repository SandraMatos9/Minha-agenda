# Minha Agenda

## Resumo do Projeto
"Minha Agenda" é uma aplicação web para gerenciar contatos pessoais. Os usuários podem adicionar, visualizar, editar e remover contatos. Cada contato possui informações básicas como nome, telefone e observações.

## ✔️ Funcionalidades
- **Adicionar Contatos:** Os usuários podem adicionar novos contatos preenchendo um formulário com o nome, telefone e observações do contato.
- **Listar Contatos:** Os contatos são listados em uma tabela, exibindo o ID, nome e telefone de cada contato.
- **Visualizar Contatos:** Os usuários podem visualizar detalhes de um contato específico.
- **Editar Contatos:** Os usuários podem editar as informações de um contato.
- **Remover Contatos:** Os usuários podem remover contatos da lista.

## ✔️ Técnicas e Tecnologias Utilizadas
- PHP
- HTML/CSS
- Bootstrap (para a interface do usuário)
- MySQL
- Apache
- Visual Studio Code (como IDE)

## 🛠️ Abrir e Rodar o Projeto

### Pré-requisitos
- [PHP](https://www.php.net/downloads.php) instalado.
- [MySQL](https://www.mysql.com/downloads/) instalado e configurado.
- Servidor Apache (pode ser configurado com [XAMPP](https://www.apachefriends.org/index.html) ou similar).

### Passos para Rodar o Projeto Localmente
1. Clone o repositório:
   ```sh
   git clone git@github.com:SandraMatosTech/minha-agenda.git

2. Navegue até o diretório do projeto:
   
cd minha-agenda

3.Configure o banco de dados MySQL:

Crie um banco de dados chamado minha_agenda.
Importe o arquivo database.sql localizado no diretório config para criar as tabelas necessárias.

4.Atualize as configurações de conexão com o banco de dados no arquivo config/db.php:
<?php
$dbHost = 'localhost';
$dbName = 'minha_agenda';
$dbUser = 'your_user';
$dbPass = 'your_password';
?>


5.Inicie o servidor Apache e acesse a aplicação:

Coloque os arquivos do projeto no diretório htdocs do seu servidor Apache.
Abra seu navegador e acesse http://localhost/minha-agenda.
