<script>
import HeaderNav from './components/HeaderNav.vue';
import MainContent from './components/MainContent.vue';
import FooterContent from './components/FooterContent.vue';

export default {
  components : {
    HeaderNav,
    MainContent,
    FooterContent,
  }
}
</script>

<template>
  <HeaderNav />
  <MainContent />
  <FooterContent />
</template>

<style lang="scss">
@use './styles/general.scss' as *;
@use './styles/partials/variables.scss' as *;
</style>
