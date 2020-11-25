<template>
<section>
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
import Card from '~/components/Card'
export default {
  name: 'Produto',
  components:{
    Card,
  },
  data(){
    return{
      items:[
         {
          nome: 'Nike',
          img: require('~/assets/img/tenis1.jpg'),
          descricao: 'Indicado para: Dia a Dia  Categoria: Caminhada, Trilha Preço: R$:75,99'
        },
        {
          nome: 'ADIDAS NMD',
          img: require('~/assets/img/tenis2.jpg'),
          descricao: 'Indicado para: Dia a Dia    Categoria: Caminhada, Trilha Preço: R$:75,99'
        },
        {
          nome: 'NIKE AIR FORCE 1',
          img:require('~/assets/img/tenis3.jpg'),
          descricao: 'Indicado para: Dia a Dia    Categoria: Caminhada, Trilha Preço: R$:75,99'
        },
        {
          nome: 'ADIDAS SUPERSTAR',
          img: require('~/assets/img/tenis4.jpg'),
          descricao: 'Indicado para: Dia a Dia    Categoria: Caminhada, Trilha Preço: R$:75,99'
        },
        {
          nome: 'Space',
          img: require('~/assets/img/tenis5.jpg'),
          descricao: 'Indicado para: Dia a Dia    Categoria: Caminhada, Trilha Preço: R$:75,99'
        },
        {
          nome: 'Space',
          img: require('~/assets/img/tenis6.jpg'),
          descricao: 'Indicado para: Dia a Dia    Categoria: Caminhada, Trilha Preço: R$:75,99'
        },
        {
          nome: 'Space',
          img: require('~/assets/img/tenis1.jpg'),
          descricao: 'Indicado para: Dia a Dia    Categoria: Caminhada, Trilha Preço: R$:75,99'
        },
        {
          nome: 'Space',
          img: require('~/assets/img/tenis2.jpg'),
          descricao: 'Indicado para: Dia a Dia    Categoria: Caminhada, Trilha Preço: R$:75,99'
        },
        {
          nome: 'Space',
          img: require('~/assets/img/tenis3.jpg'),
          descricao: 'Indicado para: Dia a Dia    Categoria: Caminhada, Trilha Preço: R$:75,99'
        },
        {
          nome: 'Space',
          img: require('~/assets/img/tenis4.jpg'),
          descricao: 'Indicado para: Dia a Dia    Categoria: Caminhada, Trilha Preço: R$:75,99'
        },
        {
          nome: 'Space',
          img: require('~/assets/img/tenis5.jpg'),
          descricao: 'Indicado para: Dia a Dia    Categoria: Caminhada, Trilha Preço: R$:75,99'
        },
        {
          nome: 'Bot',
          img: require('~/assets/img/tenis6.jpg'),
          descricao: 'Indicado para: Dia a Dia    Categoria: Caminhada, Trilha Preço: R$:75,99'
        }
      ]
    }
  }

}
</script>

<style>
.teste{
  display: flex;
  justify-content: center;
}

</style>