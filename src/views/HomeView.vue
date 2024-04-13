<template>
  <section>
  <div class="main-container">
  <div id="header-text">
    <p>CABRERAS</p>
  </div> 
                     
                
  <div id="lines">                                                  
  <svg xmlns="http://www.w3.org/2000/svg" width="224" height="11" viewBox="0 0 224 11" fill="none">
      <path fill-rule="evenodd" clip-rule="evenodd" d="M0 4.33333H212.975C213.443 1.86581 215.611 0 218.215 0C221.161 0 223.548 2.38781 223.548 5.33333C223.548 8.27885 221.161 10.6667 218.215 10.6667C215.611 10.6667 213.443 8.80086 212.975 6.33333H0V4.33333ZM218.206 8.14581C219.857 8.14581 221.195 6.88661 221.195 5.33331C221.195 3.78001 219.857 2.52081 218.206 2.52081C216.555 2.52081 215.217 3.78001 215.217 5.33331C215.217 6.88661 216.555 8.14581 218.206 8.14581Z" fill="#F0C986"/>
    </svg>
    <svg xmlns="http://www.w3.org/2000/svg" width="224" height="11" viewBox="0 0 224 11" fill="none">
      <path fill-rule="evenodd" clip-rule="evenodd" d="M0.451538 5.33333C0.451538 8.27885 2.83935 10.6667 5.78487 10.6667C8.38859 10.6667 10.5565 8.80086 11.0246 6.33333H224V4.33333H11.0246C10.5565 1.86581 8.38859 0 5.78487 0C2.83935 0 0.451538 2.38781 0.451538 5.33333ZM5.78491 8.14583C7.43576 8.14583 8.77404 6.88663 8.77404 5.33333C8.77404 3.78003 7.43576 2.52083 5.78491 2.52083C4.13407 2.52083 2.79579 3.78003 2.79579 5.33333C2.79579 6.88663 4.13407 8.14583 5.78491 8.14583Z" fill="#F0C986"/>
    </svg>
  </div>

  <div id="last-text">
      <p>UNINDO MERCADOS</p>
      <home-button-ligth @buttonStart="gotoStart" :name_button="'Começar'" />
      <home-button-dark @buttonContact="gotoContact" :name_button="'Contatar'" />
  </div>>
</div>
<!-- <div>
  <landing-page-vue />
</div> -->
<div ref="aboutref">
  <about />
</div>
<div>
  <servicos-view-vue />
</div>
<div ref="contactref">
  <contact-us />
</div>


</section>

</template>


<script>
// @ is an alias to /src
import HomeButtonLigth from '@/components/buttons/HomeButtons/homeButtonLigth.vue'
import HomeButtonDark from '@/components/buttons/HomeButtons/homeButtonDark.vue'
import About from './AboutView.vue'
import ContactUs from './ContactUs.vue'
import ServicosViewVue from './ServicosView.vue'
import LandingPageVue from './LandingPage.vue'
import WhoWeAre from '@/components/whoWeAre/whoWeAre.vue'
import cardComponents from '@/components/cards/cardComponent.vue'

export default {
  name: 'HomeView',
  data() {
    return {      
      card: {
        imageUrl: '../../public/img/Background_Hero.png',
        title: 'Título de la tarjeta',
        description: 'Descripción de la tarjeta'
      },
      nav:true,
      mobileView:false,
      abouturl: '/about',
      contacturl: '/contact-us',
      url_image: '../../public/img/Background_Hero.png',
    }
  },
  components: {
    cardComponents,
    HomeButtonDark,
    HomeButtonLigth,
    About,
    ContactUs,
    ServicosViewVue,
    WhoWeAre,
    LandingPageVue,
    },
  methods: {
    gotoStart(){
      this.$refs.aboutref.scrollIntoView({ behavior: 'smooth' });
    },
    gotoContact(){
      this.$refs.contactref.scrollIntoView({ behavior: 'smooth' });
    }
  }

}
</script>

<style scoped>


</style>