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
