<template>
  <div class="column">
    <div class="card">
      <header class="card-header">
        <p class="card-header-title has-text-grey">
          {{ title }}
        </p>
      </header>
      <div class="card-content">
        <div class="card-content-item" >
          <img :src="imagem"  height="100px" width="250px">
        </div>

      </div>

      <footer class="card-footer">
        <div class="card-footer-item">
          <p class="descricao">{{ descricao }}</p>
        </div>

      </footer>
      <div class="button">
      Comprar
      </div>

      
    </div>
  </div>
</template>

<script>
export default {
  props: {
    title: {
      type: String,
      required: true
    },
    imagem:{
      type: String,
      required: true
    },
    descricao:{
      type: String,
      required: true
    },
  }
}
</script>
<style>
.column{
  display: flex;
  flex-wrap: wrap;
  width: 400;

  }
  .button{
    display: flex;
    justify-content: center;
    background: rgb(2, 226, 2);
    color: black;
    font-size: 18px;
  }
.card{
  width: 250px;
  height: 100%;
}
.descricao{
  color: black;
}

</style>
