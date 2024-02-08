<script>
import AppHeader from './components/AppHeader.vue';
import AppMain from './components/AppMain.vue';
import FooterTop from './components/FooterTop.vue';
import FooterMain from './components/FooterMain.vue';
import FooterBottom from './components/FooterBottom.vue';
import '@fontsource/pt-sans-narrow';
import AppCard from './components/AppCard.vue';

export default {
  components: {
    AppHeader,
    AppMain,
    FooterTop,
    FooterMain,
    FooterBottom,
    AppCard
  }
}
</script>

<template>
  <AppHeader />
  <AppMain />
  <AppCard/>
  <FooterTop />
  <FooterMain/>
  <FooterBottom/>
</template>

<style lang="scss">
@use './style/general.scss' as *;
</style>
