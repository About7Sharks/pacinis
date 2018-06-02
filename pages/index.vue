<template>
<div id="main">
  <navbar/>
  <carousel/>
  <about/>
  <footerP/>
</div>
</template>

<script>
import AppLogo from '~/components/AppLogo.vue'
import navbar from '~/components/navbar.vue'
import carousel from '~/components/carousel.vue'
import about from '~/components/about.vue'
import footerP from '~/components/footerP.vue'


export default {
  
    components: {
    AppLogo,
    navbar,
    carousel,
    about,
    footerP

  }
 
}
</script>

<style>

#main{
  max-width: 1200px;
  margin: 0 auto;
  box-shadow:  0 10px 6px 6px -6px #777; 
  -webkit-box-shadow:  0 10px 6px 6px -6px #777;
  -moz-box-shadow:  0 10px 6px 6px -6px #777;
  text-shadow: 1px 1px 2px #333;


}
</style>
