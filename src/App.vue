<template>
  <div id="app">
    <section id="hero1" class="hero is-large image is-fullwidth" >
      <div class="hero-body">
        <div class="level">
          <div class="level-item has-text-left">
            <figure class="image is-fullwidth is-4x3 ">
              <img class="pins" src="../public/bppinslogo.png" alt="baking power pins logo">
            </figure>
          </div>
          <div class="level-item">
            <img class="name" src="../public/bakingpowerlogo.png" alt="baking power logo">
            <h1 class="has-text-right">I'm Nikki Petersen and I've got Baking Power!</h1>
          </div>
        </div>
      </div>
    </section>

    <section id="hero2" class="hero is-info is-large" >
      <div class="hero-body">
        <div class="container">
          <h1 class="title"> Hero #2</h1>
        </div>
      </div>
    </section>

    <section id="hero3" class="hero is-large" >
      <div class="hero-body">
        <div class="container">
          <h1 class="title"> Hero #3</h1>
        </div>
      </div>
    </section>

    <section id="hero4" class="hero is-large" >
      <div class="hero-body">
        <div class="container">
          <h1 class="title"> Hero #4</h1>
        </div>
      </div>
    </section>

  </div>
</template>

<script>
export default {
  name: 'App'
}
</script>

<style lang="scss">
#app {

  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #FFFFFF;
}

#hero1 {
  background-image: url("../public/bread.jpg");
  background-position: center center;
  background-repeat: no-repeat;
  background-attachment: fixed;
  background-size: cover;
  height: 25%;
}

#hero2 {
  background-size: cover;
  height: 25%;
}

#hero3 {
  background-size: cover;
  height: 25%;
}

#hero4 {
  background-image: url("../public/candy.jpg");
  background-position: center center;
  background-repeat: no-repeat;
  background-attachment: fixed;
  height: 25%;
}

  .pins {
    width: 150px;
  }

  .name {
    width: 350px;
  }
</style>
