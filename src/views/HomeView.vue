<template>
 <div class="container">
  <div class="row">
    <div class="col">
      <h3>Hi there, I'm</h3>
      <h1><span>NOZIPHO</span></h1>
      <h3>and I am a <span>WEB DEVELOPER</span></h3>
      <button><i class="fa-solid fa-download"><RouterLink to="/about">About ME</RouterLink></i></button>
    </div>
    <div class="col">
      <img src="https://i.postimg.cc/jdcRzwNk/BACKNOW-removebg-preview.png" alt="img">
    </div>
  </div>
</div>
</template>
  
  <script>
  
  export default {
    name: 'HomeVue',
  }
  </script>
  
  <!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
span{
  color:#36454F;
}
.container{
  min-height: 100vh;
  padding-top: 15rem;
}
.row{
  align-content: center;
}
button{
  width: 10rem;
  background-color: #36454F;
  height: 3rem;
  margin-top: 2px;
  color: white;
  margin-left: 1rem;
}
button i{
  color: white;
}
</style>
  