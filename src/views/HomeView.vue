<script>
export default{
  data() {
    return {
      show: false
    }
  }
}
</script>

<template>
  <main>
    <div class="all">
      <div class="container">
        <img 
        src="https://mwcorvettes.com/wp-content/uploads/2019/03/savethewave-300x252.gif" 
        alt="bye"
        >
        <h1>Welcome !</h1>
      </div>
      <div class="box">
        <p>I´m Leonardo Castro</p>
        <p>I´m a <span>Frontend Developer</span></p>
      </div>
      <div class="donate">
        <a v-on:click="show = !show" class="coffee">Donate Coffee ❤️</a>
      </div>
      <div class="media">
        <a href="/" target="_blank">Discord</a>
        <a href="https://github.com/leocastroz" target="_blank">Github</a>
        <a href="https://www.linkedin.com/in/leoscastro/" target="_blank">Linkedin</a>
        <a href="https://www.facebook.com/LeonardoCastro.Leoneell/" target="_blank">Facebook</a>
      </div>
    </div>
    <div v-if="show" class="pix" name="pix">
      <div class="qrcode">
        <div class="altenative-text">
          <h1>Are you sure about that ?</h1>
          <p>Remembering, you will be donating <span>your money.</span></p>
          <p><span>Thank</span> you for coming here!</p>
          <img v-if="true" src="../assets/qrcode.png" alt="">
          <p><span>Agency: </span> PicPay</p>
          <p><span>Recipient:</span> Leonardo Silva Castro</p>
        </div>   
      </div>
      <a class="close" v-on:click="show = !show">X</a>
    </div>
  </main>
</template>

<style scoped>



.pix{
  display: grid;
  align-items: center;
  justify-content: center;
  animation-duration: 1s;
  animation-name: slidein;
}

@keyframes slidein {
  0% {
    opacity: 0;
  }
  100% {
    opacity: 1;
  }
}

.altenative-text span{
  color: #43ff69;
}

.altenative-text{
  text-align: center;
  width: 400px;
}

.altenative-text h1{
  font-size: 30px;
  padding-bottom: 20px;
}

.altenative-text p{
  font-size: 16px;
  padding-bottom: 10px;
}

.altenative-text img{
  border-radius: 20px;
  padding: 15px 0 15px 0;
  width: 200px;
}


.pix a{
  cursor: pointer;
  background-color: #43ff69;
  color: #0f0f0f;
  padding: 8px 15px;
  border-radius: 5px;
  font-weight: bold;
  position: absolute;
  margin: 20px;
  right: 0;
  top: 0;
}

.pix{
  position: absolute;
  display: flex;
  width: 800px;
  height: 600px;
  background-color: #0f0f0f;
  border: 3px solid #7d7d7d;
  border-radius: 10px;
}

.container, .box, .coffee, .media{
  animation: fadeIn 5s;
}

@keyframes fadeIn {
  0% { opacity: 0; }
  100% { opacity: 1; }
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
  position: relative;
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
  display: flex;
  align-items: center;
  justify-content: center;
  margin-bottom: 80px;
  -webkit-animation: pulse 1s ease infinite;
  -moz-animation: pulse 1s ease infinite;
  -ms-animation: pulse 1s ease infinite;
  -o-animation: pulse 1s ease infinite;
  animation: pulse 1s ease infinite;
}


@-webkit-keyframes pulse {
  0% {
    -webkit-transform: scale(1);
  }
  25% {
    -webkit-transform: scale(1.1);
  }
  50% {
    -webkit-transform: scale(1);
  }
  100% {
    -webkit-transform: scale(1);
  }
}
@-moz-keyframes pulse {
  0% {
    -moz-transform: scale(1);
  }
  25% {
    -moz-transform: scale(1.1);
  }
  50% {
    -moz-transform: scale(1);
  }
  100% {
    -moz-transform: scale(1);
  }
}
@-ms-keyframes pulse {
  0% {
    -ms-transform: scale(1);
  }
  25% {
    -ms-transform: scale(1.1);
  }
  50% {
    -ms-transform: scale(1);
  }
  100% {
    -ms-transform: scale(1);
  }
}
@-o-keyframes pulse {
  
  0% { -o-transform: scale(1); }
  25% { -o-transform: scale(1.1); }
  50% { -o-transform: scale(1); }
  100% { -o-transform: scale(1); } 
}
@keyframes pulse { 
  0% {transform: scale(1);}
  50% {transform: scale(1.1);}
  100% {transform: scale(1);}
}

.donate img{
  border-radius: 10px;
  width: 200px;
}

.donate a{
  cursor: pointer;
  color: #000;
  font-weight: bold;
  text-decoration: none;
  -webkit-transition: all 0.4s;
  -moz-transition: all 0.4s;
  -o-transition: all 0.4s;
  transition: all 0.4s;
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