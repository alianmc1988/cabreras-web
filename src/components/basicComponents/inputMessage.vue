<template>
    <div>
        <label for="messagem" id="message">Messagem</label>
        <input v-model="messageValue" type="text" @input="onInput" id="message-input"/>
    </div>  
</template>

<script>
export default {
    name: 'InputMessage',
    data() {
        return {
            messageValue: ''
        }
    },
    methods: {
        onInput(event) {
        this.messageValue = event.target.value;
        this.$emit("input-change", this.messageValue);
      }
    },


}
</script>

<style>
#message-input{
  
  width: 28.625rem;
  height: 5.375rem;
  padding: 1.0656rem 1.7049rem;
  flex-shrink: 0;
  border-radius: 0.3197rem;
  border: 0.0532rem solid var(--clr-Beige-Light, #F0C986);
  background: #343333;
  color: white;

  }
  
#message{
color: var(--clr-Beige-Light, #F0C986);
font-family: "Lexend Deca";
font-size: 0.875rem;
font-style: normal;
font-weight: 300;
line-height: 150%; /* 21px */
letter-spacing: 0.0262rem;
}

</style>