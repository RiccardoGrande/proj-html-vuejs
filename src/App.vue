<script >
import AppHeader from './components/AppHeader.vue';
import AppMain from './components/AppMain.vue';
export default {
  name: 'App',
  components: {

    AppHeader,
    AppMain

  }

}
</script>

<template>
  <AppHeader></AppHeader>
  <AppMain></AppMain>
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
