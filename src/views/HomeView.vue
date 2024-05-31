<template>
  <app class="home">
    <NavBar/>
    <Container>
    <div class="head">
      <h1 class="text-3xl font-semibold m-3" >Hello</h1>
      <h1 class="text-3xl font-medium m-4">I'm Sivalingam Kavirajh</h1>
      <span class="text-2xl font-sans m-5">Dévolopeur web</span><br>
      <button class="m-6  bg-blue-700 rounded-md px-2">Contact</button>
    </div>
  </Container>
  </app>
</template>


<script>

import NavBar from '../components/NavBar.vue';
import FooterView from '../components/FooterView.vue';




export default {
  name: 'HomeView',
  components: {
    NavBar,
    FooterView
  }
}
</script>

<style scoped>

  .head{
  position: relative;
  text-align: center;
  padding: 12px;
  margin-bottom: 6px;
  height: 400px;
  width: 100%;
  color: black;
  background-color: aqua;
}


</style>
