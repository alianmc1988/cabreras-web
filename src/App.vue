<template>
  <body>
    <div>
      <landing-page />
 
    </div>
    <div>
      <about-us />

    </div>
          
  </body>

</template>



<script>
import LandingPage from './components/LandingPage.vue'
import AboutUs from './components/AboutUs.vue'
export default {
  name: 'App',
  components: {
    LandingPage, 
    AboutUs

  }
}
</script>


