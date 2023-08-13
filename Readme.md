<h1>Projeto de selecao</h1>
Este teste consiste em implementar uma aplicação básica de gerenciamento de tarefas (to-do list) com as seguintes funcionalidades:
Cadastro de tarefas:
Um usuário pode adicionar uma nova tarefa à lista, fornecendo um título e uma descrição para a mesma.
Listagem de tarefas:
O sistema deve exibir todas as tarefas cadastradas, mostrando o título e a descrição de cada uma.
Marcar tarefa como concluída:
O usuário pode marcar uma tarefa como concluída. Uma tarefa concluída não deve mais aparecer na lista de tarefas.
Remover tarefa:
O usuário pode remover uma tarefa da lista.
Aqui estão as etapas para realizar o teste prático:
Seu projeto deve:
1. Fazer uso da linguagem Java
2. Oferecer uma interface Web
3. Implementar um back end com interface de acesso (REST)
4. Parte dos dados devem ser armazenados em uma bando de dados relacional (PostgreSQL) e outra em um modelo NoSQL (MongoDB)
5. É preciso prover um diagrama de classes a nível de análise 
6. Os testes devem ser implementados em um framework de testes
Este teste prático abrange vários aspectos importantes do desenvolvimento de aplicativos web com Java, REST, PostgreSQL e desenvolvimento web. Ele avalia a capacidade do candidato de configurar o ambiente de desenvolvimento, criar uma estrutura básica de projeto, implementar rotas REST, interagir com um banco de dados e desenvolver uma interface web funcional.
Apresentar o link do código no github e o link não listado do YouTube com o uso do sistema desenvolvido no prazo de 02/08/2023!

<h2>Comentarios Relevantes</h2>
<p>Eu utilizei estes testes como um aprendizado também, por isso conta com um cadastro simples de usuarios, sem a opção de apagar usuarios, enquanto o das tarefas é mais completo, e me dei a liberdade de permite que uma tarefa seja atribuida a mais de um usuario</p>
<p>O dados que sao salvos no MongoDb sao de tarefas concluidas de um usuario, apesar de ainda nao apagar eles do postgres, seria ideal para aplicacao real</p>
<p>O foco da interface web é principalmente ser funcional e evitar recarregamentos, no uso faltam alguns aspectos como indicação de campos requiridos</p>