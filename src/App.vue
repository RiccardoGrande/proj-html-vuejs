<script >
import AppHeader from './components/AppHeader.vue';
export default {
  name: 'App',
  components: {

    AppHeader

  }

}
</script>

<template>
  <AppHeader></AppHeader>
  <section class="reclutement">
    <div class="container">
      <div class="row">
        <div class="col text-end">
          <h4>How to Enroll Your Child to a Class?</h4>
        </div>
        <div class="col d-flex align-items-center justify-content-center">
          <a href="h"></a>
          <img src="fable/hover-button2.png" alt="">
        </div>
      </div>
    </div>
  </section>
</template>

<style scoped>
* {
  padding: 0;
  margin: 0;
  box-sizing: border-box;

}

.reclutement {
  background-image: url('fable/images/pattern.png');
}

h4 {
  padding: 1rem;
  color: white;
}

img {
  height: 60px;
}
</style>
