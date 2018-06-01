<template>
    <div id="main">
        <navbar/>
        <h2>Find us in Downtown Safety Harbor</h2>
        <footerP/> 
    </div>
</template>
<script>
import footerP from '~/components/footerP.vue'
import navbar from '~/components/navbar.vue'

export default {
   components:{
       footerP,
       navbar
   }
}
</script>
<style scoped>
 #main{
  max-width: 1200px;
  margin: 0 auto;
}
h2{
    text-align: center;
    font-size: 3em;
    padding-top: 25px;
}
</style>
