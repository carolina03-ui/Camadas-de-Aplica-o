# API RESTful para Gerenciamento de Tarefas

## Descrição

Esta é uma API RESTful desenvolvida utilizando **FastAPI** para o gerenciamento de tarefas. Ela permite realizar operações de CRUD (Criar, Ler, Atualizar e Deletar) sobre tarefas, com armazenamento em memória usando listas em Python.

## Tecnologias Utilizadas

- **Python**
- **FastAPI**
- **Uvicorn** (para rodar o servidor)

## Funcionalidades

A API permite as seguintes operações:

- **GET /tarefas**: Recupera todas as tarefas.
- **GET /tarefas/{tarefa_id}**: Recupera uma tarefa específica pelo ID.
- **GET /tarefas_pesquisa**: Pesquisa tarefas pelo título.
- **POST /tarefas**: Cria uma nova tarefa.
- **PUT /tarefas/{tarefa_id}**: Atualiza uma tarefa existente pelo ID.
- **DELETE /tarefas/{tarefa_id}**: Deleta uma tarefa pelo ID.

  ## Conclusão

Este projeto demonstrou como criar uma API RESTful simples e funcional usando o **FastAPI** para gerenciar tarefas. A API permite realizar operações básicas de CRUD (Create, Read, Update, Delete) e armazena os dados em memória utilizando listas em Python, proporcionando uma implementação prática e rápida para iniciantes.


