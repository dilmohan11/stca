<template>
  <main>
    <Herobox
      header="Contact Us"
      quote="STCA is one of Versova’s premium underarm cricket league organizer since 15 years." 
    />
    <section>
        <div class="form_title flex flex-col ">
            <h3 class="text-4xl text-center p-5">You can find the address below:</h3>
            <img src="../assets/images/tennisball.png" alt="Tennis Ball picture" class="w-12 h-12 mx-auto mb-5">
        </div>
        <div class="form_address flex gap-2 my-5">
            <div class="googlemap w-1/2">
                <iframe src="https://www.google.com/maps/embed?pb=!1m14!1m8!1m3!1d15077.984910399413!2d72.814077!3d19.129744!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x0%3A0x2c88160c00e2a11e!2sSagar%20Tarang!5e0!3m2!1sen!2sin!4v1632991846268!5m2!1sen!2sin" width="600" height="450" style="border:0;" allowfullscreen="" loading="lazy"
                      class="mx-auto"></iframe>
            </div>
            <div class="address w-1/2 flex flex-col justify-center">
                  <h2 class="text-center font-semibold pb-5 text-3xl">ADDRESS AND DIRECTIONS</h2>
                  <p class="text-center text-xl pb-2 text-green-700 font-semibold">SAGAR TARANG CHS</p>
                  <p class="text-center text-xl pb-2 text-green-700 font-semibold">7 BUNGLOWS, VERSOVA</p>
                  <p class="text-center text-xl pb-2 text-green-700 font-semibold">J.P ROAD, ANDHERI WEST</p>
                  <p class="text-center text-xl pb-2 text-green-700 font-semibold">MUMBAI - 400061</p>
            </div>
        </div>
    </section>
    <Footer />
  </main>
</template>

<script>
  import Herobox from '../components/Herobox.vue'
  import Footer from '../components/Footer.vue'
export default {
  components: { Herobox, Footer },
  
}
</script>

<style>

</style>