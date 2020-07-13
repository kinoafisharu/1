<template>
  <div id="app">
    <img width="25%" src="./assets/logo.png">
    <HelloWorld msg="Вас приветствует среда для разработки vue компонентов"/>
  </div>
</template>

<script>
import HelloWorld from "./components/HelloWorld";

export default {
  name: "App",
  components: {
    HelloWorld
  }
};
</script>

<style>
#app {
  background: #000;
  font-family: "Avenir", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #fff;
  height: 100vh;
  padding: 100px;
}
</style>
