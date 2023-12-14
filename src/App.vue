
<script>
import AppFooter from './components/AppFooter.vue';
import AppHeader from './components/AppHeader.vue';
import AppMain from './components/AppMain.vue';

export default {
    name: 'App',
  components: {
    AppHeader,
    AppFooter,
    AppMain
  }
  
}
</script>

<template lang="">
  <AppHeader></AppHeader>
  <AppMain></AppMain>
  <AppFooter></AppFooter>
</template>
<style lang="">
  
</style>
