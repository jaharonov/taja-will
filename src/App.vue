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
    <b-navbar variant="transparent" toggleable="xl">
    <b-navbar-brand class="mb-0"><h1>TAJA WILL</h1></b-navbar-brand>
  </b-navbar>
    <!-- <b-navbar toggleable="xl" variant="transparent"> -->
  
  <!-- <b-navbar-toggle target="nav_collapse" class="nav-items" id="menu">MENU</b-navbar-toggle> -->
  <!-- <b-navbar-brand href="#" class="mb-5" id="h1-name">Motor City Tap Fest</b-navbar-brand> -->
  <!-- <b-navbar-toggle target="nav_collapse" variant="dark" class="nav-items ml-auto"></b-navbar-toggle>
  <b-collapse is-nav id="nav_collapse">

   
    <b-navbar-nav class="ml-auto m-0">
      <b-nav-item class="nav-items" v-bind:to="'locaccom'">LOCATION +<br/> ACCOMMODATIONS</b-nav-item>
      <b-nav-item class="nav-items" v-bind:to="'faculty'">FACULTY</b-nav-item>
      <b-nav-item class="nav-items" v-bind:to="'mcsoles'">MOTOR CITY<br/>SOLES</b-nav-item>
      <b-nav-item class="nav-items" v-bind:to="'chorchal'">MCTF CHOREOGRAPHER'S<br/>CHALLENGE</b-nav-item>
      <b-nav-item class="nav-items" v-bind:to="'partshowcase'">PARTICIPANTS<br/>SHOWCASE</b-nav-item>
      <b-nav-item class="nav-items" v-bind:to="'auditions'">AUDITIONS</b-nav-item>
      <b-nav-item class="nav-items" v-bind:to="'scholarships'">SCHOLARSHIPS</b-nav-item>
      <b-nav-item class="nav-items" v-bind:to="'store'">STORE</b-nav-item>
      <b-nav-item class="nav-items" v-bind:to="'about'">ABOUT +<br/>CONTACT</b-nav-item>
      
    </b-navbar-nav>

  </b-collapse>
</b-navbar> -->
  <!-- As a heading -->
  <!-- <b-navbar variant="transparent" toggleable="xl">
    <b-navbar-brand class="mb-0"><h1>TAJA WILL</h1></b-navbar-brand>
  </b-navbar>

<b-navbar toggleable="xl" variant="transparent">

  <b-navbar-toggle target="nav_collapse"></b-navbar-toggle>

  <b-collapse is-nav id="nav_collapse" variant="dark">

  
    <b-dropdown-item>First Action</b-dropdown-item>
    <b-dropdown-item>Second Action</b-dropdown-item>
    <b-dropdown-item>Third Action</b-dropdown-item>
    <b-dropdown-divider></b-dropdown-divider>
    <b-dropdown-item>Something else here...</b-dropdown-item>
    <b-dropdown-item disabled>Disabled action</b-dropdown-item>
  
    <b-navbar-nav class="ml-auto">

      <b-nav-form>
        <b-form-input size="sm" class="mr-sm-2" type="text" placeholder="Search"/>
        <b-button size="sm" class="my-2 my-sm-0" type="submit">Search</b-button>
      </b-nav-form>

      <b-nav-item-dropdown text="Lang" right>
        <b-dropdown-item href="#">EN</b-dropdown-item>
        <b-dropdown-item href="#">ES</b-dropdown-item>
        <b-dropdown-item href="#">RU</b-dropdown-item>
        <b-dropdown-item href="#">FA</b-dropdown-item>
      </b-nav-item-dropdown>

      <b-nav-item-dropdown right>
        
        <template slot="button-content">
          <em>User</em>
        </template>
        <b-dropdown-item href="#">Profile</b-dropdown-item>
        <b-dropdown-item href="#">Signout</b-dropdown-item>
      </b-nav-item-dropdown>
    </b-navbar-nav>

  </b-collapse>
</b-navbar> -->
  
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
        <a href="https://vimeo.com/user4594927" class="green" target="_blank"><b-img src="/static/vimeo-24.png"/></a>
        <a href="mailto:tajawill@gmail.com" class="green" target="_blank"><b-img src="/static/email-12-24.png"/></a>
        <a href="https://www.instagram.com/tajawillxo/" class="green" target="_blank"><b-img src="/static/instagram-5-24.png"/></a>
      </div>
      <br/>

       <span>&copy;2018 Website by <a href="http://www.jaharonov.com" class="green" target="_blank">J Aharonov</a>.</span>
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