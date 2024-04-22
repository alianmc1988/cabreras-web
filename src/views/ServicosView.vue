<template>
	<div class="que-oferecemos">
		<p id="first-text-section3">Que oferecemos?</p>
		<div>
			<div class="row">
				<card-component class="r"
					v-for="(image, index) in servicos"
					:key="index"
					:title="image.title"
					:imageUrl="image.url_image"
					:description="image.paragraph"
				/>
			</div>
		</div>
	</div>
</template>

<script>
import { Data } from '../data/imagesData.js'
import cardComponent from '@/components/cards/cardComponent.vue'
export default {
	name: 'ServicosView',
	components: {
		cardComponent,
	},
	data() {
		return {
			servicos: Data.services,
		}
	},
}
</script>

<style scoped>


.que-oferecemos {
	width: 100%;
	height: 100%;
	background: var(--clr-Beige-Light, #f0c986);
	display: flex;
	flex-direction: column;
	align-items: center;
	justify-content: space-between;
	padding-bottom: 3.125rem;
	min-width: 360px;

}
.r {
	align-content: center;
}

#first-text-section3 {
	color: var(--clr-Blue-Medium, #0c3143);
	text-shadow: 0rem 0.125rem 0.5rem rgba(6, 35, 49, 0.5);
	font-family: 'Lexend Exa';
	font-size: 2.625rem;
	font-style: normal;
	font-weight: 400;
	line-height: normal;
	margin-bottom: 4rem;
	margin-top: 2.625rem;
}



</style>
