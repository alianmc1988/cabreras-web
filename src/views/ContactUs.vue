<template>
    <section class="contate-nos-section4">

    <div class="contate-nos">
        <div id="contato-firstbox">
            <div id="info-required">
                <p id="contact-us">Contate-nos</p>
                <cabrera-logo-text-vue />
                <contact-form/>
            </div>
            </div>
            <div id="qr-code">
                <p id="cabreras-section4">CABRERAS</p>
                <p id="unindo-mercados-section4">UNINDO MERCADOS</p>
                <img src="../../public/img/vcard_qrcode.png" alt="QRcode v-card" id="QRcode-v-card-section-4">
        </div>
        </div>  
        <privacy-politics />
    </section>
</template>
  


<script>
import cabreraLogoTextVue from '../components/cabrerasLogoText/cabreraLogoText.vue'
import contactForm from '../components/forms/contactForm.vue'
import privacyPolitics from '../components/privacyPolitics/privacyPolitics.vue'

export default {
    name: 'ContactUs',
    components: {
        cabreraLogoTextVue,
        contactForm,
        privacyPolitics
    },
    data() {
        return {
            nav:true,
            mobileView:false,
        }
    }
}
</script>


<style scoped>



.contate-nos-section4{
background: linear-gradient(90deg, rgba(0, 0, 0, 0.50) 43.81%, rgba(15, 23, 42, 0.50) 100%), url(../../public/img/182920b76787d631ad32939fc0d652ef.png) lightgray -64.914px -60px / 109.505% 114.909% no-repeat;
background-size: cover;
background-position: center;
}
.contate-nos{
display: flex;
flex-direction: row;
justify-content: space-between;
margin-right:9.9375rem;
margin-left: 5.375rem;
padding-top: 2rem;

}

#contact-us{
color: var(--clr-Beige-Light, #F0C986);
font-family: "Lexend Deca";
font-size: 2.5rem;
font-style: normal;
font-weight: 400;
line-height: normal;
letter-spacing: 0.075rem;
margin-bottom: 1.25rem;
}

#logo-text{
display: flex;
  
}


#send-message{
width: 13.9375rem;
height: 2.8125rem;
flex-shrink: 0;
border-radius: 0.25rem;
background: var(--clr-Beige-Light, #F0C986);
color: var(--clr-Blue-Light, #113649);
font-family: "Lexend Deca";
font-size: 0.875rem;
font-style: normal;
font-weight: 500;
line-height: 150%; /* 21px */
letter-spacing: 0.0262rem;
margin-top: 0.9375rem;
}
#cabreras-section4{
color: var(--colorSec-BeigeLig, #F0C986);
leading-trim: both;
text-edge: cap;
/* Shadow/BlueDark/50% */
text-shadow: 0rem 0.25rem 0.25rem rgba(6, 35, 49, 0.50);
font-family: "Lexend Exa";
font-size: 3rem;
font-style: normal;
font-weight: 400;
line-height: normal;
letter-spacing: 0.36rem;
}

#unindo-mercados-section4{
color: var(--colorSec-BeigeLig, #F0C986);
leading-trim: both;
text-edge: cap;
/* Shadow/BlueDark/50% */
text-shadow: 0rem 0.25rem 0.25rem rgba(6, 35, 49, 0.50);
font-family: "Lexend Exa";
font-size: 1.25rem;
font-style: normal;
font-weight: 300;
line-height: normal;
letter-spacing: 0.4125rem;
}

#QRcode-v-card-section-4{
width: 13.125rem;
height: 13.125rem;
flex-shrink: 0;
margin-top: 0.9375rem;
}

#inputs-button{
display: flex;
flex-direction: column;  
  

}

#form{
display: flex;
flex-direction: column;  
margin-top: 0.9375rem;

}

#qr-code{
display: flex;
flex-direction: column;
align-items: center;
margin-top: 9.4375rem;
}

#info-required{
margin-top: 3rem;
}



</style>