<template>
<main>  
  <Herobox 
      header="Registration"
      quote="STCA is one of Versova’s premium underarm cricket league organizer since 15 years." />
  <RegisterForm />
  <Footer />
</main>
  
</template>

<script>
import Herobox from '../components/Herobox.vue'
import RegisterForm from '../components/RegisterForm.vue'
import Footer from '../components/Footer.vue'

export default {
  components: { RegisterForm, Footer, Herobox }
}
</script>

<style >


</style>