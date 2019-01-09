<template>
  <nav class="Navigation" id="menu">
    <h1 id="logo" class="topCenter">Oh Brother</h1>
    <router-link class="topLeft" to="/">Tour</router-link>
    <a class="topRight">Shop</a>
    <router-link class="bottomLeft" to="/music">Music</router-link>
    <router-link class="bottomRight" to="/video">Video</router-link>
    <a class="bottomCenter">Contact</a>
  </nav>
</template>

<script>
export default {
  name: "Navigation",
  props: {}
};

/* eslint-disable */
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
@import url(https://fonts.googleapis.com/css?family=Open+Sans:400,800,700,300);
@import url(https://fonts.googleapis.com/css?family=Squada+One);
@import url(https://fonts.googleapis.com/css?family=Playfair+Display);

a {
  position: fixed;
  font-weight: bold;
  font-size: 1.2vw;
  font-family: "Playfair Display", serif;
  letter-spacing: 0.17em;
  text-transform: uppercase;
  color: white;
  cursor: pointer;
  text-decoration: none;
  text-shadow: 2px 2px #0DFF82;
}
.Navigation {
  display: flex;
  justify-content: center;
  z-index: 10;
}
.topLeft {
  top: 1.5vw;
  left: 1.5vw;
}
.topRight {
  top: 1.5vw;
  right: 1.5vw;
}
.bottomLeft {
  bottom: 1.5vw;
  left: 1.5vw;
}
.bottomRight {
  bottom: 1.5vw;
  right: 1.5vw;
}
.topCenter {
  top: 1.2vw;
  font-size: 2.5vw;
  text-transform: uppercase;
  letter-spacing: 0.17em;
  position: fixed;
  cursor: pointer;
  margin: 0;
}
.bottomCenter {
  bottom: 1.5em;
}

#logo {
  font-family: "Open Sans", sans-serif;
  background: -webkit-linear-gradient(#0CBAE8, #0DFF82);
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
  text-decoration: none;
  font-weight: 800;
  letter-spacing: 13px;
  line-height: 1;
  z-index: 6;
  /* text-shadow: #ededed 3px 2px 0; */
}
#logo:after {
  content: "OH BROTHER";
  position: relative;
  left: 6px;
  top: -2.5vw;
}
#logo:after {
  /*background: url(https://subtlepatterns.com/patterns/crossed_stripes.png) repeat;*/
  background-image: -webkit-linear-gradient(
    left top,
    transparent 0%,
    transparent 25%,
    #555 25%,
    #555 50%,
    transparent 50%,
    transparent 75%,
    #555 75%
  );
  background-size: 6px 6px;
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
  z-index: -5;
  display: block;
  text-shadow: none;
}
</style>


