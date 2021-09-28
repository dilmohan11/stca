<template>
<main>  
  <section class="registration-hero">
    <div class="register-hero_text">
      <h1 class="text-6xl  text-white font-semibold text-center pt-24">Registration</h1>
      <div class="white-line h-2 w-28 bg-white m-auto my-5"></div>
      <p class="text-3xl text-white font-medium text-center pt-10">STPL is one of Versova’s premium underarm cricket league since two years.</p>
    </div>
  </section>
  <RegisterForm />
</main>
  
</template>

<script>
import RegisterForm from '../components/RegisterForm.vue'

export default {
  components: { RegisterForm }
}
</script>

<style >
.registration-hero {
  background: linear-gradient(to right, rgba(0,27,46,0.64), rgba(20,234,221,0.68)),  url("../assets/images/background.png");
  height: 420px;
}
.registration-hero_text {
  font-family: 'Josefin Sans', sans-serif;
}

</style>