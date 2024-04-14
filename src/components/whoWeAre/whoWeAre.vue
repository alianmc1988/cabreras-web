<template>
	<section>

	<div v-show="!is_par" class="col md-row card-container" >
		<div class="text-container">
			<p class="card-description">{{ description }}</p>
		</div>
			<div class="card-image">
				<img :src="src" class="card-image2" />
		</div>
	</div>



	<div v-show="is_par" class="col md-row card-container">
			<div class="card-image">
				<img :src="src" class="card-image" />
			</div>
		<div class="text-container">
			<p class="card-description">{{ description }}</p>
		</div>
	</div>
</section>
</template>

<script>
export default {
	props: {
		src: {
			type: String,
			required: true,
		},
		description: {
			type: String,
			required: true,
		},
		is_par: {
			type: Boolean,
			required: true,
		},
	},
}
</script>

<style scoped>
.card-container {
	display: flex; /* Utiliza flexbox para alinear elementos en una fila */
	align-items: center; /* Centra verticalmente los elementos */
}

.image-container {
	display:flex;
	width: 500; /* Tamaño de la imagen (ajústalo según sea necesario) */

}

.card-image {
	width: 100%; /* Tamaño de la imagen (ajústalo según sea necesario) */
	height: auto; /* Altura automática para mantener la proporción */
	border-radius: 0rem 4.5rem 0rem 0rem;
}

.text-container {
	display:flex;
	padding: 3rem;
 /* El texto ocupa el espacio restante disponible */
}

.card-description {
font-family: "Lexend Exa";
color: var(--clr-Beige-Medium, #C19B64);
font-size: 1.625rem;
font-style: normal;
font-weight: 400;
line-height: normal;
}

.card-image2 {
	width: 100%; /* Tamaño de la imagen (ajústalo según sea necesario) */
	height: auto; /* Altura automática para mantener la proporción */
	border-radius: 4.5rem 0rem 0rem 0rem;
}
</style>
