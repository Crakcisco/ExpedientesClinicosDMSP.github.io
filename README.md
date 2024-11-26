# ExpedientesClinicosDMSP.github.io

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">

  <meta http-equiv="X-UA-Compatible" content="ie=edge">

  <meta name="copyright" content="MACode ID, https://macodeid.com/">

  <link rel="icon" href="assets/img/historial-medico.png" type="image/x-icon">

  <title>Expediente Clínico DMSP</title>

  <link rel="stylesheet" href="assets/css/maicons.css">

  <link rel="stylesheet" href="assets/css/bootstrap.css">

  <link rel="stylesheet" href="assets/vendor/owl-carousel/css/owl.carousel.css">

  <link rel="stylesheet" href="assets/vendor/animate/animate.css">

  <link rel="stylesheet" href="assets/css/theme.css">
</head>
<body>

  <div class="back-to-top"></div>

  <header>
    <div class="topbar">
      <div class="container">
        <div class="row">
          <div class="col-sm-8 text-sm">
            <div class="site-info">
              <a href="#"><span class="mai-call text-primary"></span> 618-137-81-00</a>
              <span class="divider">|</span>
              <a href="#"><span class="mai-mail text-primary"></span> SeguridadPublicaDGO@gmail.com</a>
            </div>
          </div>

          </div>
        </div> <!-- .row -->
      </div> <!-- .container -->
    </div> <!-- .topbar -->

    <nav class="navbar navbar-expand-lg navbar-light shadow-sm">
      <div class="container">
        <a class="navbar-brand" href="#"><span class="text-primary">Expediente Clínico DMSP</a>


        <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupport" aria-controls="navbarSupport" aria-expanded="false" aria-label="Toggle navigation">
          <span class="navbar-toggler-icon"></span>
        </button>

        <div class="collapse navbar-collapse" id="navbarSupport">
          <ul class="navbar-nav ml-auto">
            <li class="nav-item active">
              <a class="nav-link" href="index.php">Inicio</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="trampa.php">Nuevo Expediente</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="trampa.php">Buscar Expediente</a>
            </li>
            <li class="nav-item">
              <a class="btn btn-primary ml-lg-3" href="login.php">Iniciar Sesión</a>
            </li>
          </ul>
        </div> 
      </div> 
    </nav>
  </header>

  <div class="page-hero bg-image overlay-dark" style="background-image: url(assets/img/inicio.jpeg);">
    <div class="hero-section">
      <div class="container text-center wow zoomIn">
        <span class="subhead">Durango Gobierno Municipal</span>
        <h1 class="display-4">Dirección Municipal de Seguridad Publica</h1>
      </div>
    </div>
  </div>


  <div class="bg-light">
    <div class="page-section py-3 mt-md-n5 custom-index">
      <div class="container">
        <div class="row justify-content-center">
          <div class="col-md-4 py-3 py-md-0">
            <div class="card-service wow fadeInUp">
              <div class="circle-shape bg-secondary text-white">
                <span class="mai-call"></span>
              </div>
              <p><span>Conexión directa</span> con la dependencia</p>
            </div>
          </div>
          <div class="col-md-4 py-3 py-md-0">
            <div class="card-service wow fadeInUp">
              <div class="circle-shape bg-primary text-white">
                <span class="mai-shield-checkmark"></span>
              </div>
              <p><span>Consultas</span> seguras</p>
            </div>
          </div>
          <div class="col-md-4 py-3 py-md-0">
            <div class="card-service wow fadeInUp">
              <div class="circle-shape bg-accent text-white">
                <span class="mai-time"></span>
              </div>
              <p><span>Tiempo de</span>respuesta reducido</p>
            </div>
          </div>
        </div>
      </div>
    </div> 

    <div class="page-section pb-0">
      <div class="container">
        <div class="row align-items-center">
          <div class="col-lg-6 py-3 wow fadeInUp">
            <h1>Información adicional</h1>
            <p class="text-black mb-4">Esta pagina web fue desarrollada como proyecto de residencia profesional para la Dirección
              Municipal de Seguridad Pública del Estado de Durango hecha por:
             <p class="text-black mb-4">Brandon Alan Sosa Salazar </p>
             <p class="text-black mb-4">Jose Francisco de la Cruz Santillan </p>
             <p class="text-black mb-4">Alumnos del Instituto Tecnologico de Durango</p>
            </p>
          </div>
          <div class="col-lg-3 wow fadeInRight" data-wow-delay="400ms">
            <div class="img-place custom-img-1">
              <img src="./assets/img/poli.png" alt="">
            </div>
          </div>
        </div>
      </div>
    </div> 
  </div> 

