<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Los Iracundos</title>
  <style>
    * {
      box-sizing: border-box;
    }

    body {
      font-family: Arial, Helvetica, sans-serif;
      margin: 20px;
      background-color: #f4f6f9;
      color: #222;
      line-height: 1.6;
    }

    /* Evita que display:flex anule el atributo hidden */
    [hidden] {
      display: none !important;
    }

    /* Regla general para que ninguna imagen se salga de su contenedor */
    img {
      max-width: 100%;
      height: auto;
      display: block;
    }

    .encabezado {
      background: #2196f3;
      color: #ffffff;
      padding: 24px 20px;
      text-align: center;
      border-radius: 6px 6px 0 0;
    }

    .encabezado h1 {
      margin: 0;
      font-size: 2rem;
    }

    .encabezado p {
      margin: 6px 0 0;
      font-size: 0.95rem;
      opacity: 0.95;
    }

    .menu {
      background: #333;
      color: #bbb;
      padding: 14px 20px;
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      align-items: center;
      gap: 6px;
      border-radius: 0 0 6px 6px;
    }

    .menu a {
      color: #ffffff;
      text-decoration: none;
      padding: 6px 10px;
      border-radius: 4px;
      transition: background 0.2s, color 0.2s;
    }

    .menu a:hover,
    .menu a.activo {
      background: #2196f3;
      color: #ffffff;
    }

    .contenido {
      display: flex;
      gap: 12px;
      margin-top: 12px;
    }

    .principal {
      background: #DDEEFF;
      padding: 30px;
      width: 70%;
      border-radius: 6px;
    }

    .lateral {
      background: #DDF5DD;
      padding: 30px;
      width: 30%;
      border-radius: 6px;
    }

    .detalle {
      background: #DDEEFF;
      padding: 30px;
      margin-top: 12px;
      border-radius: 6px;
    }

    .detalle h2,
    .principal h2 {
      margin-top: 0;
      color: #0d47a1;
      border-bottom: 2px solid #90caf9;
      padding-bottom: 8px;
    }

    .detalle h3 {
      color: #1565c0;
      margin-bottom: 6px;
    }

    .detalle a,
    .volver {
      display: inline-block;
      margin-top: 15px;
      color: #1565c0;
      font-weight: bold;
      text-decoration: none;
    }

    .detalle a:hover,
    .volver:hover {
      text-decoration: underline;
    }

    /* Estilo para la fotografía en Biografía */
    .foto-biografia {
      background: #ffffff;
      padding: 14px;
      border-radius: 6px;
      max-width: 420px;
      margin: 12px 0;
      box-shadow: 0 2px 5px rgba(0, 0, 0, 0.08);
    }

    .foto-biografia img {
      width: 100%;
      border-radius: 4px;
    }

    .foto-biografia figcaption {
      margin-top: 8px;
      font-size: 0.9rem;
      color: #444;
      text-align: center;
      font-weight: bold;
    }

    .lista-items {
      list-style: none;
      padding: 0;
    }

    .lista-items li {
      background: #ffffff;
      margin-bottom: 14px;
      padding: 16px;
      border-left: 4px solid #2196f3;
      border-radius: 4px;
    }

    /* Contenedor responsivo para reproducir videos dentro de la página */
    .video-contenedor {
      margin-top: 10px;
      max-width: 560px;
      aspect-ratio: 16 / 9;
      border-radius: 6px;
      overflow: hidden;
      background-color: #000;
      box-shadow: 0 2px 6px rgba(0, 0, 0, 0.15);
    }

    .video-contenedor iframe {
      width: 100%;
      height: 100%;
      border: 0;
      display: block;
    }

    .enlace-respaldo {
      display: inline-block;
      margin-top: 8px;
      font-size: 0.88rem;
      color: #1565c0;
    }

    /* Cuadrícula y tarjetas de la Galería */
    .galeria-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(240px, 1fr));
      gap: 16px;
      margin-top: 15px;
    }

    .tarjeta-foto {
      background: #ffffff;
      padding: 14px;
      border-radius: 6px;
      text-align: center;
      box-shadow: 0 2px 5px rgba(0, 0, 0, 0.08);
      display: flex;
      flex-direction: column;
      justify-content: space-between;
    }

    .tarjeta-foto img {
      width: 100%;
      height: 220px;
      object-fit: cover;
      border-radius: 4px;
      background-color: #bbdefb;
    }

    .tarjeta-foto p {
      margin: 10px 0 0;
      font-weight: bold;
      color: #0d47a1;
      font-size: 0.95rem;
    }

    .pie {
      background: #555;
      color: white;
      padding: 16px;
      text-align: center;
      margin-top: 12px;
      border-radius: 6px;
      font-size: 0.9rem;
    }

    .pie a {
      color: #90caf9;
      text-decoration: none;
    }

    .pie a:hover {
      text-decoration: underline;
    }

    @media (max-width: 768px) {
      .contenido {
        flex-direction: column;
      }
      .principal,
      .lateral {
        width: 100%;
      }
    }
  </style>
