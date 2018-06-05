<template>


  <div id="main">
    <navbar/>
    <b-container>
      <div class="row">
            <b-col col="8">Pizza Type</b-col>
            <b-col col="1">Medium</b-col>
            <b-col col="1">Large</b-col>
      </div>
        <div class="row">
               <b-col col="8">Mediterranean <br> Spinach, Mushrooms, olives, scallions, geta, ricotta, Parmeasan and Mozzerella cheeses and fresh spices</b-col>
            <b-col col="1">$12.95</b-col>
            <b-col col="1">$16.95</b-col>

      </div>
  
    </b-container>

    <b-container fluid>


      <div id="cMenu">
        <b-img src="/menu1.jpg" fluid></b-img>
        <b-img src="/menu2.jpg" fluid></b-img>
        <b-img src="/menu3.jpg" fluid></b-img>
      </div>
    </b-container>



  </div>




</template>
<script>
  import navbar from '~/components/navbar.vue'

  export default {
    components: {
      navbar
    }
  }

</script>
<style>
  #main {
    max-width: 1200px;
    margin: 0 auto;
  }

  #cMenu .img-fluid {
    width: 100vw;
    image-rendering: auto;
    image-rendering: crisp-edges;
    margin: 0 auto;


  }

  #pizza {
    text-align: center;
  }

</style>
