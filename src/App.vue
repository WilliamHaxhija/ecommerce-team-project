<script>
import AppHeader from './components/Header/AppHeader.vue';
import AppMain from './components/Main/AppMain.vue';
import AppFooter from './components/Footer/AppFooter.vue';

export default {
    components: {
      AppHeader,
      AppMain,
      AppFooter
    }
}

</script>

<template>
  <AppHeader></AppHeader>
  <AppMain></AppMain>
  <AppFooter></AppFooter>
</template>

<style lang="scss">

  body{
    background-color: #e4e5e6;
  }
  
</style>
