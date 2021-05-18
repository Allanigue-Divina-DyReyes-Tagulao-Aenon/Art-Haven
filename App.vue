// App.vue

<template>
  <div id="app" class="container">
    <nav class="navbar navbar-expand-sm bg-light">
      <ul class="navbar-nav">
        <li class="nav-item">
          <router-link :to="{ name: 'Create' }" class="nav-link">Traditional Arts</router-link>
        </li>
        <li class="nav-item">
          <router-link :to="{ name: 'Index' }" class="nav-link">Street Arts</router-link>
        </li>
        <li class="nav-item">
          <router-link :to="{ name: 'Digital' }" class="nav-link">Digital Arts</router-link>
        </li>
        <li class="nav-item">
          <router-link :to="{ name: 'About' }" class="nav-link">About</router-link>
        </li>
      </ul>
    </nav>
    <img class='banner' src="banner.png">
    <img class='logo' src="logo.png">
    <transition name="fade">
      <div class="gap">
        <router-view></router-view>        
      </div>
    </transition>
  </div>
</template>

<script>

export default {
  
}
</script>

<style>
    .fade-enter-active, .fade-leave-active {
      transition: opacity .5s
    }
    .fade-enter, .fade-leave-active {
      opacity: 0
    }
    .gap {
      margin-top: 50px;
    }
    .banner{
      position: absolute;
      width: 80%;
      top: -105px;
      margin-left: auto;
      margin-right: auto;
    }
    .navbar-nav{
      margin-right: auto;
      margin-left: auto;
      z-index: 100;

    }
    .logo{
        position: absolute;
        top:-10px;
        width: 5%;
        margin-right: auto;
        margin-left: auto;
        left: 34%;
    }
    
</style>