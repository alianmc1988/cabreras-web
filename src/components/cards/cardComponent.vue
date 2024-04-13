<template>
    <div class card>
	<img :src="src" class="card-image" />
      <h2>{{ title }}</h2>
      <p>{{ description }}</p>
    </div>
  </template>
  
  <script>
  export default {
    props: {
      imageUrl: {
        type: String,
        required: true
      },
      title: {
        type: String,
        required: true
      },
      description: {
        type: String,
        required: true
      }
    }
  };
  </script>
  
  <style scoped>
  .card {
    border: 1px solid #ccc;
    border-radius: 8px;
    padding: 20px;
    margin: 10px;
    width: 300px;
  }
  
  img {
    width: 100%;
    border-radius: 4px;
  }
  
  h2 {
    margin-top: 10px;
    font-size: 1.5em;
  }
  
  p {
    margin-top: 10px;
  }
  </style>
  