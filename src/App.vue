<script>
import headApp from './components/headApp.vue'
import mainApp from './components/mainApp.vue'
import bannerApp from './components/bannerApp.vue'
import footerApp from './components/footerApp.vue'
import flag from './components/flag.vue'
export default{
  components: {
      headApp,
      mainApp,
      bannerApp,
      footerApp,
      flag
  }
}
</script>

<template>
    <headApp />
    <mainApp />
    <bannerApp />
    <footerApp />
    <flag />
</template>

<style scoped>

</style>
