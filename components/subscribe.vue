<template>
  <b-container fluid>

    <div id="subscribe" class="row">
      <form name="contact" method="POST" netlify>


        <input type="email" name="email" placeholder="Enter Email to" />
            <br>

        <b-button type="submit" primary>Subscribe for Deals</b-button>

      </form>

    </div>
  </b-container>
</template>
<script>
  export default {

  }

</script>

<style scoped>
  #subscribe {
    padding: 5px;
    background-color: rgb(5, 75, 5);

  }

form{
    margin: 0 auto;
}
button{
    margin: 0 auto;
    width: 200px;
  

}
input{
    width: 200px;
    text-align: center;
}
   

</style>
