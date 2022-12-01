<script setup>
import { RouterLink, RouterView } from 'vue-router'
import HelloWorld from './components/HelloWorld.vue'
import NavBar from './components/NavBar.vue'
</script>

<template>
  <div class="wrapper">
    <header>
        <HelloWorld/>
        <div class="grid">
          <nav>
            <div class="logo">
              <h1>user <span>Panel</span></h1>
            </div>  
            <RouterLink to="/">Home</RouterLink>
            <RouterLink to="/about">About</RouterLink>
            <RouterLink to="/novo">New</RouterLink>
            <div class="footer">v1.0.1</div>
          </nav>
          <div>
            <NavBar/>
            <RouterView />
          </div>
          
    
        </div>
        
    </header>
  </div>
  
</template>

<style scoped>

header {
  max-height: 100vh;
}

nav{
  min-height: 95vh;
  background-color: #0f0f0f;
  border-right: 1px solid rgb(24, 24, 27);
}

.grid{
  display: grid;
  grid-template-columns: 250px auto;
}

.logo{
  display: flex;
  align-items: center;
  justify-content: center;
  height: 100px;
  color: #43ff69;
  font-family: 'Permanent Marker', cursive;
  font-size: 20px;
  text-shadow: #00ff33 1px 0 10px;
}

.logo span{
  color: #fff;
}

nav a{
  justify-content: center;
  display: flex;
  color: #7d7d7d;
  text-decoration: none;
  padding: 20px 0;
  font-family: 'Poppins', sans-serif;
}

nav a.router-link-exact-active {
  color: #43ff69;
}

.footer{
  text-align: center;
  padding: 20px 0;
  border-top: 1px solid rgb(24, 24, 27);
  bottom: 0;
  position: absolute;
  width: 100%;
}



</style>
