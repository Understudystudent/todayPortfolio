<template>
  
  <main class="container-fluid">
    <router-view />
  </main>
  
  

  
  <!-- Navbar -->
  <!-- <nav>
    <router-link to="/">Home</router-link> |
    <router-link to="/about">About</router-link> |
    <router-link to="/resume">Resume</router-link> |
    <router-link to="/projects">Project</router-link> |
    <router-link to="/skills">Review</router-link> |
    <router-link to="/contact">Reach Me</router-link> 
  </nav> -->
  <NavBar/>
  <FooterView/>
</template>

<script>
import FooterView from './components/FooterView.vue';
import NavBar from './components/NavBar.vue';


export default {
  components: {
    NavBar,
    FooterView,
  }
}
</script>


<style src="@/assets/css/style.css"></style>
