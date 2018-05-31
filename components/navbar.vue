<template>
  <b-navbar class="row" toggleable="lg">

    <b-navbar-toggle target="nav_collapse"></b-navbar-toggle>

    <b-navbar-brand class="col-sm-7" to="/pacinis"><div id="header"><div id="paciniH">Pacini's</div>  Italian Bar and Grill</div></b-navbar-brand>

    <b-collapse is-nav id="nav_collapse">





        <b-navbar-nav>
          <b-nav-item to="/About">About</b-nav-item>

   <b-nav-item to="/location">Location</b-nav-item>

          <b-nav-item-dropdown text="Menus">
            <b-nav-item to="/Menu">Main Menu</b-nav-item>
            <b-nav-item to="/dailySpecials">Daily Specials</b-nav-item>
            <b-nav-item to="/bar">Open Bar</b-nav-item>
            <b-nav-item to="/desserts">Desserts</b-nav-item>
            <b-nav-item to="/kidsMenu">Kids Menu</b-nav-item>
          </b-nav-item-dropdown>


       
        </b-navbar-nav>


   

    </b-collapse>
  </b-navbar>
</template>
<script>
  export default {

  }

</script>
<style >
@import url('https://fonts.googleapis.com/css?family=Italianno|Open+Sans');
  .navbar {
    background-color: rgb(255, 255, 255);
    margin: 0 auto;
    padding-right: 100px;
  }

  .nav-link {
    font-size: 2em;
    border-radius: 10px;
  }

  .navbar-brand {
    font-size: 3.5em;
  }
.nav-item{
    padding: 15px;
}
#header{
    color: rgb(170, 30, 30);
    font-family: 'Italianno', cursive;
    -webkit-font-smoothing: antialiased;
    
}
#paciniH{
    color: black;
    font-size: 1.3em;
    display: inline-flex;
}
@media only screen and (max-width: 740px) {
    .navbar {
        font-size: 0.55em;
    }
}
</style>
