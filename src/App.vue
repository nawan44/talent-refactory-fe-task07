<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <HelloWorld msg="Welcome to Your Vue.js App"/>
<About />
<Services/>

<Client/>
<MediaPartner/>
  </div>
</template>


<script>
import HelloWorld from './components/HelloWorld.vue'
import About from "./components/section/About.vue"
import Client from "./components/section/Client.vue"
import MediaPartner from "./components/section/MediaPartner.vue"
import Services from "./components/section/Services.vue"


export default {
  name: 'App',
  components: {
    HelloWorld, About, Client, MediaPartner, Services
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
  margin-top: 60px;
}
</style>
