<template>
    <section class="container">
        <h1>Coleção CA</h1>
        <div class="teste">
        <p>Não é novidade nenhuma o quão conturbado foi este ano de 2020, que a demanda de vários produtos foi alta, inclusive os sapatos, tênis etc.
Apesar das dificuldades, a CA se saiu bem e ofereceu a máxima qualidade como sempre. Veja alguns exemplos da nossa coleção e maiores vendas:
</p>
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
      <p>Ambas linhas e modelos fizeram muito sucesso por causa da sua qualidade, inegável, e sua estética, considerados um dos mais bonitos produzidos pela Nike. Vale ressaltar também seu uso, que podem ser usados para caminhar, sair e até mesmo correr, claro, que com cuidado do mesmo. Venham aproveitar as promoções das nossas lojas de calçados, inclusive essas duas belezinhas acima.</p>
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