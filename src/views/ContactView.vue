<script setup>
</script>

<template>
  <main>
    <div class="all">
      <div class="container">
        <span></span>
        <h1>Contact !</h1>
      </div>
      <div class="box">
        <div class="labels">
          <p>Enviar</p>
          <input type="text">
          <br>
          <p>Enviar</p>
          <input type="text">
          <br>
          <p>Enviar</p>
          <input type="text">
          <br>
          <p>Enviar</p>
          <input type="text">
        </div>
        <div class="">
          <img src="https://cdn.dribbble.com/users/1322735/screenshots/14134247/media/a3c84750d3fbaf4759bec145cc48ced5.png?compress=1&resize=400x300" alt="">
        </div>
      </div>
    </div>
    <div class="footer">
      <a href="/">CHAT-BOX</a>
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


main img{
  width: 300px;
}

main h1{
  font-size: 60px;
  margin-left: 10px;
  font-weight: bold;
}

.container{
  display: flex;
  justify-content: center;
  align-items: center;
}

.container span{
  width: 5px;
  height: 40px;
  background-color: #43ff69;
}

.box{
  display: flex;
  align-items: center;
  justify-content: space-evenly;
  padding: 20px;
  margin-top: 40px;
  min-width: 800px;
  border-radius: 10px;
  border: 3px solid #7d7d7d;
  background-color: #131313;  
}
.box input{
  width: 300px;
  margin: 10px 0 10px 0;
  padding: 10px;
  border: 1px solid #18181b;
  background-color: #141414;
}

.labels{
}

.footer{
  margin: 20px;
  padding: 5px 10px;
  background-color: #43ff69;
  bottom: 0;
  right: 0;
  position: absolute;
  border-radius: 5px;
}
.footer a{
  font-weight: bold;
  color: #131313;
  text-decoration: none;
}
</style>