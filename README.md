<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Los Iracundos — Legado Musical</title>
  <link rel="stylesheet" href="estilos.css">
</head>
<body>

  <div class="contenedor-principal">

    <header id="tope-pagina" class="encabezado">
      <div class="vinilo-emblema" aria-hidden="true"></div>
      <div class="encabezado-titulos">
        <h1>Los Iracundos</h1>
        <p>Leyendas de la Nueva Ola y la Balada Romántica — Proyecto de Desarrollo de Plataformas Web</p>
      </div>
    </header>

    <nav class="menu">
      <a href="#inicio">Inicio</a>
      <a href="#biografia">Biografía</a>
      <a href="#galeria">Galería</a>
      <a href="#albumes">Álbumes</a>
      <a href="#conciertos">Conciertos</a>
      <a href="#videos">Videos</a>
      <a href="#audios">Audios MP3</a>
      <a href="#musica">Catálogo</a>
      <a href="#letras">Letras</a>
    </nav>

    <!-- INICIO -->
    <main id="inicio" class="pagina contenido">
      <section class="principal">
        <h2>Bienvenidos</h2>
        <p>Hola, bienvenido a la página biográfica y musical del grupo uruguayo <strong>Los Iracundos</strong>.</p>
        <p>Sumérgete en la nostalgia romántica de los años 60 y 70: explora su historia desde Paysandú, su galería fotográfica, sus álbumes en vinilo más emblemáticos, próximas presentaciones homenaje, videos, audios en MP3 y las letras que marcaron generaciones.</p>

        <div class="accesos-inicio">
          <a href="#albumes" class="btn-estilo btn-oceano">Explorar álbumes</a>
          <a href="#audios" class="btn-estilo btn-dorado">Escuchar audios MP3</a>
          <a href="#letras" class="btn-estilo btn-oceano">Leer letras con audio</a>
        </div>
      </section>

      <aside class="lateral">
        <h3 id="saludo">Ficha del grupo</h3>
        <p><strong>Origen:</strong> Paysandú, Uruguay (1958)</p>
        <p><strong>Género:</strong> Pop rock / Balada romántica / Nueva ola</p>
        <p><strong>Voz inmortal:</strong> Eduardo Franco</p>
        <p><strong>Éxito emblemático:</strong> <em>Puerto Montt</em> (1968)</p>
      </aside>
    </main>

    <!-- BIOGRAFÍA -->
    <section id="biografia" class="pagina detalle" hidden>
      <h2>Biografía</h2>

      <div class="bloque-bio">
        <h3>Nombre artístico</h3>
        <p>El nombre artístico del grupo es <strong>Los Iracundos</strong>.</p>
      </div>

      <div class="bloque-bio">
        <h3>Biografía breve</h3>
        <p>
          Los Iracundos es una banda uruguaya de pop rock originaria de Paysandú, considerada en Uruguay la más importante del género. Se originó en 1958 bajo el nombre Los Blue Kings, inspirada en el rock and roll estadounidense de la época, y tuvieron su debut oficial en 1961, año en que lanzaron su primer sencillo con el sello uruguayo Clave. En 1964, firmaron con el sello RCA Victor en Argentina, donde cambiaron su nombre por Los Iracundos y adoptaron su característico estilo melódico y romántico, incorporándose al movimiento de la «nueva ola». La banda tuvo un crecimiento exponencial durante la década de 1960 que los consagraría internacionalmente, con numerosos discos editados, participaciones en películas y giras por América, Europa y Estados Unidos, incluyendo una presentación en el Madison Square Garden de Nueva York. Su mayor éxito vino en 1968 con «Puerto Montt» (Franco/Valdez), la canción más recordada de su carrera. El grupo reafirmó su popularidad en los años 1970 y 1980, editando varios discos de oro. El cantante Eduardo Franco es el autor de casi todo el repertorio compuesto por la banda, que también incluye composiciones instrumentales.
        </p>
      </div>

      <div class="bloque-bio">
        <h3>País de origen</h3>
        <p>El país de origen del grupo es Uruguay.</p>
      </div>

      <div class="bloque-bio">
        <h3>Género musical</h3>
        <p>El repertorio musical del grupo se basa en géneros como el pop, la canción melódica, la balada romántica, el rock, la nueva ola, la música instrumental y la música beat.</p>
      </div>

      <div class="bloque-bio">
        <h3>Año de inicio de su carrera</h3>
        <p>El grupo inició su carrera bajo el nombre de Los Blue Kings entre 1958 hasta el año de 1963, después en 1964 adoptaron el nombre de Los Iracundos, el cual ha sido el nombre de la agrupación hasta el día de hoy.</p>
      </div>

      <div class="bloque-bio">
        <h3>Fotografía del grupo</h3>
        <figure class="foto-biografia">
          <img src="Los_Iracundos_en_1968.jpg" alt="Los Iracundos en 1968">
          <figcaption>Los Iracundos en 1968.</figcaption>
        </figure>
      </div>

      <a class="volver" href="#inicio">← Volver al inicio</a>
    </section>

    <!-- GALERÍA -->
    <section id="galeria" class="pagina detalle" hidden>
      <h2>Galería</h2>
      <p>Momentos históricos de la trayectoria de Los Iracundos (pasa el cursor sobre cada fotografía):</p>

      <div class="galeria-grid">
        <div class="tarjeta-foto">
          <div class="marco-foto">
            <img src="Los_Blue_Kings_entre_1958-1963.jpg" alt="Los Blue Kings entre 1958 y 1963">
          </div>
          <p>Los Blue Kings entre 1958 - 1963</p>
        </div>
        <div class="tarjeta-foto">
          <div class="marco-foto">
            <img src="Los_Iracundos_en_1974.jpg" alt="Los Iracundos en 1974">
          </div>
          <p>Los Iracundos en 1974</p>
        </div>
        <div class="tarjeta-foto">
          <div class="marco-foto">
            <img src="Los_Iracundos_en_1982.jpg" alt="Los Iracundos en 1982">
          </div>
          <p>Los Iracundos en 1982</p>
        </div>
        <div class="tarjeta-foto">
          <div class="marco-foto">
            <img src="Los_Iracundos_en_1995.jpg" alt="Los Iracundos en 1995">
          </div>
          <p>Los Iracundos en 1995</p>
        </div>
      </div>

      <a class="volver" href="#inicio">← Volver al inicio</a>
    </section>

    <!-- ÁLBUMES MUSICALES -->
    <section id="albumes" class="pagina detalle" hidden>
      <h2>Álbumes Musicales</h2>
      <p>Discografía destacada en vinilo LP que consolidó el sonido romántico y melódico de Los Iracundos en toda Hispanoamérica:</p>

      <div class="albumes-grid">
        <div class="tarjeta-album">
          <div class="portada-vinilo">
            <div class="disco-mini"></div>
          </div>
          <span class="anio-album">1967 • RCA Victor</span>
          <h3>Los Iracundos en Roma</h3>
          <p><strong>Temas destacados:</strong> <em>Es la lluvia que cae</em>, <em>Calla</em>, <em>El desengaño</em>.</p>
        </div>

        <div class="tarjeta-album">
          <div class="portada-vinilo dorada">
            <div class="disco-mini"></div>
          </div>
          <span class="anio-album">1968 • RCA Victor</span>
          <h3>Puerto Montt</h3>
          <p><strong>Temas destacados:</strong> <em>Puerto Montt</em>, <em>Ven que estoy hirviendo</em>, <em>Felicidad, felicidad</em>.</p>
        </div>

        <div class="tarjeta-album">
          <div class="portada-vinilo">
            <div class="disco-mini"></div>
          </div>
          <span class="anio-album">1970 • RCA Victor</span>
          <h3>Los Iracundos (Te lo pido de rodillas)</h3>
          <p><strong>Temas destacados:</strong> <em>Te lo pido de rodillas</em>, <em>Va cayendo una lágrima</em>.</p>
        </div>

        <div class="tarjeta-album">
          <div class="portada-vinilo esmeralda">
            <div class="disco-mini"></div>
          </div>
          <span class="anio-album">1971 • RCA Victor</span>
          <h3>Agua con amor</h3>
          <p><strong>Temas destacados:</strong> <em>Chiquilina</em>, <em>Agua con amor</em>, <em>Marionetas de cartón</em>.</p>
        </div>

        <div class="tarjeta-album">
          <div class="portada-vinilo dorada">
            <div class="disco-mini"></div>
          </div>
          <span class="anio-album">1979 • Microfón</span>
          <h3>Amor y fe</h3>
          <p><strong>Temas destacados:</strong> <em>Aprontate a vivir</em>, <em>Por ese amor</em>, <em>Infidelidad es tu traición</em>.</p>
        </div>

        <div class="tarjeta-album">
          <div class="portada-vinilo">
            <div class="disco-mini"></div>
          </div>
          <span class="anio-album">1985 • RCA</span>
          <h3>Tú con él</h3>
          <p><strong>Temas destacados:</strong> <em>Tú con él</em>, <em>Las puertas del olvido</em>, <em>Me voy o me quedo</em>.</p>
        </div>
      </div>

      <a class="volver" href="#inicio">← Volver al inicio</a>
    </section>

    <!-- PRÓXIMOS CONCIERTOS -->
    <section id="conciertos" class="pagina detalle" hidden>
      <h2>Próximos Conciertos y Presentaciones</h2>
      <p>Fechas confirmadas de la <strong>Gira Legado Romántico — Puerto Montt Eterno</strong>:</p>

      <div class="lista-conciertos">
        <div class="tarjeta-concierto">
          <div class="fecha-concierto">
            <span class="dia">28</span>
            <span class="mes">Nov 2026</span>
          </div>
          <div class="detalle-concierto">
            <h3>Anfiteatro del Río Uruguay</h3>
            <p><strong>Ciudad:</strong> Paysandú, Uruguay • <strong>Hora:</strong> 21:00 hrs</p>
          </div>
          <span class="estado-entrada">Entradas disponibles</span>
        </div>

        <div class="tarjeta-concierto">
          <div class="fecha-concierto">
            <span class="dia">12</span>
            <span class="mes">Dic 2026</span>
          </div>
          <div class="detalle-concierto">
            <h3>Teatro Gran Rex</h3>
            <p><strong>Ciudad:</strong> Buenos Aires, Argentina • <strong>Hora:</strong> 20:30 hrs</p>
          </div>
          <span class="estado-entrada">Últimas localidades</span>
        </div>

        <div class="tarjeta-concierto">
          <div class="fecha-concierto">
            <span class="dia">16</span>
            <span class="mes">Ene 2027</span>
          </div>
          <div class="detalle-concierto">
            <h3>Teatro Centro Cívico Eloy Alfaro</h3>
            <p><strong>Ciudad:</strong> Guayaquil, Ecuador • <strong>Hora:</strong> 20:00 hrs</p>
          </div>
          <span class="estado-entrada">Preventa activa</span>
        </div>

        <div class="tarjeta-concierto">
          <div class="fecha-concierto">
            <span class="dia">14</span>
            <span class="mes">Feb 2027</span>
          </div>
          <div class="detalle-concierto">
            <h3>Especial Día de los Enamorados — Arena Puerto Montt</h3>
            <p><strong>Ciudad:</strong> Puerto Montt, Chile • <strong>Hora:</strong> 21:30 hrs</p>
          </div>
          <span class="estado-entrada">Próximamente</span>
        </div>
      </div>

      <a class="volver" href="#inicio">← Volver al inicio</a>
    </section>

    <!-- AUDIOS MP3 -->
    <section id="audios" class="pagina detalle" hidden>
      <h2>Audios en MP3</h2>
      <p>Selecciona una canción de la lista para ir directamente a su reproductor o navega entre pistas:</p>

      <div class="indice-canciones">
        <span>Ir a la canción:</span>
        <a href="#pista-puerto-montt">1. Puerto Montt</a>
        <a href="#pista-fabula">2. Fábula</a>
        <a href="#pista-te-lo-pido">3. Te lo pido de rodillas</a>
      </div>

      <div class="lista-audios">
        <div id="pista-puerto-montt" class="tarjeta-audio">
          <strong>1. Puerto Montt (1968)</strong>
          <p class="info-pista">Álbum: <em>Puerto Montt</em></p>
          <audio controls preload="none">
            <source src="puerto_montt.mp3" type="audio/mpeg">
            Tu navegador no soporta la reproducción de audio HTML5.
          </audio>
          <div class="enlaces-cruzados">
            <a href="#letra-puerto-montt">Leer letra</a>
            <a href="#pista-fabula">Siguiente canción ↓</a>
          </div>
        </div>

        <div id="pista-fabula" class="tarjeta-audio">
          <strong>2. Fábula (1972)</strong>
          <p class="info-pista">Álbum: <em>Los Iracundos</em></p>
          <audio controls preload="none">
            <source src="fabula.mp3" type="audio/mpeg">
            Tu navegador no soporta la reproducción de audio HTML5.
          </audio>
          <div class="enlaces-cruzados">
            <a href="#pista-puerto-montt">↑ Anterior</a>
            <a href="#letra-fabula">Leer letra</a>
            <a href="#pista-te-lo-pido">Siguiente canción ↓</a>
          </div>
        </div>

        <div id="pista-te-lo-pido" class="tarjeta-audio">
          <strong>3. Te lo pido de rodillas (1970)</strong>
          <p class="info-pista">Álbum: <em>Los Iracundos</em></p>
          <audio controls preload="none">
            <source src="te_lo_pido_de_rodillas.mp3" type="audio/mpeg">
            Tu navegador no soporta la reproducción de audio HTML5.
          </audio>
          <div class="enlaces-cruzados">
            <a href="#pista-fabula">↑ Anterior</a>
            <a href="#letra-te-lo-pido">Leer letra</a>
          </div>
        </div>
      </div>

      <a class="volver" href="#inicio">← Volver al inicio</a>
    </section>

    <!-- CATÁLOGO DE CANCIONES -->
    <section id="musica" class="pagina detalle" hidden>
      <h2>Música — Catálogo musical y discografía</h2>
      <ul class="lista-items">
        <li>
          <strong>Puerto Montt</strong> (1968) — Álbum: <em>Puerto Montt</em>
          <div class="enlaces-cruzados">
            <a href="#pista-puerto-montt">Escuchar MP3</a>
            <a href="#letra-puerto-montt">Ver letra con audio</a>
          </div>
        </li>
        <li>
          <strong>Te lo pido de rodillas</strong> (1970) — Álbum: <em>Los Iracundos</em>
          <div class="enlaces-cruzados">
            <a href="#pista-te-lo-pido">Escuchar MP3</a>
            <a href="#letra-te-lo-pido">Ver letra con audio</a>
          </div>
        </li>
        <li>
          <strong>Fábula</strong> (1972) — Álbum: <em>Los Iracundos</em>
          <div class="enlaces-cruzados">
            <a href="#pista-fabula">Escuchar MP3</a>
            <a href="#letra-fabula">Ver letra con audio</a>
          </div>
        </li>
        <li><strong>Es la lluvia que cae</strong> (1967) — Álbum: <em>Los Iracundos en Roma</em></li>
        <li><strong>Tú con él</strong> (1985) — Álbum: <em>Tú con él</em></li>
        <li><strong>Chiquilina</strong> (1971) — Álbum: <em>Agua con amor</em></li>
        <li><strong>Aprontate a vivir</strong> (1979) — Álbum: <em>Amor y fe</em></li>
      </ul>

      <a class="volver" href="#inicio">← Volver al inicio</a>
    </section>

    <!-- VIDEOS -->
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

    <!-- F. LETRAS DE CANCIONES -->
    <section id="letras" class="pagina detalle" hidden>
      <h2>Letras de canciones</h2>
      <p>Reproduce la pista asociada a cada canción mientras sigues su letra organizada por estrofas:</p>

      <div class="indice-canciones">
        <span>Saltar a la canción:</span>
        <a href="#letra-puerto-montt">1. Puerto Montt</a>
        <a href="#letra-fabula">2. Fábula</a>
        <a href="#letra-te-lo-pido">3. Te lo pido de rodillas</a>
      </div>

      <!-- Canción 1: Puerto Montt -->
      <div id="letra-puerto-montt" class="bloque-letra">
        <div class="cabecera-letra">
          <div>
            <h3>1. Puerto Montt</h3>
            <span class="subtitulo-letra">Álbum: <em>Puerto Montt</em> (1968)</span>
          </div>
          <a href="#musica" class="btn-catalogo">← Regresar al catálogo musical</a>
        </div>

        <div class="reproductor-letra">
          <span>Escuchar canción mientras lees:</span>
          <audio controls preload="none">
            <source src="puerto_montt.mp3" type="audio/mpeg">
            Tu navegador no soporta la reproducción de audio HTML5.
          </audio>
        </div>

        <div class="texto-letra">
          <p>
            Sentado frente al mar<br>
            Mil besos yo le di<br>
            Después le dije adiós<br>
            Todo termina aquí<br>
            Y ella me dijo así.
          </p>
          <p>
            Abrázame y verás<br>
            Que el mundo es de los dos<br>
            Salgamos a correr<br>
            Busquemos el ayer<br>
            Que nos hizo feliz.
          </p>
          <p>
            Puerto Montt, Puerto Montt<br>
            Me alejé de ti<br>
            Sin saber por qué<br>
            Y yo la dejé<br>
            Sola frente al mar<br>
            Bajo el cielo azul<br>
            De Puerto Montt.
          </p>
          <p>
            Mil violines en su voz<br>
            Susurraron un adiós<br>
            Y un amor que se quedó<br>
            Perdido frente al mar<br>
            Y el viento lo llevó.
          </p>
          <p>
            Silencio sin piedad<br>
            Encontraré al volver<br>
            Mas en la soledad<br>
            Su voz me gritará:<br>
            «No, no te vayas de mí».
          </p>
          <p>
            Puerto Montt, Puerto Montt<br>
            Me alejé de ti<br>
            Sin saber por qué<br>
            Y yo la dejé<br>
            Sola frente al mar<br>
            Bajo el cielo azul<br>
            De Puerto Montt.
          </p>
          <p>
            La-la-la, la, la<br>
            La-la-la, la, la<br>
            La-la-la, la, la<br>
            La-la-la<br>
            La-la-la, la, la<br>
            La-la-la, la, la.
          </p>
        </div>

        <div class="enlaces-cruzados">
          <a href="#musica">← Catálogo musical</a>
          <a href="#letra-fabula">Siguiente letra: Fábula ↓</a>
        </div>
      </div>

      <!-- Canción 2: Fábula -->
      <div id="letra-fabula" class="bloque-letra">
        <div class="cabecera-letra">
          <div>
            <h3>2. Fábula</h3>
            <span class="subtitulo-letra">Álbum: <em>Los Iracundos</em> (1972)</span>
          </div>
          <a href="#musica" class="btn-catalogo">← Regresar al catálogo musical</a>
        </div>

        <div class="reproductor-letra">
          <span>Escuchar canción mientras lees:</span>
          <audio controls preload="none">
            <source src="fabula.mp3" type="audio/mpeg">
            Tu navegador no soporta la reproducción de audio HTML5.
          </audio>
        </div>

        <div class="texto-letra">
          <p>
            El Sol sobre mi cama hoy me vuelve a despertar<br>
            Y yo quiero dormir, dormir, dormir para olvidar<br>
            Que vivo en un desierto de cemento y soledad.
          </p>
          <p>
            Y tú, entre brindis, noches y amantes<br>
            De ese mundo loco y errante<br>
            No vas a volver<br>
            Y yo sufriré<br>
            Resignado al ver<br>
            Que lo nuestro fue...
          </p>
          <p>
            Fábula, de un pobre tonto que siempre te amó<br>
            Y que sus puertas nunca más cerró<br>
            Con la esperanza de volverte a ver.
          </p>
          <p>
            Fábula, de una muchacha que siempre creyó<br>
            En cuentos de hadas y que confundió<br>
            Las madrugadas con amanecer.<br>
            Fábula, la-la-la-la-la-la-la-la-la-la.
          </p>
          <p>
            Mi vida ya no es vida, yo no sé qué voy a hacer<br>
            Rogando a Dios le pido me devuelva tu querer<br>
            Me estoy volviendo loco de sufrir y de llorar.
          </p>
          <p>
            Y tú, entre brindis, noches y amantes<br>
            De ese mundo loco y errante<br>
            No vas a volver<br>
            Y yo sufriré<br>
            Resignado al ver<br>
            Que lo nuestro fue...
          </p>
          <p>
            Fábula, de un pobre tonto que siempre te amó<br>
            Y que sus puertas nunca más cerró<br>
            Con la esperanza de volverte a ver.<br>
            Fábula, de una muchacha que siempre creyó<br>
            En cuentos de hadas y que confundió<br>
            Las madrugadas con amanecer.<br>
            Fábula, la-la-la-la-la-la-la-la-la-la.
          </p>
        </div>

        <div class="enlaces-cruzados">
          <a href="#letra-puerto-montt">↑ Anterior: Puerto Montt</a>
          <a href="#musica">← Catálogo musical</a>
          <a href="#letra-te-lo-pido">Siguiente letra: Te lo pido de rodillas ↓</a>
        </div>
      </div>

      <!-- Canción 3: Te lo pido de rodillas -->
      <div id="letra-te-lo-pido" class="bloque-letra">
        <div class="cabecera-letra">
          <div>
            <h3>3. Te lo pido de rodillas</h3>
            <span class="subtitulo-letra">Álbum: <em>Los Iracundos</em> (1970)</span>
          </div>
          <a href="#musica" class="btn-catalogo">← Regresar al catálogo musical</a>
        </div>

        <div class="reproductor-letra">
          <span>Escuchar canción mientras lees:</span>
          <audio controls preload="none">
            <source src="te_lo_pido_de_rodillas.mp3" type="audio/mpeg">
            Tu navegador no soporta la reproducción de audio HTML5.
          </audio>
        </div>

        <div class="texto-letra">
          <p>
            Te llamé porque hace un año que no hablamos<br>
            Para romper aquel adiós que nos juramos<br>
            Voy a pedirte de rodillas que regreses junto a mí<br>
            Porque soy de ti<br>
            Y te quiero como antes, mucho más.
          </p>
          <p>
            Te llamé porque te quiero todavía<br>
            Porque este amor me atormenta noche y día<br>
            Voy a pedirte de rodillas que regreses junto a mí<br>
            Porque soy de ti<br>
            Y te quiero como antes, mucho más.
          </p>
          <p>
            Voy a pedirte de rodillas que regreses junto a mí<br>
            Porque soy de ti<br>
            Y te quiero como antes, mucho más.
          </p>
        </div>

        <div class="enlaces-cruzados">
          <a href="#letra-fabula">↑ Anterior: Fábula</a>
          <a href="#musica">← Regresar al catálogo musical</a>
        </div>
      </div>

      <a class="volver" href="#inicio">← Volver al inicio</a>
    </section>

    <footer class="pie">
      <div class="redes-sociales">
        <span>Redes oficiales de Los Iracundos:</span>
        <a href="https://www.facebook.com/losiracundosoriginales/" target="_blank" rel="noopener noreferrer">Facebook</a>
        <a href="https://www.instagram.com/losiracundosoriginales" target="_blank" rel="noopener noreferrer">Instagram</a>
        <a href="https://losiracundos.com/" target="_blank" rel="noopener noreferrer">Sitio web</a>
        <a href="https://www.tiktok.com/@losiracundosoriginales" target="_blank" rel="noopener noreferrer">TikTok</a>
        <a href="https://x.com/Los_Iracundos" target="_blank" rel="noopener noreferrer">X</a>
        <a href="https://www.youtube.com/@LosIracundosOriginales" target="_blank" rel="noopener noreferrer">YouTube</a>
      </div>

      <div class="creditos-pie">
        Hecho por Randy Daves De Santis Cruz - Carrera de Sistemas de Información 3er Semestre "C" Vespertino - Creado en el año 2026 - Comentarios y sugerencias al correo:
        <a href="mailto:randydavesdesantiscruz1996@gmail.com">randydavesdesantiscruz1996@gmail.com</a> - Todos los derechos reservados
      </div>
    </footer>

  </div>

  <button id="btn-subir" type="button" title="Regresar al inicio de la página">↑ Inicio</button>

  <script>
    document.querySelectorAll(".video-contenedor iframe").forEach(function (frame) {
      var url = frame.getAttribute("src") || "";
      var coincidencia = url.match(/(?:youtube\.com\/watch\?v=|youtu\.be\/)([a-zA-Z0-9_-]{11})/);
      if (coincidencia) {
        frame.src = "https://www.youtube.com/embed/" + coincidencia[1];
      }
    });

    var todosLosAudios = document.querySelectorAll("audio");
    todosLosAudios.forEach(function (reproductor) {
      reproductor.addEventListener("play", function () {
        todosLosAudios.forEach(function (otro) {
          if (otro !== reproductor) {
            otro.pause();
          }
        });
      });
    });

    document.getElementById("btn-subir").addEventListener("click", function () {
      window.scrollTo({ top: 0, behavior: "smooth" });
    });

    function mostrar() {
      var hash = location.hash.slice(1) || "inicio";
      var id = hash;
      var destino = null;

      if (hash.indexOf("pista-") === 0) {
        id = "audios";
        destino = document.getElementById(hash);
      } else if (hash.indexOf("letra-") === 0) {
        id = "letras";
        destino = document.getElementById(hash);
      }

      var paginas = document.querySelectorAll(".pagina");
      var enlaces = document.querySelectorAll(".menu a");
      var existe = false;

      paginas.forEach(function (p) {
        var esActual = (p.id === id);

        if (!esActual && !p.hidden) {
          p.querySelectorAll("iframe").forEach(function (frame) {
            frame.src = frame.src;
          });
          p.querySelectorAll("audio").forEach(function (audio) {
            audio.pause();
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

      if (destino) {
        destino.scrollIntoView({ behavior: "smooth", block: "start" });
      } else {
        window.scrollTo({ top: 0, behavior: "smooth" });
      }
    }

    window.addEventListener("hashchange", mostrar);
    mostrar();
  </script>

</body>
</html>
