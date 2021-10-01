<template>
  <main>
    <Herobox 
      header="About Us"
      quote="STCA is one of Versova’s premium underarm cricket league organizer since 15 years."
    />
    <section>
      <div class="about_title flex flex-col ">
            <h3 class="text-4xl text-center p-5">Our Story</h3>
            <img src="../assets/images/tennisball.png" alt="Tennis Ball picture" class="w-12 h-12 mx-auto mb-5">
        </div>
        <div class="about_content flex gap-2 my-5">
            <div class="para w-1/2 px-16">
                <p>
                    Lorem ipsum dolor sit amet, consectetur adipiscing elit. Suspendisse convallis aliquam aliquet.
                    Sed consectetur ultricies leo non imperdiet. Integer nibh mauris, finibus quis elit.
                </p>
            </div>
            <div class="para w-1/2 px-16">
                  <p>
                    Lorem ipsum dolor sit amet, consectetur adipiscing elit. Suspendisse convallis aliquam aliquet.
                    Sed consectetur ultricies leo non imperdiet. Integer nibh mauris, finibus quis elit.
                </p>
            </div>
          </div>
    </section>
  </main>
</template>

<script>
  import Herobox from '../components/Herobox.vue'
  import Footer from '../components/Footer.vue'
export default {
  components: { Herobox, Footer }
}
</script>
 
<style>

</style>