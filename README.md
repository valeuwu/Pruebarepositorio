# Pruebarepositorio
{% load static %}

<link
rel = "stylesheet"
type = "text/css"
href = "{% static  'adoptanimal/css/bootstrap.css' %}"
/>

<html>
    <body>
      <body style="background-color:#eb7373;"> <!-- color de fondo -->

        <nav id="navbar-example2" class="navbar navbar-light bg-light px-3">
          <a class="navbar-brand" href="#">AdoptAnimal
            <img src="{% static 'img/logo.png' %}" class="img" alt="..." width = "40">
          </a>
          <ul class="nav nav-pills">
            <li class="nav-item">
              <a class="nav-link" href="#scrollspyHeading1">Quienes somos</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#scrollspyHeading2">Como puedes adoptar</a>
            </li>
            <li class="nav-item dropdown">
              <a class="nav-link dropdown-toggle" data-bs-toggle="dropdown" href="#" role="button" aria-expanded="false"></a>
              <ul class="dropdown-menu">
                <li><a class="dropdown-item" href="#scrollspyHeading3">Third</a></li>
                <li><a class="dropdown-item" href="#scrollspyHeading4">Fourth</a></li>
                <li><hr class="dropdown-divider"></li>
                <li><a class="dropdown-item" href="#scrollspyHeading5">Fifth</a></li>
              </ul>
            </li>
          </ul>
        </nav> <!-- barra superior-->

        

        <div align = "center">
          
          <img src="{% static 'img/banner2.gif' %}" class="gif" alt="..." width = "1500"> <!--banner-->
          
          <div data-bs-spy="scroll" data-bs-target="#navbar-example2" data-bs-offset="0" class="scrollspy-example" tabindex="0">
            <h2 id="scrollspyHeading1">Quienes somos</h2>
            <p> <div class="mw-80" width = "100px">ADOPTANIMAL es un proyecto que permite
              adoptar mascotas sin hogar de la manera más
              fácil y sencilla mediante una aplicación móvil.
              
              Nuestra aplicación permite crear un perfil para las
              mascotas que serán dadas en adopción, de esta
              forma los usuarios que quieran un nuevo
              compañero tendrán toda la información a su
              disposición para escoger un compañero ideal
              según lo que busquen, facilitando de esta forma
              que todas nuestras mascotas tengan más
              oportunidades de ser adoptados. Todos los animales tienen derecho a ser felices.

              <p></p>
             
              <img src="{% static 'img/familiaconperro.png' %}" class="img" alt="..." width = "700">
            </div></p>

            <h2 id="scrollspyHeading2">¿Cómo puedes adoptar?</h2>
            <p>Descarga nuestra aplicación y te mostraremos una selección de mascotas que puede que te gusten. 
              Aparecerá una imagen de la mascota que se encunetra en adopción con una pequeña descripción. 
              Si consideras que esta mascota es la ideal para ti, preciona el corazón, de esta forma nos harás saber que estas interesado. 
              Podrás acceder a un chat con la persona que realiza la adopción. </p>
            <img src="{% static 'img/peluso.png' %}" class="img" alt="...">

          </div> <!--secciones-->

        <p></p>

        <div class="card" style="width: 18rem;">
            <img src="{% static 'img/img.png' %}" class="card-img-top" alt="...">
            <div class="card-body">
              <h5 class="card-title">El gatito agradecido <3</h5>
              <p class="card-text">Gracias por visitar nuestra página.</p>
              <a href="#" class="btn btn-primary">Ir al inicio</a>
            </div>
          </div> <!-- tarjeta gatito-->
          

     

    </body>
</html>
