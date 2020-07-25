<template>
  <div id="app">
    <section id="hero1" class="hero is-medium is-fullwidth" >
      <div class="hero-head">
        <nav class="navbar">
          <div class="container">
            <div class="navbar-brand">
              <span class="navbar-burger burger" data-target="navbarMenuHeroA">
                <span></span>
                <span></span>
                <span></span>
              </span>
            </div>
              <div id="navbarMenuHeroA" class="navbar-menu">
                <div class="navbar-end">
                  <a class="navbar-item">
                    Home
                  </a>
                  <a class="navbar-item">
                    Examples
                  </a>
                  <a class="navbar-item">
                    Documentation
                  </a>
                </div>
              </div>
          </div>
        </nav>
      </div>
      <div class="hero-body">
        <div class="container">
          <img id="pins" class="is-vcentered" src="../public/bppinslogo.png" alt="baking power pins logo" width="200">
          <img id="name" src="../public/bakingpowerlogo.png" alt="baking power logo">
          <h1 class="title hero1-title">I'm Nikki Petersen and I've got Baking Power!</h1>
            <p class="hero1-p is-size-2">This is a website for my bakery, where I make cakes and bread and cupcakes and cookies and so many
            other yummy things. I like to bake sweet things but also have enjoyed making bread since we've all been
            in lock down during the Covid pandemic.</p>
        </div>
      </div>
    </section>

    <section id="hero2" class="hero is-medium" >
      <div class="hero-body">
        <div class="container">
          <div class="columns is-vcentered">
            <div class="column is-pulled-left">
              <img src="../public/food2.jpg" alt="cookies and milk" width="350">
            </div>
            <div class="column is-pulled-right">
              <h1 class="title">This is where I talk about making cookies. </h1>
              <p class="subtitle has-text-left">Aren't cookies the best? They can be chewy and crisp (if you're good at making them),
                and sweet but not too sweet. Cookie lorem ipsum dolor sit amet lollipop gummies. Croissant powder caramels cake soufflé.
                Gingerbread bear claw ice cream fruitcake biscuit sugar plum. Tootsie roll bear claw jelly cotton candy.
                Wafer apple pie gummi bears cupcake fruitcake wafer chocolate bar gummies.
                Gummies marshmallow ice cream ice cream chocolate cake cupcake.</p>
            </div>
          </div>
        </div>
      </div>
    </section>

    <section id="hero3" class="hero is-medium" >
      <div class="hero-body">
        <div class="container">
          <div class="columns is-vcentered">
            <div class="column is-pulled-left">
              <h1 class="title">This is where I talk about making cake. </h1>
              <p class="subtitle has-text-left">Actually, cake might be the best. It is moist and crumbly at the same time, sweet and
                smooth and creamy. Bonbon pudding muffin candy oat cake marzipan chocolate cake. Carrot cake apple pie
                cheesecake fruitcake tootsie roll lollipop. Cookie tiramisu muffin apple pie fruitcake chocolate cake.
                Macaroon marshmallow jelly beans oat cake apple pie cheesecake. Lemon drops tootsie roll liquorice jujubes sugar plum. </p>
            </div>
            <div class="column is-pulled-right">
              <img src="../public/cake.jpg" alt="cake" width="350">
            </div>
          </div>

        </div>
      </div>
    </section>

    <section id="hero4" class="hero is-large" >
      <div class="hero-body">
        <div class="container">
          <h1 class="title"> Hero #4</h1>
          <h3 class="subtitle">This contact form isn't hooked up, so you're welcome to reach out, but just
          know that I won't be getting the info. Thanks!</h3>
          <div class="columns is-vcentered"  width="500">
            <div class="column"></div>
            <div class="column is-one-third">
              <div class="field">
                <label class="label">Name</label>
                <div class="control">
                  <input class="input" type="text" placeholder="e.g Alex Smith">
                </div>
              </div>

              <div class="field">
                <label class="label">Email</label>
                <div class="control">
                  <input class="input" type="email" placeholder="e.g. alexsmith@gmail.com">
                </div>
              </div>
            </div>
            <div class="column"></div>
          </div>
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
  font-size: large;
}

#hero1 {
  background-image: url("../public/bread.jpg");
  background-position: center center;
  background-repeat: no-repeat;
  background-attachment: fixed;
  background-size: cover;
}

#hero2 {
  background-size: cover;
}

#hero3 {
  background-size: cover;
}

#hero4 {
  background-image: url("../public/food1.jpg");
  background-position: center center;
  background-repeat: no-repeat;
  background-attachment: fixed;
  background-size: cover;
}

#pins {
  margin: 40px;
}

.navbar-item,
.hero1-title {
  color: white;
}

.navbar-item img {
  max-height: 4.0rem;
}

.hero1-p {
  margin: 0 100px;
  line-height: 1.2;
}
</style>
