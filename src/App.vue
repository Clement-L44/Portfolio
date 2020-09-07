
<template>

  <div class="page-wrap" id="app">
    <Header/>
    <Contenu/>
    <Footer/>
  </div>

</template>

<script>
import Header from './components/Header/Header.vue'
import Footer from './components/Footer/Footer.vue'
import Contenu from './components/Content/Content.vue'

export default {

  name: 'App',
  components: {
    Header,
    Footer,
    Contenu
  }
}


</script>

<style>
  @import './App.css';
</style>
