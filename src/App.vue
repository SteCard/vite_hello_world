<script>

import AppTitle from './components/AppTitle.vue'; //Comunico l'esistenza della componente AppTitle

export default {
  components:{
    AppTitle //Comunico che può utilizzare la componente AppTitle
  }
}
</script>

<template>
  <div>
    <AppTitle /> <!-- Utilizzo la componente -->
  </div>
</template>


<style scoped>
  
</style>