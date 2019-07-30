<template>
  <div id="home">
    <div id="container">
      <div class="nav-item">
        <a class="nav-button" v-on:click="aboutMe()">About me</a>
      </div>

      <div class="nav-item">
        <a class="nav-button" v-on:click="projects()">Projects</a>
      </div>
      <div class="nav-item">
        <a class="nav-button" href="/static/PatrickDowlingResume.pdf">Resume</a>
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style lang="scss" scoped>
@media only screen and (min-width: 840px) {
  #container {
    flex-direction: row;
  }
}
@media only screen and (max-width: 840px) {
  #container {
    flex-direction: column;
  }
}
.nav-button {
  padding: 2vh;
  cursor: pointer;
  text-decoration: none;
  font-family: Arial, Helvetica, sans-serif;
  font-size: 50px;
  color: white;
}

#container {
  display: flex;
  grid-gap: 10px;
  padding: 2vh;
}

.nav-button:hover {
  color: white;
}

#home {
  background-color: black;
  opacity: 0.8;
  display: inline-block;
  border-radius: 30px;
}
</style>