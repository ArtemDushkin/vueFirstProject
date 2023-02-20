<template>
<div id="app">
  <h1>WishList</h1>
  <hr>
  <li> {{ todos[0] }} </li>
  <li> {{ todos[1] }} </li>
  <input type='text' v-model='name'>




</div>
</template>

<script>
import TodoList from './components/todoList.vue';

export default {
  name: 'App',
  data() {
    return {
      todos: [
        'Rest near the Ocean',
        'Gravel bike']
    }

  },
  components: {
    TodoList,
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
