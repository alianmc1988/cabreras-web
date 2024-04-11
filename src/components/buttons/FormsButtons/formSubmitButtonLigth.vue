<template>
    
    <button id="send-message" @click="sendMessage()">{{name_button}}</button>

</template>


<script>
export default {
  name: 'formSubmitButtonLigth',
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
  sendMessage() {
    this.$emit('click-button')
    }
  }
}
</script>

<style scoped>

#send-message{
width: 13.9375rem;
height: 2.8125rem;
flex-shrink: 0;
border-radius: 0.25rem;
background: var(--clr-Beige-Light, #F0C986);
color: var(--clr-Blue-Light, #113649);
font-family: "Lexend Deca";
font-size: 0.875rem;
font-style: normal;
font-weight: 500;
line-height: 150%; /* 21px */
letter-spacing: 0.0262rem;
margin-top: 0.9375rem;
}
</style>