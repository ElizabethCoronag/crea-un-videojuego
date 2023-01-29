<!DOCTYPE html>
<html lang="es">
    <head>
        <title>Proyecto|TercerParcial|Programación</title>
        <!-- Bootstrap -->
        <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.2.2/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-Zenh87qX5JnK2Jl0vWa8Ck2rdkQ2Bzep5IDxbcnCeuOxjzrPF/et3URy9Bv1WTRi" crossorigin="anonymous">
        <!-- Iconos de Bootstrap -->
        <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.9.1/font/bootstrap-icons.css">
        <!-- CSS -->
        <link href="style.css" rel="stylesheet">
        <!--fonts-->
        <link rel="preconnect" href="https://fonts.googleapis.com">
        <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
        <link href="https://fonts.googleapis.com/css2?family=Montserrat+Alternates&family=Noto+Serif&display=swap" rel="stylesheet">
    </head>
    <body>
        <!--barra de navegación-->
        <nav class="navbar bg-body-tertiary">
            <div class="container">
              <a class="navbar-brand" href="#">
                <img src="imagenes/Logo1.jpg" alt="LogoV" width="30" height="24">
              </a>
            </div>
        </nav>
        <!--Titulo-->
        <section class="hero align-items-stretch">
            <div class="hero-principal d-flex flex-column justify-content-center align-items-center">
              <h1>Un titulo</h1>
            </div>
        </section>
        <!--seccion oscura-->
        <br>
        <section id="seccion-oscura" class="seccion-oscura">
            <div class="container">
              <div class="container text-center rectangulo d-flex justify-content-evenly">
                <div class="row">
                  <div class="col-12 col-md-6 seccion-titulo" id="empieza a hacer videojuegos">
                    Subtitulo
                  </div>
                  <div class="col-12 col-md-6 descripcion">
                    jhbu                  
                  </div>
                  </div>
                </div>
              </div>
            </div>
        </section>
        <!--explicacion (opcional)-->
        <section id="seccion-xplicacion" class="seccion-explicacion">
            <h1>Algo contigo</h1>
            <p>Y hace falta que te diga que me muero por tener algo contigo, y es que no te has dado cuenta de lo mucho que me cuesta ser tu amiga, ya me quedan muy pocos caminos y aunque te parezca un desatino, no quisiera yo morirme sin tener algo contigo</p>
        </section>
        <!--lista videos-->
        <nav id="seccion-videos" class="navbar bg-body-tertiary px-3 mb-3">
            <a class="seccion-videos" href="#">Inicio</a>
            <ul class="nav nav-pills">
              <li class="nav-item">
                <a class="nav-link" href="#scrollspyHeading1">First</a>
              </li>
              <li class="nav-item">
                <a class="nav-link" href="#scrollspyHeading2">Second</a>
              </li>
              <li class="nav-item dropdown">
                <a class="nav-link dropdown-toggle" data-bs-toggle="dropdown" href="#" role="button" aria-expanded="false">Dropdown</a>
                <ul class="dropdown-menu">
                  <li><a class="dropdown-item" href="#scrollspyHeading3">Third</a></li>
                  <li><a class="dropdown-item" href="#scrollspyHeading4">Fourth</a></li>
                  <li><hr class="dropdown-divider"></li>
                  <li><a class="dropdown-item" href="#scrollspyHeading5">Fifth</a></li>
                </ul>
              </li>
            </ul>
        </nav>
        <div data-bs-spy="scroll" data-bs-target="#navbar-example2" data-bs-root-margin="0px 0px -40%" data-bs-smooth-scroll="true" class="scrollspy-example bg-body-tertiary p-3 rounded-2" tabindex="0">
            <h4 id="scrollspyHeading1">First heading</h4>
            <p>...</p>
            <h4 id="scrollspyHeading2">Second heading</h4>
            <p>...</p>
            <h4 id="scrollspyHeading3">Third heading</h4>
            <p>...</p>
            <h4 id="scrollspyHeading4">Fourth heading</h4>
            <p>...</p>
            <h4 id="scrollspyHeading5">Fifth heading</h4>
            <p>...</p>
        </div>
        <!--lista contenido-->
        <br>
        <section id="seccion-contenido" class="seccion-contenido">
          <div class="row">
            <div class="col-4">
              <div id="list-example" class="list-group">
                <a class="list-group-item list-group-item-action" href="#list-item-1">Item 1</a>
                <a class="list-group-item list-group-item-action" href="#list-item-2">Item 2</a>
                <a class="list-group-item list-group-item-action" href="#list-item-3">Item 3</a>
                <a class="list-group-item list-group-item-action" href="#list-item-4">Item 4</a>
              </div>
            </div>
            <div class="col-8">
              <div data-bs-spy="scroll" data-bs-target="#list-example" data-bs-smooth-scroll="true" class="scrollspy-example" tabindex="0">
                <h4 id="list-item-1">Item 1</h4>
                <p>Y cuando hablas los angeles cantan desde arriba, las palabras cotidianas parecen convertirse en canciones de amor, entregas tu corazon y alma para mi, y la vida siempre sera, la vida en rosa</p>
                <iframe width="350" height="200" src="https://www.youtube.com/embed/5LuV3hM8krY" title="El protagonista egocéntrico- Harry Potter vs How I met your mother" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen aling="center"></iframe>
                <h4 id="list-item-2">Item 2</h4>
                <p>Y cuando hablas los angeles cantan desde arriba, las palabras cotidianas parecen convertirse en canciones de amor, entregas tu corazon y alma para mi, y la vida siempre sera, la vida en rosa</p>
                <h4 id="list-item-3">Item 3</h4>
                <p>Y cuando hablas los angeles cantan desde arriba, las palabras cotidianas parecen convertirse en canciones de amor, entregas tu corazon y alma para mi, y la vida siempre sera, la vida en rosa</p>
                <h4 id="list-item-4">Item 4</h4>
                <p>Y cuando hablas los angeles cantan desde arriba, las palabras cotidianas parecen convertirse en canciones de amor, entregas tu corazon y alma para mi, y la vida siempre sera, la vida en rosa</p>            </div>
            </div>
          </div>

        <!--video 5-->
        <br>
        <section id="seccion-video">
            <iframe width="500" height="300" src="https://www.youtube.com/embed/5LuV3hM8krY" title="El protagonista egocéntrico- Harry Potter vs How I met your mother" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen aling="center"></iframe>
        </section>

        </section>
        <footer>

        </footer>
    </body>
</html>
