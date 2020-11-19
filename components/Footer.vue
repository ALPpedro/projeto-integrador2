<template>
    <footer>
      <div class="organizar">
      <div class="texto">
        <p>CEARÁ CALÇADOS <br>
        Agradecemos por sua preferência,
        sigam-nos em nossas redes sociais, para
        ficarem por dentro de nossas novidades.
        </p>
      </div>
        
      <div class="teste">
        <h4> &nbsp; REDES SOCIAIS &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;</h4>
      
          <div class="social">
            <a href="https://www.facebook.com/cearacalcadosdedobradasp">
              <img src="~/assets/img/FPRETO.png" alt="facebook" srcset="">
              Facebook
            </a> 
            <a href="https://www.instagram.com/cearacalcados1/?hl=pt-br">
              <img src="~/assets/img/IPRETO.png" alt="instagram" srcset="">
              Instagram
            </a>
        </div>
      </div>
      <div class="contato">
           <p>
            CONTATO <br> Rua 21 de março, Centro Nº542-Santa Ernestina cearacalçados@gmail.com 16 99170-5107 16 98236-2242 </p>


      </div>
      </div>
          <h4 class="direitos">© 2020 Direitos reservados: <a><nuxt-link 
           to="/"
           exact-active-class="is-active">
              &nbsp; Ceará Calçados
            </nuxt-link></a></h4>
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
.texto{
  display: flex;
  flex-direction: column;
  justify-content: center;
  color: white;
  width: 15%;
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
.contato{
  width: 15%;
}
@media(max-width: 750px)
{
  .organizar{
    display: flex;
    flex-direction: column; }
  .texto{
    width: 100%;
  }
  .contato{
    width: 100%;
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
</style>
