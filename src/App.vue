<template>
  <div id="app">
    {{ message }}
    <HelloWorld msg="Welcome to Your Vue.js App"/>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'

export default {
  data() {
    return {
      message: "Hello World1",
    };
  },
  name:'App',
  components:{
    HelloWorld
  }

};
</script>

<style>
#app {
  font-size: 18px;
  font-family: "Roboto", sans-serif;
  color: blue;
}
</style>