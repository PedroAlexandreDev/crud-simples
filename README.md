📋 To-Do List API

API RESTful para gerenciamento de tarefas (To-Do List), desenvolvida em Spring Boot.
🚀 Funcionalidades

    Criar uma nova tarefa

    Listar todas as tarefas

    Atualizar uma tarefa

    Marcar uma tarefa como concluída

    Deletar uma tarefa

🛠 Tecnologias utilizadas

    Java 17

    Spring Boot

    Spring Web

    Maven

    H2 Database (opcional)

    Swagger OpenAPI (opcional)

📂 Estrutura do Projeto

src/main/java/com/app/todolist
├── controller   # Camada de controle (REST API)
├── service      # Lógica de negócio
├── entity       # Entidades JPA
└── repository   # Acesso ao banco de dados

📑 Endpoints principais
Método	Endpoint	Descrição
POST	/api/tasks	Criar nova tarefa
GET	/api/tasks	Listar todas as tarefas
PUT	/api/tasks/{id}	Atualizar tarefa existente
POST	/api/tasks/{id}/complete	Marcar tarefa como concluída
DELETE	/api/tasks/{id}	Deletar tarefa
🧪 Como rodar o projeto localmente

    Clone o repositório:

git clone https://github.com/seu-usuario/seu-repo.git

    Acesse a pasta do projeto:

cd seu-repo

    Rode o projeto no IDE de sua preferência (Eclipse, IntelliJ, VS Code).

    Acesse:

        API: http://localhost:8080/api/tasks

        (Se tiver Swagger) Documentação Swagger: http://localhost:8080/swagger-ui.html

🎯 Melhorias futuras

    Implementar autenticação e autorização (JWT)

    Adicionar testes unitários e de integração

    Deploy em nuvem (Render, Railway, etc.)

⚡ Obs.: Se quiser, também posso te gerar um README com badges (build passing, license, spring boot version, etc.) pra ficar ainda mais profissional! 🎖️

Quer que eu mande uma versão com badges também? 🚀
