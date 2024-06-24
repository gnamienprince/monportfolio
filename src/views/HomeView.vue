<script setup>
import BoiteDomaine from '../components/BoiteDomaine.vue'
import ProjetComponent from '../components/ProjetComponent.vue'

// les informations pour les modules
const information1 = {
  icon: 'icon1.svg',
  titre: 'Infographie',
  description:
    'Je suis plus dans la simplicité et dans le professionnalisme car en infographie, tout ce qui es simple est beau',
  titre2: 'chose que j’aime concevoir',
  description2: 'flyers, cartes de visite, affiche de tout genre, bagde, kakemono etc...',
  titre3: 'outils de conception',
  description3: 'Photoshop, Illustrator, In design, Première pro, Filmora, capcut, figma'
}

const information2 = {
  icon: 'icon2.svg',
  titre: 'Front end',
  description: 'je code le front end des applications avec le coeur, car elle presente la façade de votre structure en ligne',
  titre2: 'mes langages et frameworks',
  description2: 'HTML, CSS, JS, VuJS, bulma, bootrasp',
  titre3: 'outils de conception',
  description3: 'VS code, github'
}

const information3 = {
  icon: 'icon3.svg',
  titre: 'Back end',
  description: 'Qui dit back end dit logique et cela me connais. vous aurez un back bien structuré et dans les moindres détail',
  titre2: 'mes langages et frameworks',
  description2: 'PHP, MySQL, Laravel',
  titre3: 'outils de conception',
  description3: 'Mamp, laragon'
}

const information4 = {
  icon: 'icon4.svg',
  titre: 'Mobile ui/ux',
  description: 'coder et rendre les applications mobiles faciles à utiliser à travers une ergonomie conviviale',
  titre2: 'mes langages et frameworks',
  description2: 'dart, java, flutter',
  titre3: 'outils de conception',
  description3: 'android studio, VS code'
}
</script>

<template>
  <div class="block mt-6">
    <div class="container is-mobile is-centered">
      <div class="is-primary has-text-primary is-size-2 is-half title has-text-centered is-mobile">
        Infographe, Développeur Web et mobile
      </div>
    </div>

    <div class="columns is-centered">
      <div class="column is-6 has-text-centered is-size-4 is-mobile">
        je conçois de belles créas, code de belles choses de manière simple et attrayant
      </div>
    </div>
  </div>
  <div class="block">
    <div class="columns is-centered is-mobile">
      <div class="mt-6">
        <img src="../assets/images/photo.png" alt="" width="220" />
      </div>
    </div>
  </div>

  <div class="block">
    <div class="is-background-primary mt-6 p-6">
      <div
        class="has-text-centered has-text-white is-size-2 is-half is-family-secondary is-centered"
      >
        Salut, je m’appelle Gnamien prince, ravi de vous rencontrer
      </div>
      <div
        class="column is-three-fifths is-offset-one-fifth is-size-5 has-text-dark is-centered has-text-centered"
      >
        Je travail en tant que freelance dans le domaine du design et du developpement informatique
        depuis plus de 2 ans avec plusieurs entreprises qui solicite mes services, elles ont
        toujours été satisfaites par mon determinisme et mon professionnalisme
      </div>
    </div>
  </div>

  <div class="container">
    <div class="block">
      <div class="columns is-desktop">
        <div class="column">
          <BoiteDomaine :information="information1"/>
        </div>
        <div class="column">
          <BoiteDomaine :information="information2"/>
        </div>
        <div class="column">
          <BoiteDomaine :information="information3"/>
        </div>
        <div class="column">
          <BoiteDomaine :information="information4"/>
        </div>
      </div>
    </div>
    <div class="block mt-6 mb-6">
      <div class="has-text-white title has-text-centered">Mes Travaux</div>
    </div>

    <div class="columns">
      <div class="column">
        <ProjetComponent />
      </div>
    </div>
  </div>
</template>
