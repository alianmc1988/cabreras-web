<template>
	<!-- working here -->
	<section class="contate-nos-section4">
		<div class="container py-5 d-md-flex">
			<div class="contact-container my-5 container">
				<div id="info-required">
					<p id="contact-us">Contate-nos</p>
					<cabrera-logo-text-vue />
					<contact-form />
				</div>
			</div>
			<div class="qrcode container">
				<qr-code />
			</div>
		</div>
		<div class="container">
			<privacy-politics />
		</div>
	</section>
</template>

<script>
import cabreraLogoTextVue from '../components/cabrerasLogoText/cabreraLogoText.vue'
import contactForm from '../components/forms/contactForm.vue'
import privacyPolitics from '../components/privacyPolitics/privacyPolitics.vue'
import qrCode from '../components/qrCode/qrCode.vue'

export default {
	name: 'ContactUs',
	components: {
		cabreraLogoTextVue,
		contactForm,
		privacyPolitics,
		qrCode,
	},
	data() {
		return {
			nav: true,
			mobileView: false,
		}
	},
}
</script>

<style scoped>
.contate-nos-section4 {
	background: linear-gradient(
			90deg,
			rgba(0, 0, 0, 0.5) 43.81%,
			rgba(15, 23, 42, 0.5) 100%
		),
		url(../../public/img/rezised/182920b76787d631ad32939fc0d652ef-min.png)
			lightgray -64.914px -60px / 109.505% 114.909% no-repeat;
	background-size: cover;
	background-position: center;
}
.contate-nos {
	display: flex;
	flex-direction: row;
	justify-content: space-between;
	margin-right: 9.9375rem;
	margin-left: 5.375rem;
	padding-top: 2rem;
}

#contact-us {
	color: var(--clr-Beige-Light, #f0c986);
	font-family: 'Lexend Deca';
	font-size: 2.5rem;
	font-style: normal;
	font-weight: 400;
	line-height: normal;
	letter-spacing: 0.075rem;
	margin-bottom: 1.25rem;
}

.qrcode {
	align-items: center;
}

.contact-container {
}
</style>
