<!DOCTYPE html>
<html5 lang="es">

<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Los Iracundos</title>
  <style>
    * { box-sizing: border-box; }
    body { font-family: Arial; margin: 20px; }
    .encabezado { background: #2196f3; color: green; padding: 20px; text-align: center; }
    .encabezado h1 { margin: 0; }
    .menu { background: #333; color: blue; padding: 20px; }
    .menu a { color: white; text-decoration: none; padding: 0 8px; }
    .menu a:hover { color: #2196f3; text-decoration: underline; }
    .contenido { display: flex; gap: 10px; margin-top: 10px; }
    .principal { background: #DDEEFF; padding: 30px; width: 70%; }
    .lateral { background: #DDF5DD; padding: 30px; width: 30%; }
    .detalle { background: #DDEEFF; padding: 30px; margin-top: 10px; }
    .detalle a { color: #1565c0; }
    .pie { background: #555; color: white; padding: 15px; text-align: center; margin-top: 10px; }
  </style>
</head>

<body>

  <!-- PÁGINA DE INICIO -->
  <div id="inicio" class="pagina">
    <div class="encabezado">
      <h1>Los Iracundos</h1>
    </div>
    <div class="menu">
      <a href="#biografía" target="_blank" rel="noopener">Biografía</a> |
      <a href="#galería" target="_blank" rel="noopener">Galería</a> |
      <a href="#videos musicales" target="_blank" rel="noopener">Videos</a> |
      <a href="#catálogo de canciones" target="_blank" rel="noopener">Catálogo de canciones</a>
      <a href="#letras de canciones" target="_blank" rel="noopener">Letras de canciones</a>
    </div>
    <div class="contenido">
      <div class="principal">
        <h2>Bienvenidos</h2>
        <p>Hola, bienvenido a la página biográfica del grupo Los Iracundos</p>
      </div>
      <div class="lateral">
        <h2>Proyecto de Desarrollo de Plataformas Web</h2>
        <p>Buenas noches</p>
      </div>
    </div>
  </div>

  <!-- BIOGRAFÍA -->
  <div id="biografia" class="pagina" hidden>
    <div class="encabezado">
      <h1>Biografía</h1>
    </div>
    <div class="detalle">
      <h2>Nombre artístico</h2>
      <p>El nombre artistico del grupo es Los Iracundos.</p>
      <h2>Biografía breve</h2>
      <p>Los Iracundos es una banda uruguaya de pop rock originaria de Paysandú, considerada en Uruguay la más importante del género. Se originó en 1958 bajo el nombre Los Blue Kings, inspirada en el rock and roll estadounidense de la época, y tuvieron su debut oficial en 1961, año en que lanzaron su primer sencillo con el sello uruguayo Clave. En 1964, firmaron con el sello RCA Victor en Argentina, donde cambiaron su nombre por Los Iracundos y adoptaron su característico estilo melódico y romántico, incorporándose al movimiento de la «nueva ola». La banda tuvo un crecimiento exponencial durante la década de 1960 que los consagraría internacionalmente, con numerosos discos editados, participaciones en películas y giras por América, Europa y Estados Unidos, incluyendo una presentación en el Madison Square Garden de Nueva York. Su mayor éxito vino en 1968 con «Puerto Montt» (Franco/Valdez), la canción más recordada de su carrera. El grupo reafirmó su popularidad en los años 1970 y 1980, editando varios discos de oro. El cantante Eduardo Franco es el autor de casi todo el repertorio compuesto por la banda, que también incluye composiciones instrumentales.</p>
      <h2>País de origen</h2>
      <p>El país de origen del grupo es de Uruguay.</p>
      <p><a href="#inicio">← Volver al inicio</a></p>
    </div>
  </div>

  <!-- FOTOS -->
  <div id="fotos" class="pagina" hidden>
    <div class="encabezado">
      <img src="randy.jpeg" alt="Randy" width="300">
      <img src="randy1.jpeg" alt="Randy 1" width="300">
      <p><a href="#inicio">← Volver al inicio</a></p>
    </div>
  </div>

<!-- MÚSICA -->
  <div id="musica" class="pagina" hidden>
    <div class="encabezado">
      <h1>Música</h1>
    </div>
    <div class="detalle">
      <h2>Discografía y canciones</h2>
      <p>Nombre de la canción</p>
      <audio controls src="La Casa del Sol Naciente (The House Of The Rising Sun) - Jinsop.mp3" style="width: 100%;"></audio>
      <p><a href="#inicio">← Volver al inicio</a></p>
    </div>
  </div>

<!-- VIDEO -->
  <div id="video" class="pagina" hidden>
    <div class="encabezado">
      <h1>Video</h1>
    </div>
    <div class="detalle">
      <h2>Videos</h2>
      <p>Nombre del video</p>
      <video controls src="video_randy.mp4" style="width: 100%; max-height: 450px;"></video>
      <p><a href="#inicio">← Volver al inicio</a></p>
    </div>
  </div>
  
  <!-- PIE (se ve en todas las páginas) -->
  <div class="pie">
    Comentarios y sugerencias al correo: randydavesdesantiscruz1996@gmail.com - © 2026 Randy De Santis - Todos los derechos reservados
  </div>

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

</html5>
      </p>
    </div>
  </div>
</body>
</html>
