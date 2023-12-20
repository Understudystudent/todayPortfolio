<template>
<nav class="navbar navbar-expand-lg navbar-light bg-light">
  <div class="container-fluid">
  <router-link to="/">
    <img alt="Vue logo" src="https://lh3.googleusercontent.com/u/0/drive-viewer/AEYmBYRdn0FRnl3uukePCUTrBlaBj1yI_kmAmmGQuMzXGdCtkMXj_pmuYKi6q0a4kfvxtu2GJmbWiFGlVNmNSJ1eaCCbFa-N7w=w1920-h868">  
  </router-link>

    
    <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarSupportedContent">
      <ul class="navbar-nav me-auto mb-2 mb-lg-0">
        <li class="nav-item">
          <!-- <a class="nav-link active" aria-current="page" href="#">Home</a> -->
           <router-link to="/"> Home</router-link>
        </li>
        <li class="nav-item">
            <router-link to="/about"> About</router-link>
        </li>
        <li class="nav-item">
            <router-link to="/resume">Resume</router-link> |

        </li>
        <li class="nav-item">
            <router-link to="/projects">Project</router-link> |
        </li>

        <li class="nav-item">
            <router-link to="/skills">Review</router-link> |
        </li>
        <li class="nav-item">
            <router-link to="/contact">Reach Me</router-link> 
        </li>
      </ul>
      
    </div>
  </div>
</nav>
</template>


<script>

</script>

<style scoped>

</style>