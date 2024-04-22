<template>
    <section>
    <div ngIf="languaje == 'en'" class="strip-nav-exterior d-md-none">
        <div class="list-wrapper ">
            <div class="menu">
                <h5>Menu</h5>
            </div>
            <ul class="navbar-nav">
                <li class="nav-item active">
                <router-link to="/" id="logo-url">
                <img alt="Vue logo" src="../../public/img/Logo-Beage (1).png" id="logo-url">
                </router-link> 
                </li>

                <li class="nav-item active">
                    <router-link class="nav-link active" to="/">Home</router-link> 
                </li>
                <li class="nav-item">
                    <router-link class="nav-link active" to="/servicos">Services</router-link>
                </li>
                <li class="nav-item">
                    <router-link class="nav-link active" to="/about">About</router-link>
                </li>
                <li class="nav-item">
                    <router-link class="nav-link active" to="/contact-us">Contact Us</router-link>
                </li>
            </ul>
            <div class="menu  mt-4">
                <h5>Social Networks</h5>
            </div>
            <ul class="navbar-nav socialNetworks-list">
                <li class="nav-item active">
                    <a class="nav-link active" aria-current="page" href="https://www.facebook.com/alian.medinascabrera" target="blank">Facebook</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" aria-current="page" href="https://www.instagram.com/medinascabrera/" target="blank">Instagram</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" aria-current="page" href="https://twitter.com/AmcAlian" target="blank">Tweeter</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" aria-current="page" href="https://www.linkedin.com/in/alian-medina-7a14101a9/" target="blank">Linkedin</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" aria-current="page" href="https://github.com/alianmc1988" target="blank">GitHub</a>
                </li>
            </ul>
        </div>
    
    </div>
    <!-- Barra de nav cell spanish -->
    <div ngIf="languaje == 'es'" class="strip-nav-exterior d-md-none">
        <div class="list-wrapper ">
            <div class="menu">
                <h5>Menu</h5>
            </div>
            <ul class="navbar-nav">
                <li class="nav-item active">
                    <router-link class="nav-link active" to="/">Home</router-link> 
                </li>
                <li class="nav-item">
                    <router-link class="nav-link active" to="/servicos">Services</router-link>
                </li>
                <li class="nav-item">
                    <router-link class="nav-link active" to="/about">About</router-link>
                </li>
                <li class="nav-item">
                    <router-link class="nav-link active" to="/contact-us">Contact Us</router-link>
                </li>
            </ul>
            <div class="menu  mt-4">
                <h5>Redes Sociales</h5>
            </div>
            <ul class="navbar-nav socialNetworks-list">
                <li class="nav-item active">
                    <a class="nav-link active" aria-current="page" href="https://www.facebook.com/alian.medinascabrera" target="blank">Facebook</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" aria-current="page" href="https://www.instagram.com/medinascabrera/" target="blank">Instagram</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" aria-current="page" href="https://twitter.com/AmcAlian" target="blank">Tweeter</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" aria-current="page" href="https://www.linkedin.com/in/alian-medina-7a14101a9/" target="blank">Linkedin</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" aria-current="page" href="https://github.com/alianmc1988" target="blank">GitHub</a>
                </li>
            </ul>
        </div>
    
    </div>
    <!-- Fin barra nav cell spanish -->
    
    <!-- barra nav PC English -->
    <nav ngIf="languaje == 'en'" class="navbar d-md-flex navbar-expand-md navbar-dark bg-dark banner">
        <div class="container long">
            <div class="navbar-toggler-icon d-md-none"></div>
    
            <!-- <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarsExample08" aria-controls="navbarsExample08" aria-expanded="false" aria-label="Toggle navigation">
          <span class="navbar-toggler-icon"></span>
        </button> -->
    
            <div class="collapse navbar-collapse justify-content-md-center" id="navbarsExample08">
                <ul class="navbar-nav">
                <li class="nav-item active">
                    <router-link class="nav-link active" to="/">Home</router-link> 
                </li>
                <li class="nav-item">
                    <router-link class="nav-link active" to="/servicos">Services</router-link>
                </li>
                <li class="nav-item">
                    <router-link class="nav-link active" to="/about">About</router-link>
                </li>
                <li class="nav-item">
                    <router-link class="nav-link active" to="/contact-us">Contact Us</router-link>
                </li>
            </ul>
            </div>
            <app-switch></app-switch>
        </div>
    
    
    </nav>
    <!-- Fin barra nav PC English -->
    
    <!-- Barra nav PC Spanish -->
    <nav ngIf="languaje == 'es'" class="navbar d-md-flex navbar-expand-md navbar-dark bg-dark banner">
        <div class="container long">
            <div class="navbar-toggler-icon d-md-none"></div>
    
            <div class="collapse navbar-collapse justify-content-md-center" id="navbarsExample08">
                <ul class="navbar-nav">
                <li class="nav-item active">
                    <router-link class="nav-link active" to="/">Home</router-link> 
                </li>
                <li class="nav-item">
                    <router-link class="nav-link active" to="/servicos">Services</router-link>
                </li>
                <li class="nav-item">
                    <router-link class="nav-link active" to="/about">About</router-link>
                </li>
                <li class="nav-item">
                    <router-link class="nav-link active" to="/contact-us">Contact Us</router-link>
                </li>
            </ul>
            </div>
            <app-switch></app-switch>
        </div>
    
    
    </nav>
    </section>
    </template>
    
    <script>
    export default {
        name: 'NavBar'
    }
    
    </script>
    
    <style scoped>
    .bd-placeholder-img {
        font-size: 1.125rem;
        text-anchor: middle;
        -webkit-user-select: none;
        -moz-user-select: none;
        user-select: none;
      }
      nav{
        z-index: 20;
        width: 100%;
        position: fixed;
       
        }
        
      .strip-nav-exterior{
        z-index: 50;
        position: fixed;
        background-color: transparent;
        width: 230px;
        padding-bottom: 2px;
        padding-top: 40px;
        left: -180px;   /*original -180px*/
        transition: .7s;
        height: 30px;
      }
      .strip-nav-exterior:hover{
        left: 0;
        transition: 0.7s;
        height: 100%;
        background-color: rgb(31, 29, 34);
        
      }
      
      .menu{
        border-bottom: rgb(216, 133, 0) 2px solid;
      }
     .menu h5{
        /* color: cornsilk; */
        margin-left: 30px;
      }
      
      .list-wrapper{
      background-color: transparent;
        padding-top: 50px;
        padding-bottom: 50px;
        box-sizing: content-box;
        max-width: 170px;
      }
      .list-wrapper li{
        padding-left: 30px;
      }
      
      .list-wrapper li a{
      display: inline-block;
      color: aliceblue;
      }
      .list-wrapper li a:hover{
        text-decoration: underline 2px solid white;
        }
       
      img{
        padding-left: 10px;
        width: 65px;
        height: 20px;
      }
      
      @media (min-width: 768px) {
        .bd-placeholder-img-lg {
          font-size: 3.5rem;
        }
        img{
          padding-left: 10px;
          width: 65px;
        }
        nav{
          z-index: 50;
          width: 100%;
          position: fixed;
          transition: 500ms;
         
          }
        #logo-url {
            height: 40px;
            width: 60px;
            margin: auto;
            margin-left: 0 ;
            }
                    
      }
    
    </style>