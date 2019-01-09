<template>
  <div class="container">
    <div
      v-for="(date, index) in dates"
      :key="index"
      class="post">
        <div class="when">{{date.when}}</div>
        <div class="city">{{date.city}}</div>
        <div class="where">{{date.where}}</div>
        <div class="maps">{{date.maps}}</div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Tour',
  props: {

  },
  data() {
    return {
      dates: [
        { when: 'JAN 25', city: 'BERLIN, GER', where: 'FUNKHAUS', maps: 'GET DIRECTION' },
        { when: 'JAN 25', city: 'BERLIN, GER', where: 'FUNKHAUS', maps: 'GET DIRECTION' },
        { when: 'JAN 25', city: 'BERLIN, GER', where: 'FUNKHAUS', maps: 'GET DIRECTION' },
        { when: 'JAN 25', city: 'BERLIN, GER', where: 'FUNKHAUS', maps: 'GET DIRECTION' },
        { when: 'JAN 25', city: 'BERLIN, GER', where: 'FUNKHAUS', maps: 'GET DIRECTION' },
      ],
    };
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
  @import url(https://fonts.googleapis.com/css?family=VT323); 

  .container {
    width: 60vw;
    position: absolute;
    color: #FCFF2A;
  }
  .post {
    display: flex;
    margin-bottom: 1em;
    font-size: 1.5vw;
    font-family: 'VT323', monospace;
    letter-spacing: 0.17em;
  }
  .when {
    width: 15%
  }
  .city {
    width: 30%
  }
  .where {
    width: 30%
  }
  .maps {
    width: 25%;
    cursor: pointer;
  }
</style>
