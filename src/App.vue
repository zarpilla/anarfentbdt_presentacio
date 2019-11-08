<template>
  <div id="app">
    <HelloWorld msg="Anar Fent"/>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'app',
  components: {
    HelloWorld
  }
}
</script>

<style>
@font-face {
    font-family: 'Pine Forest Personal Use';
    src: url('./assets/PineForestPersonalUse.woff2') format('woff2'),
        url('./assets/PineForestPersonalUse.woff') format('woff');
    font-weight: normal;
    font-style: normal;
}
body{
  margin: 0;
  padding: 0;
}
#app {
  font-family: 'Pine Forest Personal Use', 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}



</style>
