<template>
  <div>
    <nav class="navbar is-tomato" role="navigation" aria-label="main navigation">
  <div class="navbar-brand">

    <a role="button" class="navbar-burger burger" aria-label="menu" aria-expanded="false" data-target="navbarBasicExample">
      <span aria-hidden="true"></span>
      <span aria-hidden="true"></span>
      <span aria-hidden="true"></span>
    </a>
  </div>

  <div class="navbar-menu">
    <div class="navbar-start">
       <img src="~/assets/img/Logo.jpg" width="100px" height="200px">
      <a class="navbar-item"   v-for="(item, key) of items"
            :key="key">
            <nuxt-link class="nuxt"
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
          title: 'Ceará Calçados',
          icon: 'home',
          to: { name: 'index' }
        },
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
  background-color: black;
}
#paginas{
  text-decoration-color: white;
  color: white;
}
.nuxt{
  color: rgb(247, 49, 0);
}
</style>

