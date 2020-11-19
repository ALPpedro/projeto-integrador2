<template>
  <div>
    <nav class="navbar is-black" role="navigation" aria-label="main navigation">
  <div class="navbar-brand">
    <a class="navbar-item" href="">
      <img src="~/assets/img/Logo.jpg" width="50" height="50">
       <nuxt-link 
           to="/"
           exact-active-class="is-active">
              Ceará Calçados
            </nuxt-link>
    </a>

    <a role="button" class="navbar-burger burger" aria-label="menu" aria-expanded="false" data-target="navbarBasicExample">
      <span aria-hidden="true"></span>
      <span aria-hidden="true"></span>
      <span aria-hidden="true"></span>
    </a>
  </div>

  <div id="navbarBasicExample" class="navbar-menu">
    <div class="navbar-start">
      <a class="navbar-item"   v-for="(item, key) of items"
            :key="key">
            <nuxt-link
              :to="item.to"
            >
              <b-icon :icon="item.icon" /> {{ item.title }}
            </nuxt-link>
        </a>
      </div>
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

