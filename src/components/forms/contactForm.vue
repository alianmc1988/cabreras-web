<template>
	<div>
		<inputForm
			type="text"
			:Nome="'Nome'"
			@input-change="onInputChange"
			id="form"
		/>
		<inputForm
			type="email"
			:Nome="'Email'"
			@input-change="onEmailChange"
			id="form"
		/>
		<InputMessage @input-change="onMessageChange" id="form" />
		<formSubmitButtonLigth :name_button="'Enviar'" @click-button="submitForm" />
	</div>
</template>

<script>
import InputMessage from '../basicComponents/inputMessage.vue'
import inputForm from '../basicComponents/inputForm.vue'
import formSubmitButtonLigth from '../buttons/FormsButtons/formSubmitButtonLigth.vue'

export default {
	name: 'contactForm',
	components: {
		inputForm,
		InputMessage,
		formSubmitButtonLigth,
	},
	data() {
		return {
			nav: true,
			mobileView: false,
			name: '',
			email: '',
			message: '',
		}
	},

	methods: {
		onInputChange(value) {
			this.name = value
		},
		onEmailChange(value) {
			this.email = value
		},
		onMessageChange(value) {
			this.message = value
		},
		submitForm() {
			// Verificar si algún campo está vacío
			if (this.name === '' || this.email === '' || this.message === '') {
				alert('Por favor, preencha todos os campos!')
				return // Detener la ejecución si hay campos vacíos
			}
			if (!this.email.includes('@') || !this.email.includes('.')) {
				alert('Por favor, insira um e-mail válido!')
				return // Detener la ejecución si el email no es válido
			}
			const requestOptions = {
				method: 'POST',
				headers: {
					'Content-Type': 'application/json',
					'X-API-Key': 'dev-dennis',
				},
				body: JSON.stringify({
					name: this.name,
					email: this.email,
					message: this.message,
				}),
			}

			fetch('https://email_contact.cabrerasltd.com', requestOptions)
				.then((response) => {
					if (response.status === 200) {
						alert('Formulário enviado com sucesso!')
						return response.json() // Convertir respuesta a JSON si es necesario
					} else {
						throw new Error('Error al enviar el formulario') // Manejar errores de HTTP
					}
				})
				.then((data) => {
					// Procesar la respuesta JSON si es necesario
					console.log(data)
				})
				.catch((error) => {
					console.error('Error:', error)
					alert(
						'Ocurrió un error al enviar el formulario. Por favor, inténtelo de nuevo.',
					)
				})
		},
	},
}
</script>
<style scoped>
#form {
	display: flex;
	flex-direction: column;
	margin-top: 0.9375rem;
}

#logo-text {
	display: flex;
}

#name {
	color: var(--clr-Beige-Light, #f0c986);
	font-family: 'Lexend Deca';
	font-size: 0.875rem;
	font-style: normal;
	font-weight: 300;
	line-height: 150%; /* 21px */
	letter-spacing: 0.0262rem;
}

#name-input {
	width: 28.625rem;
	padding: 1.0656rem 1.7049rem;
	border-radius: 0.3197rem;
	border: 0.0532rem solid var(--clr-Beige-Light, #f0c986);
	background: #343333;
}

#e-mail {
	color: var(--clr-Beige-Light, #f0c986);
	font-family: 'Lexend Deca';
	font-size: 0.875rem;
	font-style: normal;
	font-weight: 300;
	line-height: 150%; /* 21px */
	letter-spacing: 0.0262rem;
}

#email-input {
	width: 28.625rem;
	padding: 1.0656rem 1.7049rem;

	border-radius: 0.3197rem;
	border: 0.0532rem solid var(--clr-Beige-Light, #f0c986);
	background: #343333;
}

#message {
	color: var(--clr-Beige-Light, #f0c986);
	font-family: 'Lexend Deca';
	font-size: 0.875rem;
	font-style: normal;
	font-weight: 300;
	line-height: 150%; /* 21px */
	letter-spacing: 0.0262rem;
}

#message-input {
	width: 28.625rem;
	height: 5.375rem;
	padding: 1.0656rem 1.7049rem;
	flex-shrink: 0;
	border-radius: 0.3197rem;
	border: 0.0532rem solid var(--clr-Beige-Light, #f0c986);
	background: #343333;
}

#send-message {
	width: 13.9375rem;
	height: 2.8125rem;
	flex-shrink: 0;
	border-radius: 0.25rem;
	background: var(--clr-Beige-Light, #f0c986);
	color: var(--clr-Blue-Light, #113649);
	font-family: 'Lexend Deca';
	font-size: 0.875rem;
	font-style: normal;
	font-weight: 500;
	line-height: 150%; /* 21px */
	letter-spacing: 0.0262rem;
	margin-top: 0.9375rem;
}
#cabreras-section4 {
	color: var(--colorSec-BeigeLig, #f0c986);
	/* Shadow/BlueDark/50% */
	text-shadow: 0rem 0.25rem 0.25rem rgba(6, 35, 49, 0.5);
	font-family: 'Lexend Exa';
	font-size: 3rem;
	font-style: normal;
	font-weight: 400;
	line-height: normal;
	letter-spacing: 0.36rem;
}

#unindo-mercados-section4 {
	color: var(--colorSec-BeigeLig, #f0c986);

	/* Shadow/BlueDark/50% */
	text-shadow: 0rem 0.25rem 0.25rem rgba(6, 35, 49, 0.5);
	font-family: 'Lexend Exa';
	font-size: 1.25rem;
	font-style: normal;
	font-weight: 300;
	line-height: normal;
	letter-spacing: 0.4125rem;
}

#QRcode-v-card-section-4 {
	width: 13.125rem;
	height: 13.125rem;
	flex-shrink: 0;
	margin-top: 0.9375rem;
}

#inputs-button {
	display: flex;
	flex-direction: column;
}

#form {
	display: flex;
	flex-direction: column;
	margin-top: 0.9375rem;
}

#qr-code {
	display: flex;
	flex-direction: column;
	align-items: center;
	margin-top: 9.4375rem;
}

#info-required {
	margin-top: 3rem;
}

.privacy-politics {
	display: flex;
	justify-content: center;
	margin-top: 4.3438rem;
	padding-bottom: 2.2563rem;
	gap: 0.625rem;
}

#privacy-politics-cookies {
	color: var(--clr-Beige-Light, #f0c986);

	font-family: 'Lexend Exa';
	font-size: 1rem;
	font-style: normal;
	font-weight: 400;
	line-height: normal;
}

#cabreras-year {
	color: var(--clr-Beige-Light, #f0c986);

	font-family: Lexend Exa;
	font-size: 1rem;
	font-style: normal;
	font-weight: 400;
	line-height: normal;
}

#cabreras-year-div {
	display: flex;
	justify-content: center;
	align-items: center;
	gap: 0.1875rem;
}
</style>
