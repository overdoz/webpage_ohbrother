<template>
  <div id="app">
    <router-view/>
    <div class="nav">

    <Navigation/>
    </div>
  </div>
</template>

<script>
import Navigation from './components/Navigation.vue';


export default {
  name: 'app',
  components: {
    Navigation,
  },
};
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
#nav {
  padding: 30px;
}

#nav a {
  font-weight: bold;
  color: #2c3e50;
}

#nav a.router-link-exact-active {
  color: #42b983;
}
.nav {
  z-index: 100;
}
</style>
