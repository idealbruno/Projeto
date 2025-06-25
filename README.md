# Projeto
Lista de tarefas em HTML, CSS E JAVASCRIPT

<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Lista de Tarefas</title>
  <link rel="stylesheet" href="style.css" />
</head>
<body>
  <div class="container">
    <h1>📋 Lista de Tarefas</h1>
    <input id="task-input" type="text" placeholder="Digite uma tarefa..." />
    <button onclick="addTask()">Adicionar</button>
    <ul id="task-list"></ul>
  </div>
  <script src="script.js"></script>
</body>
</html>


CSS

body {
  font-family: Arial, sans-serif;
  background-color: #f4f4f4;
  display: flex;
  justify-content: center;
  padding-top: 50px;
}
.container {
  background: #e3dede;
  padding: 20px;
  border-radius: 8px;
  box-shadow: 0 0 10px rgba(0,0,0,0.1);
}
ul {
  list-style: none;
  padding: 0;
}
li {
  display: flex;
  justify-content: space-between;
  padding: 8px 0;
}
.done {
  text-decoration: line-through;
  color: gray;
}

