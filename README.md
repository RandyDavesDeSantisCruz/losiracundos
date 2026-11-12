<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta name="description" content="Sitio web sobre Los Iracundos, grupo musical uruguayo: biografía, álbumes, galería, videos, canciones y letras.">
  <title>Los Iracundos</title>
  <link rel="icon" type="image/jpeg" href="imagenes/logo.jpg">
  <link rel="stylesheet" href="estilos.css">
</head>
<body>

  <!-- A. ENCABEZADO -->
  <header class="encabezado" id="encabezado">
    <img class="logo" src="imagenes/logo.jpg" alt="Logotipo de Los Iracundos" width="150" height="150">
    <div class="titulo-grupo">
      <h1>Los Iracundos</h1>
      <p>Grupo musical uruguayo &middot; Desde 1958</p>
    </div>
  </header>

  <nav class="menu" id="menu" aria-label="Menú principal">
    <a href="#inicio">Inicio</a>
    <a href="#artista">Artista</a>
    <a href="#albumes">Álbumes</a>
    <a href="#galeria">Galería</a>
    <a href="#videos">Videos</a>
    <a href="#canciones">Canciones</a>
    <a href="#letras">Letras</a>
    <a href="#presentaciones">Presentaciones</a>
    <a href="#autor">Autor</a>
  </nav>

  <main>

    <!-- INICIO -->
    <div class="pagina contenido" id="inicio">
      <div class="principal">
        <h2>Bienvenidos</h2>
        <p>Hola, bienvenido a mi página biográfica</p>
        <p>Proyecto de Desarrollo de Plataformas Web</p>
        <p>
          Este sitio está dedicado a <strong>Los Iracundos</strong>, uno de los grupos
          más queridos de la música romántica latinoamericana. Conoce su historia,
          revisa sus álbumes, mira su galería, disfruta sus videos y escucha sus
          canciones más representativas.
        </p>
      </div>
      <div class="lateral">
        <p id="saludo">Buenas noches</p>
        <p><strong>Ficha rápida</strong></p>
        <ul class="ficha">
          <li>País: Uruguay</li>
          <li>Inicio: 1958</li>
          <li>Género: Balada romántica</li>
        </ul>
      </div>
    </div>

    <!-- B. PRESENTACIÓN DEL ARTISTA -->
    <div class="pagina detalle" id="artista" hidden>
      <h2>Presentación del artista</h2>
      <div class="perfil">
        <figure>
          <img src="imagenes/artista.jpg" alt="Fotografía del grupo Los Iracundos">
          <figcaption>Los Iracundos</figcaption>
        </figure>

        <div class="datos">
          <dl>
            <dt>Nombre artístico</dt>
            <dd>Los Iracundos</dd>

            <dt>País de origen</dt>
            <dd>Uruguay (ciudad de Paysandú)</dd>

            <dt>Género musical</dt>
            <dd>Balada romántica y pop latino, con raíces en el rock and roll y la nueva ola</dd>

            <dt>Año de inicio de su carrera</dt>
            <dd>1958 (en sus comienzos se llamaron Los Blue Kings)</dd>

            <dt>Formación original</dt>
            <dd>Eduardo Franco, Juan Carlos Velázquez, Leonardo Franco, Juan Bosco Zabalo, Hugo Burgueño y Jesús María Febrero</dd>
          </dl>

          <h3>Biografía breve</h3>
          <p>
            Los Iracundos nacieron en Paysandú, Uruguay, cuando un grupo de jóvenes
            decidió formar una banda inspirada en el rock and roll estadounidense.
            Al firmar con la discográfica RCA Victor adoptaron el nombre con el que
            se hicieron famosos y se instalaron en Buenos Aires para grabar sus
            primeros discos.
          </p>
          <p>
            A mediados de los años 60 lograron fama internacional con baladas
            románticas para el público juvenil, y en 1968 «Puerto Montt» se convirtió
            en su canción más emblemática. Con el paso de los años, el nombre fue
            continuado por distintas formaciones que siguen presentándose en
            escenarios de América.
          </p>
        </div>
      </div>

      <h3 class="subtitulo">Trayectoria</h3>
      <div class="linea-tiempo">
        <div class="hito">
          <span class="anio">1958</span>
          <p>En Paysandú, Uruguay, un grupo de adolescentes forma la banda con el nombre de Los Blue Kings.</p>
        </div>
        <div class="hito">
          <span class="anio">1961</span>
          <p>Debutan en el escenario del Teatro Florencio Sánchez.</p>
        </div>
        <div class="hito">
          <span class="anio">1965</span>
          <p>Acompañan a la cantante italiana Rita Pavone en una gira por Argentina.</p>
        </div>
        <div class="hito">
          <span class="anio">1966</span>
          <p>Viajan a Europa y graban en Italia el álbum «Los Iracundos en Roma».</p>
        </div>
        <div class="hito">
          <span class="anio">1968</span>
          <p>Graban «Puerto Montt», su mayor éxito, en los estudios de RCA en Argentina, y reciben un disco de oro en Córdoba.</p>
        </div>
        <div class="hito">
          <span class="anio">1989</span>
          <p>Fallece Eduardo Franco, voz y compositor del grupo; Jorge Gatto queda como vocalista.</p>
        </div>
        <div class="hito">
          <span class="anio">2022</span>
          <p>Fallece Juan Carlos Velázquez, último integrante de la formación original.</p>
        </div>
      </div>

      <div class="dato-curioso">
        <strong>Dato curioso:</strong> se cuenta que Eduardo Franco compuso
        «Puerto Montt» sin haber estado nunca en esa ciudad de Chile.
      </div>

      <p class="volver"><a href="#inicio">← Volver al inicio</a></p>
    </div>

    <!-- ÁLBUMES -->
    <div class="pagina detalle" id="albumes" hidden>
      <h2>Álbumes</h2>
      <p>Algunos de los discos de estudio más recordados de Los Iracundos.</p>

      <div class="albumes">
        <div class="album">
          <div class="disco"></div>
          <h3>Calla</h3>
          <p class="anio">1965</p>
        </div>
        <div class="album">
          <div class="disco"></div>
          <h3>Los Iracundos en Roma</h3>
          <p class="anio">1967</p>
        </div>
        <div class="album">
          <div class="disco"></div>
          <h3>La lluvia terminó</h3>
          <p class="anio">1969</p>
        </div>
        <div class="album">
          <div class="disco"></div>
          <h3>Y te has quedado sola</h3>
          <p class="anio">1974</p>
        </div>
        <div class="album">
          <div class="disco"></div>
          <h3>Aprontate a vivir</h3>
          <p class="anio">1983</p>
        </div>
        <div class="album">
          <div class="disco"></div>
          <h3>Tú con él</h3>
          <p class="anio">1984</p>
        </div>
      </div>
      <p class="nota">Los años pueden variar según la fuente consultada.</p>

      <p class="volver"><a href="#inicio">← Volver al inicio</a></p>
    </div>

    <!-- C. GALERÍA DE IMÁGENES -->
    <div class="pagina detalle" id="galeria" hidden>
      <h2>Galería de imágenes</h2>
      <div class="galeria">
        <div class="foto">
          <img src="imagenes/foto1.jpg" alt="Fotografía 1 de Los Iracundos" loading="lazy">
          <div class="leyenda">Los Iracundos · Foto 1</div>
        </div>
        <div class="foto">
          <img src="imagenes/foto2.jpg" alt="Fotografía 2 de Los Iracundos" loading="lazy">
          <div class="leyenda">Los Iracundos · Foto 2</div>
        </div>
        <div class="foto">
          <img src="imagenes/foto3.jpg" alt="Fotografía 3 de Los Iracundos" loading="lazy">
          <div class="leyenda">Los Iracundos · Foto 3</div>
        </div>
        <div class="foto">
          <img src="imagenes/foto4.jpg" alt="Fotografía 4 de Los Iracundos" loading="lazy">
          <div class="leyenda">Los Iracundos · Foto 4</div>
        </div>
      </div>
      <p class="volver"><a href="#inicio">← Volver al inicio</a></p>
    </div>

    <!-- D. VIDEOS MUSICALES -->
    <div class="pagina detalle" id="videos" hidden>
      <h2>Videos musicales</h2>
      <h3>Puerto Montt</h3>

      <div class="video-contenedor">
        <!-- Opción 1: video propio con el elemento HTML5 video -->
        <video controls preload="metadata">
          <source src="videos/video.mp4" type="video/mp4">
          Tu navegador no soporta el elemento de video.
        </video>

        <!-- Opción 2: video de YouTube (borra el bloque video de arriba y activa este)
        <iframe src="https://www.youtube.com/embed/ID_DEL_VIDEO"
                title="Video musical de Los Iracundos"
                allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
                allowfullscreen></iframe>
        -->
      </div>
      <p class="volver"><a href="#inicio">← Volver al inicio</a></p>
    </div>

    <!-- E. CATÁLOGO DE CANCIONES (máximo 5) -->
    <div class="pagina detalle" id="canciones" hidden>
      <h2>Catálogo de canciones</h2>
      <p>Las canciones más representativas de Los Iracundos.</p>

      <div class="catalogo">

        <div class="tarjeta">
          <span class="numero">Canción 1</span>
          <h3>Puerto Montt</h3>
          <audio controls preload="none" src="musica/cancion1.mp3">
            Tu navegador no soporta el elemento de audio.
          </audio>
          <a class="boton" href="musica/cancion1.mp3" download>⬇ Descargar MP3</a>
          <a class="boton secundario" href="#letra-1">Ver letra</a>
        </div>

        <div class="tarjeta">
          <span class="numero">Canción 2</span>
          <h3>Va cayendo una lágrima</h3>
          <audio controls preload="none" src="musica/cancion2.mp3">
            Tu navegador no soporta el elemento de audio.
          </audio>
          <a class="boton" href="musica/cancion2.mp3" download>⬇ Descargar MP3</a>
          <a class="boton secundario" href="#letra-2">Ver letra</a>
        </div>

        <div class="tarjeta">
          <span class="numero">Canción 3</span>
          <h3>Te lo pido de rodillas</h3>
          <audio controls preload="none" src="musica/cancion3.mp3">
            Tu navegador no soporta el elemento de audio.
          </audio>
          <a class="boton" href="musica/cancion3.mp3" download>⬇ Descargar MP3</a>
          <a class="boton secundario" href="#letra-3">Ver letra</a>
        </div>

        <div class="tarjeta">
          <span class="numero">Canción 4</span>
          <h3>Y te has quedado sola</h3>
          <audio controls preload="none" src="musica/cancion4.mp3">
            Tu navegador no soporta el elemento de audio.
          </audio>
          <a class="boton" href="musica/cancion4.mp3" download>⬇ Descargar MP3</a>
          <a class="boton secundario" href="#letra-4">Ver letra</a>
        </div>

        <div class="tarjeta">
          <span class="numero">Canción 5</span>
          <h3>Tú con él</h3>
          <audio controls preload="none" src="musica/cancion5.mp3">
            Tu navegador no soporta el elemento de audio.
          </audio>
          <a class="boton" href="musica/cancion5.mp3" download>⬇ Descargar MP3</a>
          <a class="boton secundario" href="#letra-5">Ver letra</a>
        </div>

      </div>
      <!-- Deja el botón "Descargar MP3" solo en las canciones que puedas distribuir legalmente. -->
      <p class="volver"><a href="#inicio">← Volver al inicio</a></p>
    </div>

    <!-- F. LETRAS DE CANCIONES -->
    <div class="pagina detalle" id="letras" hidden>
      <h2>Letras de canciones</h2>

      <div class="indice-letras">
        <a class="boton" href="#letra-1">Puerto Montt</a>
        <a class="boton" href="#letra-2">Va cayendo una lágrima</a>
        <a class="boton" href="#letra-3">Te lo pido de rodillas</a>
        <a class="boton" href="#letra-4">Y te has quedado sola</a>
        <a class="boton" href="#letra-5">Tú con él</a>
      </div>

      <!-- Reemplaza el texto de cada .letra por la letra completa
           (letra propia, de dominio público o con reproducción autorizada) -->

      <div class="letra-tarjeta" id="letra-1">
        <h3>Puerto Montt</h3>
        <div class="reproductor">
          <audio controls preload="none" src="musica/cancion1.mp3">
            Tu navegador no soporta el elemento de audio.
          </audio>
        </div>
        <div class="letra">Aquí va la letra de «Puerto Montt».</div>
        <div class="navegacion-letras">
          <span></span>
          <a href="#letra-2">Siguiente canción →</a>
        </div>
        <p class="volver"><a href="#canciones">← Volver al catálogo musical</a></p>
      </div>

      <div class="letra-tarjeta" id="letra-2">
        <h3>Va cayendo una lágrima</h3>
        <div class="reproductor">
          <audio controls preload="none" src="musica/cancion2.mp3">
            Tu navegador no soporta el elemento de audio.
          </audio>
        </div>
        <div class="letra">Aquí va la letra de «Va cayendo una lágrima».</div>
        <div class="navegacion-letras">
          <a href="#letra-1">← Canción anterior</a>
          <a href="#letra-3">Siguiente canción →</a>
        </div>
        <p class="volver"><a href="#canciones">← Volver al catálogo musical</a></p>
      </div>

      <div class="letra-tarjeta" id="letra-3">
        <h3>Te lo pido de rodillas</h3>
        <div class="reproductor">
          <audio controls preload="none" src="musica/cancion3.mp3">
            Tu navegador no soporta el elemento de audio.
          </audio>
        </div>
        <div class="letra">Aquí va la letra de «Te lo pido de rodillas».</div>
        <div class="navegacion-letras">
          <a href="#letra-2">← Canción anterior</a>
          <a href="#letra-4">Siguiente canción →</a>
        </div>
        <p class="volver"><a href="#canciones">← Volver al catálogo musical</a></p>
      </div>

      <div class="letra-tarjeta" id="letra-4">
        <h3>Y te has quedado sola</h3>
        <div class="reproductor">
          <audio controls preload="none" src="musica/cancion4.mp3">
            Tu navegador no soporta el elemento de audio.
          </audio>
        </div>
        <div class="letra">Aquí va la letra de «Y te has quedado sola».</div>
        <div class="navegacion-letras">
          <a href="#letra-3">← Canción anterior</a>
          <a href="#letra-5">Siguiente canción →</a>
        </div>
        <p class="volver"><a href="#canciones">← Volver al catálogo musical</a></p>
      </div>

      <div class="letra-tarjeta" id="letra-5">
        <h3>Tú con él</h3>
        <div class="reproductor">
          <audio controls preload="none" src="musica/cancion5.mp3">
            Tu navegador no soporta el elemento de audio.
          </audio>
        </div>
        <div class="letra">Aquí va la letra de «Tú con él».</div>
        <div class="navegacion-letras">
          <a href="#letra-4">← Canción anterior</a>
          <span></span>
        </div>
        <p class="volver"><a href="#canciones">← Volver al catálogo musical</a></p>
      </div>

      <p class="volver"><a href="#inicio">← Volver al inicio</a></p>
    </div>

    <!-- PRESENTACIONES -->
    <div class="pagina detalle" id="presentaciones" hidden>
      <h2>Próximas presentaciones</h2>
      <div class="aviso">
        <h3>Sin fechas confirmadas por ahora</h3>
        <p>
          En las fuentes consultadas (noviembre de 2026) no aparecen conciertos
          próximos programados. Las fechas pueden cambiar: consulta el sitio oficial
          para conocer las novedades.
        </p>
        <p>
          <a class="boton" href="https://losiracundos.com" target="_blank" rel="noopener noreferrer">Ir al sitio oficial</a>
        </p>
      </div>
      <p class="volver"><a href="#inicio">← Volver al inicio</a></p>
    </div>

    <!-- AUTOR DEL SITIO -->
    <div class="pagina detalle" id="autor" hidden>
      <h2>Autor del sitio</h2>
      <h3>Randy De Santis</h3>
      <p>
        Hola, me llamo Randy De Santis y tengo 29 años. Soy nacido en Guayaquil
        pero he vivido en Ventanas prácticamente toda mi vida y actualmente
        estudio en el 3er Semestre de la carrera de Sistemas de Información de
        la Universidad Técnica de Babahoyo.
      </p>
      <p class="volver"><a href="#inicio">← Volver al inicio</a></p>
    </div>

  </main>

  <!-- G. PIE DE PÁGINA -->
  <footer class="pie" id="pie">
    <div class="pie-columnas">
      <div class="pie-bloque">
        <h3>Estudiante</h3>
        <p>Randy De Santis</p>
        <p>Carrera: Sistemas de Información (3er semestre)</p>
        <p>Universidad Técnica de Babahoyo</p>
        <p>Asignatura: Desarrollo de Plataformas Web</p>
        <p>Año de elaboración: 2026</p>
      </div>

      <div class="pie-bloque redes">
        <h3>Redes oficiales de Los Iracundos</h3>
        <a href="https://losiracundos.com" target="_blank" rel="noopener noreferrer">Sitio web</a>
        <a href="https://www.facebook.com/LosIracundosOficial/" target="_blank" rel="noopener noreferrer">Facebook</a>
        <a href="https://www.instagram.com/losiracundosoficial/" target="_blank" rel="noopener noreferrer">Instagram</a>
        <a href="https://www.youtube.com/@LosIracundosOficial" target="_blank" rel="noopener noreferrer">YouTube</a>
      </div>

      <div class="pie-bloque">
        <h3>Contacto</h3>
        <p>
          Comentarios y sugerencias al correo:
          <a href="mailto:randydavesdesantiscruz1996@gmail.com">randydavesdesantiscruz1996@gmail.com</a>
        </p>
      </div>
    </div>
    <p class="derechos">&copy; 2026 Randy De Santis - Todos los derechos reservados</p>
  </footer>

  <!-- Botón para volver al inicio de la página -->
  <button type="button" class="btn-arriba" id="btn-arriba" aria-label="Volver arriba" title="Volver arriba">&uarr;</button>

  <script>
    // Muestra solo la página que indica la dirección (#artista, #galeria, #letra-1, etc.)
    // Si el enlace apunta a un elemento dentro de una página (por ejemplo #letra-3),
    // se muestra la página que lo contiene y se desplaza hasta ese elemento.
    function mostrar() {
      var id = decodeURIComponent(location.hash.slice(1)) || "inicio";
      var destino = document.getElementById(id);
      var pagina = destino ? destino.closest(".pagina") : null;

      if (!pagina) {
        pagina = document.getElementById("inicio");
        destino = null;
      }

      document.querySelectorAll(".pagina").forEach(function (p) {
        p.hidden = (p !== pagina);
      });

      // Resalta en el menú la sección actual
      document.querySelectorAll(".menu a").forEach(function (a) {
        a.classList.toggle("activo", a.getAttribute("href") === "#" + pagina.id);
      });

      if (destino && destino !== pagina) {
        destino.scrollIntoView({ behavior: "smooth", block: "start" });
      } else {
        window.scrollTo(0, 0);
      }
    }

    // Saludo según la hora del visitante
    function saludar() {
      var h = new Date().getHours();
      var texto = h < 12 ? "Buenos días" : (h < 19 ? "Buenas tardes" : "Buenas noches");
      document.getElementById("saludo").textContent = texto;
    }

    // Botón "volver arriba": aparece al bajar y sube suavemente
    var btnArriba = document.getElementById("btn-arriba");
    window.addEventListener("scroll", function () {
      btnArriba.classList.toggle("visible", window.scrollY > 300);
    });
    btnArriba.addEventListener("click", function () {
      window.scrollTo({ top: 0, behavior: "smooth" });
    });

    window.addEventListener("hashchange", mostrar);
    // Al terminar de cargar se vuelve a ubicar la página, porque el navegador
    // salta por su cuenta a la sección cuando se abre una dirección con #
    window.addEventListener("load", function () { setTimeout(mostrar, 100); });
    saludar();
    mostrar();
  </script>

