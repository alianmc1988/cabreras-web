<template>
    <section class="contate-nos-section4">

    <div class="contate-nos">
        <div id="contato-firstbox">
            <div id="info-required">
                <p id="contact-us">Contate-nos</p>
                <div id="logo-text">
                    <img src="../../public/img/Ellipse 6.svg" alt="logo container" id="logo-section-4">
                    <div id="introduction">
                        <p id="intro-text">Olá, somos os CABRERA. Precisa de ajuda? Utilize o seguinte formulário ou envie-nos um e-mail para comercial@cabrerasltd.com.</p>
                    </div>
                </div>
                <div id="inputs-button">
                    <form id="form">
                        <label for="fname" id="name">Nome:</label>
                        <input type="name" id="name-input" name="name"><br>
                        <label for="email" id="e-mail">Email:</label>
                        <input type="email" id="email-input" name="email"><br>
                        <label for="lname" id="message">Messagem:</label>
                        <input type="text" id="message-input" name="messagem">
                      </form>
                      <button id="send-message">Enviar messagem</button>
                </div>
            </div>
            </div>
            <div id="qr-code">
                <p id="cabreras-section4">CABRERAS</p>
                <p id="unindo-mercados-section4">UNINDO MERCADOS</p>
                <img src="../../public/img/vcard_qrcode.png" alt="QRcode v-card" id="QRcode-v-card-section-4">
        </div>
        </div>  
        <div class="privacy-politics">
            <div>
            <p id="privacy-politics-cookies">Política de privacidade • Aviso legal • Cookies</p>
            </div>
            <div id="cabreras-year-div">
            <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" viewBox="0 0 16 16" fill="none">
                <path d="M1 8C1 11.866 4.13401 15 8 15C11.866 15 15 11.866 15 8C15 4.13401 11.866 1 8 1C4.13401 1 1 4.13401 1 8ZM16 8C16 12.4183 12.4183 16 8 16C3.58172 16 0 12.4183 0 8C0 3.58172 3.58172 0 8 0C12.4183 0 16 3.58172 16 8ZM8.14648 4.99219C6.93359 4.99219 6.21875 5.91211 6.21875 7.49414V8.55469C6.21875 10.125 6.92188 11.0156 8.14648 11.0156C9.125 11.0156 9.78711 10.4297 9.875 9.59766H11.1699V9.69141C11.0703 11.1387 9.81641 12.1582 8.14062 12.1582C6.04883 12.1582 4.87109 10.8223 4.87109 8.55469V7.48242C4.87109 5.2207 6.07227 3.84375 8.14062 3.84375C9.82227 3.84375 11.0762 4.89844 11.1699 6.41602V6.50391H9.875C9.78711 5.625 9.10742 4.99219 8.14648 4.99219Z" fill="#F0C986"/>
              </svg>
              <p id="cabreras-year">CABRERAs LTDA. 2024</p>       
            </div>     
        </div>
    </section>
</template>
  




<style scoped>

*{
    margin: 0;
    padding: 0;
    font-family: 'Lexend', sans-serif;
    box-sizing: border-box;
}

.logo{
width: 2.0661rem;
height: 1.7432rem;
flex-shrink: 0;
margin-left: 10.7081rem;  
      
}

.logo-site{
margin-right: 10rem;
}



nav{
display: flex;
align-items: center;
justify-content: space-between;
flex-wrap: wrap;
}

nav ul li{
display: inline-block;
list-style: none;
margin:1.4763rem 4.6875rem;
}

nav ul li a{
color: var(--clr-Beige-Light, #F0C986);
leading-trim: both;
text-edge: cap;
font-family: Lexend;
font-size: 1rem;
font-style: normal;
font-weight: 400;
line-height: normal;
text-decoration: none;
}

nav ul li a::after{
content:'';
width: 0%;
height: 0.1875rem;
background: #ff004f;
position: absolute;
left: 0;
bottom: -0.375rem;
transition: 0.5s;
}


.header-text{
margin: 18.75rem 48.1875rem 30.25rem 10.625rem;
color: var(--clr-Beige-Light, #F0C986);
leading-trim: both;
text-edge: cap;
text-shadow: 0rem 0.125rem 0.25rem rgba(6, 35, 49, 0.50);
font-family: "Lexend Exa";
font-size: 4rem;
font-style: normal;
font-weight: 400;
line-height: normal;
letter-spacing: 1.505rem;
}


#lines{
width: 28.75rem;
display: flex;  
justify-content: space-between;
margin-left: 1.875rem;  
}

#last-text{
width: 35rem;
margin-top: 1.875rem;
color: var(--clr-Beige-Light, #F0C986);
leading-trim: both;
text-edge: cap;
text-shadow: 0rem 0.125rem 0.25rem rgba(6, 35, 49, 0.50);
font-family: "Lexend Exa";
font-size: 1.5rem;
font-style: normal;
font-weight: 400;
line-height: normal;
letter-spacing: 1.2625rem;
}


.quem-somos{
width: 100%;
height: 100%;
background-color: rgba(6,35,49,1);
display: flex;
flex-direction: column; 
align-content: center;
padding-bottom: 3.125rem;
}

#box1{
display: flex;
flex-direction: row;
align-items: center; 
}

