<template>
  <Navbar/>
  <router-view/>
  <Footer/>
</template>



<script>
import Navbar from './components/Navbar.vue'
import Footer from './components/Footer.vue';

export default {
  components: {
    Navbar,
   Footer
  }
}
</script>

<style scope>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  overflow-x: hidden;
  text-align: center;
  margin-top: 130px;
}

nav {
  padding: 30px;
}

nav a {
  font-weight: bold;
  color: #2c3e50;
}

nav a.router-link-exact-active {
  color: #42b983;
}
</style>
