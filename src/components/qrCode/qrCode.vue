<template>
<div id="qr-code">
    <p id="cabreras-section4">CABRERAS</p>
    <p id="unindo-mercados-section4">UNINDO MERCADOS</p>
    <img src="../../../public/img/vcard_qrcode.png" alt="QRcode v-card" id="QRcode-v-card-section-4">
</div>
</template>

<script>
export default {
    name: 'QrCode',
    data() {
        return {
            nav:true,
            mobileView:false,
        }
    }

}
</script>

<style>
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

#qr-code{
display: flex;
flex-direction: column;
align-items: center;
margin-top: 9.4375rem;
}
</style>


    