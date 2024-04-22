<template>
    <div>
    <label for="name" id="name">{{Nome}}</label>
    <input v-model="inputValue" :type="type" @input="onInput" id="name-input"/>
    </div>
  </template>
  
  <script>
  export default {
    props: {
      type: {
        type: String,
        default: "text"
      },
      Nome: {
        type: String,
        default: "Nome"
      }
    },
    data() {
      return {
        inputValue: ""
      };
    },
    methods: {
      onInput(event) {
        this.inputValue = event.target.value;
        this.$emit("input-change", this.inputValue);
      }
    }
  };
  </script>
 <style> 

  #name{
    color: var(--clr-Beige-Light, #F0C986);
    font-family: "Lexend Deca";
    font-size: 0.875rem;
    font-style: normal;
    font-weight: 300;
    line-height: 150%; /* 21px */
    letter-spacing: 0.0262rem;

    }
    
    #name-input{
    width: 100%;
    padding: 1.0656rem 1.7049rem;   
    border-radius: 0.3197rem;
    border: 0.0532rem solid var(--clr-Beige-Light, #F0C986);
    background: #343333;
    color: white;
    }
 
    </style>