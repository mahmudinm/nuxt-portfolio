<template>
  <div :style="{ background: `url(${backgroundHero}) no-repeat` }">
    <Navbar/>
    <nuxt/>
  </div>
</template>

<script>
import Navbar from "~/components/Navbar";
import backgroundHero from '~/assets/background-hero.svg'
export default {
  data: function() {
    return {
      backgroundHero
    }
  },
  components : {
    Navbar
  }
}
</script>


<style>
</style>

