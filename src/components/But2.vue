<template>
  <section class="section is-medium bg-img">
    <h1 class="title has-text-centered"><span>NOTRE BUT ?</span></h1>
    <h2 class="subtitle">Créer et animer des formations pour améliorer et transformer vos pratiques en entreprise.</h2>
    <div class="columns">
      <div class="column ">
        <div class="card-content">
          <div class="media">
            <div class="media-left">
              <figure class="image ">
<!--      img des différents but          -->
                <img class="picto is-rounded" src="../assets/newImg/ecoute.webp" alt="Placeholder image">
              </figure>
            </div>
            <div class="media-content text-start ">
              <!--        txt à la suite des img       -->
              <p class="subtitle is-4">ECOUTE ET ANALYSE
                EN FONCTION DE VOTRE PROFIL</p>
            </div>
          </div>
        </div>
      </div>
      <div class="column">
        <div class="card-content">
          <div class="media">
            <div class="media-left">
              <figure class="image ">
                <img class="picto is-rounded" src="../assets/newImg/mesure.webp" alt="Placeholder image">
              </figure>
            </div>
            <div class="media-content text-start">
              <p class="subtitle is-4 ">ADAPTATION
                FORMATIONS SUR MESURE</p>
            </div>
          </div>
        </div>
      </div>
    </div>
    <div class="columns">
      <div class="column">
        <div class="card-content">
          <div class="media">
            <div class="media-left">
              <figure class="image ">
                <img class="picto is-rounded" src="../assets/newImg/professionnel.webp" alt="Placeholder image">
              </figure>
            </div>
            <div class="media-content text-start">
              <p class="subtitle is-4">PROFESSIONNELS
                DU METIERS</p>
            </div>
          </div>
        </div>
      </div>
      <div class="column">
        <div class="card-content">
          <div class="media">
            <div class="media-left">
              <figure class="image is-rounded">
                <img class="picto is-rounded" src="../assets/newImg/pratiques.webp" alt="Placeholder image">
              </figure>
            </div>
            <div class="media-content text-start">
              <p class="subtitle is-4">CAS PRATIQUES ET
                RETOURS D'EXPERIENCE</p>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: "But2"
}
</script>

<style scoped>

.section{
  padding: 4rem;
}

.media {
  display: flex;
  justify-content: space-between;
  align-items: center;
}

.title{
  font-family: ChampagnelimousineBold;
  margin-bottom: 5rem;
}
.subtitle {
  font-family: ChampagnelimousineBold;
  font-size: 1.5rem;
}

img {
  border: #066382 solid 2px;
  border-radius: 50%;
  overflow: hidden;
  width: 5rem;
  height: inherit;
  border-radius: inherit;
  object-fit: cover;
  object-position:center;
}

.has-background{
  background: rgb(0,0,0);
}

.bg-img {
  background-image: url(../assets/background-assets/back.jpg) ;
  background-position: center center;
  background-repeat:  no-repeat;
  background-attachment: fixed;
  background-size:  cover;
}
</style>