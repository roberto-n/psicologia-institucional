<template>
  <div class="hello">
    <nav class="nav">
      <img class="logo" src="../assets/psicologia.png" />
      <h4>Telefones:XXX-XXXXX<br>
        XXXXXXXXX
      </h4>
      <h4>CRP:XXXXX-XXXX</h4>
    </nav>
    <div class="principal" >
      <img class="foto" src="../assets/mulher.jpg" />
      <div>
        <h4> Nome:XXXXXXXX-XXXXXX</h4>
        <h2 class="titulo">Titulos:</h2>
        <h3>Formada em Psicologia Pela Universidade XXXXXXXXXXXX</h3>
        <h3>CRP:XXXXX-XXXX<br>
            pós-graduação em :Psicologia Clínica </h3>
        <h2>Abordagem:Cognitivo-Comportamental </h2>
      </div>
    </div>
    <div class="atendimentos">
      <h2 class="titulo">Tipos De Atendimento</h2><br>
        <h2  class="titulo">PSICODIAGNÓSTICO <br>
        PSICOTERAPIA DE CRIANÇAS, ADOLESCENTES E ADULTOS EM DIVERSAS MODALIDADES<br>
        ORIENTAÇÃO VOCACIONAL / PROFISSIONAL – individual e em grupo<br>
        ORIENTAÇÃO DE PAIS
      </h2>
    </div>
    <div class="contato">
      <div>
      <img class="foto" src="../assets/consutorio.jpg" />
      <h2>Endereço:XXXXXXXXXXX</h2>
      <h2>Forma de contato:<br>
        Email:XXXXXXXXXXX
        telefones:XXXXXXXXX<br>
        XXXXXXXXXXXXXX</h2>
      </div>
       <div>
         <h5>Deiche sua mensagem <br> eu entro em contato com você </h5>
        <form class="form">
        <label for="Nome">Nome:</label>
        <input type="text"  name="Nome" style="height: 25px;" ><br>
        <label for="Telefone">Telefone:</label>
        <input type="text"  name="Telefone" style="height: 25px;"><br>
        <label for="Mensagem">Mensagem:</label>
        <textarea name="Mensagem" rows="10" cols="50"></textarea> <br>
        <button type="button">Enviar</button>
        </form>
       </div>
       <img class="mapa" src="../assets/mapa.jpg" />
    </div>
    <div class="links">
      <h3 class="titulo">Links Externos</h3>
        <h3 class="titulo">:https://site.cfp.org.br/
        <br>https://www.crpsp.org/
        <br>https://transparencia.cfp.org.br/wp-content/uploads/sites/10/2005/05/Codigo-de-Etica-Profissional-do-Psicologo.pdf
      </h3>
    </div>
    <footer>criado por</footer>
  </div>
</template>

<script>
export default {
  name: "HelloWorld",
};
</script>


<style >
.hallo{
  width: 100%;
  height: 100%;
  padding:0;
  margin:0;
}
.nav {
  display: flex;
  justify-content: space-around;
  align-items: center;
  height: 50px;
  width: 100%;
  margin: 0px;
  background-color: blue;
}
.principal {
  display: flex;
  justify-content: space-around;
  border-style: solid;
  background-image: url('../assets/fundo4.jpg');
  background-repeat: no-repeat; 
  background-size: cover; 
}
.foto {
  height: 250px;
  width: 380px;
  margin:10px;
}
.contato {
  display: flex;
  border-style: solid;
  background-image: url('../assets/fundo2.jpg');
  background-repeat: no-repeat; 
  background-size: cover; 
  margin-left: -10px;
  height: 550px;
  width: 100%;
}
.form{
  color:white;
   height: 450px;
  width: 450px;
  font-size: 40px;
  
}
.mapa{
   height: 450px;
  width: 450px;
  margin: 20px;
}
.logo{
  height: 50px;
  
}
.atendimentos{
  background-color: rgb(172, 198, 247);
  margin: 0px;
}
.links{
  background-color: #40e0d0;
}
footer{
   color: white;
   background-color: rgb(15, 15, 87);
}
.titulo{
  padding:0;
  margin:0;
  font-size: 25px;
}
h2{
  margin-left: 10px;
}
h3{
  font-size: 25px;
  margin-left: 10px;
}
h4{
  font-size: 25px;
  margin-left: 10px;
}
h5{
  margin-left: 10px;
  font-size: 35px;
color: white;}
</style>
