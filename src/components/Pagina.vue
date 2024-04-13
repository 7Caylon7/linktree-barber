<template>
  <div class="page">
    <nav class="navbar">
      <div class="logo">
        <img src="../assets/cilindro.png" alt="ilustração de cilindro de barbearia">
        <div class="text-logo">
          <h1 style="font-size: 150px;">JP</h1>
          <p style="font-size: 50px;">BARBEARIA</p>
        </div>
        <img src="../assets/cilindro.png" alt="ilustração de cilindro de barbearia">
      </div>
      <p style="font-size: 25px;">EST - 1997</p>
    </nav>
    <main class="conteudo">
      <div class="contato">
        <h3>Contato:</h3>
        <button><a href="https://api.whatsapp.com/message/VN4QR33RKZ2ID1?autoload=1&app_absent=0" target="_blank"><span class="pi pi-whatsapp" style="font-size: 1.5rem;"><strong style="font-family: Pirata; font-size: 30px;"> Whatsapp</strong></span></a></button>
        <button><a href="https://www.instagram.com/jpbarbeiro10" target="_blank"><span class="pi pi-instagram" style="font-size: 1.5rem;"><strong style="font-family: Pirata; font-size: 30px;"> Instagram</strong></span></a></button>
        <!-- <button><a href="#" target="_blank"><span class="pi pi-facebook" style="font-size: 1.5rem;"><strong style="font-family: Pirata; font-size: 30px;"> Facebook</strong></span></a></button> -->
        <button><a href="https://maps.app.goo.gl/2TfigiAguhqiWvrFA" target="_blank"><span class="pi pi-map-marker" style="font-size: 1.5rem;"><strong style="font-family: Pirata; font-size: 30px;"> Endereço</strong></span></a></button>
      </div>
      <div class="planos">
        <h3>Pacotes:</h3>
        <p>Em breve...</p>
      </div>
    </main>

    <footer class="footer">
      <h3 style="font-size: 20px;">₢ 2024 - Caylon Solon</h3>
      <p>Todos os direitos reservados</p>
    </footer>
    
  </div>
</template>

<script>
export default {
  name: 'PaginaOne'
}
</script>

<style scoped>
@font-face {
  font-family: DirtyCrown;
  src: url('../assets/DirtyCrown.ttf')format('truetype');
}

@font-face {
  font-family: Pirata;
  src: url('../assets/PirataOne-Regular.ttf')format('truetype');
}


.navbar{
  font-family: DirtyCrown;
  color: #fff;
  background: #292727;
  display: flex;
  flex-direction: column;
  align-items: center;
  padding: 30px 0;
  border-bottom-left-radius: 16px;
  border-bottom-right-radius: 16px;
}

.logo{
  display: flex;
  flex-direction: row;
  text-align: center;
  align-items: center;
  gap: 10px;
}

.logo img{
  max-width: 70px
}

.conteudo{
  display: flex;
  flex-direction: column;
  flex-wrap: wrap;
  gap: 20px;
  align-items: center;
  text-align: center;
  margin: 10px 400px;
  padding: 50px 0;
  color: #fff;
  background: rgba(57, 57, 57, 0.56);
  border-radius: 8px;
  box-shadow: 0 4px 30px rgba(0, 0, 0, 0.1);
  backdrop-filter: blur(5.1px);
  -webkit-backdrop-filter: blur(5.1px);
  font-family: Pirata;
  font-size: 40px;
}

.contato {
  display: flex;
  flex-direction: column;
  gap: 10px;
}

.contato button{
  padding: 15px 90px;
  border-radius: 8px;
  border: none;
  transition: transform 0.5s ease-out;
}

.contato button:hover{
  transform: scale(1.2);
  background: #292727;
  box-shadow: 0 4px 30px rgba(0, 0, 0, 0.1);
  backdrop-filter: blur(0px);
  -webkit-backdrop-filter: blur(0px);
  
}

.contato a{
  color: #292727;
}

.contato a:hover{
  color: #fff;
}


.footer{
  color: #fff;
  background: #292727;
  display: flex;
  flex-direction: column;
  align-items: center;
  padding: 30px 0;
  border-top-left-radius: 16px;
  border-top-right-radius: 16px;
}

@media screen and (min-width: 300px) and (max-width: 1200px){
.conteudo{
  margin: 10px 0;
}

.contato button{
  background: #292727;
}

.contato a{
  color: #fff;
}


}


</style>
