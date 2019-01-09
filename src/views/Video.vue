<template>
  <div class="about">
    <iframe class="video" src="https://www.youtube.com/embed/S8khElA9xCw" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
  </div>
</template>

<script>
export default {
  name: 'videoPage',
  components: {
    
  }
}
</script>

<style scoped>
  .video {
    width: 99vw;
    height: 99vh;
  }
  .about {
    background-color: black;
    width: 100vw;
    height: 100vh;
  }
</style>