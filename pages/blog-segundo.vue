<template>
    <section class="container">
        <h1>A nova coleção feminina da marca Jordan.</h1>

      <div class="teste">
      <p>Estampas ousadas de animais, tecidos suntuosos e cores ricas elevam a variedade, e cada peça é projetada com a intenção de ser colocada em camadas durante os meses mais frios. Continuando a reiterar um streetwear essencial para o dia a dia, a coleção é liderada pelo Faux Leather Flight Suit da Jordan Brand - uma peça única feita com materiais pesados ​​que tem um padrão em relevo allover e detalhes metálicos. Peças básicas (e marcantes) como a jaqueta de pele falsa da marca Jordan têm o objetivo de complementar um visual pronto para a rua e servir a um design conversível 2 em 1, permitindo a transformação de uma jaqueta longa para curta com um zíper rápido. </p>
      </div>

      <div class="grupo">
      <img src="~/assets/img/jordanf.jpg" alt="">
      </div>

      <div class="botoes">
          <n-link to="/blog-primeiro">
      <h2>Blog-1</h2>
          </n-link>
          <n-link to="/blog">
      <h2>Blogs</h2>
          </n-link>
      </div>
    </section>
</template>
<style scoped>
.container h1{
    display: flex;
    justify-content: center;
    color: black;
    font-size: 25px;
}
.container p{
    width: 500px;
    text-align: center;
}
.grupo{
        display: flex;
    justify-content: center;
}
.grupo img{    width: 500px;}
.teste{
    display: flex;
    justify-content: center;
}
.botoes{
    display: flex;
    margin-top: 50px;
    justify-content: space-around;
}
</style>