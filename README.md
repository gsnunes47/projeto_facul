# Projeto SoftForge — Hotel Management System

> 📚 **Projeto acadêmico** — sistema de gerenciamento hoteleiro desenvolvido em grupo com Python e Flask.

Projeto desenvolvido durante a faculdade como proposta de um sistema interno para gerenciamento de um hotel. Foi também um dos primeiros contatos do grupo com desenvolvimento web utilizando Flask.

A aplicação reúne autenticação de usuários, diferentes níveis de acesso e funcionalidades voltadas à organização da rotina dos funcionários.

## Funcionalidades implementadas

- Login e logout de usuários;
- Cadastro de usuários por um gerente;
- Perfis de acesso para gerente, atendente e funcionário;
- Listagem de funcionários;
- Filtro de funcionários por cargo;
- Pesquisa de funcionários por nome ou e-mail;
- Criação e acompanhamento de tarefas;
- Registro de quem concluiu uma tarefa e quando ela foi realizada;
- Exclusão de tarefas restrita ao gerente;
- Área de reservas;
- Páginas de erro personalizadas para 401 e 404.

## Tecnologias

- Python
- Flask
- Flask-Login
- Flask-WTF / WTForms
- Flask-SQLAlchemy
- Flask-Bcrypt
- SQLite
- HTML
- CSS

## Estrutura

O projeto utiliza Flask no backend, templates renderizados com Jinja e SQLite para persistência dos dados.

Os usuários possuem cargos diferentes, utilizados pelo sistema para controlar algumas ações. Gerentes podem cadastrar usuários e excluir tarefas, enquanto funcionários possuem acesso mais restrito ao gerenciamento das tarefas.

## Contexto

Este é um projeto acadêmico desenvolvido em grupo e mantido como registro de aprendizado. O repositório contém código produzido por diferentes integrantes e reflete um período inicial de contato com Flask, Git e desenvolvimento colaborativo.

Algumas partes ficaram incompletas — especialmente a área de reservas — e o projeto não é mantido atualmente.
