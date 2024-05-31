<template>
  
  <app-bar class="">

    <h1>kavirajh</h1>
    /<fa :icon="['fab', 'youtube']" />/
    <v-btn text @click="scroll('home')" class="text-blue">Home</v-btn>
    <button text @click="scroll('about')" class="text-blue">About</button>
    <button text @click="scroll('portfolio')" class="text-blue">Portfolio</button>
    <button text @click="scroll('Projects')" class="text-blue">Projects</button>
    <button text @click="scroll('contact')" class="text-blue">Contact</button>
  </app-bar>

</template>



<script>
import { fab } from '@fortawesome/free-brands-svg-icons';

export default {
  methods: {
  scroll(refName) {
    const element = document.getElementById(refName);
    element.scrollIntoView({behavior: "smooth"});
}
}


}

</script>

<style scoped>

</style>