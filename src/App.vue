<template>
  <div>
    <div id="background">
      <Navigation /> 
      <div id="footer">
        <Footer />
      </div>
      <div id="footer2">
        <Footer2 />
      </div>
    </div>
  </div>

</template>

<script>
// import HelloWorld from './components/HelloWorld.vue'
// import Index from './Index.vue'
import Navigation from './components/Navigation.vue'
import Footer from './components/Footer.vue'
import Footer2 from './components/Footer2.vue'

export default {
  name: 'App',
  components: {
    // HelloWorld
    // Index
    Navigation,
    Footer,
    Footer2
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

#background{
  height: 1000px;
  z-index: 0;
  background-image: url("../src/assets/shib.jpg");
  
  position: relative;
}

#footer {
  bottom: 60px;
  position: absolute;
  width: 70%;
  margin-left: 15%;
}

#footer2 {
  bottom: 0px;
  position: absolute;
  width: 100%;
}
</style>
