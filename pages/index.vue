<template>
<section>
    <div class="video">
      <video controls>
       <source src="~/assets/video/video.mp4" type="video/mp4">
     </video>
     </div>
     <div class="column is-mobile">
           <card class="teste"
      v-for="(item, key) of items"
            :key="key"
        :title="item.nome"
        :imagem="item.img"
        :descricao="item.descricao"
        >
      </card>
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
  },
  data(){
    return{
      items:[
         {
          nome: 'Nike',
          img: require('~/assets/img/tenis1.jpg'),
          descricao: 'Indicado para: Dia a Dia    Categoria: Caminhada, Trilha Preço: R$ 75,99'
        },
        {
          nome: 'Space',
          img:require('~/assets/img/tenis1.jpg'),
          descricao: 'Indicado para: Dia a Dia    Categoria: Caminhada, Trilha Preço: R$ 75,99'
        },
        {
          nome: 'Space',
          img: require('~/assets/img/tenis2.jpg'),
          descricao: 'Indicado para: Dia a Dia    Categoria: Caminhada, Trilha Preço: R$ 75,99'
        },
        {
          nome: 'Bot',
          img: require('~/assets/img/tenis6.jpg'),
          descricao: 'Indicado para: Dia a Dia    Categoria: Caminhada, Trilha Preço: R$ 75,99'
        }
      ]
    }
  }
}
</script>
<style scoped>
.video{
  display: flex;
  justify-content: center;
  margin-top: 2rem;
}
.teste{
  display: flex;
  justify-content: center;
}
</style>