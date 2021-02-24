<template>
  <div id="app" class="container">
    <TodoInput/>
    <TodoList/>
  </div>
</template>

<script>
import TodoInput from './components/TodoInput';
import TodoList from './components/TodoList';

export default {
  name: 'App',
  components:{
    TodoInput,
    TodoList
  }
}
</script>

<style>

</style>
