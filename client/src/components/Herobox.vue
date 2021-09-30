<template>
  <section class="registration-hero">
    <div class="register-hero_text">
      <h1 class="text-6xl  text-white font-semibold text-center pt-24">{{ header }}</h1>
      <div class="white-line h-2 w-28 bg-white m-auto my-5"></div>
      <p class="text-3xl text-white font-medium text-center pt-10 mx-auto w-1/2">{{ quote }}</p>
    </div>
  </section>
</template>

<script>
export default {
    props: ['header', 'quote'],
    data() {
        return {

        }
    }
}
</script>

<style>
.registration-hero {
  background: linear-gradient(to right, rgba(0,27,46,0.64), rgba(20,234,221,0.68)),  url("../assets/images/background.png");
  height: 420px;
}
.registration-hero_text {
  font-family: 'Josefin Sans', sans-serif;
}
</style>