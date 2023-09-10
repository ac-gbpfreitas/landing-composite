<template>
  <NavComponent />
  <HeaderComponent />
  <MainContent />
  <FooterComponent />
</template>

<script>
import FooterComponent from './components/FooterComponent.vue';
import HeaderComponent from './components/HeaderComponent.vue';
import MainContent from './components/MainContent.vue';
import NavComponent from './components/NavComponent.vue';


export default {
  name: 'App',
  components: {
    NavComponent,
    HeaderComponent,
    MainContent,
    FooterComponent
  },
}
</script>

<style lang="scss" scoped>
//npm install --save-dev node-sass sass-loader

#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
