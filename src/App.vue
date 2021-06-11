<template>
  <div>
    <div id="header"></div>
    <div id="main-container">
      <h1>Todos</h1>
    </div>
  </div>
</template>

<script>
import Search from "./components/search.vue";
import Todo from "./components/todo";
import todoAdd from "./components/todoAdd.vue";

export default {
  name: "App",
  components: {
    Search,
    Todo
  },
};
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
