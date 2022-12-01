<script setup>
</script>

<template>
  <main>
    <div class="all">
      <div class="container">
        <h1>New !</h1>
      </div>
      <div class="box">
        <p>I´m Leonardo Castro</p>
        <p>I´m a <span>Software Developer</span></p>
      </div>
      <div class="donate">
        <a class="coffee" href="/">Donate Coffee</a>
      </div>
      <div class="media">
        <a href="/">Discord</a>
        <a href="/">Github</a>
        <a href="/">Linkedin</a>
        <a href="/">Facebook</a>
      </div>
    </div>
  </main>
</template>

<style scoped>

*{
  font-family: 'Poppins', sans-serif;
}

main{
  background-color: #131313;
  display: flex;
  justify-content: center;
  align-items: center;
  height: 85vh;
}

.all{
  text-align: center;
}

.container{
  display: flex;
  justify-content: center;
  align-items: center;
}

.box{
  font-size: 50px;
  margin: 40px 0 80px 0;
}

.box p{
  font-weight: bold;
}

.box span{
  text-shadow: #00ff33 1px 0 10px;
  color: #43ff69;
  font-weight: bold;
}

.donate{
  margin-bottom: 80px;
}

.donate a{
  color: #000;
  font-weight: bold;
  text-decoration: none;
}
.donate .coffee{
  background-color: #43ff69;
  padding: 10px;
  border-radius: 3px;
}

.media a{
  color: #fff;
  text-decoration: none;
  padding: 0 20px;
}

.media a:hover{
  color: #43ff69;
}

main img{
  width: 70px;
}

main h1{
  font-size: 60px;
  margin-left: 10px;
  font-weight: bold;
  
}
</style>