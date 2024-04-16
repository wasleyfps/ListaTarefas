<template>
  <h1>Lista de Tarefas</h1>
  <TodoList/>
  <footer>
    <p>Projeto desenvolvido por <a href="https://www.wasley.com.br/">Wasley Carvalho</a>  ❤️☕</p>
  </footer>
</template>

<script>

import TodoList from './components/TodoList.vue'

export default {
  name: 'App',
  components: {
    TodoList
  }
}
</script>

<style>
* {
  font-family: Helvetica, sans-serif;
}

h1 {
  text-align: center;
  color: #333;
}

footer {
  position: fixed;
  bottom: 0;
  left: 0;
  width: 100%;
  padding: 10px;
  background-color: #f5f5f5;
  text-align: center;
  border-top: 1px solid #ccc;
  color: #333;
}
a {
  color: #30134b;
  text-decoration: none;
}
</style>
