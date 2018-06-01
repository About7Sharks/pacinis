<template>

    
    <div id="main">
        <navbar/>
        <div id="cMenu">
        <b-img src="/menu1.jpg" fluid></b-img>
        <b-img src="/menu2.jpg" fluid></b-img>
        <b-img src="/menu3.jpg" fluid></b-img>
</div>
    </div>
</template>
<script>
import navbar from '~/components/navbar.vue'

export default {
    components:{
        navbar
    }
}
</script>
<style>

 #main{
  max-width: 1200px;
  margin: 0 auto;
}
#cMenu .img-fluid{
width: 100vw;
image-rendering: auto;
  image-rendering: crisp-edges;
    margin: 0 auto;
   
    
}
</style>
