<template>
  <div id="footerP">
        <div class="google-maps">

        <iframe class="col-sm-12" src="http://maps.google.com/maps?q=27.990941,-82.697674&z=15&output=embed"></iframe>

        </div>

        <div id="footer">
        <h4>727-412-8053</h4>
        <h5>997 Main Street
            <br> Safety Harbor Florida 34695</h5>
        </div>
  </div>
</template>
<style>
#footer h4{
  color: black;
}
#footerP{
  padding-top: 100px;
  margin: 0 auto;
  text-align: center;
  font-size: 3em;
  color: red;
}
iframe{
  height: 500px;
}
.google-maps{
  max-width: 800px;
  margin: 0 auto;
}
</style>
<script>
export default {
  
}
</script>

