<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Todo App</title>
  <link rel="stylesheet" href="css/style.css/todoapp.css">
</head>
<body>

  <div class="container">
    <h2>Todo List</h2>

    <div class="input-section">
      <input id="taskInput" type="text" placeholder="Add your task">
      <button onclick="addTask()">Add</button>
    </div>

    <ul id="taskList"></ul>
  </div>

  <script src="js/script.js/todoapp.js"></script>
</body>
</html>
