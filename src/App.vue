<script >
import AppHeader from './components/AppHeader.vue';
import AppMain from './components/AppMain.vue';
import AppFooter from './components/AppFooter.vue';
export default {
  name: 'App',
  components: {

    AppHeader,
    AppMain,
    AppFooter

  }

}
</script>

<template>
  <AppHeader></AppHeader>
  <AppMain></AppMain>
  <AppFooter></AppFooter>
</template>

<style >
* {
  padding: 0;
  margin: 0;
  box-sizing: border-box;

}

body {
  font-family: 'Ysabeau', sans-serif;
}
</style>
