<template>
<section>
  <h1 class="titulo">Página Inicial</h1>
  <div class="filme"><iframe class="video" src="https://www.youtube.com/embed/YE7VzlLtp-4?showinfo=0" frameborder="0" allowfullscreen></iframe>
</div>
  </section>

</template>

<script>
import Footer from '~/components/Footer'
import Card from '~/components/Card'

export default {
  name: 'HomePage',

  components: {
    Card,
    Footer
  }
}
</script>
<style scoped>

.titulo{
  display: flex;
  justify-content: center; 
  margin-top: 0.5rem;
  font-size: 50px;

}
.video{
  width: 600px;
  height: 300px;
}
.filme{
  display: flex;
  justify-content: center;
}
</style>