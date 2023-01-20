<script >
import ComponentsHeader from './components/ComponentsHeader.vue';
import MainAppForum from './components/main/MainAppForum.vue';
import MainLastNews from './components/main/MainLastNews.vue';
import MainSection from './components/main/MainSection.vue';
import MainSubscribe from './components/main/MainSubscribe.vue';
import ComponentsFooter from './components/ComponentsFooter.vue';


export default{
  components: {
    ComponentsHeader,
    MainAppForum,
    MainLastNews,
    MainSection,
    MainSubscribe,
    ComponentsFooter

  }
}
</script>

<template>
  <link rel="stylesheet" 
        href="https://use.fontawesome.com/releases/v5.2.0/css/all.css" 
        integrity="sha384-hWVjflwFxL6sNzntih27bfxkr27PmbbK/iSvJ+a4+0owXq79v+lsFkW54bOGbiDQ" 
        crossorigin="anonymous">
        <link  rel="stylesheet"  href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.2.0/css/all.min.css"  />
    <ComponentsHeader />
    <MainAppForum />
    <MainLastNews />
    <MainSection />
    <MainSubscribe />
    <ComponentsFooter />
</template>

<style lang="scss">
@use './Style/general.scss' as *; 
@use './Style/partials/variables' as *; 
@use 'bootstrap/scss/bootstrap.scss' as *;

</style>
