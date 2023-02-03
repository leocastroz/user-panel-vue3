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
          <form action="https://formsubmit.co/leonardoleoneell@gmail.com" method="POST">
            <h2>Send me an email</h2>
            <input type="hidden" name="_next">
            <input type="text" name="name" placeholder="Full name">
            <input type="email" name="email" placeholder="Email">
            <input type="text" name="subject" placeholder="Subject">
            <textarea name="message" cols="30" rows="10" placeholder="message"></textarea>
            <button type="submit">Send </button>  
          </form>
        </div>
        <div class="img-send">
          <h2>If you prefer, I have a <span>contact form</span></h2>
          <div class="social-link">
            <a class="telegram" href="/">Telegram</a>
            <a class="whatsapp" href="/">WhatsApp</a>
            <a class="linkedin" href="/">Linkedin</a>
            <a class="github" href="/">Github</a>
          </div>
          
        </div>
        <div class="chanel">
          <img src="https://cdn3d.iconscout.com/3d/premium/thumb/love-chat-4059078-3364001.png" alt="">
        </div>
      </div>
    </div>
  </main>
</template>

<style scoped>



.chanel{
  
  position: absolute;
  right: 80px;
  bottom:-50px;
}
.chanel img {
  width: 200px;
}
.img-send{
  text-align: right;
  width: 300px;
}
.img-send h2{
  font-weight: bold;
  color: #43ff69;
  padding-bottom: 50px;
}

.img-send span{
  border-bottom: 2px dashed #43ff69;
  font-weight: bold;
  color: #43ff69;
  padding-bottom: 10px;
}

.social-link{
  display: grid;
  justify-content: end;
  grid-template-columns: auto auto;
  padding-bottom: 20px;
}

.social-link a{
  display: grid;
  width: 100px;
  text-align: center;
  margin: 10px 0 10px 10px;
  color: #fff;
  text-decoration: none;
  padding: 5px;
}

.social-link .telegram{
  background-color:#27a5e5;
  border-radius: 3px;
}

.social-link .whatsapp{
  background-color:#1daa51  ;
  border-radius: 3px;
}

.social-link .linkedin{
  background-color: #0072ac;
  border-radius: 3px;
}

.social-link .github{
  background-color: #24292e ;
  border-radius: 3px;
}
form button{
  margin-top: 10px;
  padding: 5px 10px;
  width: 100px;
  background-color: #fff;
  color: #131313;
  font-weight: bold;
  border-radius: 4px;
  transition-timing-function: cubic-bezier(0.4, 0, 0.2, 1);
  transition-duration: 500ms;
}

form button:hover{
  transition-timing-function: cubic-bezier(0.4, 0, 0.2, 1);
  transition-duration: 500ms;
  background-color: #43ff69;
}

form textarea{
  background-color: #141414;
  border: 2px solid #1f1f22;
  border-radius: 4px;
}

textarea[placeholder]
{
  padding: 10px 0 0 10px;
  color: #fff;
}

.box input[placeholder]{
  color: #fff;
}

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
  padding: 40px;
  margin-top: 40px;
  min-width: 800px;
  border-radius: 10px;
  background-color: #1c1c1d;
}
.box input{
  width: 300px;
  margin: 10px 0 10px 0;
  padding: 10px;
  border: 2px solid #1f1f22;
  background-color: #141414;
  border-radius: 4px;
}

.labels form{
  display: grid;
}

</style>