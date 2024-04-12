<template>
    
    <button id="b-contact" @click="goTo()">{{name_button}}</button>

</template>


<script>
export default {
  name: 'HomeButtonDark',
  data() {
    return {

      nav:true,
      mobileView:false,
    }
  },
  props: {
    goTourl: String,
    name_button: String
},
methods: {
    goTo() {
      this.$emit('buttonContact')
    }
  }
}
</script>

<style scoped>


#b-contact{
background-color:transparent;
width:12.0625rem;
height:2.6875rem;
border-radius: 2rem;
border: 0.125rem solid var(--clr-Beige-Light, #F0C986);
box-shadow: 0rem 0.125rem 0.25rem 0rem rgba(240, 201, 134, 0.24);
backdrop-filter: blur(0.75rem);
color: var(--clr-Beige-Light, #F0C986);
font-family: "Lexend";
font-size: 1rem;
font-style: normal;
font-weight: 400;
line-height: normal;
cursor: pointer;
transition: background-color 0.3s, color 0.3s, border-color 0.3s;
}


</style>