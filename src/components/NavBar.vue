<template>
  
  <div id="button" class=" flex justify-end">
    <v-app-bar>
    <button class="py-2 px-5 bg-blue-700 hover:bg-blue-800 m-2 bo rounded-md" >Home</button>
    <button class="py-2 px-5 bg-blue-700 hover:bg-blue-800 m-2 bo rounded-md">About</button>
    <button class="py-2 px-5 bg-blue-700 hover:bg-blue-800 m-2 bo rounded-md">Portfolio</button>
    <button class="py-2 px-5 bg-blue-700 hover:bg-blue-800 m-2 bo rounded-md">Project</button>
    <button class="py-2 px-5 bg-blue-700 hover:bg-blue-800 m-2 bo rounded-md">Contact</button>
    </v-app-bar>
  </div>

</template>



<script>
import App from '@/App.vue';


export default {
  components: { App },
  methods: {
  scroll(refName) {
    const element = document.getElementById(refName);
    element.scrollIntoView({behavior: "smooth"});
}
}


}

</script>
<style scoped>
#button {
  background-color: aquamarine;
}

</style>

