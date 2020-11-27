<template>
<section>
  <div class="blog">
    <div class="column">
       <n-link to="/blog-primeiro">
        <div class="card">
      <header class="card-header">
        <p class="card-header-title has-text-grey">
         Coleção CA.
        </p>
      </header>
      <div class="card-content">
        <div class="card-content-item" >
          Não é novidade o imprevisto que ocorreu esse ano, pela situação covid 2020...
        </div>

      </div>
      <footer class="card-footer">
        <div class="card-footer-item">
          <p class="descricao">Autor: Gutavo Telles</p>
        </div>
      </footer>
    </div>
  </n-link>
   <n-link to="/blog-segundo">
     <div class="card">
      <header class="card-header">
        <p class="card-header-title has-text-grey">
          A nova coleção feminina da marca Jordan.
        </p>
      </header>
      <div class="card-content">
        <div class="card-content-item" >
         A coleção Court to Runway Holiday 2020 da Jordan Brand reinterpreta esportes autênticos com tecidos luxuosos...
        </div>

      </div>

      <footer class="card-footer">
        <div class="card-footer-item">
          <p class="descricao">Autor: Site da Nike</p>
        </div>
      

      </footer>

      
    </div>
    </n-link>
    </div>
  </div>
  </section>
</template>

<script>
import Footer from '~/components/Footer'
export default {

}
</script>

<style scoped>

.column{
  margin-top: 50px;
  display: flex;
  justify-content: space-around;

}

</style>
