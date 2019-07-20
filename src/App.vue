<template>

  <div id="app">

    <Footer></Footer>

  </div>
</template>

<script>
/*import Home from './components/home.vue'*/
import Footer from './components/footer.vue'

export default {
  name: 'app',
  data() {
    return {
    }
  },
  components: {
    Footer
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
</style>
