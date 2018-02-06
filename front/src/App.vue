<template>
  <div id="app">
    <navbar> </navbar>
    <register> </register>

  </div>
</template>

<script>
  import Navbar from './components/Navbar.vue'
  import Register from './components/authentication/Register.vue'
export default {
    components: {
      'navbar': Navbar,
      'register': Register,
    }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}
</style>