</head>
<body>

  <header class="encabezado">
    <h1>Los Iracundos</h1>
    <p>Proyecto de Desarrollo de Plataformas Web</p>
  </header>

  <nav class="menu">
    <a href="#inicio">Inicio</a> <span>|</span>
    <a href="#biografia">Biografía</a> <span>|</span>
    <a href="#galeria">Galería</a> <span>|</span>
    <a href="#videos">Videos</a> <span>|</span>
    <a href="#musica">Catálogo de canciones</a> <span>|</span>
    <a href="#letras">Letras de canciones</a>
  </nav>

  <!-- PÁGINA: INICIO -->
  <main id="inicio" class="pagina contenido">
    <section class="principal">
      <h2>Bienvenidos</h2>
      <p>Hola, bienvenido a la página biográfica del grupo <strong>Los Iracundos</strong>.</p>
      <p>Explora en el menú superior la historia de esta legendaria agrupación uruguaya, su galería de recuerdos, videos destacados, discografía y las letras de sus canciones más recordadas.</p>
    </section>

    <aside class="lateral">
      <h3 id="saludo">Bienvenido a mi sitio.</h3>
      <p><strong>Origen:</strong> Paysandú, Uruguay (1958)</p>
      <p><strong>Género:</strong> Pop rock / Balada romántica / Nueva ola</p>
      <p><strong>Éxito emblemático:</strong> <em>Puerto Montt</em> (1968)</p>
    </aside>
  </main>

  <!-- PÁGINA: BIOGRAFÍA -->
  <section id="biografia" class="pagina detalle" hidden>
    <h2>Biografía</h2>

    <h3>Nombre artístico</h3>
    <p>El nombre artístico del grupo es <strong>Los Iracundos</strong>.</p>

    <h3>Biografía breve</h3>
    <p>
      Los Iracundos es una banda uruguaya de pop rock originaria de Paysandú, considerada en Uruguay la más importante del género. Se originó en 1958 bajo el nombre Los Blue Kings, inspirada en el rock and roll estadounidense de la época, y tuvieron su debut oficial en 1961, año en que lanzaron su primer sencillo con el sello uruguayo Clave. En 1964, firmaron con el sello RCA Victor en Argentina, donde cambiaron su nombre por Los Iracundos y adoptaron su característico estilo melódico y romántico, incorporándose al movimiento de la «nueva ola». La banda tuvo un crecimiento exponencial durante la década de 1960 que los consagraría internacionalmente, con numerosos discos editados, participaciones en películas y giras por América, Europa y Estados Unidos, incluyendo una presentación en el Madison Square Garden de Nueva York. Su mayor éxito vino en 1968 con «Puerto Montt» (Franco/Valdez), la canción más recordada de su carrera. El grupo reafirmó su popularidad en los años 1970 y 1980, editando varios discos de oro. El cantante Eduardo Franco es el autor de casi todo el repertorio compuesto por la banda, que también incluye composiciones instrumentales.
    </p>

    <h3>País de origen</h3>
    <p>El país de origen del grupo es Uruguay.</p>

    <h3>Género musical</h3>
    <p>El repertorio musical del grupo se basa en géneros como el pop, la canción melódica, la balada romántica, el rock, la nueva ola, la música instrumental y la música beat.</p>

    <h3>Año de inicio de su carrera</h3>
    <p>El grupo inició su carrera bajo el nombre de Los Blue Kings entre 1958 hasta el año de 1963, después en 1964 adoptaron el nombre de Los Iracundos, el cual ha sido el nombre de la agrupación hasta el día de hoy.</p>

    <h3>Fotografía del grupo</h3>
    <figure class="foto-biografia">
      <img src="Los_Iracundos_en_1968.jpg" alt="Los Iracundos en 1968">
      <figcaption>Los Iracundos en 1968.</figcaption>
    </figure>

    <a class="volver" href="#inicio">← Volver al inicio</a>
  </section>

  <!-- PÁGINA: GALERÍA -->
  <section id="galeria" class="pagina detalle" hidden>
    <h2>Galería</h2>
    <p>Momentos históricos de la trayectoria de Los Iracundos:</p>

    <div class="galeria-grid">
      <div class="tarjeta-foto">
        <img src="Los_Blue_Kings_entre_1958-1963.jpg" alt="Los Blue Kings entre 1958 y 1963">
        <p>Los Blue Kings entre 1958 - 1963</p>
      </div>
      <div class="tarjeta-foto">
        <img src="Los_Iracundos_en_1974.jpg" alt="Los Iracundos en 1974">
        <p>Los Iracundos en 1974</p>
      </div>
      <div class="tarjeta-foto">
        <img src="Los_Iracundos_en_1982.jpg" alt="Los Iracundos en 1982">
        <p>Los Iracundos en 1982</p>
      </div>
      <div class="tarjeta-foto">
        <img src="Los_Iracundos_en_1995.jpg" alt="Los Iracundos en 1995">
        <p>Los Iracundos en 1995</p>
      </div>
    </div>

    <a class="volver" href="#inicio">← Volver al inicio</a>
  </section>

  <!-- PÁGINA: CATÁLOGO DE CANCIONES -->
  <section id="musica" class="pagina detalle" hidden>
    <h2>Música — Discografía y canciones</h2>
    <ul class="lista-items">
      <li><strong>Puerto Montt</strong> (1968) — Álbum: <em>Puerto Montt</em></li>
      <li><strong>Te lo pido de rodillas</strong> (1970) — Álbum: <em>Los Iracundos</em></li>
      <li><strong>Es la lluvia que cae</strong> (1967) — Álbum: <em>Los Iracundos en Roma</em></li>
      <li><strong>Tú con él</strong> (1985) — Álbum: <em>Tú con él</em></li>
      <li><strong>Chiquilina</strong> (1971) — Álbum: <em>Agua con amor</em></li>
      <li><strong>Aprontate a vivir</strong> (1979) — Álbum: <em>Amor y fe</em></li>
    </ul>

    <a class="volver" href="#inicio">← Volver al inicio</a>
  </section>

  <!-- PÁGINA: VIDEOS -->
  <section id="videos" class="pagina detalle" hidden>
    <h2>Videos</h2>
    <ul class="lista-items">
      <li>
        <strong>Los Iracundos - Tú con él</strong>
        <div class="video-contenedor">
          <iframe src="https://www.youtube.com/embed/vM1ijxK55lY" title="Los Iracundos - Tú con él" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
        </div>
        <a class="enlace-respaldo" href="https://www.youtube.com/watch?v=vM1ijxK55lY" target="_blank" rel="noopener noreferrer">Ver en YouTube</a>
      </li>
    </ul>

    <a class="volver" href="#inicio">← Volver al inicio</a>
  </section>

  <!-- PÁGINA: LETRAS DE CANCIONES -->
  <section id="letras" class="pagina detalle" hidden>
    <h2>Letras de canciones</h2>

    <h3>Puerto Montt</h3>
    <p>
      Sentado frente al mar<br>
      Mil besos yo le di<br>
      Después le dije adiós<br>
      Todo termina aquí<br>
      Y ella me dijo así.<br>

      Abrázame y verás<br>
      Que el mundo es de los dos<br>
      Salgamos a correr<br>
      Busquemos el ayer<br>
      Que nos hizo feliz<br>

      Puerto Montt<br>
      Puerto Montt<br>
      Me alejé de ti<br>
      Sin saber por qué<br>

      Y yo la dejé<br>
      Sola frente al mar<br>
      Bajo el cielo azul<br>
      De Puerto Montt<br>

      Mil violines en su voz<br>
      Susurraron un adiós<br>
      Y un amor que se quedó<br>
      Perdido frente al mar<br>
      Y el viento lo llevó<br>

      Silencio sin piedad<br>
      Encontraré al volver<br>
      Mas en la soledad<br>
      Su voz me gritará<br>
      No, no te vayas de mí<br>

      Puerto Montt<br>
      Puerto Montt<br>
      Me alejé de ti<br>
      Sin saber por qué<br>

      Y yo la dejé<br>
      Sola frente al mar<br>
      Bajo el cielo azul<br>
      De Puerto Montt<br>

      La-la-la, la, la<br>
      La-la-la, la, la<br>
      La-la-la, la, la<br>
      La-la-la<br>

      La-la-la, la, la<br>
      La-la-la, la, la<br>
    </p>

    <h3>Fábula</h3>
    <p>
      El Sol sobre mi cama, hoy me vuelve a despertar<br>
      Y yo quiero dormir, dormir, dormir para olvidar<br>
      Que vivo en un desierto de cemento y soledad<br>

      Y tú<br>
      Entre brindis, noches<br>
      Y amantes<br>
      De ese mundo loco<br>
      Y errante<br>
      No vas a volver<br>
      Y yo sufriré<br>
      Resignado al ver<br>
      Que lo nuestro fue<br>

      Fábula<br>
      De un pobre tonto que siempre te amo<br>
      Y que sus puertas nunca más cerró<br>
      Con la esperanza de volverte a ver<br>

      Fábula<br>
      De una muchacha que siempre creyó<br>
      En cuentos de hadas y que confundió<br>
      Las madrugadas con amanecer<br>

      Fábula<br>
      La-la-la-la-la-la-la-la-la-la<br>
      La-la-la-la-la-la-la-la-la-la<br>
      La-la-la-la-la-la-la-la-la-la<br>

      Mi vida ya no es vida yo no sé que voy a hacer<br>
      Rogando a Dios le pido, me devuelva tu querer<br>
      Me estoy volviendo loco de sufrir y de llorar<br>

      Y tú<br>
      Entre brindis, noches y amantes<br>
      De ese mundo loco<br>
      Y errante<br>
      No vas a volver<br>
      Y yo sufriré<br>
      Resignado al ver<br>
      Que lo nuestro fue<br>

      Fábula<br>
      De un pobre tonto que siempre te amo<br>
      Y que sus puertas nunca más cerró<br>
      Con la esperanza de volverte a ver<br>

      Fábula<br>
      De una muchacha que siempre creyó<br>
      En cuentos de hadas y que confundió<br>
      Las madrugadas con amanecer<br>

      Fábula<br>
      La-la-la-la-la-la-la-la-la-la<br>
      La-la-la-la-la-la-la-la-la-la<br>
      La-la-la-la-la-la-la-la-la-la<br>
    </p>

    <h3>Te lo pido de rodillas</h3>
    <p>
      Te llamé porque hace un año que no hablamos<br>
      Para romper aquel adiós que nos juramos<br>
      Voy a pedirte de rodillas que regreses junto a mí<br>
      Porque soy de ti<br>
      Y te quiero como antes, mucho más<br>
      Te llamé porque te quiero todavía<br>
      Porque este amor<br>
      Me atormenta<br>
      Noche y día<br>
      Voy a pedirte de rodillas que regreses junto a mí<br>
      Porque soy de ti<br>
      y te quiero<br>
      Como antes,<br>
      Mucho más<br>
      Voy a pedirte de rodillas que regreses junto a mí<br>
      Porque soy de ti<br>
      y te quiero<br>
      Como antes,<br>
      Mucho más
    </p>

    <a class="volver" href="#inicio">← Volver al inicio</a>
  </section>

  <footer class="pie">
    Comentarios y sugerencias al correo:
    <a href="mailto:randydavesdesantiscruz1996@gmail.com">randydavesdesantiscruz1996@gmail.com</a>
    — © 2026 Randy De Santis - Todos los derechos reservados
  </footer>

  <script>
    // Convierte automáticamente enlaces watch?v= o youtu.be/ al formato /embed/ válido
    document.querySelectorAll(".video-contenedor iframe").forEach(function (frame) {
      var url = frame.getAttribute("src") || "";
      var coincidencia = url.match(/(?:youtube\.com\/watch\?v=|youtu\.be\/)([a-zA-Z0-9_-]{11})/);
      if (coincidencia) {
        frame.src = "https://www.youtube.com/embed/" + coincidencia[1];
      }
    });

    function mostrar() {
      var id = location.hash.slice(1) || "inicio";
      var paginas = document.querySelectorAll(".pagina");
      var enlaces = document.querySelectorAll(".menu a");
      var existe = false;

      paginas.forEach(function (p) {
        var esActual = (p.id === id);

        // Detiene los videos si el usuario cambia a otra sección
        if (!esActual && !p.hidden) {
          p.querySelectorAll("iframe").forEach(function (frame) {
            frame.src = frame.src;
          });
        }

        p.hidden = !esActual;
        if (esActual) existe = true;
      });

      if (!existe) {
        document.getElementById("inicio").hidden = false;
        id = "inicio";
      }

      enlaces.forEach(function (a) {
        a.classList.toggle("activo", a.getAttribute("href") === "#" + id);
      });
    }

    window.addEventListener("hashchange", mostrar);
    mostrar();
  </script>

</body>
</html>
