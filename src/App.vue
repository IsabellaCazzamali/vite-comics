<script>
/* Import the components */
import AppHeader from './components/AppHeader.vue';
import AppMain from './components/AppMain.vue';
import AppFooter from './components/AppFooter.vue';

export default {
  name: 'App',
  /* Register the components */
  components: {
    AppHeader,
    AppMain,
    AppFooter
  }
}
</script>

<template>


  <!-- Use the components -->
  <AppHeader></AppHeader>

  <AppMain></AppMain>

  <AppFooter></AppFooter>


</template>

