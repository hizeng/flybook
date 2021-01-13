<template>
  <div id="app">
    <!-- <img alt="Vue logo" src="./assets/logo.png"> -->
    <!-- <HelloWorld msg="Welcome to Your Vue.js App"/> -->
    <LayoutComponent/>
  </div>
</template>

<script>
// import HelloWorld from './components/HelloWorld.vue'
import LayoutComponent from'./components/LayoutComponent.vue'

export default {
  name: 'App',
  components: {
    // HelloWorld
    LayoutComponent
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
  width: 100%;
  height: 100%;
}
*{
  height: 100%;
  width:100%;
  box-sizing: border-box;

}
body html{
  height: 100%;
  width:100%;

}
body{
  margin:0;
  padding:0;
}
img{
  vertical-align: middle;
}
</style>
