<template>
      <div id="app" class="container">
    <h1>Todo App</h1>
  <todo-list></todo-list>
    </div>
</template>

<script>
import TodoList from './components/TodoList.vue'
export default {
  name: 'app',
  components: {
   TodoList 
  } 
}
</script>


<style>
@import './assets/base.css';
*{
  box-sizing: border-box;
}

.container {
  max-width: 600px;
  margin: 0 auto;
}

#app {
  margin-top: 10px;
  font-weight: normal;
  font-size: 24px;
}

</style>
