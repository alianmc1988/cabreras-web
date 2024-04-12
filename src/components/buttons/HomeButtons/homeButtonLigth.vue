<template>
    
    <button id="b-start" @click="goTo()">{{name_button}}</button>

</template>


<script>
export default {
  name: 'HomeButtonLigth',
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
      this.$emit('buttonStart')
    }
  }
}
</script>

<style scoped>

#b-start{
width:12.0625rem;
height:2.6875rem;
border-radius: 2rem;
background: var(--clr-Beige-Light, #F0C986);
box-shadow: 0rem 0.25rem 0.25rem 0rem rgba(240, 201, 134, 0.24);
border: 0.125rem solid var(--clr-Beige-Light, #F0C986);
color: var(--clr-Blue-Light, #113649);
font-family: "Lexend";
font-size: 1rem;
font-style: normal;
font-weight: 400;
line-height: normal; 
margin-top: 1.875rem;
margin-left: 3.125rem;
cursor: pointer;
transition: background-color 0.3s, color 0.3s, border-color 0.3s;
}

</style>