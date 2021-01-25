<template>
  <div id="app">
<Header />
<About />
<Services/>

<Client/>
<Portofolio/>
<MediaPartner/>
<Contact />
<Footer />
  </div>
</template>


<script>
import Header from './components/Header.vue'
import About from "./components/section/About.vue"
import Client from "./components/section/Client.vue"
import MediaPartner from "./components/section/MediaPartner.vue"
import Services from "./components/section/Services.vue"
import Contact from "./components/section/Contact.vue"
import Portofolio from './components/section/Portofolio.vue'
import Footer from './components/Footer.vue'

export default {
  name: 'App',
  components: {
    Header, About, Client, MediaPartner, Services, Contact,
    Portofolio, Footer
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
}
</style>
