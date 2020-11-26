<template>
  <div>
    <template>
    <b-navbar>
        <template slot="brand">
                <img
                    src="~/assets/img/Logo.jpg"
                    width="70px" height="70px"
                >
        </template>
        <template slot="start">
            <b-navbar-item v-for="(item, key) of items"
            :key="key">
            <nuxt-link class="nuxt"
              :to="item.to"
            >
              <b-icon :icon="item.icon" /> {{ item.title }}
            </nuxt-link>
            </b-navbar-item>
        </template>

    </b-navbar>
    </template>
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

