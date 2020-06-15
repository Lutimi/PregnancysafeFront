<template>
  <div id="app">

    <!-- Navigation -->
    <nav class="navbar navbar-expand-lg navbar   fixed-top" id="mainNav" style="background-color:#BEB5F5;">
      <div class="container">
        <a class="navbar-brand text-white  js-scroll-trigger" href="#pagetop">
        <img src="" width="30" height="30" class="d-inline-block align-top" alt="">Pregnancy Safe</a>
        <button class="navbar-toggler navbar-toggler-right" type="button" data-toggle="collapse" data-target="#navbarResponsive" aria-controls="navbarResponsive" aria-expanded="false" aria-label="Toggle navigation" style="background-color:#EDDDCC;" >
          Menu
          <i class="fas fa-bars"></i>
        </button>
        <div class="collapse navbar-collapse" id="navbarResponsive">
          <ul class="navbar-nav text-uppercase ml-auto">
            <li class="nav-item">
              <a class="nav-link js-scroll-trigger" href="#services">About</a>
            </li>
            <li class="nav-item">
              <a class="nav-link js-scroll-trigger" href="#portfolio">Services</a>  <router-link to="/page2">Navigate to Page2</router-link>
            </li>
            <li class="nav-item">
              <a class="nav-link js-scroll-trigger" href="#about">Consultas</a>
            </li>
            <li class="nav-item">
              <a class="nav-link js-scroll-trigger" href="#team">Api</a>
            </li>
            <li class="nav-item">
              <a class="nav-link js-scroll-trigger" href="#contact">Login</a>
            </li>
          </ul>
        </div>
     
      </div>
    </nav>

    <!-- Header -->
    <header class="masthead">
      <div class="container">
        <div class="intro-text">
          <div class="intro-lead-in">Cuida tu embarazo</div>
          <div class="intro-heading text-uppercase">Resuelve todas tus dudas</div>
          <a class="btn btn-primary btn-xl text-uppercase js-scroll-trigger" href="#services">comenza</a>
        </div>
      </div>
    </header>

    <!-- Encuestas a gran escala -->
    <section id="services">
      <div class="container">
        <div class="row">
          <div class="col-lg-12 text-center">
            <h2 class="section-heading text-uppercase">Encuestas a gran escala</h2>
            <h3 class="section-subheading text-muted"></h3>
          </div>
        </div>
        <div class="row text-center">
          <div class="col-md-4">
            <span class="fa-stack fa-4x">
              <i class="fas fa-circle fa-stack-2x text-primary"></i>
              <i class="fas fa-shopping-cart fa-stack-1x fa-inverse"></i>
            </span>
            <h4 class="service-heading">Citas</h4>
            <p class="text-muted text-justify"> 
              Citas virtuales con especiales, dispuesto a resolver todas tus dudas e inquetudes

            </p>
          </div>
          <div class="col-md-4">
            <span class="fa-stack fa-4x">
              <i class="fas fa-circle fa-stack-2x text-primary"></i>
              <i class="fas fa-laptop fa-stack-1x fa-inverse"></i>
            </span>
            <h4 class="service-heading">Comunicación</h4>
            <p class="text-muted text-justify">Comunicación de forma inmediata con especialistas (obstetras) por medio de chat</p>
          </div>
          <div class="col-md-4">
            <span class="fa-stack fa-4x">
              <i class="fas fa-circle fa-stack-2x text-primary"></i>
              <i class="fas fa-lock fa-stack-1x fa-inverse"></i>
            </span>
            <h4 class="service-heading">Informacion</h4>
            <p class="text-muted text-justify">Médicos dedicados a la salud de mujeres en las distintas etapas de su embarazo brindadando videos y documentos con informacion precisa recomendada por los mejores doctores </p>
          </div>
     
          
        </div>
         <div class=" center-block">
    <button id="singlebutton" name="singlebutton" class="btn btn-primary center-block">empieza</button>
</div>
        
<div class="text-center  mt-lg-5">
 
