﻿# Teste-API-SpringBoot
 
## Descrição

Esta é uma API simples de gerenciamento de tarefas desenvolvida com Spring Boot. Ela permite listar, adicionar e excluir tarefas.

## Tecnologias Utilizadas
* Java

* Spring Boot

* Jackson (para manipulação de JSON)



## Documentação da API

## Endpoints

### 1. Listar Tarefas

```http
  GET /tasks
```

| Parâmetro   | Tipo       | Descrição                                   |
| :---------- | :--------- | :------------------------------------------ |
| `task`      | `string` |Retorna a lista de tarefas cadastradas.  |

### 2. Criar Tarefa

```http
    POST /tasks
```

| Parâmetro   | Tipo       | Descrição                                   |
| :---------- | :--------- | :------------------------------------------ |
| `task`      | `string` | **Obrigatório**.O nome da tarefa a ser adicionada |

### 3. Deletar Todas as Tarefas

```http
    DELETE /tasks
```

## Melhorias Futuras

* Adicionar suporte para banco de dados.

* Criar um endpoint para deletar tarefas individualmente.

* Implementar autenticação e autorização.


