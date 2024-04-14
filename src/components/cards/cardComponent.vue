<template>
	<div class="col md-row px-5">
		<div class="card h-3">
			<img :src="imageUrl" />
			<h2>{{ title }}</h2>
			<div class="container overflow-scroll">
				<p>{{ description }}</p>
			</div>
		</div>
	</div>
</template>

<script>
export default {
	props: {
		imageUrl: {
			type: String,
			required: true,
		},
		title: {
			type: String,
			required: true,
		},
		description: {
			type: String,
			required: true,
		},
	},
}
</script>

<style scoped>
.card {
	border: 1px solid #ccc;
	border-radius: 8px;
	padding: 20px;
	margin: 10px;
	width: 500px;
	height: 600px;
}

img {
	width: 100%;
	border-radius: 4px;
	height: 20rem;
}

h2 {
	margin-top: 10px;
	font-size: 1.5em;
}

p {
	margin-top: 10px;
	font-size: 1.5em;
}
</style>
