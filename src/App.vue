<script>
import headApp from './components/headApp.vue'
import mainApp from './components/mainApp.vue'
import bannerApp from './components/bannerApp.vue'

export default{
  components: {
      headApp,
      mainApp,
      bannerApp
  }
}
</script>

<template>
    <headApp />
    <mainApp />
    <bannerApp />
</template>

<style scoped>

</style>
