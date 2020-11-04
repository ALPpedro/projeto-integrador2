<template>
<section>
  <h1 class="titulo">Página Produto</h1>
    <div class="column is-mobile">
      <card class="teste"
      v-for="(item, key) of items"
            :key="key"
        :title="item.nome"
        :imagem="item.img"
        :descricao="item.descricao"
        >
        <button>Comprar</button>
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
          img: '~/assets/img/tenis1.jpg',
          descricao: 'Indicado para: Dia a Dia'
        },
        {
          nome: 'ADIDAS NMD',
          img: '~/assets/img/tenis2.jpg',
          descricao: 'Indicado para: Dia a Dia  Categoria: Caminhada, Preço: R$:75,99'
        },
        {
          nome: 'NIKE AIR FORCE 1',
          img: '~/assets/img/tenis2.jpg',
          descricao: 'Indicado para: Dia a Dia  Material: Sintético Categoria: Caminhada Preço: R$:75,99'
        },
        {
          nome: 'ADIDAS SUPERSTAR',
          img: '~/assets/img/tenis2.jpg',
          descricao: 'Indicado para: Dia a Dia  Material: Sintético Categoria: Caminhada Preço: R$:75,99'
        },
        {
          nome: 'Space',
          img: '~/assets/img/tenis2.jpg',
          descricao: 'Indicado para: Dia a Dia  Material: Sintético Categoria: Caminhada Preço: R$:75,99'
        },
        {
          nome: 'Space',
          img: '~/assets/img/tenis2.jpg',
          descricao: 'Indicado para: Dia a Dia  Material: Sintético Categoria: Caminhada Preço: R$:75,99'
        },
        {
          nome: 'Space',
          img: '~/assets/img/tenis2.jpg',
          descricao: 'Indicado para: Dia a Dia  Material: Sintético Categoria: Caminhada Preço: R$:75,99'
        },
        {
          nome: 'Space',
          img: '~/assets/img/tenis2.jpg',
          descricao: 'Indicado para: Dia a Dia  Material: Sintético Categoria: Caminhada Preço: R$:75,99'
        },
        {
          nome: 'Space',
          img: '~/assets/img/tenis2.jpg',
          descricao: 'Indicado para: Dia a Dia  Material: Sintético Categoria: Caminhada Preço: R$:75,99'
        },
        {
          nome: 'Space',
          img: '~/assets/img/tenis2.jpg',
          descricao: 'Indicado para: Dia a Dia  Material: Sintético Categoria: Caminhada Preço: R$:75,99'
        },
        {
          nome: 'Space',
          img: '~/assets/img/tenis2.jpg',
          descricao: 'Indicado para: Dia a Dia  Material: Sintético Categoria: Caminhada Preço: R$:75,99'
        },
        {
          nome: 'Bot',
          img: '~/assets/img/tenis2.jpg',
          descricao: 'Indicado para: Dia a Dia  Material: Sintético Categoria: Caminhada Preço: R$:75,99'
        }
      ]
    }
  }

}
</script>

<style>
.titulo{
  display: flex;
  justify-content: center; 
  margin-top: 0.5rem;
  font-size: 50px;
}
.teste{
  display: flex;
  justify-content: center;
}

</style>