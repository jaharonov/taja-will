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
      <h1 class="text-left">TAJA WILL</h1>
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
      
   
    <footer class="pb-2">
      <br/>
      <b-container class="pb-2">
      <a href="https://www.facebook.com/motorcity.tapfest" target="_blank"><b-img :src="'./static/facebook.png'"/></a>
      <a href="https://www.instagram.com/motorcitytapfest/" target="_blank"><b-img :src="'./static/instagram.png'"/></a>
      <a href="https://twitter.com/motorcitytap" target="_blank"><b-img :src="'./static/twitter.png'"/></a>
      <br/>
      </b-container>
       <span>&copy;2018 Website by <a href="http://www.jaharonov.com" target="_blank">J Aharonov</a>.</span>
    </footer>
    <!-- </div> -->
    
    
  

  
</div>
</b-container>
  </html>
</template>

<style>
a:link {
  text-decoration: none;
}
h1, h2 {
  font-weight: normal;
}

ul {
  list-style-type: none;
  padding: 0;
}

li {
  display: inline-block;
  margin: 0 10px;
}

a {
  color: #42b983;
}

/* mouse over link */
a:hover {
  color: #3aa173;
}

/* selected link */
a:active {
  color: lightcoral;
}
</style>

<style>
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