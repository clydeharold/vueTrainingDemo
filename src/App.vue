<template>
  <div id="app">
    <div class="wrapper">
      <sideBar/>
      <div id="content">
        <navBar/>

        <img src="./assets/logo.png" alt="">
        <router-view/>
      </div>
    </div>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld'
import sideBar from './components/sideBar'
import navBar from './components/navBar'
import pageContent from './components/pageContent'
export default {
  name: 'App',
  components: {
    HelloWorld,
    sideBar,
    navBar,
    pageContent
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>

<style src='./assets/style.css'></style>
