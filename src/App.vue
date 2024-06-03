<script>
import AppHeader from './components/Header/AppHeader.vue';
import AppMain from './components/Main/AppMain.vue';

export default {
    components: {
      AppHeader,
      AppMain,
    }
}

</script>

<template>
  <AppHeader></AppHeader>
  <AppMain></AppMain>
</template>

<style lang="scss">
  body{
    background-color: #e4e5e6;
  }
</style>
