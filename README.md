# Gerenciador-de-tarefas

#Domínio do Problema (Escopo)

O projeto será uma aplicação web simples para o gerenciamento de tarefas pessoais. O sistema permitirá que usuários criem, editem, visualizem e excluam tarefas (CRUD) e contará com um sistema de autenticação via login/token para controle de acesso. A transação implementada no sistema será a marcação de uma tarefa como concluída.

#A aplicação terá as seguintes funcionalidades principais:

    Cadastro de Usuário e Login (com autenticação JWT)

    Gerenciamento de Tarefas (CRUD: criar, listar, atualizar e excluir)

    Marcar Tarefa como Concluída (Transação)

#Transação Abordada

A transação implementada no sistema será a marcação de uma tarefa como concluída.

    Quando um usuário marca uma tarefa como concluída, o sistema deve:

    Verificar se a tarefa existe e pertence ao usuário autenticado.

    Atualizar o status da tarefa para "concluído" (completed: true).

    Registrar a data e hora da conclusão (completed_at: timestamp).

    Garantir que a operação seja concluída (se algo falhar, a atualização não deve ser aplicada parcialmente).

#Principais Tecnologias Utilizadas

  Back-end

    Node.js + Express.js (Framework para API REST)

    Sequelize (ORM para banco de dados SQL) - talvez outra alternativa

    JWT (JSON Web Token) (Autenticação)

    PostgreSQL (Banco de dados)

  Front-end

    React.js (Framework para a interface)

    Tailwind CSS (Estilização simples e rápida)