#box2{
display: flex;
flex-direction: row;  
align-items: center;
}

#photo1{
margin-top: 3.125rem;
width: 45rem;
height: 21.875rem;
flex-shrink: 0;
border-radius: 0rem 4.5rem 0rem 0rem;
}

#paragraphs_box1{
margin-left: 4.75rem;
margin-right: 4.75rem;

}

.text-box1{
margin-top: 3.125rem;  
}

#first-text-box1 {  
font-family: "Lexend Exa";
color: var(--clr-Beige-Medium, #C19B64);
leading-trim: both;
text-edge: cap;  
font-size: 2.625rem;
font-style: normal;
font-weight: 400;
line-height: normal;
}

#second-text-box1{
color: var(--clr-Beige-Light, #F0C986);
leading-trim: both;
text-edge: cap;
font-family: "Lexend";
font-size: 1.5rem;
font-style: normal;
font-weight: 400;
line-height: 3rem; /* 200% */
}

#photo2{
width: 45rem;
height: 21.875rem;
flex-shrink: 0;
}

#box3{
display: flex;
flex-direction: row; 
align-items: center;   
}

#photo3{
width: 45rem;
height: 21.875rem;
flex-shrink: 0;
border-radius: 0rem 0rem 4.5rem 0rem;
}

.text-box2{
color: var(--clr-Beige-Light, #F0C986);
leading-trim: both;
text-edge: cap;
font-family: Lexend;
font-size: 1.5rem;
font-style: normal;
font-weight: 400;
line-height: 3rem;
margin-left: 4.75rem;
margin-right: 4.75rem;
}

.text-box3{
color: var(--clr-Beige-Light, #F0C986);
leading-trim: both;
text-edge: cap;
font-family: Lexend;
font-size: 1.5rem;
font-style: normal;
font-weight: 400;
line-height: 3rem; 
margin-top: 2.75rem;
margin-left: 4.75rem;
margin-right: 4.75rem;
}

#b-start{
width:12.0625rem;
height:2.6875rem;
border-radius: 2rem;
background: var(--clr-Beige-Light, #F0C986);
box-shadow: 0rem 0.25rem 0.25rem 0rem rgba(240, 201, 134, 0.24);
border: 0.125rem solid var(--clr-Beige-Light, #F0C986);
color: var(--clr-Blue-Light, #113649);
leading-trim: both;
text-edge: cap;
font-family: "Lexend";
font-size: 1rem;
font-style: normal;
font-weight: 400;
line-height: normal; 
margin-top: 1.875rem;
margin-left: 3.125rem;
}

#b-contact{
background-color:transparent;
width:12.0625rem;
height:2.6875rem;
border-radius: 2rem;
border: 0.125rem solid var(--clr-Beige-Light, #F0C986);
box-shadow: 0rem 0.125rem 0.25rem 0rem rgba(240, 201, 134, 0.24);
backdrop-filter: blur(0.75rem);
color: var(--clr-Beige-Light, #F0C986);
leading-trim: both;
text-edge: cap;
font-family: "Lexend";
font-size: 1rem;
font-style: normal;
font-weight: 400;
line-height: normal;
}
.que-oferecemos{
width: 100%;
height: 100%;
background: var(--clr-Beige-Light, #F0C986);
display: flex;
flex-direction: column; 
align-items: center;
justify-content: space-between;
padding-bottom: 3.125rem;

}

#first-text-section3{
color: var(--clr-Blue-Medium, #0C3143);
leading-trim: both;
text-edge: cap;
text-shadow: 0rem 0.125rem 0.5rem rgba(6, 35, 49, 0.50);
font-family: "Lexend";
font-size: 2.625rem;
font-style: normal;
font-weight: 400;
line-height: normal;
margin-bottom: 4rem;
margin-top: 2.625rem;
}

#firstbox-3imags-section3{
display: flex;
justify-content: center;
gap: 3.125rem;

}

#firstdiv-section3{
width: 22.5rem;
border-radius: 1.5rem 1.5rem 0rem 0rem;
background: var(--clr-White-Light, #F9F9F9);
box-shadow: 0.125rem 0.25rem 0.5rem 0rem rgba(6, 35, 49, 0.50);
}

#photo1-section3{
width: 22.5rem;
height: 15.625rem;
background: lightgray 0rem -2.2418rem / 100% 189.732% no-repeat;
box-shadow: 0.25rem 0.25rem 0.25rem 0rem rgba(0, 0, 0, 0.25);
border-radius: 1.5rem 1.5rem 0rem 0rem;
}

#text1-firstdiv-s3{
color: var(--clr-Blue-Medium, #0C3143);
font-family: Lexend;
font-size: 1.5rem;
font-style: normal;
font-weight: 400;
line-height: normal;
margin-left: 0.5rem;
margin-top: 0.5rem;
}

#text2-firstdiv-s3{
color: var(--clr-Blue-Medium, #0C3143);
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

#seconddiv-section3{
width: 22.5rem;
border-radius: 1.5rem 1.5rem 0rem 0rem;
background: var(--clr-White-Light, #F9F9F9);
box-shadow: 0.125rem 0.25rem 0.5rem 0rem rgba(6, 35, 49, 0.50);
}

#text1-seconddiv-s3{
color: var(--clr-Blue-Medium, #0C3143);
font-family: Lexend;
font-size: 1.5rem;
font-style: normal;
font-weight: 400;
line-height: normal;
margin-left: 0.5rem;
margin-top: 0.5rem;
}

#text2-seconddiv-s3{
color: var(--clr-Blue-Medium, #0C3143);
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


#photo2-section3{  
width: 22.5rem;
height: 15.625rem;
border-radius: 1.5rem 1.5rem 0rem 0rem;
background:lightgray 50% / cover no-repeat;
}

#thirddiv-section3{
width: 22.5rem;
border-radius: 1.5rem 1.5rem 0rem 0rem;
background: var(--clr-White-Light, #F9F9F9);
box-shadow: 0.125rem 0.25rem 0.5rem 0rem rgba(6, 35, 49, 0.50);
}

#text1-thirddiv-s3{
color: var(--clr-Blue-Medium, #0C3143);
font-family: Lexend;
font-size: 1.5rem;
font-style: normal;
font-weight: 400;
line-height: normal;
margin-left: 0.5rem;
margin-top: 0.5rem;
}

#text2-thirddiv-s3{
color: var(--clr-Blue-Medium, #0C3143);
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


#photo3-section3{
width: 22.5rem;
height: 15.625rem;
background:lightgray 0.0799rem -12.3836rem / 100% 189.732% no-repeat;
box-shadow: 0.25rem 0.25rem 0.25rem 0rem rgba(0, 0, 0, 0.25);
border-radius: 1.5rem 1.5rem 0rem 0rem;
}

#secondbox-3imags-section3{
display: flex;
justify-content: center;
gap: 3.125rem;
margin-top: 4rem;
}

#fourthdiv-section3{
width: 22.5rem;
border-radius: 1.5rem 1.5rem 0rem 0rem;
background: var(--clr-White-Light, #F9F9F9);
box-shadow: 0.125rem 0.25rem 0.5rem 0rem rgba(6, 35, 49, 0.50);
}

#text1-fourthdiv-s3{
color: var(--clr-Blue-Medium, #0C3143);
font-family: Lexend;
font-size: 1.5rem;
font-style: normal;
font-weight: 400;
line-height: normal;
margin-left: 0.5rem;
margin-top: 0.5rem;
}

#text2-fourthdiv-s3{
color: var(--clr-Blue-Medium, #0C3143);
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

#photo4-section3{
width: 22.5rem;
height: 15.625rem;
background: lightgray 0.0445rem 0.0002rem / 99.912% 99.982% no-repeat;
box-shadow: 0.25rem 0.25rem 0.25rem 0rem rgba(0, 0, 0, 0.25);
border-radius: 1.5rem 1.5rem 0rem 0rem;
}

#fifthdiv-section3{
width: 22.5rem;
border-radius: 1.5rem 1.5rem 0rem 0rem;
background: var(--clr-White-Light, #F9F9F9);
box-shadow: 0.125rem 0.25rem 0.5rem 0rem rgba(6, 35, 49, 0.50);
}

#text1-fifthdiv-s3{
color: var(--clr-Blue-Medium, #0C3143);
font-family: Lexend;
font-size: 1.5rem;
font-style: normal;
font-weight: 400;
line-height: normal;
margin-left: 0.5rem;
margin-top: 0.5rem;
}

#text2-fifthdiv-s3{
color: var(--clr-Blue-Medium, #0C3143);
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

#photo5-section3{
width: 22.5rem;
height: 15.625rem; 
background: lightgray 0rem -2.2418rem / 100% 189.732% no-repeat;
box-shadow: 0.25rem 0.25rem 0.25rem 0rem rgba(0, 0, 0, 0.25);
border-radius: 1.5rem 1.5rem 0rem 0rem;
}

#sixthdiv-section3{
width: 22.5rem;
border-radius: 1.5rem 1.5rem 0rem 0rem;
background: var(--clr-White-Light, #F9F9F9);
box-shadow: 0.125rem 0.25rem 0.5rem 0rem rgba(6, 35, 49, 0.50);
}

#text1-sixthdiv-s3{
color: var(--clr-Blue-Medium, #0C3143);
font-family: Lexend;
font-size: 1.5rem;
font-style: normal;
font-weight: 400;
line-height: normal;
margin-left: 0.5rem;
margin-top: 0.5rem;
}

#text2-sixthdiv-s3{
color: var(--clr-Blue-Medium, #0C3143);
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



#photo6-section3{
width: 22.5rem;
height: 15.625rem;
background: lightgray -7.9138rem -8.9884rem / 181.389% 189.732% no-repeat;
box-shadow: 0.25rem 0.25rem 0.25rem 0rem rgba(0, 0, 0, 0.25);
border-radius: 1.5rem 1.5rem 0rem 0rem;
}
.contate-nos-section4{
background-size: cover;
background-position: center;
background-image: url(../../public/img/182920b76787d631ad32939fc0d652ef.png);
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

#introduction{
width: 23.875rem;
height: 5.1875rem;
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

#logo-text{
display: flex;
  
}

#name{
color: var(--clr-Beige-Light, #F0C986);
font-family: "Lexend Deca";
font-size: 0.875rem;
font-style: normal;
font-weight: 300;
line-height: 150%; /* 21px */
letter-spacing: 0.0262rem;
}

#name-input{
width: 28.625rem;
padding: 1.0656rem 1.7049rem;   
border-radius: 0.3197rem;
border: 0.0532rem solid var(--clr-Beige-Light, #F0C986);
background: #343333;
}

#e-mail{
color: var(--clr-Beige-Light, #F0C986);
font-family: "Lexend Deca";
font-size: 0.875rem;
font-style: normal;
font-weight: 300;
line-height: 150%; /* 21px */
letter-spacing: 0.0262rem;
}

#email-input{
  
width: 28.625rem;
padding: 1.0656rem 1.7049rem;

border-radius: 0.3197rem;
border: 0.0532rem solid var(--clr-Beige-Light, #F0C986);
background: #343333;
}

#message{
color: var(--clr-Beige-Light, #F0C986);
font-family: "Lexend Deca";
font-size: 0.875rem;
font-style: normal;
font-weight: 300;
line-height: 150%; /* 21px */
letter-spacing: 0.0262rem;
}

#message-input{
  
width: 28.625rem;
height: 5.375rem;
padding: 1.0656rem 1.7049rem;
flex-shrink: 0;
border-radius: 0.3197rem;
border: 0.0532rem solid var(--clr-Beige-Light, #F0C986);
background: #343333;
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


.privacy-politics{
display: flex;
justify-content: center;
margin-top: 4.3438rem;
padding-bottom: 2.2563rem;
gap: 0.625rem;
}

#privacy-politics-cookies{
color: var(--clr-Beige-Light, #F0C986);
leading-trim: both;
text-edge: cap;
font-family: Lexend;
font-size: 1rem;
font-style: normal;
font-weight: 400;
line-height: normal;
}

#cabreras-year{
color: var(--clr-Beige-Light, #F0C986);
leading-trim: both;
text-edge: cap;
font-family: Lexend;
font-size: 1rem;
font-style: normal;
font-weight: 400;
line-height: normal;
}

#cabreras-year-div{
display: flex;
justify-content: center;
align-items: center;
gap: 0.1875rem;
}
/* 
// <uniquifier>: Use a uniquifier for the class name
// <weight>: Use a value from 100 to 900

.lexend-<lexend> {
  font-family: "Lexend", sans-serif;
  font-optical-sizing: auto;
  font-weight: <100>;
  font-style: normal;
} */
</style>