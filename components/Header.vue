<template>
  <!-- Header
  =============================================-->
  <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
  <nuxt-link class="navbar-brand" to="/"><Logo/> </nuxt-link>
  <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarTogglerDemo02" aria-controls="navbarTogglerDemo02" aria-expanded="false" aria-label="Toggle navigation">
    <span class="navbar-toggler-icon"></span>
  </button>

  <div class="collapse navbar-collapse" id="navbarTogglerDemo02">
    <ul class="navbar-nav ml-auto mt-2 mt-lg-0">
      <li class="nav-item ">
        <nuxt-link class="nav-link" to="/">Home </nuxt-link>
      </li>
      <li class="nav-item ">
        <nuxt-link class="nav-link" to="/about">About </nuxt-link>
      </li>
      <li class="nav-item ">
        <nuxt-link class="nav-link" to="/contact-us">Contact us </nuxt-link>
      </li>

      
    </ul>
 
  </div>
</nav>
  <!-- #header end -->
</template>

<script>
import Logo from '../components/Logo'
export default {
  components:{
    Logo
  }
};
</script>

<style>
</style>