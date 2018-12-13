<template>
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">
    <link href="https://fonts.googleapis.com/css?family=Viga" rel="stylesheet">
    <link href="https://fonts.googleapis.com/css?family=Roboto+Condensed" rel="stylesheet">

  </head>
  <b-container class="p-5">
  <div id="app" variant="transparent">
    <div class="fixed-top p-2">
    <header>
      <b-navbar toggleable="md" variant="transparent">

  <b-navbar-toggle target="nav_collapse"></b-navbar-toggle>

  <b-navbar-brand href="#"><h1>TAJA WILL</h1></b-navbar-brand>

  <b-collapse is-nav id="nav_collapse">

    <b-navbar-nav>
      <b-nav-item href="#">Link</b-nav-item>
      <b-nav-item href="#" disabled>Disabled</b-nav-item>
    </b-navbar-nav>

    <!-- Right aligned nav items -->
    <b-navbar-nav class="ml-auto">

      <b-nav-item-dropdown text="Lang" right>
        <b-dropdown-item href="#">EN</b-dropdown-item>
        <b-dropdown-item href="#">ES</b-dropdown-item>
        <b-dropdown-item href="#">RU</b-dropdown-item>
        <b-dropdown-item href="#">FA</b-dropdown-item>
      </b-nav-item-dropdown>

      <b-nav-item-dropdown right>
        <!-- Using button-content slot -->
        <b-dropdown-item href="#">Profile</b-dropdown-item>
        <b-dropdown-item href="#">Signout</b-dropdown-item>
      </b-nav-item-dropdown>
    </b-navbar-nav>

  </b-collapse>
</b-navbar>
      <!-- <h1 class="text-left">TAJA WILL</h1>
      <span class="float-right">
  <b-btn v-b-toggle.collapse1 variant="primary">Toggle Collapse</b-btn>
  <b-collapse id="collapse1" class="mt-2">
    <b-card>
      <p class="card-text">Collapse contents Here</p>
      <b-btn v-b-toggle.collapse1_inner size="sm">Toggle Inner Collapse</b-btn>
      <b-collapse id=collapse1_inner class="mt-2">
        <b-card>Hello!</b-card>
      </b-collapse>
    </b-card>
  </b-collapse>
</span> -->
    </header>
<div class="row">
<div class="col-3">

   </div>
   <div class="col-3">
         
   </div>
   </div>
 </div>  
 <div class="row p-5"></div>
   
<!-- navbar-1.vue -->
    <router-view></router-view>
    
      <!-- <div class="row fixed-bottom"> -->
      
   
    <footer class="p-2">
      <div class="float-center">
        <a href="https://vimeo.com/user4594927" target="_blank"><b-img src="/static/vimeo-24.png"/></a>
        <a href="mailto:tajawill@gmail.com" target="_blank"><b-img src="/static/email-12-24.png"/></a>
        <a href="https://www.instagram.com/tajawillxo/" target="_blank"><b-img src="/static/instagram-5-24.png"/></a>
      </div>
      <br/>

       <span>&copy;2018 Website by <a href="http://www.jaharonov.com" target="_blank">J Aharonov</a>.</span>
    </footer>
    <!-- </div> -->
    
    
  

  
</div>
</b-container>
  </html>
</template>

<style lang="scss">

a:link {
  text-decoration: none;
}
h1, h2 {
  font-weight: normal;
  color: #2c3e50;
}

ul {
  list-style-type: none;
  padding: 0;
}

li {
  display: inline-block;
  margin: 0 10px;
}

/* a {
  color: #42b983;
}

a:hover {
  color: #3aa173;
}

a:active {
  color: lightcoral;
} */

body {
  margin: 0;
}
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  position: relative;
}
@import './styles/custom-bootstrap.scss';
@import '../node_modules/bootstrap/scss/bootstrap.scss';
</style>

<script type="javascript">
export default {
  name: 'app',
  images: [
        { src: './static/twitter.png', alt: 'Twitter logo' },
        { src: './static/instagram.png', alt: 'Instagram logo' },
        { src: './static/facebook.png', alt: 'Facebook logo' }
  ],
  methods: {
    reload: function() {    
       console.log('what is it loading?')
    }
  }
}
</script>