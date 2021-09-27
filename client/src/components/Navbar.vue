<template>
<header class="navbar h-24 flex justify-between text-white font-bold text-xl">

  <img src="../assets/images/logo.png" alt="" class="">
  <!-- <div class="">
          <img src="" alt="Sagar Tarang Cricket Association Logo">
    </div> -->
  <nav class="flex justify-around self-center w-1/2">
      <router-link :to="{name: 'Home'}">Home</router-link>
      <router-link :to="{name: 'About'}">About Us</router-link>
      <router-link :to="{name: 'Contact'}">Contat Us</router-link>
      <router-link :to="{name: 'Register'}">Register</router-link>
  </nav>
</header>
</template>

<script>


export default {

}
</script>

<style>
.navbar {
  background-color: #0F7173;
}
</style>