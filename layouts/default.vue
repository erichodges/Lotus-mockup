<template>
  <div class="div-with-background">
    <Nav />
    <nuxt/>
    <Footer />
  </div>
</template>


<script>
  import Nav from '@/components/Nav'
  import Footer from '@/components/Footer'
  

  export default {
    components: {
      Nav,
      Footer,
      
    }
  }
</script>

<style lang="scss">
  .div-with-background { 
    height: 100vh; 
    align-items: center;
    text-align: center;

    background-image: url('~/assets/images/2017_lotus_evora_sport_410-2560x1440.jpg');
    background-size: cover;
    background-repeat: no-repeat;
    background-position: center center;
}

</style>
