<script setup>
const props = defineProps({
  information: String
})
</script>

<template>
  <div class="has-text-centered pt-6">
    <figure>
      <img src="../assets/images/icon4.svg" />
    </figure>
    <p class="is-primary has-text-primary title">{{ props.information.titre }}</p>
    <p class="is-size-6">{{ props.information.description }}</p>
    <p class="has-text-primary subtitle">{{ props.information.titre2 }}</p>
    <p class="">{{ props.information.description2 }}</p>
    <p class="has-text-primary is-size-5">  {{ props.information.titre3 }}</p>
    <p class="">  {{ props.information.description }}</p>
  </div>
</template>

<style>
</style>
