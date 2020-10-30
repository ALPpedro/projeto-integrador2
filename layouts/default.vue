<template>
  <div>
    <nav
      class="navbar header is-expanded is-black"
      role="navigation"
      aria-label="main navigation"
    >
      <div class="navbar-brand">
         <img src="~/assets/img/Logo.jpg" alt="" width="50px" height="50px">
        <a class="centralizar navbar-item">
           <nuxt-link 
           to="/"
           exact-active-class="is-active">
              Ceará Calçados
            </nuxt-link>
        </a>
        <div class="navbar-burguer">
          <span/>
          <span/>
          <span/>
          <span/>
          <span/>
        </div>
        <a class="navbar-item"   v-for="(item, key) of items"
            :key="key">
            <nuxt-link
              :to="item.to"
              exact-active-class="is-active"
            >
              <b-icon :icon="item.icon" /> {{ item.title }}
            </nuxt-link>
        </a>
      </div>
    </nav>
     <div>
          <nuxt/>
       <Footer/>
        </div>

  </div>
</template>

<script>
import Footer from "~/components/Footer"
export default {
  data () {
    return {
      items: [
         {
          title: 'Produtos',
          icon: 'cart',
          to: { name: 'produto' }
        },

        {
          title: 'Sobre',
          icon: 'information',
          to: { name: 'sobre' }
        },

         {
          title: 'Blog',
          icon: 'blogger',
          to: { name: 'blog' }
        }
      ]
    }
  }
}
</script>
<style>
.navbar-brand{
  align-items: center;
}
.navbar{
  width: 100%;
  height: 70px;
}
</style>

