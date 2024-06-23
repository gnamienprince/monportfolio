<script setup>
import BoiteDomaine from '../components/BoiteDomaine.vue'
import ProjetComponent from '../components/ProjetComponent.vue'

// les informations pour les modules

</script>

<template>
  <div class="container is-mobile is-centered">
     <div class="is-primary has-text-primary is-family-secondary is-half is-size-2 is-size-2-mobile has-text-centered is-mobile">
        Infographe, Développeur Web et mobile
     </div>
  </div>
  <div class="columns is-centered">
     <div class="column is-6 has-text-centered is-size-4 is-mobile">
        je conçois de belles créas, code de belles choses de manière simple et attrayant
     </div>
  </div>
  <div class="columns is-centered is-mobile">
    <div class="mt-6">
      <img src="../assets/images/photo.png" alt="" width="220">
    </div>
  </div>

  <div class="is-background-primary mt-6 p-6">
      <div class="has-text-centered has-text-white is-size-2 is-half is-family-secondary is-centered">
        Salut, je m’appelle Gnamien prince, ravi de vous rencontrer
      </div>
      <div class="column is-three-fifths is-offset-one-fifth is-size-5 has-text-dark is-centered has-text-centered">
        Je travail en tant que freelance dans le domaine du design et du developpement informatique depuis plus de 2 ans avec plusieurs entreprises qui solicite mes services, elles ont toujours été satisfaites par mon determinisme et mon professionnalisme
      </div>
  </div>

  <div class="container">
    <div class="columns">
      <div class="column">
        <BoiteDomaine/>
      </div>
       <div class="column">
        <BoiteDomaine />
      </div>
       <div class="column">
        <BoiteDomaine />
      </div>
       <div class="column">
        <BoiteDomaine />
      </div>
    </div>

    <div class="is-primary has-text-primary is-size-3 has-text-centered">
      Mes Travaux
    </div>

    <div class="columns">
      <div class="column">
        <ProjetComponent />
      </div>
    </div>
  </div>
  
  
</template>
