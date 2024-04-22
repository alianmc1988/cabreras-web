<template>
	<div class="col md-row px-5">
		<div class="card h-3">
			<img :src="imageUrl" class="img"/>
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
	max-width: 50vh;
	min-width: 35vh;
	height: 650px;
}

.img {
	width: 100%;
  	height: 40%;
	border-radius: 4px;
}

h2 {
	margin-top: 10px;
	font-size: 1.5em;
}

p {
	margin-top: 10px;
	font-size: 1.5em;
}














#first-text-section3 {
	color: var(--clr-Blue-Medium, #0c3143);
	leading-trim: both;
	text-edge: cap;
	text-shadow: 0rem 0.125rem 0.5rem rgba(6, 35, 49, 0.5);
	font-family: 'Lexend';
	font-size: 2.625rem;
	font-style: normal;
	font-weight: 400;
	line-height: normal;
	margin-bottom: 4rem;
	margin-top: 2.625rem;
}

#firstbox-3imags-section3 {
	display: flex;
	justify-content: center;
	gap: 3.125rem;
}

#firstdiv-section3 {
	width: 22.5rem;
	border-radius: 1.5rem 1.5rem 0rem 0rem;
	background: var(--clr-White-Light, #f9f9f9);
	box-shadow: 0.125rem 0.25rem 0.5rem 0rem rgba(6, 35, 49, 0.5);
}

#photo1-section3 {
	width: 22.5rem;
	height: 15.625rem;
	background: lightgray 0rem -2.2418rem / 100% 189.732% no-repeat;
	box-shadow: 0.25rem 0.25rem 0.25rem 0rem rgba(0, 0, 0, 0.25);
	border-radius: 1.5rem 1.5rem 0rem 0rem;
}

#text1-firstdiv-s3 {
	color: var(--clr-Blue-Medium, #0c3143);
	font-family: Lexend;
	font-size: 1.5rem;
	font-style: normal;
	font-weight: 400;
	line-height: normal;
	margin-left: 0.5rem;
	margin-top: 0.5rem;
}

#text2-firstdiv-s3 {
	color: var(--clr-Blue-Medium, #0c3143);
	leading-trim: both;
	text-edge: cap;
	font-family: Lexend;
	font-size: 1rem;
	font-style: normal;
	font-weight: 400;
	line-height: 1.5rem;
	margin: 0.5rem 0.5rem;
	text-align: justify;
	/* 150% */
}

#seconddiv-section3 {
	width: 22.5rem;
	border-radius: 1.5rem 1.5rem 0rem 0rem;
	background: var(--clr-White-Light, #f9f9f9);
	box-shadow: 0.125rem 0.25rem 0.5rem 0rem rgba(6, 35, 49, 0.5);
}

#text1-seconddiv-s3 {
	color: var(--clr-Blue-Medium, #0c3143);
	font-family: Lexend;
	font-size: 1.5rem;
	font-style: normal;
	font-weight: 400;
	line-height: normal;
	margin-left: 0.5rem;
	margin-top: 0.5rem;
}

#text2-seconddiv-s3 {
	color: var(--clr-Blue-Medium, #0c3143);
	leading-trim: both;
	text-edge: cap;
	font-family: Lexend;
	font-size: 1rem;
	font-style: normal;
	font-weight: 400;
	line-height: 1.5rem;
	margin: 0.5rem 0.5rem;
	text-align: justify;
}

#photo2-section3 {
	width: 22.5rem;
	height: 15.625rem;
	border-radius: 1.5rem 1.5rem 0rem 0rem;
	background: lightgray 50% / cover no-repeat;
}

#thirddiv-section3 {
	width: 22.5rem;
	border-radius: 1.5rem 1.5rem 0rem 0rem;
	background: var(--clr-White-Light, #f9f9f9);
	box-shadow: 0.125rem 0.25rem 0.5rem 0rem rgba(6, 35, 49, 0.5);
}

#text1-thirddiv-s3 {
	color: var(--clr-Blue-Medium, #0c3143);
	font-family: Lexend;
	font-size: 1.5rem;
	font-style: normal;
	font-weight: 400;
	line-height: normal;
	margin-left: 0.5rem;
	margin-top: 0.5rem;
}

#text2-thirddiv-s3 {
	color: var(--clr-Blue-Medium, #0c3143);
	leading-trim: both;
	text-edge: cap;
	font-family: Lexend;
	font-size: 1rem;
	font-style: normal;
	font-weight: 400;
	line-height: 1.5rem;
	margin: 0.5rem 0.5rem;
	text-align: justify;
}

