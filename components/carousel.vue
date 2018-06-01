<template>
    <div id="carousel">
    <b-carousel controls indicators :interval="4000" style="text-shadow: 1px 1px 2px #333;">
      <b-carousel-slide img-src="/food3.jpg">
        <h2>
          Located On Main Street
        </h2>
      </b-carousel-slide>
      <b-carousel-slide img-src='/food2.jpg'>
        <h2>"Best food in Safety Harbor" -Steve</h2>
      </b-carousel-slide>
      <b-carousel-slide img-src='/food4.jpg'>
        <h2>Enter Email Below For special</h2>
      </b-carousel-slide>
    </b-carousel>
   </div>
</template>
<script>
export default {
    
}
</script>
<style>
#carousel img{
    max-height: 50vh;

}
</style>
