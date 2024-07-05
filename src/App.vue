<template>
  <NavBar></NavBar>
    <router-view/>
    
  <Footer/>
</template>

<script>
import Footer from './components/Footer';
import NavBar from './components/NavBar';

  export default {
    components: {
      NavBar,
      Footer,
    },
    data(){
      return {
        isloading: false,
      };
    },
  }
</script>
<style src="@/assets/css/style.css"></style>