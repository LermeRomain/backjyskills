<template>
  <nav class="navbar" role="navigation" aria-label="main navigation">
    <div class="navbar-brand">
      <a class="navbar-item" href="/">
<!--  logo bakjy dans la navbar      -->
        <img src="../assets/newImg/SymboleBlanc.webp" alt="logo groupe bakjy">
      </a>

      <a role="button" class="navbar-burger is-right" aria-label="menu" aria-expanded="false" data-target="navbarBasicExample">
        <span aria-hidden="true"></span>
        <span aria-hidden="true"></span>
        <span aria-hidden="true"></span>
      </a>
    </div>

    <div id="navbarBasicExample" class="navbar-menu">
      <div class="navbar-end is-hidden-mobile">
        <a class="title text-center" href="/">
          <!--  Titre du site dans la navbar      -->
          BAKJY <span>SKILLS</span>
        </a>
      </div>

      <div class="navbar-end">
        <div class="navbar-item">
          <div class="buttons">
            <a class="button is-primary" href="#form">
              <!--  icone telephone et nous contacter btn de la navbar      -->
              <strong class="fas fa-phone" />
              <strong>Nous contacter</strong>
            </a>
          </div>
        </div>
      </div>
    </div>
  </nav>
</template>

<script>
export default {
  name: "NavBar"
}
document.addEventListener('DOMContentLoaded', () => {

  // Get all "navbar-burger" elements
  const $navbarBurgers = Array.prototype.slice.call(document.querySelectorAll('.navbar-burger'), 0);

  // Add a click event on each of them
  $navbarBurgers.forEach( el => {
    el.addEventListener('click', () => {

      // Get the target from the "data-target" attribute
      const target = el.dataset.target;
      const $target = document.getElementById(target);

      // Toggle the "is-active" class on both the "navbar-burger" and the "navbar-menu"
      el.classList.toggle('is-active');
      $target.classList.toggle('is-active');

    });
  });

});

</script>

<style scoped>

.navbar {
  background-color: white;
  padding: 1.5rem;
}

h1{
  color: #066382;
}
.content{
  margin: 1rem 0 0 0;
}
.button{
  background-color: white;
  color: #066382;
  border: solid 2px #066382;
}

.button:hover{
  background-color: white;
  color: #066382;
  border: solid 2px #066382;
}

.navbar-burger{
  color: #066382;
  background-color: #066382;
}

.navbar-menu{
  background-color: white;
  box-shadow: none;
}

.title{
  color: #066382;
  font-family: ChampagnelimousineBold;
}

.title:hover{
  transform: scale(1.2);
  transition-duration: 0.5s;
}

span{
  font-family: Champagnelimousine;
}

.fas{
  margin-right: 1rem;
}

</style>