#photo3-section3 {
	width: 22.5rem;
	height: 15.625rem;
	background: lightgray 0.0799rem -12.3836rem / 100% 189.732% no-repeat;
	box-shadow: 0.25rem 0.25rem 0.25rem 0rem rgba(0, 0, 0, 0.25);
	border-radius: 1.5rem 1.5rem 0rem 0rem;
}

#secondbox-3imags-section3 {
	display: flex;
	justify-content: center;
	gap: 3.125rem;
	margin-top: 4rem;
}

#fourthdiv-section3 {
	width: 22.5rem;
	border-radius: 1.5rem 1.5rem 0rem 0rem;
	background: var(--clr-White-Light, #f9f9f9);
	box-shadow: 0.125rem 0.25rem 0.5rem 0rem rgba(6, 35, 49, 0.5);
}

#text1-fourthdiv-s3 {
	color: var(--clr-Blue-Medium, #0c3143);
	font-family: Lexend;
	font-size: 1.5rem;
	font-style: normal;
	font-weight: 400;
	line-height: normal;
	margin-left: 0.5rem;
	margin-top: 0.5rem;
}

#text2-fourthdiv-s3 {
	color: var(--clr-Blue-Medium, #0c3143);
	leading-trim: both;
	text-edge: cap;
	font-family: Lexend;
	font-size: 1rem;
	font-style: normal;
	font-weight: 400;
	line-height: 1.5rem;
	margin: 0.5rem 0.5rem;
	text-align: justify;
}

#photo4-section3 {
	width: 22.5rem;
	height: 15.625rem;
	background: lightgray 0.0445rem 0.0002rem / 99.912% 99.982% no-repeat;
	box-shadow: 0.25rem 0.25rem 0.25rem 0rem rgba(0, 0, 0, 0.25);
	border-radius: 1.5rem 1.5rem 0rem 0rem;
}

#fifthdiv-section3 {
	width: 22.5rem;
	border-radius: 1.5rem 1.5rem 0rem 0rem;
	background: var(--clr-White-Light, #f9f9f9);
	box-shadow: 0.125rem 0.25rem 0.5rem 0rem rgba(6, 35, 49, 0.5);
}

#text1-fifthdiv-s3 {
	color: var(--clr-Blue-Medium, #0c3143);
	font-family: Lexend;
	font-size: 1.5rem;
	font-style: normal;
	font-weight: 400;
	line-height: normal;
	margin-left: 0.5rem;
	margin-top: 0.5rem;
}

#text2-fifthdiv-s3 {
	color: var(--clr-Blue-Medium, #0c3143);
	leading-trim: both;
	text-edge: cap;
	font-family: Lexend;
	font-size: 1rem;
	font-style: normal;
	font-weight: 400;
	line-height: 1.5rem;
	margin: 0.5rem 0.5rem;
	text-align: justify;
}

#photo5-section3 {
	width: 22.5rem;
	height: 15.625rem;
	background: lightgray 0rem -2.2418rem / 100% 189.732% no-repeat;
	box-shadow: 0.25rem 0.25rem 0.25rem 0rem rgba(0, 0, 0, 0.25);
	border-radius: 1.5rem 1.5rem 0rem 0rem;
}

#sixthdiv-section3 {
	width: 22.5rem;
	border-radius: 1.5rem 1.5rem 0rem 0rem;
	background: var(--clr-White-Light, #f9f9f9);
	box-shadow: 0.125rem 0.25rem 0.5rem 0rem rgba(6, 35, 49, 0.5);
}

#text1-sixthdiv-s3 {
	color: var(--clr-Blue-Medium, #0c3143);
	font-family: Lexend;
	font-size: 1.5rem;
	font-style: normal;
	font-weight: 400;
	line-height: normal;
	margin-left: 0.5rem;
	margin-top: 0.5rem;
}

#text2-sixthdiv-s3 {
	color: var(--clr-Blue-Medium, #0c3143);
	leading-trim: both;
	text-edge: cap;
	font-family: Lexend;
	font-size: 1rem;
	font-style: normal;
	font-weight: 400;
	line-height: 1.5rem;
	margin: 0.5rem 0.5rem;
	text-align: justify;
}

#photo6-section3 {
	width: 22.5rem;
	height: 15.625rem;
	background: lightgray -7.9138rem -8.9884rem / 181.389% 189.732% no-repeat;
	box-shadow: 0.25rem 0.25rem 0.25rem 0rem rgba(0, 0, 0, 0.25);
	border-radius: 1.5rem 1.5rem 0rem 0rem;
}

</style>
