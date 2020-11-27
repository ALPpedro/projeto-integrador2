<template>
    <section class="container">
        <h1>Coleção CA</h1>
        <div class="teste">
        <p>Não é novidade o imprevisto que ocorreu esse ano, pela situação covid 2020, em que a demanda de diversos produtos, foram significativas,  inclusive calçados. Apesar das dificuldades que o mundo se encontra, o Ceará Calçados ofereceu a seus clientes, a melhor qualidade dos produtos e melhores atendimentos. Veja alguns exemplos da nossa coleção e as produções mais vendidas.</p>
</div>

      <h1>Nike 12 Molas</h1>
      <div class="grupo">
      <img src="~/assets/img/nike.jpg" alt="">
      <img src="~/assets/img/nikemolas.jpg" alt="">
      </div>

      <h1>Air Max 270</h1>
      <div class="grupo">
      <img src="~/assets/img/airmax.jpg" alt="">
      <img src="~/assets/img/airmax2.jpg" alt="">
      </div>
      <h1>Air Max Jordan</h1>

      <div class="grupo">
      <img src="~/assets/img/jordan.jpg" alt="">
      <img src="~/assets/img/jordan2.jpg" alt="">
      </div>
      <div class="teste">
      <p>Texturas e modelos dos produtos Nike, fazem da loja um verdadeiro sucesso, pois, a qualidade é excelente  e sua estética, considerada moderna, chama atenção de muitas pessoas. Vale ressaltar, também, seu uso, que é indicado em caminhadas, corridas e trilhas. Venham aproveitar as promoções que Ceará calçados oferece.</p>
      </div>
      <div class="botoes">
          <n-link to="/blog">
      <h2>Blogs</h2>
          </n-link>
          <n-link to="/blog-segundo">
      <h2>Blog-2</h2>
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
.grupo{
    display: flex;
    justify-content: center;
}
.grupo img{
    width: 250px;
}
.container p{
    width: 500px;
    text-align: center;
            color: black;
    font-size: 18px;
}
.teste{
    display: flex;
    justify-content: center;
}
.botoes{
    display: flex;
    margin-top: 50px;
    justify-content: space-around;
}
@media(max-width: 750px){
    .grupo img{
        display: flex;
    width: 45%;
    justify-content: space-around;
}
}
</style>