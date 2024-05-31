<template>
  <NavBar/>
  <nav>
    
  </nav>
  <FooterView/>
  
</template>



<script>

import NavBar from '../components/NavBar.vue';
import FooterView from '../components/FooterView.vue';
import { fab } from '@fortawesome/free-brands-svg-icons';


export default {
  name: 'HomeView',
  components: {
    NavBar,
    FooterView
  }
}
</script>
