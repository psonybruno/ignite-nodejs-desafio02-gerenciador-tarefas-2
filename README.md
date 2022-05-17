# [NODEJS] Desafio 02: Gerenciador de Tarefas (2)

### Requisitos
- [x] Should be able to create a new user;
- [x] Should be able to list all user's todos;
- [x] Should be able to create a new todo;
- [x] Should be able to update a todo;
- [x] Should be able to mark a todo as done;
- [x] Should be able to delete a todo;
- [x] Should be able to find user by username in header and pass it to request.user;
- [x] Should be able to let user create a new todo when is in free plan and have less than ten todos;
- [x] Should be able to let user create infinite new todos when is in Pro plan;
- [x] Should be able to put user and todo in request when both exits;
- [x] Should be able to find user by id route param and pass it to request.user;

### Regras de negócio
- [x] Should not be able to create a new user when username already exists;
- [x] Should not be able to update a non existing todo;
- [x] Should not be able to mark a non existing todo as done;
- [x] Should not be able to delete a non existing todo;
- [x] Should not be able to find a non existing user by username in header;
- [x] Should not be able to let user create a new todo when is not Pro and already have ten todos;
- [x] Should not be able to put user and todo in request when user does not exists;
- [x] Should not be able to put user and todo in request when todo id is not uuid;
- [x] Should not be able to put user and todo in request when todo does not exists;
- [x] Should not be able to pass user to request.user when it does not exists;