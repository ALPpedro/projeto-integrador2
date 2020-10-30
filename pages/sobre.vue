<template>
<section class="section">
     <div class="titulo">
      <h1 class="Title is-1"> Sobre </h1>
    </div>
<div class="sobre">
  <div class="sobreI">
    <img src="~/assets/img/loja.PNG" alt="loja">
  </div>
  <div class="sobreT">
          <h2 class="card-title">Ceará Calçados</h2>
          <p class="card-text">A empresa Ceará calçados, fundada por Francisco das Chagas, começou com um pequeno centro comercial em 2004, sob venda de cintos, carteiras e relógios. Em certo ponto de seu desenvolvimento, houve um engrandecimento, passando a vender rasteiras, passando a ter um lucro maior para o aprimoramento de seus negócios comercializados, o que abriu portas para iniciar sua trajetória de conquistas. No ano de 2007, sua empresa foi aberta com sede em Dobrada, na rua Francisco Barbieri, tendo como referencia a Câmara Municipal, onde permaneceu até 2011, para que uma outra loja, com estabelecimento mais amplo, tivesse êxito maior. Atualmente, a empresa mais ampla encontra- se em Santa Ernestina, fazendo com que os clientes calcem a moda com estilo, oferecendo o melhor ao consumidor.</p>
  </div>
</div>

</section>
 
</template>

<script>
import Footer from '~/components/Footer'
export default {

}
</script>

<style>
.titulo{
  display: flex;
  justify-content: center; 
   margin-top: 0.5rem;
  font-size: 50px;
}
.sobreI img{
  width: 800px;
  height: 500px;
  padding: 10px;

}
.sobreI {
  display: flex;
  justify-content: center;
  align-items: center;
}
.sobreT{
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items:center;
  box-shadow: black 2px;
}
.sobreT h2{
  display: flex;
  align-items: center;
  justify-content:center;
  color: black;
  padding-top: 10px;
  padding-bottom: 20px;
}
.sobreT p{
  display: flex;
  align-items: center;
  justify-content: center;
  color: black;
  padding-left: 10px;
  width: 70%;
}
</style>