</body>
</html>

estilos.css

css
/* ==========================================================
   estilos.css  ·  Sitio web de Los Iracundos
   Proyecto de Desarrollo de Plataformas Web
   ========================================================== */

* { box-sizing: border-box; }

body {
  font-family: Arial, sans-serif;
  margin: 20px;
  color: #222;
}

[hidden] { display: none !important; }

/* ---------- A. ENCABEZADO ---------- */
.encabezado {
  background: linear-gradient(135deg, #1565c0, #2196f3);
  color: white;
  padding: 20px;
  text-align: center;
  display: flex;
  justify-content: center;
  align-items: center;
  gap: 18px;
  flex-wrap: wrap;
}
.encabezado .logo {
  width: 150px;
  height: 150px;
  object-fit: cover;
  border: 4px solid white;
  border-radius: 12px;
  box-shadow: 0 4px 12px rgba(0, 0, 0, .4);
  transition: transform .3s ease;
}
.encabezado .logo:hover { transform: scale(1.05) rotate(-2deg); }
.encabezado h1 {
  margin: 0;
  font-size: 2.4rem;
  letter-spacing: 1px;
}
.encabezado p {
  margin: 5px 0 0;
  font-style: italic;
  opacity: .9;
}

.menu {
  background: #333;
  color: white;
  padding: 20px;
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
  gap: 6px 0;
}
.menu a {
  color: white;
  text-decoration: none;
  padding: 0 12px;
}
.menu a + a { border-left: 1px solid #777; }
.menu a:hover {
  color: #2196f3;
  text-decoration: underline;
}
.menu a.activo {
  color: #64b5f6;
  font-weight: bold;
}

/* ---------- BLOQUES GENERALES ---------- */
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
.lateral .ficha {
  margin: 8px 0 0;
  padding-left: 20px;
  line-height: 1.7;
}

.detalle {
  background: #DDEEFF;
  padding: 30px;
  margin-top: 10px;
}
.detalle a { color: #1565c0; }
.detalle h2 {
  margin-top: 0;
  border-bottom: 3px solid #2196f3;
  padding-bottom: 8px;
}

.volver { margin: 20px 0 0; }

/* ---------- B. PRESENTACIÓN DEL ARTISTA ---------- */
.perfil {
  display: flex;
  flex-wrap: wrap;
  gap: 25px;
  align-items: flex-start;
}
.perfil figure {
  margin: 0;
  flex: 0 0 280px;
  max-width: 100%;
}
.perfil figure img {
  width: 100%;
  height: auto;
  min-height: 200px;
  border: 4px solid #2196f3;
  border-radius: 6px;
  background: #bbdefb;
  display: block;
}
.perfil figcaption {
  text-align: center;
  font-size: .9rem;
  margin-top: 6px;
}
.perfil .datos { flex: 1 1 320px; }
.datos dl { margin: 0 0 15px; }
.datos dt {
  font-weight: bold;
  color: #0d47a1;
}
.datos dd { margin: 0 0 10px; }

.detalle h3.subtitulo { margin: 30px 0 15px; }

/* Línea de tiempo */
.linea-tiempo {
  margin: 10px 0 0 10px;
  padding-left: 25px;
  border-left: 4px solid #2196f3;
}
.hito {
  position: relative;
  margin-bottom: 18px;
}
.hito::before {
  content: "";
  position: absolute;
  left: -35px;
  top: 3px;
  width: 16px;
  height: 16px;
  background: white;
  border: 4px solid #1565c0;
  border-radius: 50%;
}
.hito .anio {
  display: block;
  font-weight: bold;
  font-size: 1.1rem;
  color: #0d47a1;
}
.hito p { margin: 2px 0 0; }

.dato-curioso {
  background: #fff8e1;
  border-left: 6px solid #ffc107;
  border-radius: 6px;
  padding: 12px 16px;
  margin-top: 25px;
}

/* ---------- ÁLBUMES ---------- */
.albumes {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(160px, 1fr));
  gap: 15px;
}
.album {
  background: white;
  border-radius: 8px;
  padding: 18px;
  text-align: center;
  box-shadow: 0 2px 5px rgba(0, 0, 0, .2);
  transition: transform .25s ease, box-shadow .25s ease;
}
.album:hover {
  transform: translateY(-5px);
  box-shadow: 0 10px 18px rgba(0, 0, 0, .3);
}
.album h3 {
  margin: 0 0 4px;
  font-size: 1.05rem;
  color: #0d47a1;
}
.album .anio { margin: 0; color: #555; }
.disco {
  width: 110px;
  height: 110px;
  margin: 0 auto 12px;
  border-radius: 50%;
  background:
    radial-gradient(circle, #fff 0 6%, #2196f3 6% 28%, transparent 28%),
    conic-gradient(transparent 0 35%, rgba(255, 255, 255, .22) 45%,
                   transparent 55% 85%, rgba(255, 255, 255, .22) 95%, transparent),
    #212121;
  box-shadow: 0 3px 8px rgba(0, 0, 0, .4);
  transition: transform .8s ease;
}
.album:hover .disco { transform: rotate(180deg); }
.nota {
  font-size: .85rem;
  color: #455a64;
  margin-top: 15px;
}

/* ---------- C. GALERÍA ---------- */
.galeria {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
  gap: 15px;
}
.foto {
  position: relative;
  overflow: hidden;
  border-radius: 8px;
  aspect-ratio: 4 / 3;
  background: linear-gradient(135deg, #90caf9, #e3f2fd);
  box-shadow: 0 2px 6px rgba(0, 0, 0, .25);
  transition: transform .3s ease, box-shadow .3s ease;
  cursor: pointer;
}
.foto img {
  width: 100%;
  height: 100%;
  object-fit: cover;
  display: block;
  transition: transform .4s ease, filter .4s ease;
}
.foto .leyenda {
  position: absolute;
  left: 0;
  right: 0;
  bottom: 0;
  padding: 10px;
  background: rgba(13, 71, 161, .85);
  color: white;
  text-align: center;
  transform: translateY(100%);
  transition: transform .3s ease;
}
.foto:hover {
  transform: translateY(-5px);
  box-shadow: 0 10px 20px rgba(0, 0, 0, .35);
}
.foto:hover img {
  transform: scale(1.12) rotate(1deg);
  filter: brightness(1.1) saturate(1.3);
}
.foto:hover .leyenda { transform: translateY(0); }

/* ---------- D. VIDEOS ---------- */
.video-contenedor {
  max-width: 800px;
  background: #000;
  border-radius: 8px;
  overflow: hidden;
  box-shadow: 0 4px 12px rgba(0, 0, 0, .35);
}
.video-contenedor video,
.video-contenedor iframe {
  display: block;
  width: 100%;
  aspect-ratio: 16 / 9;
  border: 0;
}

/* ---------- E. CATÁLOGO DE CANCIONES ---------- */
.catalogo {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
  gap: 15px;
}
.tarjeta {
  background: white;
  padding: 18px;
  border-left: 6px solid #2196f3;
  border-radius: 6px;
  box-shadow: 0 2px 5px rgba(0, 0, 0, .2);
  transition: transform .25s ease, box-shadow .25s ease;
}
.tarjeta:hover {
  transform: translateY(-4px);
  box-shadow: 0 8px 16px rgba(0, 0, 0, .3);
}
.tarjeta h3 { margin: 0 0 4px; }
.tarjeta .numero {
  color: #1565c0;
  font-size: .85rem;
  font-weight: bold;
  text-transform: uppercase;
}
.tarjeta audio {
  width: 100%;
  margin: 10px 0;
}
.detalle a.boton {
  display: inline-block;
  background: #2196f3;
  color: white;
  text-decoration: none;
  padding: 8px 14px;
  border-radius: 4px;
  margin: 4px 6px 0 0;
  font-size: .9rem;
  transition: background .2s ease;
}
.detalle a.boton:hover { background: #0d47a1; }
.detalle a.boton.secundario { background: #455a64; }
.detalle a.boton.secundario:hover { background: #263238; }

/* ---------- F. LETRAS ---------- */
.indice-letras {
  display: flex;
  flex-wrap: wrap;
  gap: 8px;
  margin-bottom: 20px;
}
.letra-tarjeta {
  background: white;
  border-radius: 8px;
  padding: 20px;
  margin-bottom: 25px;
  box-shadow: 0 2px 6px rgba(0, 0, 0, .2);
  scroll-margin-top: 10px;
}
.letra-tarjeta h3 {
  margin: 0 0 10px;
  color: #0d47a1;
}
/* El reproductor se queda visible mientras se lee la letra */
.reproductor {
  position: sticky;
  top: 0;
  z-index: 5;
  background: #e3f2fd;
  padding: 10px;
  border-radius: 6px;
  margin-bottom: 12px;
}
.reproductor audio {
  width: 100%;
  margin: 0;
}
.letra {
  white-space: pre-line;
  line-height: 1.9;
  font-size: 1.05rem;
  background: #f7fbff;
  border: 1px solid #bbdefb;
  border-radius: 6px;
  padding: 15px 20px;
  max-height: 340px;
  overflow-y: auto;
}
.navegacion-letras {
  display: flex;
  justify-content: space-between;
  flex-wrap: wrap;
  gap: 10px;
  margin-top: 15px;
}
.navegacion-letras a { text-decoration: none; }
.navegacion-letras a:hover { text-decoration: underline; }

/* ---------- PRESENTACIONES ---------- */
.aviso {
  background: white;
  border-left: 6px solid #ff9800;
  border-radius: 6px;
  padding: 18px;
  box-shadow: 0 2px 5px rgba(0, 0, 0, .2);
}
.aviso h3 { margin: 0 0 8px; }
.aviso p { margin: 6px 0; }

/* ---------- G. PIE DE PÁGINA ---------- */
.pie {
  background: #555;
  color: white;
  padding: 25px 15px 15px;
  margin-top: 10px;
}
.pie-columnas {
  display: flex;
  flex-wrap: wrap;
  gap: 25px;
  justify-content: space-between;
  text-align: left;
}
.pie-bloque { flex: 1 1 230px; }
.pie-bloque h3 {
  margin: 0 0 10px;
  padding-bottom: 6px;
  border-bottom: 2px solid #2196f3;
  font-size: 1.05rem;
}
.pie-bloque p { margin: 5px 0; }
.pie a { color: #90caf9; }
.pie .redes a {
  display: inline-block;
  margin: 4px 6px 4px 0;
  padding: 6px 14px;
  background: #2196f3;
  color: white;
  border-radius: 20px;
  text-decoration: none;
  font-size: .9rem;
  transition: background .2s ease, transform .2s ease;
}
.pie .redes a:hover {
  background: #0d47a1;
  transform: translateY(-2px);
}
.derechos {
  text-align: center;
  margin: 20px 0 0;
  padding-top: 12px;
  border-top: 1px solid #777;
}

/* ---------- BOTÓN VOLVER ARRIBA ---------- */
.btn-arriba {
  position: fixed;
  right: 20px;
  bottom: 20px;
  width: 46px;
  height: 46px;
  border: none;
  border-radius: 50%;
  background: #2196f3;
  color: white;
  font-size: 1.4rem;
  cursor: pointer;
  box-shadow: 0 3px 8px rgba(0, 0, 0, .4);
  opacity: 0;
  visibility: hidden;
  transition: opacity .3s ease, visibility .3s ease, background .2s ease, transform .2s ease;
  z-index: 20;
}
.btn-arriba.visible {
  opacity: 1;
  visibility: visible;
}
.btn-arriba:hover {
  background: #0d47a1;
  transform: translateY(-3px);
}

/* ---------- DISEÑO ADAPTABLE (RESPONSIVE) ---------- */
@media (max-width: 700px) {
  body { margin: 10px; }
  .contenido { flex-direction: column; }
  .principal, .lateral { width: 100%; }
  .detalle { padding: 20px; }
  .encabezado h1 { font-size: 1.8rem; }
  .encabezado .logo { width: 110px; height: 110px; }
  .menu { padding: 15px 10px; }
  .menu a { padding: 4px 10px; }
}
