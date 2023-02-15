
# To do list

Lista de tarefas desenvolvida com Spring, realizado operação de adição de tarefas, atualização e exclusão. 
Foi utilizando banco de dados H2 que roda em tempo de execução.




## Documentação da API

#Cadastrar novas trarefas pelo método POST 

Endereço requisição http://localhost:8080/api/v1/tasks

   {
        "title": "Tarefa 4  - Deletando",
        "description": "Delete task 4",
        "deadLine": "2023-02-12T01:14:51"
    }

--------------------------------------------------


#### Retorna lista de todas tarefas com método GET
http://localhost:8080/api/v1/tasks


--------------------------------------------------


#### Retorna um item pelo id com método GET
#Exemplo http://localhost:8080/api/v1/tasks/{id}

http://localhost:8080/api/v1/tasks/3


--------------------------------------------------

# Atualiza lista de tarefas com método PUT
#Exemplo http://localhost:8080/api/v1/tasks/{id}

http://localhost:8080/api/v1/tasks/1


--------------------------------------------------

# Deleta tarefa passando o id com método DELETE
#Exemplo http://localhost:8080/api/v1/tasks/{id}

http://localhost:8080/api/v1/tasks/1




