<script>

import AppTitle from './components/AppTitle.vue'; //Comunico l'esistenza della componente AppTitle

import AppJumbotron from './components/AppJumbotron.vue'; //Comunico l'esistenza della componente AppTitle

export default {
  components:{
    AppTitle, //Comunico che può utilizzare la componente AppTitle
    AppJumbotron
  }
}
</script>

<template>
  <div>
    <AppTitle /> <!-- Utilizzo la componente -->
    <AppJumbotron />
  </div>
</template>


<style scoped>
  
</style>