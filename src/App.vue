<template>
  <NavBar/>
  <router-view/>
  <Footer/>
</template>

<script>
import NavBar from './components/NavBar.vue';
import Footer from './components/FooterVue.vue';
export default{
  name:'App',
  components:{
    NavBar, Footer
  }
}
</script>

<style>
#app {
  font-family: Georgia, 'Times New Roman', Times, serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  /* text-align: center; */
  color: orangered;
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  background-color: white ;

}
h3{
  text-align: center;
}




</style>
