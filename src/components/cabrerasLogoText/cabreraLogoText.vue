<template>
    <div id="logo-text">
        <img src="../../../public/img/Ellipse 6.svg" alt="logo container" id="logo-section-4">
        <div id="introduction">
            <p id="intro-text">Olá, somos os CABRERA. Precisa de ajuda? Utilize o seguinte formulário ou envie-nos um e-mail para comercial@cabrerasltd.com.</p>
        </div>
    </div>
</template>

<script>
export default {
    name: 'cabreraLogoText',
    data() {
        return {
            nav:true,
            mobileView:false,
        }
    },
}
</script>

<style>
#logo-text{
display: flex;
  
}
#introduction{
width: 75%;
height: 100%;
flex-shrink: 0;
border-radius: 0.25rem;
border: 0.0625rem solid var(--clr-Beige-Light, #F0C986);
background: #343333;
margin-left: 1.0625rem;
}

#intro-text{
color: #FFF;
font-family: "Lexend Deca";
font-size: 0.875rem;
font-style: normal;
font-weight: 300;
line-height: 150%; /* 21px */
letter-spacing: 0.0262rem;
padding: 0.625rem;
}
</style>