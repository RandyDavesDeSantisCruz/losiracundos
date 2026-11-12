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
