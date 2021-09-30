<template>
  <v-app>
    <navbar/>
<parallax/>    <v-main>
      <router-view/>
    </v-main>
<footer-dev/>
</v-app>
</template>

<script>
import FooterDev from './components/footerDev.vue';
import Navbar from './components/navbar.vue';

export default {
  name: 'App',

  data: () => ({
    
  }),
  components:{
    Navbar,
    FooterDev

  }
};
</script>
