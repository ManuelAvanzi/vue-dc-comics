<template>
  <div id="app">
    <header-container />
    <main-content/>
    <footer-container/>
    <footer-list></footer-list>
    <footer-bottome/>
    
  </div>
</template>

<script>
import HeaderContainer from './components/HeaderContainer.vue'

import MainContent from './components/MainContent.vue'
import FooterContainer from './components/FooterContainer.vue'
import FooterList from './components/FooterList.vue'
import FooterBottome from './components/FooterBottome.vue'


export default {
  name: 'App',
  components: {

   HeaderContainer,
   MainContent,
   FooterContainer,
   FooterList,
    FooterBottome
  
  }
}
</script>


    MainContent
    MainContent<style 
    HeaderContainerlang="scss">
    @import './style/main.scss';
   
</style>
