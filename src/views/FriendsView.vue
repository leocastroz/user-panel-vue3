<script setup>
</script>

<template>
  <main>
    <div class="all">
      <div class="container">
        <span></span>
        <h1>Friends !</h1>
      </div>
      <div class="box">
        <p>Here are some <span>friends</span> who helped me in my professional career.</p>
      </div>
      <div class="friends">
        <div class="card-friend">
          <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcS9oka0QHdz9trvloCNNGCVB8yQltgTRJGDCHuyGzRZzKJQxwn5eJpE7IrOXaZnm3rS2ds&usqp=CAU" alt="">
          <div>
            <h3>Your name</h3>
            <p>Desenvolvedor .NET | Vue</p>
          </div>
        </div>

        <div class="card-friend">
          <img src="https://ubernewsroomapi.10upcdn.com/wp-content/uploads/2018/12/Nikki-Krishnamurthy-400x400.jpg" alt="">
          <div>
            <h3>Your name</h3>
            <p>Desenvolvedor React | TS</p>
          </div>
        </div>

        <div class="card-friend">
          <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcS9oka0QHdz9trvloCNNGCVB8yQltgTRJGDCHuyGzRZzKJQxwn5eJpE7IrOXaZnm3rS2ds&usqp=CAU" alt="">
          <div>
            <h3>Your name</h3>
            <p>Desenvolvedor Vue | JS</p>
          </div>
        </div>

        <div class="card-friend">
          <img src="https://ubernewsroomapi.10upcdn.com/wp-content/uploads/2018/12/Nikki-Krishnamurthy-400x400.jpg" alt="">
          <div>
            <h3>Your name</h3>
            <p>Desenvolvedor Vue | TS</p>
          </div>
        </div>

        <div class="card-friend">
          <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcS9oka0QHdz9trvloCNNGCVB8yQltgTRJGDCHuyGzRZzKJQxwn5eJpE7IrOXaZnm3rS2ds&usqp=CAU" alt="">
          <div>
            <h3>Your name</h3>
            <p>Desenvolvedor React | Vue</p>
          </div>
        </div>

        <div class="card-friend">
          <img src="https://ubernewsroomapi.10upcdn.com/wp-content/uploads/2018/12/Nikki-Krishnamurthy-400x400.jpg" alt="">
          <div>
            <h3>Your name</h3>
            <p>Desenvolvedor React | TS</p>
          </div>
        </div>

        <div class="card-friend">
          <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcS9oka0QHdz9trvloCNNGCVB8yQltgTRJGDCHuyGzRZzKJQxwn5eJpE7IrOXaZnm3rS2ds&usqp=CAU" alt="">
          <div>
            <h3>Your name</h3>
            <p>Desenvolvedor React | Flutter</p>
          </div>
        </div>
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
  justify-content: center;
  align-items: center;
  height: 85vh;
}


.container{
  padding: 30px 0 0 30px;
  display: flex;
  justify-content: start;
  align-items: center;
}
.container span{
  width: 5px;
  height: 40px;
  background-color: #43ff69;
}

.box{
  padding: 0 0 0 30px;
}

.friends{
  display: grid;
  grid-template-columns: auto auto auto;
  width: 100%;
  padding: 50px 0 0 30px;
}

.card-friend{
  margin: 0 0 30px 0;
  border-radius: 8px;
  align-items: center;
  display: flex;
  width: 350px;
  color: #9d9d9d;
  background-color: #0f0f0f;
  border-right: 8px solid #43ff69;
}

.card-friend h3{
  color: #8fffa5;
  font-weight: bold;
}

.card-friend img{
  border-radius: 8px;
}

.card-friend div{
  padding: 0 0 0 20px;
}

.box span{
  color: #43ff69; 
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