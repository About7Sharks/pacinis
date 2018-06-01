<template>
<div>
<navbar/>
<carousel/>
<about/>
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

<script>
import AppLogo from '~/components/AppLogo.vue'
import navbar from '~/components/navbar.vue'
import carousel from '~/components/carousel.vue'
import about from '~/pages/about.vue'


export default {
  components: {
    AppLogo,
    navbar,
    carousel,
    about

  }
}
</script>

<style>

</style>
