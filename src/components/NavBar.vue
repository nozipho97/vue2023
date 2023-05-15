<template>
  <nav class="nav">
      <div class="container-fluid">
        <router-link to="/"><i class="fa-solid fa-house-user"></i>Home</router-link>
        <router-link to="/about"><i class="fa-solid fa-address-card"></i>About</router-link>
        <router-link to="/education"><i class="fa-solid fa-file"></i>Education & Experience</router-link>
        <router-link to="/projects"><i class="fa-solid fa-diagram-project"></i>Projects</router-link>
        <router-link to="/testimonials"><i class="fa-solid fa-comment"></i>Testimonials</router-link>
        <router-link to="/contact"><i class="fa-solid fa-address-book"></i>Contact</router-link>
      </div>
    </nav>
    
   
    </template>
    
    <!-- <script>
    export default {
       name:'Header'
    }
    </script> -->
    
    <style scoped>
   
    
    nav a {
      font-weight: bold;
      color:#36454F;
      text-decoration: none;
      justify-content: space-evenly;
      margin-left:50px;
      margin-right:50px;
      background-color: transparent;
      padding-top: 2rem;
      
    }
  nav a.router-link-exact-active {
  color:orangered;
} 
    
    </style>