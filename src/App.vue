<template>
  <router-view/>
</template>

<script>
import HomeView from './views/HomeView.vue';
import './assets/tailwind.css';


export default {
  name: 'App',
  components:{
    HomeView
  }
 
  }

</script>