<template>
  <div>
    
    <AppHeader />
    <AppMain />
    <AppFooter />
  </div>
</template>

<script>
import NavigationComponent from './components/NavigationComponent.vue';
import AppHeader from './components/AppHeader.vue';
import AppMain from './components/AppMain.vue';
import AppFooter from './components/AppFooter.vue';

export default {
  components: {
    AppHeader,
    AppMain,
    AppFooter,
    NavigationComponent,
  },
  data() {
    return {
      navigationData: {
        logo: 'avada-marketing-logo.png',
      },
    };
  },
};
</script>

<style scoped>
  body {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
  }
</style>

