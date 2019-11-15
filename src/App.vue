<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png" />
    <Task :task="task" />
  </div>
</template>

<script>
import Task from "./components/Task.vue";

export default {
  name: "app",
  components: {
    Task
  },
  data: () => ({
    task: {
      title: "i am title",
      id: 222
    }
  })
};
</script>

<style>
@import './index.css';

#app {
  font-family: "Avenir", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
