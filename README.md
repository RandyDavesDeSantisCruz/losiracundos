<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta name="description" content="Página Homenaje a Los Iracundos">
  <title>Los Iracundos</title>
  <style>
    * { box-sizing: border-box; }

    body {
      font-family: Arial, sans-serif;
      margin: 20px;
    }

    [hidden] { display: none !important; }

    .encabezado {
      background: #2196f3;
      color: white;
      padding: 20px;
      text-align: center;
    }
    .encabezado h1 { margin: 0; }

    .menu {
      background: #333;
      color: white;
      padding: 20px;
    }
    .menu a {
      color: white;
      text-decoration: none;
      padding: 0 8px;
    }
    .menu a:hover {
      color: #2196f3;
      text-decoration: underline;
    }

    .contenido {
      display: flex;
      gap: 10px;
      margin-top: 10px;
    }
    .principal {
      background: #DDEEFF;
      padding: 30px;
      width: 70%;
    }
    .lateral {
      background: #DDF5DD;
      padding: 30px;
      width: 30%;
    }

    .detalle {
      background: #DDEEFF;
      padding: 30px;
      margin-top: 10px;
    }
    .detalle a { color: #1565c0; }

    .galeria {
      display: flex;
      flex-wrap: wrap;
      gap: 15px;
      margin: 0 0 20px;
    }
    .galeria figure { margin: 0; }
    .galeria img {
      max-width: 220px;
      height: auto;
      border: 3px solid #2196f3;
      border-radius: 4px;
      background: #fff;
    }
    .galeria figcaption {
      text-align: center;
      margin-top: 5px;
    }

    audio, video {
      display: block;
      max-width: 100%;
      margin: 10px 0 20px;
    }

    .pie {
      background: #555;
      color: white;
      padding: 15px;
      text-align: center;
      margin-top: 10px;
    }
    .pie a { color: #90caf9; }

    @media (max-width: 700px) {
      .contenido { flex-direction: column; }
      .principal, .lateral { width: 100%; }
    }
  </style>
</head>
<body>

  <header class="encabezado">
    <h1>Los Iracundos</h1>
  </header>

  <nav class="menu">
    <a href="#biografia">Biografía</a> |
    <a href="#fotos">Fotos</a> |
    <a href="#musica">Música</a> |
    <a href="#video">Video</a>
  </nav>

  <main>

    <!-- INICIO -->
    <section class="pagina contenido" id="inicio">
      <article class="principal">
        <h2>Bienvenidos</h2>
        <p>Hola, bienvenido a mi página biográfica</p>
        <p>Proyecto de Desarrollo de Plataformas Web</p>
      </article>
      <aside class="lateral">
        <p>Buenas noches</p>
      </aside>
    </section>

    <!-- BIOGRAFÍA -->
    <section class="pagina detalle" id="biografia" hidden>
      <h2>Biografía</h2>
      <h3>Randy De Santis</h3>
      <p>
        Hola, me llamo Randy De Santis y tengo 29 años. Soy nacido en Guayaquil
        pero he vivido en Ventanas prácticamente toda mi vida y actualmente
        estudio en el 3er Semestre de la carrera de Sistemas de Información de
        la Universidad Técnica de Babahoyo.
      </p>
      <p><a href="#inicio">← Volver al inicio</a></p>
    </section>

    <!-- FOTOS -->
    <section class="pagina detalle" id="fotos" hidden>
      <h2>Fotos</h2>
      <div class="galeria">
        <figure>
          <img src="img/randy.jpg" alt="Foto de Randy">
          <figcaption>Randy</figcaption>
        </figure>
        <figure>
          <img src="img/randy1.jpg" alt="Foto 1 de Randy">
          <figcaption>Randy 1</figcaption>
        </figure>
      </div>
      <p><a href="#inicio">← Volver al inicio</a></p>
    </section>

    <!-- MÚSICA -->
    <section class="pagina detalle" id="musica" hidden>
      <h2>Música</h2>
      <h3>Discografía y canciones</h3>
      <p>Nombre de la canción</p>
      <audio controls src="audio/cancion.mp3">
        Tu navegador no soporta el elemento de audio.
      </audio>
      <p><a href="#inicio">← Volver al inicio</a></p>
    </section>

    <!-- VIDEO -->
    <section class="pagina detalle" id="video" hidden>
      <h2>Video</h2>
      <h3>Videos</h3>
      <p>Nombre del video</p>
      <video controls width="480" src="video/video.mp4">
        Tu navegador no soporta el elemento de video.
      </video>
      <p><a href="#inicio">← Volver al inicio</a></p>
    </section>

  </main>

  <footer class="pie">
    Randy Daves De Santis Cruz - Carrera de Sistemas de información 3er Semestre "C" Vespertino - Hecho en el 2026
    <a href="mailto:randydavesdesantiscruz1996@gmail.com">randydavesdesantiscruz1996@gmail.com</a>
    - &copy; 2026 Randy De Santis - Todos los derechos reservados
  </footer>

  <script>
    // Muestra solo la página que indica la dirección (#biografia, #fotos, etc.)
    function mostrar() {
      var id = location.hash.slice(1) || "inicio";
      var paginas = document.querySelectorAll(".pagina");
      var existe = false;

      paginas.forEach(function (p) {
        p.hidden = (p.id !== id);
        if (p.id === id) existe = true;
      });

      if (!existe) document.getElementById("inicio").hidden = false;
    }

    window.addEventListener("hashchange", mostrar);
    mostrar();
  </script>

</body>
</html>
