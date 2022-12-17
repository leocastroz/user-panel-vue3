<script setup>
</script>

<template>
  <main>
      <div class="container">
        <h1>YOUR PROFILE !</h1>
      </div>
      <div class="box">
        <div class="picture">
          <img class="img-profile" src="https://avatars.githubusercontent.com/u/72839343?v=4" alt="profile">
          <p>Leonardo Silva Castro</p>
          <p>20y | Student | Development</p>
        </div>
        <div class="fields">
          <p>Your Changes</p>
          <input type="text" placeholder="name">
          <input type="text" placeholder="last name">
          <input type="text" placeholder="year">
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
  height: 85vh;
}

main h1{
  font-size: 40px;
  margin-left: 10px;
  font-weight: bold;
  
}

.container{
  padding: 30px;
  background-color: #43ff69;
  color: #131313;
}

.container span{
  content: "";
  width: 5px;
  height: 40px;
  background-color: #43ff69;
}

.box{
  padding: 100px;
  display: flex;
  align-items: center;
  justify-content: start;
}

.picture {
  text-align: center;
}
.picture img{
  box-shadow: 0px 0px 30px 1px #2e2e2e;
  border-radius: 100%;
  width: 300px;
  margin-bottom: 20px;
}

.fields{
  display: grid;

}
.fields input{
  margin: 20px;
}

</style>