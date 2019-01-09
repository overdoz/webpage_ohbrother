<template>
  <div class="music">
    <div class="background"/>
   <iframe src="https://open.spotify.com/embed/track/6q6zoFtAGdZywlSvXvOpf7" class="track" frameborder="0" allowtransparency="true" allow="encrypted-media"></iframe>
   <iframe src="https://open.spotify.com/embed/track/6xZWWhS0C5pWGmqJRo5ra4" class="track" frameborder="0" allowtransparency="true" allow="encrypted-media"></iframe>
   <iframe src="https://open.spotify.com/embed/track/0ww2LfzXTpO94ebJhXvZTu" class="track" frameborder="0" allowtransparency="true" allow="encrypted-media"></iframe>
  </div>
</template>

<script>
export default {
  name: 'musicPage',
  components: {
    
  }
}
</script>

<style scoped>
  .track {
    width: 14vw;
    height: 30vh;
    margin: 5vw;
    z-index: 10;
    box-shadow:20px 20px 50px rgb(56, 56, 56); 
  }
  .music {
    
    width: 100vw;
    height: 100vh;
    display: flex;
    justify-content: center;
    align-items: center;
    background-color: antiquewhite;
  }
  .background {
    background-image: url(https://sonne-wolken.de/wp-content/uploads/2014/01/Berlin-Streetart-1-1170x732.jpg);
    background-size: cover;
    -webkit-filter: grayscale(100%); /* Safari 6.0 - 9.0 */
    filter: grayscale(100%);
    width: 100vw;
    height: 100vh;
    position: absolute;
    opacity: 0.5;
  }
</style>