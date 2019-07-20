<template>
  <div id="footer">
    <div class="container">

        <div class="column">
          <a class="thumbnail" href='mailto:patrick.dowling41@gmail.com'>
            <i class="fa fa-envelope"></i>
          </a>
        </div>

        <div class="column">
          <a class="thumbnail" href='https://www.linkedin.com/in/patrick-dowling-454ab8148'>
            <i class="fa fa-linkedin"></i>
          </a>
        </div>

        <div class="column">
          <a class="thumbnail" href='https://github.com/patrickdowling41'>
            <i class="fa fa-github"></i>
          </a>
        </div>
    </div>
  </div>
  
</template>

<script>
export default {

}
</script>

<style lang="css" scoped>

#footer {
  background-color: black;
  opacity: 0.6;
  display: inline-block;
  border-radius: 30px;
}

i {
  margin: 25px;
}

.container {
  display: inline-block;
}

.thumbnail{
  font-size:50px;
  color:white;
}

.column {
  display: inline;
}

</style>