let todos = [];

function addTodo(todo) {
  todos.push(todo);
}

function removeTodo(index) {
  todos.splice(index, 1);
}

function displayTodos() {
  todos.forEach((todo, index) => {
    console.log(`${index + 1}. ${todo}`);
  });
}

addTodo('Buy groceries');
addTodo('Do laundry');
addTodo('Walk the dog');

displayTodos();

removeTodo(1);

displayTodos();
