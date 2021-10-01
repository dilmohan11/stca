<template>
  <main>
    <section class="hero_section">
      <div class="flex justify-center self-center pt-64 ">
        <h1 class="text-6xl text-white ">
        <span class="uppercase cricket_h1 font-bold">Cricket</span> is life!
      </h1>
      </div>
      <div class="submit text-center">
            <button class="text-lg px-4 py-4 font-semibold rounded-xl mt-5 bg-green-700 text-white hover:text-gray-50
                            hover:bg-green-900 transform transition ease-linear duration-200">
                Register Now
            </button>
        </div>
    </section>
  </main>
</template>

<script>
export default {
  
  components: {
    
  }
}
</script>

<style>
  .hero_section {
    background: linear-gradient(to right, rgba(0,0,0,0.3), rgba(0,0,0,0.3)), url('../assets/images/hero_background.jpg');
    height: 100vh;
  }
  .cricket_h1 {
    color:#14EADD;
  }
</style>
