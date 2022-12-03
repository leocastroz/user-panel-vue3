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
          <img src="https://media-exp1.licdn.com/dms/image/C4D03AQEceEhxGvxNMg/profile-displayphoto-shrink_800_800/0/1633645176654?e=1675296000&v=beta&t=eMQSbTEnJZjrbCa2XylcCBbBE2Bo-mlfwMlOOPp_6_k" alt="">
          <div>
            <h3>Pablo Araújo</h3>
            <p>Desenvolvedor .NET | Vue</p>
          </div>
        </div>

        <div class="card-friend">
          <img src="https://media-exp1.licdn.com/dms/image/D5603AQGyAvKVqHW4KQ/profile-displayphoto-shrink_200_200/0/1670004070367?e=1675296000&v=beta&t=jvyIRHOIcqoL9JFjf_zTia5u9i-VTVTlVfqA0nrYAU4" alt="">
          <div>
            <h3>Adrian Knapp</h3>
            <p>Desenvolvedor React | TS</p>
          </div>
        </div>

        <div class="card-friend">
          <img src="https://felipecss.com/img/contact.2b6a9b5a.png" alt="">
          <div>
            <h3>Felipe Cosme</h3>
            <p>Desenvolvedor Vue | JS</p>
          </div>
        </div>

        <div class="card-friend">
          <img src="https://media-exp1.licdn.com/dms/image/D4D03AQEJjW8U-gkKlw/profile-displayphoto-shrink_800_800/0/1665437114281?e=1675296000&v=beta&t=Vt74Oej1LwShAR3HvRLhxczKcGIxtIdPev8ktchsRy4" alt="">
          <div>
            <h3>Samuel Pereira</h3>
            <p>Desenvolvedor Vue | TS</p>
          </div>
        </div>

        <div class="card-friend">
          <img src="https://media-exp1.licdn.com/dms/image/C4D03AQHESn2OZCAayA/profile-displayphoto-shrink_800_800/0/1658585129733?e=1675296000&v=beta&t=iJMcfSNuqV1NPPQyMXLntmkTQ1_m8rd5BYbuhSlSBlg" alt="">
          <div>
            <h3>Daywison Silva</h3>
            <p>Desenvolvedor React | Vue</p>
          </div>
        </div>

        <div class="card-friend">
          <img src="https://media-exp1.licdn.com/dms/image/D4D35AQEwgpfeQd967A/profile-framedphoto-shrink_800_800/0/1667334595812?e=1670655600&v=beta&t=-ZtvGSvAw5ewrNZCYeO7n-66BuLB7uG5IMQFcQiiaog" alt="">
          <div>
            <h3>Pedro Guilherme</h3>
            <p>Desenvolvedor React | TS</p>
          </div>
        </div>

        <div class="card-friend">
          <img src="https://media-exp1.licdn.com/dms/image/C4D03AQED73sDJy780A/profile-displayphoto-shrink_800_800/0/1651623140378?e=1675296000&v=beta&t=TVu30sob6p3E4L90slxj6Ga8wps5WYJKqS3KnDOYZ_s" alt="">
          <div>
            <h3>Vinicius Okamoto</h3>
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