<template>
    <div id="main">
        <navbar/>
        <about/>
    </div>
</template>

<script>
import navbar from '~/components/navbar.vue'
import about from '~/components/about.vue'
import footerP from '~/components/footerP.vue'


export default {
    components: {
        navbar,
        about,

    }
}
</script>
<style>
 #main{
  max-width: 1200px;
  margin: 0 auto;
  
}

</style>
