<template>
  <div class="home">
    <div class="background"/>
    <Tour/>
  </div>
</template>

<script>
// @ is an alias to /src
import Tour from '@/components/Tour.vue'

export default {
  name: 'home',
  components: {
    Tour
  }
}
</script>

<style scoped>
  .home {
    font-family: 'Avenir', Helvetica, Arial, sans-serif;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    text-align: center;
    color: #000000;
    font-weight: bold;
    display: flex;
    justify-content: center;
    align-items: center;
    background-color: #000;
    height: 100vh;
    width: 100vw;
    padding: 0;
    margin: 0;
  }
  .background {
    background-image: url(https://media.giphy.com/media/3otPoxcPHdFHZcl3Gg/giphy.gif);
    background-size: cover;
    -webkit-filter: grayscale(100%); /* Safari 6.0 - 9.0 */
    filter: grayscale(100%);
    opacity: 0.5;
    height: 100vh;
    width: 100vw;
  }
</style>
