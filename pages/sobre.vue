<template>
<section>
<div class="sobre">
    <img src="~/assets/img/loja.PNG" alt="loja">
    <div class="texto"><h2 class="card-title">Ceará Calçados</h2>
          <p class="card-text">A empresa Ceará calçados, fundada por Francisco das Chagas, começou com um pequeno centro comercial em 2004, sob venda de cintos, carteiras e relógios. Em certo ponto de seu desenvolvimento, houve um engrandecimento, passando a vender rasteiras, passando a ter um lucro maior para o aprimoramento de seus negócios comercializados, o que abriu portas para iniciar sua trajetória de conquistas. No ano de 2007, sua empresa foi aberta com sede em Dobrada, na rua Francisco Barbieri, tendo como referencia a Câmara Municipal, onde permaneceu até 2011, para que uma outra loja, com estabelecimento mais amplo, tivesse êxito maior. Atualmente, a empresa mais ampla encontra- se em Santa Ernestina, fazendo com que os clientes calcem a moda com estilo, oferecendo o melhor ao consumidor.</p>
</div>
          </div>

</section>
 
</template>

<script>
export default {

}
</script>

<style scoped>
.sobre{
  margin-top: 2rem;
}
.sobre img{
  width: 40%;
  height: 40%;
}
.texto{
  width: 30%;
  height: 40%;
  border: solid rgb(168, 168, 168);
  text-align: center;
}
.texto h2{
  margin-top: 2rem;
}
.texto p{
  margin: 2rem;
}
.sobre{
  display: flex;
  flex-direction: row;
  justify-content: space-around;
}
</style>
