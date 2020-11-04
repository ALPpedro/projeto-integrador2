<template>
    <footer>
      <div class="rodape">
      <div class="organizar">
      <div class="texto">
        <p>CEARÁ CALÇADOS <br>
        agradecemos por sua<br> preferência,
        nos siga em <br>nossas redes sociais,<br> para
        ficar por dentro<br> de nossas novidades.
        </p>
      </div>
        
      <div class="teste">
        <h4> &nbsp; REDES SOCIAIS &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;</h4>
      
          <div class="social">
            <a href="https://www.facebook.com/cearacalcadosdedobradasp">
              <img src="~/assets/img/Logo.jpg" alt="facebook" srcset="">
              Facebook
            </a> 
            <a href="https://www.instagram.com/cearacalcados1/?hl=pt-br">
              <img src="~/assets/img/Logo.jpg" alt="instagram" srcset="">
              Instagram
            </a>
        </div>
      </div>
      <div class="contato">
           <p>
            CONTATO <br> Rua 21 de março, Nº542 <br> centro, Santa Ernestina <br> cearacalçados@gmail.com <br> 16 99170-5107 <br> 16 98236-2242 </p>


      </div>
      </div>
<<<<<<< HEAD
          <h4 class="direitos">© 2020 Direitos reservados: <a><nuxt-link 
           to="/"
           exact-active-class="is-active">
              &nbsp; Ceará Calçados
            </nuxt-link></a></h4>
=======
      </div>
          <h4 class="direitos">© 2020 Direitos reservados: <a> &nbsp; Ceará Calçados</a></h4>
>>>>>>> 1040c3e9427dc56655aebe4032069157e0929a06
    </footer>
</template>

<script>
export default {

}
</script>

<style scoped>
.organizar{  display: flex;
  justify-content: space-around;}
footer{
  width:100%;
  background-color: gray;
  margin-top: 50px;
}
footer .texto{
  display: flex;
  flex-direction: column;
  justify-content: center;
  color: white;
}
footer h1{
  display: flex;
  flex-direction: column;
  justify-content: center;
  padding-top: 20px;
  align-items:center;
  color: white;
}
footer p{
    border-left: lightgray solid 3px;
  color: white;
  padding-left:10px;
  margin-top: 30px;
}
footer .social img{
  display: flex;
  padding: 10px;
  width: 50px;
  height: 50px;
}
footer .social{
  display: flex;
  flex-direction: column;
}
.social a{
  display: flex;
  flex-direction: row;
  align-items: center;
  text-decoration: none;
  color: white;
}
.direitos{
  border-top: solid 3px lightgray;
  color: white;
  padding: 5px;
  display: flex;
  justify-content: center;
}
.direitos a{
  text-decoration: none;
  color: white;
}
.teste{
  border-left: lightgray solid 3px;
  margin-top: 30px;
  color: white;
  display: flex;
  flex-direction: column;
}
@media(max-width: 750px)
{
  .organizar{
    display: flex;
    flex-direction: column;
    align-items: center;
  }
  .teste{
    border-left: none;
  border-top: lightgray solid 3px;
  margin-top: 30px;
  color: white;
}
footer p{
   border-left: none;
    border-top: lightgray solid 3px;
  color: white;
  padding-left:10px;
  margin-top: 30px;
}
}
<<<<<<< HEAD
</style>
=======

@media(min-width:400px){
  footer.rodape{
    display: flex;
    flex-direction: column;
  }
footer.teste{
  border-top: lightgray solid 3px;
  border-bottom: lightgray solid 3px;
  margin-top: 30px;
  color: white;
  }
footer.texto{
  border-top: lightgray solid 3px;
  border-bottom: lightgray solid 3px;
  margin-top: 30px;
  color: white;
}
footer.contato{
  border-top: lightgray solid 3px;
  border-bottom: lightgray solid 3px;
  margin-top: 30px;
  color: white;
}
footer.direitos{
  border-top: lightgray solid 3px;
  margin-top: 30px;
  color: white;
}
}
@media(min-width:760px){
  footer.rodape{
    display: flex;
    flex-direction: row;
    justify-content: space-around;
  }
}
@media(min-width:1100){
  .organizar{  display: flex;
  justify-content: space-around;}
footer{
  width:100%;
  background-color: gray;
  margin-top: 50px;
}
footer .texto{
  display: flex;
  flex-direction: column;
  justify-content: center;
  color: white;
}
footer h1{
  display: flex;
  flex-direction: column;
  justify-content: center;
  padding-top: 20px;
  align-items:center;
  color: white;
}
footer p{
    border-left: lightgray solid 3px;
  color: white;
  padding-left:10px;
  margin-top: 30px;
}
footer .social img{
  display: flex;
  padding: 10px;
  width: 50px;
  height: 50px;
}
footer .social{
  display: flex;
  justify-content: center;
}
.direitos{
  border-top: solid 3px lightgray;
  color: white;
  padding: 5px;
  display: flex;
  justify-content: center;
}
.direitos a{
  text-decoration: none;
  color: white;
}
.teste{
  border-left: lightgray solid 3px;
  margin-top: 30px;
  color: white;
}
}
</style>
>>>>>>> 1040c3e9427dc56655aebe4032069157e0929a06
