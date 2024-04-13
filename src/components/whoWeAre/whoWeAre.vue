<template>
	<div class="card-container">
	  <div class="image-container">
		<img :src="src" class="card-image" />
	  </div>
	  <div class="text-container">
		<p class="card-description">{{ description }}</p>
	  </div>
	</div>
  </template>
  
  <script>
  export default {
	props: {
	  src: {
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
  .card-container {
	display: flex; /* Utiliza flexbox para alinear elementos en una fila */
	align-items: center; /* Centra verticalmente los elementos */
  }
  
  .image-container {
	flex: 0 0 auto; /* Establece el tamaño fijo para el contenedor de la imagen */
	margin-right: 20px; /* Espacio entre la imagen y el texto */
  }
  
  .card-image {
	width: 100px; /* Tamaño de la imagen (ajústalo según sea necesario) */
	height: auto; /* Altura automática para mantener la proporción */
	border-radius: 5px; /* Borde redondeado para la imagen */
  }
  
  .text-container {
	flex: 1; /* El texto ocupa el espacio restante disponible */
  }
  
  .card-description {
	margin: 0; /* Elimina el margen predeterminado del párrafo */
	font-size: 14px; /* Tamaño de fuente del texto */
	color: var(--clr-Beige-Light, #f0c986);
  }
  </style>
  