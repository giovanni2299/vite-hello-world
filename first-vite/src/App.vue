<script>
import AppTitle from './components/AppTitle.vue'
import AppHero from './components/AppHero.vue'

export default{
  components:{
    AppTitle,
    AppHero
  }
}
</script>

<template>
  <div id="fulScreen">
    <AppTitle/>
    <AppHero/>

  </div>
</template>

<style>
  #fulScreen{
    height: 100vh;
  }

</style>
