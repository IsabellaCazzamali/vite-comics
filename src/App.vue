<script>
/* Import the components */
import AppHeader from './components/AppHeader.vue';
import AppMain from './components/AppMain.vue';

export default {
  name: 'App',
  /* Register the components */
  components: {
    AppHeader,
    AppMain
  }
}
</script>

<template>


  <!-- Use the components -->
  <AppHeader></AppHeader>

  <AppMain></AppMain>


  <footer></footer>
</template>

<style>



</style>
