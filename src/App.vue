<template>

  <div id="app">

      <div id="page-wrapper">

        <div id="gap">
        </div>

        <div id="home-wrapper">
          <Home></Home> 
        </div>
      </div>

      <div id="footer-wrapper">
        <Footer></Footer>
      </div>

  </div>
</template>

<script>
import Home from './components/home.vue'
import Footer from './components/footer.vue'

export default {
  name: 'app',
  components: {
    Footer,
    Home
  }
}
</script>

<style>

html, body {
  height: 100%;
  padding: 0%;
  margin: 0%;
}

body { 
  background-position: center center;
  background-repeat:  no-repeat;
  background-attachment: fixed;
  background-size:  cover;
  background-image: url('/images/portfolio-background.jpg');
}

#page-wrapper{
  min-height: calc(100vh - 150px);
  text-align: center;
}

#footer-wrapper {
  text-align: center;
}

#gap {
  min-height: calc(46vh - 50px);
}

</style>
