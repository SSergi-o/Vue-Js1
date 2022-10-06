<template>
  <link rel="stylesheet" href="./src/style.css" />
  <div id="app">
    <h1>Tecnologias web</h1>
    <img
      alt="Vue logo"
      src="https://images.unsplash.com/photo-1571171637578-41bc2dd41cd2?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=1470&q=80"
      style="width: 512px"
    />

    <HelloWorld msg="" />
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue';

export default {
  name: 'App',
  components: {
    HelloWorld,
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
