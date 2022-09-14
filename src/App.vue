<template>
  <div id="app">
    <NavBar />
    <MainContainer />
    <MainFooter />
  </div>
</template>
    


<script>
import MainContainer from './components/MainContainer.vue'
import NavBar from './components/NavBar.vue'
import MainFooter from './components/MainFooter.vue'


export default {
  name: 'App',
  components: {
    MainContainer,
    NavBar,
    MainFooter,
}
}

</script>

<style lang="scss">
@import './styles/main.scss';

</style>