</div>
        
      </div>
      
    </section>

    <!-- Portfolio Grid -->
    <!-- <Portfolio></Portfolio> -->

    <!-- About -->
   

    <!-- Team -->
    <!-- <section class="bg-light" id="team">
      <div class="container">
        <div class="row">
          <div class="col-lg-12 text-center">
            <h2 class="section-heading text-uppercase">Our Amazing Team</h2>
            <h3 class="section-subheading text-muted">Lorem ipsum dolor sit amet consectetur.</h3>
          </div>
        </div>
        <div class="row">
          <div class="col-sm-4">
            <div class="team-member">
              <img class="mx-auto rounded-circle" src="img/team/1.jpg" alt="">
              <h4>Kay Garland</h4>
              <p class="text-muted">Lead Designer</p>
              <ul class="list-inline social-buttons">
                <li class="list-inline-item">
                  <a href="#">
                    <i class="fab fa-twitter"></i>
                  </a>
                </li>
                <li class="list-inline-item">
                  <a href="#">
                    <i class="fab fa-facebook-f"></i>
                  </a>
                </li>
                <li class="list-inline-item">
                  <a href="#">
                    <i class="fab fa-linkedin-in"></i>
                  </a>
                </li>
              </ul>
            </div>
          </div>
          <div class="col-sm-4">
            <div class="team-member">
              <img class="mx-auto rounded-circle" src="img/team/2.jpg" alt="">
              <h4>Larry Parker</h4>
              <p class="text-muted">Lead Marketer</p>
              <ul class="list-inline social-buttons">
                <li class="list-inline-item">
                  <a href="#">
                    <i class="fab fa-twitter"></i>
                  </a>
                </li>
                <li class="list-inline-item">
                  <a href="#">
                    <i class="fab fa-facebook-f"></i>
                  </a>
                </li>
                <li class="list-inline-item">
                  <a href="#">
                    <i class="fab fa-linkedin-in"></i>
                  </a>
                </li>
              </ul>
            </div>
          </div>
          <div class="col-sm-4">
            <div class="team-member">
              <img class="mx-auto rounded-circle" src="img/team/3.jpg" alt="">
              <h4>Diana Pertersen</h4>
              <p class="text-muted">Lead Developer</p>
              <ul class="list-inline social-buttons">
                <li class="list-inline-item">
                  <a href="#">
                    <i class="fab fa-twitter"></i>
                  </a>
                </li>
                <li class="list-inline-item">
                  <a href="#">
                    <i class="fab fa-facebook-f"></i>
                  </a>
                </li>
                <li class="list-inline-item">
                  <a href="#">
                    <i class="fab fa-linkedin-in"></i>
                  </a>
                </li>
              </ul>
            </div>
          </div>
        </div>
        <div class="row">
          <div class="col-lg-8 mx-auto text-center">
            <p class="large text-muted">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Aut eaque, laboriosam veritatis, quos non quis ad perspiciatis, totam corporis ea, alias ut unde.</p>
          </div>
        </div>
      </div>
    </section> -->

    <!-- Clients -->


    <!-- Contact -->
    <section id="contact">
      <div class="container">
        <div class="row">
          <div class="col-lg-12 text-center">
            <h2 class="section-heading text-uppercase">Unete a Median</h2>
            <h3 class="section-subheading  text-white">ya tienes cuenta? </h3>
          </div>
          
        </div>
        <div class="row">
          <div class="col-lg-12">
            <form id="contactForm" name="sentMessage" novalidate="novalidate">
              <div class="row">
                <div class="col-md-6">
                  <div class="form-group">
                    <input class="form-control" id="name" type="text" placeholder="Your Name *" required="required" data-validation-required-message="Please enter your name.">
                    <p class="help-block text-danger"></p>
                  </div>
                  <div class="form-group">
                    <input class="form-control" id="email" type="email" placeholder="Your Email *" required="required" data-validation-required-message="Please enter your email address.">
                    <p class="help-block text-danger"></p>
                  </div>
                  <div class="form-group">
                    <input class="form-control" id="phone" type="tel" placeholder="Your Phone *" required="required" data-validation-required-message="Please enter your phone number.">
                    <p class="help-block text-danger"></p>
                  </div>
                </div>
                <div class="col-md-6">
                  <div class="form-group">
                    <textarea class="form-control" id="message" placeholder="Your Message *" required="required" data-validation-required-message="Please enter a message."></textarea>
                    <p class="help-block text-danger"></p>
                  </div>
                </div>
                <div class="clearfix"></div>
                <div class="col-lg-12 text-center">
                  <div id="success"></div>
                  <button id="sendMessageButton" class="btn btn-primary btn-xl text-uppercase" type="submit">Send Message</button>
                </div>
              </div>
            </form>
          </div>
        </div>
      </div>
    </section>

    <!-- Footer -->
    <footer>
      <div class="container">
        <div class="row">
          <div class="col-md-4">
            <span class="copyright">Copyright &copy; PregnancySafe 2020</span>
          </div>
          <div class="col-md-4">
            <ul class="list-inline social-buttons">
              <li class="list-inline-item">
                <a href="#">
                  <i class="fab fa-twitter"></i>
                </a>
              </li>
              <li class="list-inline-item">
                <a href="#">
                  <i class="fab fa-facebook-f"></i>
                </a>
              </li>
              <li class="list-inline-item">
                <a href="#">
                  <i class="fab fa-linkedin-in"></i>
                </a>
              </li>
            </ul>
          </div>
          <div class="col-md-4">
            <ul class="list-inline quicklinks">
              <li class="list-inline-item">
                <a href="#">Privacy Policy</a>
              </li>
              <li class="list-inline-item">
                <a href="#">Terms of Use</a>
              </li>
            </ul>
          </div>
        </div>
      </div>
    </footer>

    <!-- Portfolio Modals -->

    <!-- Modal 1 -->
  

    <!-- Modal 6 -->
    
  </div>
</template>

<script>

import Portfolio from './components/Portfolio'

export default {
  name: 'app',
  components: {
    Portfolio
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

body {
  background: black;
}
</style>
