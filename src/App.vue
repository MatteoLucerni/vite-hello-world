<script>
import AppTitle from './components/AppTitle.vue';
import AppHero from './components/AppHero.vue';

export default {
  components: {
    AppTitle,
    AppHero
  }
}
</script>


<template>
  <div class="container text-center mt-5">
    <AppTitle />

    <AppHero />
  </div>
</template>

<style>
body {
  background-color: rgb(112, 66, 66);
}
</style>