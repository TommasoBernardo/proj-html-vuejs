<script >
import ComponentsHeader from './components/ComponentsHeader.vue';
import MainAppForum from './components/main/MainAppForum.vue';
import MainForum from './components/main/MainForum.vue';
import MainJoin from './components/main/MainJoin.vue';
import MainLastNews from './components/main/MainLastNews.vue';
import ComponentsFooter from './components/ComponentsFooter.vue';


export default{
  components: {
    ComponentsHeader,
    MainAppForum,
    MainForum,
    MainJoin,
    MainLastNews,
    ComponentsFooter

  }
}
</script>

<template>
  <link rel="stylesheet" 
        href="https://use.fontawesome.com/releases/v5.2.0/css/all.css" 
        integrity="sha384-hWVjflwFxL6sNzntih27bfxkr27PmbbK/iSvJ+a4+0owXq79v+lsFkW54bOGbiDQ" 
        crossorigin="anonymous">
    <ComponentsHeader />
    <MainAppForum />
    <MainForum />
    <MainJoin />
    <MainLastNews />
    <ComponentsFooter />
</template>

<style lang="scss">
@use './Style/general.scss' as *; 
@use './Style/partials/variables' as *; 
@use 'bootstrap/scss/bootstrap.scss' as *;
</style>
