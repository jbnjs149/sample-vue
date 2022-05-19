<template>
  <HeaderComponent />
  <div class="container-fluid">
    <HomeComponent />
  </div>
</template>

<script>
import HomeComponent from './components/Pages/Home.vue';
import HeaderComponent from './components/Shared/Header.vue';

export default {
  name: 'App',
  components: {
    HomeComponent,
    HeaderComponent
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}
</style>
