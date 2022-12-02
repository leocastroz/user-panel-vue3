<script setup>
import { RouterLink, RouterView } from 'vue-router'
import HelloWorld from './components/HelloWorld.vue'
import NavBar from './components/NavBar.vue'
</script>

<template>
  <div class="wrapper">
    
    <header>
      <div class="warning">
        <div>
          <h1>Para uma melhor <span>experiência</span></h1>
          <p>utilize uma resolução maior!</p>
          <p>Recomendamos uma resolução </p>
          <p>de 1000px ou 15 polegadas.</p>
        </div>
      </div>
        <HelloWorld/>
        <div class="grid">
          <nav>
            <div class="logo">
              <h1>user <span>Panel</span></h1>
            </div>  
            <RouterLink to="/"><span class="material-symbols-outlined">home</span><p class="home">Home</p></RouterLink>
            <RouterLink to="/tech"><span class="material-symbols-outlined">code</span><p class="home">Technologies</p></RouterLink>
            <RouterLink to="/tools"><span class="material-symbols-outlined">computer</span><p class="home">Tools</p></RouterLink>
            <RouterLink to="/about"><span class="material-symbols-outlined">person</span><p class="home">About</p></RouterLink>
            <RouterLink to="/experience"><span class="material-symbols-outlined">next_week</span><p class="home">Experiences</p></RouterLink>
            <div class="footer">© all rights reserved - 2022</div>
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

@media(min-width: 900px) {
  .warning{
    display: none;
  }
}

@media(max-width: 900px) {
  .warning{
  text-align: center;
  align-items: center;
  justify-content: center;
  z-index: 999;
  position: absolute;
  display: grid;
  width: 100%;
  height: 100%;
  background-color: #0f0f0f;
  }

  .warning h1{
    font-weight: bold;
    padding: 20px;
  }

  .warning span {
    font-weight: bold;
    color: #43ff69;
  }
}

@media(max-width: 1250px){
  
  header .home{
    display: none;
    background-color: tomato;
  }
  header .logo{
    text-align: center;
  }
  header .grid{
    grid-template-columns: 150px auto;
  }
}

header .home{
  margin: 0 0 0 5px;
}

header {
  overflow-y: hidden;
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
  display: flex;
  justify-content: center;
  padding: 20px 0;
  border-top: 1px solid rgb(24, 24, 27);
  bottom: 0;
  position: absolute;
  width: 100%;
  font-size: 12px;
}



</style>
