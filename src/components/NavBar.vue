<script>
  export default{
  data() {
    return {
      show: true
    }
  },
  methods:{
    handleDarkMode(){
      this.show = !this.show
    }
  }
}
</script>

<template>
    <div :class="`top ${show && 'dark-mode'}`">
        <div class="extras">
          <RouterLink to="/contact">Contact</RouterLink>
          <RouterLink to="/stamps">Stamps</RouterLink>
          <RouterLink to="/friends">Friends</RouterLink>
        </div>
        <div class="profile">
          <a @click="handleDarkMode"><span class="material-symbols-outlined">brightness_6</span></a>
          <a href="/"><span class="material-symbols-outlined">notifications</span></a>
          <RouterLink to="/myprofile"><img class="img-profile" src="https://avatars.githubusercontent.com/u/72839343?v=4" alt="profile"></RouterLink>
        </div>
    </div>
</template>


<style scoped>
.profile a{
  cursor: pointer;
  user-select: none;
}

.dark-mode{
  transition-timing-function: cubic-bezier(0.4, 0, 0.2, 1);
  transition-duration: 500ms;
  background-color: #ffffff !important;
}

.top{
    transition-timing-function: cubic-bezier(0.4, 0, 0.2, 1);
    transition-duration: 500ms;
    font-family: 'Poppins', sans-serif;
    align-items: center;
    justify-content: space-between;
    display: flex;
    background-color: #0f0f0f;
    width: 100%;
    height: 10vh;
    border-bottom: 1px solid rgb(24, 24, 27);
  }

.top .extras a{
    padding: 0 20px;
    text-decoration: none;
    color: #7d7d7d;
  }
  .top .profile{
    display: flex;
    align-items: center;
  }
  
  .top .profile a{
    padding: 0 20px;
    text-decoration: none;
    color: #7d7d7d;
  }
  .top .profile img{
    margin: 0 25px 0 25px;
    border-radius: 100%;
    width: 60px;
  }

  .top a.router-link-exact-active {
    color: #43ff69;
  }

</style>