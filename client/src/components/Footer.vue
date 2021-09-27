<template>
<footer class="navbar h-24 flex  text-white font-bold text-xl">
  
  <router-link :to="{name: 'Home'}" class="w-1/3">
    <img src="../assets/images/logo.png" alt="Sagar Tarang Association Logo" class="">
  </router-link>
  
  <nav class="flex justify-around self-center w-1/3 ">
      <router-link 
        :to="{name: 'Home'}" 
        class="hover:text-blue-300 transform transition duration-300 ease-linear">
        Home
      </router-link>
      <router-link 
        :to="{name: 'About'}" 
        class="hover:text-blue-300 transform transition duration-300 ease-linear">
        About Us
      </router-link>
      <router-link 
        :to="{name: 'Contact'}" 
        class="hover:text-blue-300 transform transition duration-300 ease-linear">
        Contact Us
      </router-link>
      <router-link 
        :to="{name: 'Register'}" 
        class="hover:text-blue-300 transform transition duration-300 ease-linear">
        Register
      </router-link>
  </nav>

  <div class="w-1/3 flex self-center justify-end pr-10">
      @2021 STCA. All rights reserved.
  </div>
</footer>
</template>

<script>


export default {

}
</script>

<style>
.navbar {
  background-color: #0F7173;
}

.router-link-exact-active{
  color: #14EADD;
}
</style>