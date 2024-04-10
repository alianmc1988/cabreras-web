<template>
<div id="nav">
<i class="fa-solid fa-bars"></i>

  <router-link to="/" id="logo-url">
        <img alt="Vue logo" src="../../public/img/Logo-Beage (1).png" id="logo-url">
  </router-link> 
  <router-link to="/">Home</router-link> 
  <router-link to="/about">About</router-link>
  <router-link to="/servicos">Services</router-link>
  <router-link to="/contact-us">Contact Us</router-link>

</div>
</template>

<script>
export default {
    name: 'NavBar'
}

</script>

<style scoped>
#nav{
    background-color: #222;
    border-bottom: 4px solid #111;
    padding: 15px 50px;
    display: flex;
    align-items: center;
    justify-content: flex-end;

}

#nav a {
    color: #9d9d9d;
    margin-left: 12px;
    text-decoration: none;
    transition: .9;
}

#nav a:hover {
    color: white;
}

#logo-url {
  height: 40px;
  width: 60px;
  margin: auto;
  margin-left: 0 ;
}
  /* Media query para pantallas más pequeñas (como tablets y celulares) */
@media (max-width: 100vh) {
  nav ul {
    flex-direction: column; /* Apila los elementos verticalmente */
    align-items: stretch; /* Ajusta el ancho de los elementos al 100% */
  }

}

</style>