<!--
  <div class="page-section">
    <div class="container">
      <h1 class="text-center wow fadeInUp">Envianos tus comentarios</h1>
      <form class="main-form" action="http://localhost:3000/send-email" method="POST">
        <div class="row mt-5">
          <div class="col-12 col-sm-6 py-2 wow fadeInLeft">
            <input type="text" class="form-control" name="nombre" placeholder="Nombre completo">
          </div>
          <div class="col-12 col-sm-6 py-2 wow fadeInRight">
            <input type="text" class="form-control" name="email" placeholder="Email">
          </div>
          <div class="col-12 col-sm-6 py-2 wow fadeInLeft" data-wow-delay="300ms">
            <input type="date" class="form-control" name="fecha">
          </div>
          <div class="col-12 col-sm-6 py-2 wow fadeInRight" data-wow-delay="300ms">
            <select name="departamento" id="departement" class="custom-select">
              <option value="general">Medico general</option>
              <option value="cardiology">Cardiologo</option>
              <option value="dental">Dentista</option>
              <option value="neurology">Nutriologo</option>
              <option value="orthopaedics">Ortopedista</option>
            </select>
          </div>
          <div class="col-12 py-2 wow fadeInUp" data-wow-delay="300ms">
            <input type="text" class="form-control" name="telefono" placeholder="Numero telefonico">
          </div>
          <div class="col-12 py-2 wow fadeInUp" data-wow-delay="300ms">
            <textarea name="mensaje" id="message" class="form-control" rows="6" placeholder="Mensaje"></textarea>
          </div>
        </div>
        <button type="submit" class="btn btn-primary mt-3 wow zoomIn">Enviar</button>
      </form>
    </div>
  </div> 
-->

  <footer class="page-footer">
    <div class="container">
      <div class="row px-md-3">
        <div class="col-sm-6 col-lg-3 py-3">
          <h5>Dependencia</h5>
          <ul class="footer-menu">
            <li><a href="index.php">Inicio</a></li>
            <li><a href="trampa.php">Nuevo Registro</a></li>
            <li><a href="trampa.php">Buscar Expediente</a></li>
            <li><a href="login.php">Iniciar Sesión</a></li>
          </ul>
        </div>
        <div class="col-sm-6 col-lg-3 py-3">
          <h5>Más información</h5>
          <ul class="footer-menu">
            <li><a href="terminos.php">Terminos y condiciones</a></li>
            <li><a href="privacidad.php">Privacidad</a></li>
            <li><a href="advertencias.php">Advertencias</a></li>
          </ul>
        </div>
        <div class="col-sm-6 col-lg-3 py-3">
          <h5>Contacto</h5>
          <p class="footer-link mt-2">Carretera a Mexico kilometro 2.5, Blvrd de la Juventud S/N, Durango, 34208 Victoria de Durango, Durango</p>
          <a href="#" class="footer-link">618-137-81-00</a>
          <a href="#" class="footer-link">SeguridadPublicaDGO@gmail.com</a>

          <h5 class="mt-3">Redes Sociales</h5>
          <div class="footer-sosmed mt-3">
            <a href="https://www.facebook.com/SEGP.DC/?locale=es_LA" target="_blank"><span class="mai-logo-facebook-f"></span></a>
            <a href="https://x.com/dmspdgo" target="_blank"><span class="mai-logo-twitter"></span></a>
          </div>
        </div>
      </div>

      <hr>

      <p id="copyright">Copyright &copy; 2024 <a target="_blank">Alumnos ITD</a>. Todos los derechos reservados</p>
    </div>
  </footer>

<script src="assets/js/jquery-3.5.1.min.js"></script>

<script src="assets/js/bootstrap.bundle.min.js"></script>

<script src="assets/vendor/owl-carousel/js/owl.carousel.min.js"></script>

<script src="assets/vendor/wow/wow.min.js"></script>

<script src="assets/js/theme.js"></script>
  
</body>
</html>
