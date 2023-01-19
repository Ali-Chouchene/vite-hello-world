<script>
import AppHero from './components/AppHero.vue';
import AppTitle from './components/AppTitle.vue';

export default {
  data() {
    return {
      name: 'ali'
    }
  },
  components: {
    AppTitle,
    AppHero
  },
}

</script>

<template>
  <div class="container">
    <AppTitle></AppTitle>
    <AppHero></AppHero>
  </div>
</template>

<style scoped>

</style>
