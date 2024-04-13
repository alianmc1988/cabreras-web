<template>
	<div class="whowearebox">
		<img :url_image="url_image" />
		<div class="text-box1">
			<div id="paragraphs_box1">
				<br />
				<p id="second-text-box1">
					CABRERAS é uma empresa de comércio eletrônico que conecta exportadores
					brasileiros com importadores internacionais.
				</p>
			</div>
		</div>
	</div>
</template>

<script>
import img from '../../public/img/QSoomos_1.webp'
export default {
	name: 'WhoWeAre',
	components: {
		img,
	},
	props: {
		url_image: {
			type: String,
			default: 'No_image',
		},
		description: {
			type: String,
			default: 'No_description',
		},

		id: {
			type: String,
			default: 'No_id',
		},
	},
}
</script>
