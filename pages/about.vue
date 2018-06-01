<template>
    <div>
        <div id="panel1" class="row">
      <div id="text" class="col-sm-9">
        <h2>The Pacini Way</h2>
        <p>Over the past 25 years Pacinis has served authentic,delicious Italian cuisine throughout the Boston area. Our customers
          recognized our commitment to excellence by voting us their first choice in Italian Dining. We look forward to serving
          our new customers with the same commitment to excellence. Buon Appetito</p>
      </div>

      <div id="awards" class="col-sm-3">
        <b-img src="/award1.png" alt="" />
        <h6> Pacini's Regional Gold for Restaurant Takeout</h6>
        <b-img src="/award1.png" alt="" />
        <h6>Pacini's Regional Bronze for Pizza Place</h6>
        <b-img src="/award1.png" alt="" />
        <h6> Pacini's #1 Choice for Italian Restaurant</h6>
      </div>

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
#panel1{
    text-align: center;
}
</style>

