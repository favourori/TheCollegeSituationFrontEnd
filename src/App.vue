<template>
  <div id="app">
    <div id="nav " >
        <nav class="nav-color z-depth-0"  >
    <div class="nav-wrapper">
      <div class="container">
      <a href="#" class="brand-logo z-depth-0" style="font-weight: 100; font-size: 18px">
        <img src="@/assets/logo.png" width="210px" style="margin-top: 8px">
        
        </a>
      <ul id="nav-mobile" class="right hide-on-med-and-down">
        <li><a href="sass.html">blog</a></li>
        <li><a href="badges.html">login / signup</a></li>
        <li><a href="collapsible.html">Downoad App</a></li>
      </ul>
      </div>
    </div>
  </nav>
        
    
    </div>
    <router-view/>
  </div>
</template>

<style>
.nav-color{
  background: #243665
}

</style>
