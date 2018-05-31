<template>
  <b-navbar class="row" toggleable="md">

    <b-navbar-toggle target="nav_collapse"></b-navbar-toggle>

    <b-navbar-brand class="col-sm-6" to="/pacinis">Pacini's Italian Bar and Grill</b-navbar-brand>

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
<style>
  .navbar {
    background-color: rgba(93, 165, 26, 0.295);
  }

  .nav-link {
    font-size: 2em;
    border-radius: 10px;
  }

  .navbar-brand {
    font-size: 3em;
  }
.nav-item{
    padding: 15px;
}
</style>
