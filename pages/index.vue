<template>
    <div>
        <p>前端技术博客</p>
          <ul>
            <li><nuxt-link :to="{name:'index'}">HOME</nuxt-link></li>
            <li><nuxt-link :to="{name:'about'}">ABOUT</nuxt-link></li>
            <li><nuxt-link :to="{name:'news',params:{newsID:1}}">NEWS</nuxt-link></li>
            <li><nuxt-link :to="{name:'asyncData'}">asyncData</nuxt-link></li>
        </ul>
        <div>
          <img src="~static/images/1.jpg" alt="">
        </div>
    </div>
</template>

<script>
import AppLogo from "~/components/AppLogo.vue";
// import jQuery from'~/static/lib/js/jquery-1.11.2.min.js'
// import '~/static/lib/js/pageswitch'
export default {
  components: {
    AppLogo
  },

};
</script>

