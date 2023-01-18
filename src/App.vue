<script >
import ComponentsHeader from './components/ComponentsHeader.vue';
import ComponentsFooter from './components/ComponentsFooter.vue';
import MainAppForum from './components/main/MainAppForum.vue';
import MainForum from './components/main/MainForum.vue';
import MainJoin from './components/main/MainJoin.vue';
import MainLastNews from './components/main/MainLastNews.vue';

export default{
  components: {
    ComponentsHeader,
    ComponentsFooter,
    MainAppForum,
    MainForum,
    MainJoin,
    MainLastNews
  }
}
</script>

<template>

</template>

<style lang="scss">
@use './Style/general.scss' as *; 
@use './Style/partials/variables' as *; 
@use 'bootstrap/scss/bootstrap.scss' as *;
</style>
