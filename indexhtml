
<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Patitas & Puntadas | Ropa y accesorios para perros y gatos</title>
  <meta name="description" content="Venta y arreglo de ropa y accesorios para perros y gatos. Abriguitos, collares, camas y arreglos a medida.">
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link href="https://fonts.googleapis.com/css2?family=Baloo+2:wght@500;700;800&family=Nunito:wght@400;600;700&display=swap" rel="stylesheet">
  <style>
    :root {
      --verde: #b8e0c2;
      --verde-claro: #e3f4e7;
      --verde-osc: #5e9e6e;
      --amarillo: #fff1a8;
      --amarillo-claro: #fffbe3;
      --amarillo-osc: #f2c94c;
      --texto: #3d4a3f;
      --texto-suave: #6b7a6d;
      --blanco: #ffffff;
      --radio: 28px;
      --sombra: 0 10px 30px rgba(94, 158, 110, 0.15);
    }
    * { box-sizing: border-box; margin: 0; padding: 0; }
    html { scroll-behavior: smooth; }
    body {
      font-family: "Nunito", system-ui, sans-serif;
      color: var(--texto);
      background: var(--amarillo-claro);
      line-height: 1.65;
    }
    h1, h2, h3, .logo { font-family: "Baloo 2", "Nunito", sans-serif; line-height: 1.15; }
    a { color: inherit; text-decoration: none; }
    .contenedor { width: min(1100px, 100% - 32px); margin-inline: auto; }
    section { padding: 80px 0; position: relative; }
    h2 { font-size: clamp(1.8rem, 4vw, 2.5rem); text-align: center; color: var(--verde-osc); }
    .subtitulo { text-align: center; color: var(--texto-suave); max-width: 600px; margin: 8px auto 44px; }
    .huellitas { text-align: center; font-size: 1.1rem; letter-spacing: 6px; opacity: .6; }

    .btn {
      display: inline-block; padding: 13px 28px; border-radius: 999px; font-weight: 700;
      border: 3px solid transparent; cursor: pointer; font-family: inherit; font-size: 1rem;
      transition: transform .2s, box-shadow .2s, background .2s;
    }
    .btn:hover { transform: translateY(-3px) rotate(-1deg); box-shadow: 0 8px 18px rgba(0,0,0,.08); }
    .btn-amarillo { background: var(--amarillo-osc); color: var(--texto); }
    .btn-verde { background: var(--verde-osc); color: #fff; }
    .btn-borde { border-color: var(--verde-osc); color: var(--verde-osc); background: #fff; }

    /* Header */
    header {
      position: sticky; top: 0; z-index: 50;
      background: rgba(255, 251, 227, .92); backdrop-filter: blur(8px);
      border-bottom: 3px dashed var(--verde);
    }
    .nav { display: flex; align-items: center; justify-content: space-between; height: 72px; }
    .logo { font-size: 1.5rem; font-weight: 800; color: var(--verde-osc); display: flex; align-items: center; gap: 6px; }
    .logo span { color: var(--amarillo-osc); }
    .nav ul { list-style: none; display: flex; gap: 26px; }
    .nav ul a { font-weight: 700; color: var(--texto-suave); padding: 6px 12px; border-radius: 999px; transition: background .2s; }
    .nav ul a:hover { background: var(--verde-claro); color: var(--verde-osc); }
    .menu-btn { display: none; background: var(--verde-claro); border: 0; width: 44px; height: 44px; border-radius: 50%; font-size: 1.4rem; cursor: pointer; }

    /* Hero */
    .hero { background: linear-gradient(180deg, var(--verde-claro) 0%, var(--amarillo-claro) 100%); padding: 90px 0 110px; overflow: hidden; }
    .hero .contenedor { display: grid; grid-template-columns: 1.1fr 1fr; gap: 40px; align-items: center; }
    .insignia { display: inline-block; background: var(--amarillo); padding: 6px 16px; border-radius: 999px; font-weight: 700; font-size: .9rem; margin-bottom: 18px; }
    .hero h1 { font-size: clamp(2.2rem, 5.5vw, 3.6rem); color: var(--verde-osc); margin-bottom: 18px; }
    .hero h1 em { font-style: normal; background: var(--amarillo); padding: 0 10px; border-radius: 14px; }
    .hero p { font-size: 1.15rem; color: var(--texto-suave); margin-bottom: 30px; max-width: 520px; }
    .hero-botones { display: flex; gap: 12px; flex-wrap: wrap; }

    .hero-ilustracion { position: relative; display: grid; place-items: center; }
    .burbuja {
      width: min(380px, 85vw); aspect-ratio: 1; border-radius: 50%;
      background: var(--amarillo); display: grid; place-items: center; position: relative;
      box-shadow: inset 0 -12px 0 rgba(242, 201, 76, .35);
    }
    .burbuja .mascotas { font-size: clamp(5rem, 14vw, 8rem); animation: flotar 3.5s ease-in-out infinite; }
    .adorno { position: absolute; font-size: 2rem; animation: flotar 4s ease-in-out infinite; }
    .adorno.a1 { top: 6%; left: 4%; animation-delay: .5s; }
    .adorno.a2 { top: 12%; right: 2%; animation-delay: 1s; }
    .adorno.a3 { bottom: 8%; left: 10%; animation-delay: 1.5s; }
    .adorno.a4 { bottom: 4%; right: 12%; }
    @keyframes flotar { 0%,100% { transform: translateY(0); } 50% { transform: translateY(-12px); } }

    .ola { position: absolute; bottom: -1px; left: 0; width: 100%; height: 60px; }

    /* Tarjetas */
    .grid { display: grid; gap: 26px; }
    .grid-3 { grid-template-columns: repeat(3, 1fr); }
    .grid-4 { grid-template-columns: repeat(4, 1fr); }
    .tarjeta {
      background: var(--blanco); border-radius: var(--radio); padding: 30px 26px; text-align: center;
      box-shadow: var(--sombra); border: 3px solid var(--verde-claro); transition: transform .25s;
    }
    .tarjeta:hover { transform: translateY(-6px) rotate(.5deg); }
    .icono {
      width: 84px; height: 84px; margin: 0 auto 16px; border-radius: 50%;
      display: grid; place-items: center; font-size: 2.4rem; background: var(--amarillo);
    }
    .tarjeta:nth-child(even) .icono { background: var(--verde); }
    .tarjeta h3 { font-size: 1.4rem; color: var(--verde-osc); margin-bottom: 6px; }
    .tarjeta p { color: var(--texto-suave); }

    /* Tienda */
    .verde { background: var(--verde-claro); }
    .filtros { display: flex; justify-content: center; gap: 10px; flex-wrap: wrap; margin-bottom: 36px; }
    .filtro {
      padding: 9px 20px; border-radius: 999px; border: 3px solid var(--verde); background: #fff;
      cursor: pointer; font-weight: 700; font-family: inherit; color: var(--texto); transition: all .2s;
    }
    .filtro:hover { background: var(--amarillo-claro); }
    .filtro.activo { background: var(--verde-osc); border-color: var(--verde-osc); color: #fff; }
    .producto { padding: 0; overflow: hidden; display: flex; flex-direction: column; text-align: left; }
    .producto .img { height: 160px; display: grid; place-items: center; font-size: 4rem; background: var(--amarillo-claro); position: relative; }
    .producto:nth-child(even) .img { background: #f0f9f2; }
    .producto .para {
      position: absolute; top: 12px; left: 12px; background: #fff; padding: 3px 12px;
      border-radius: 999px; font-size: .8rem; font-weight: 700;
    }
    .producto .nuevo { position: absolute; top: 12px; right: 12px; background: var(--amarillo-osc); padding: 3px 12px; border-radius: 999px; font-size: .8rem; font-weight: 700; }
    .producto .info { padding: 20px; display: flex; flex-direction: column; flex: 1; }
    .producto h3 { font-size: 1.15rem; }
    .producto .tallas { font-size: .88rem; color: var(--texto-suave); margin: 4px 0 12px; }
    .producto .pie { margin-top: auto; display: flex; align-items: center; justify-content: space-between; gap: 8px; }
    .precio { font-family: "Baloo 2", sans-serif; font-size: 1.5rem; font-weight: 800; color: var(--verde-osc); }
    .btn-mini {
      background: var(--amarillo); border: 0; border-radius: 999px; padding: 8px 14px;
      font-weight: 700; cursor: pointer; font-family: inherit; transition: transform .2s;
    }
    .btn-mini:hover { transform: scale(1.06); }

    /* Cesta flotante */
    .cesta {
      position: fixed; right: 20px; bottom: 20px; z-index: 60; background: var(--verde-osc); color: #fff;
      border-radius: 999px; padding: 12px 20px; font-weight: 700; box-shadow: 0 8px 22px rgba(0,0,0,.18);
      display: flex; align-items: center; gap: 8px;
    }
    .cesta .contador { background: var(--amarillo-osc); color: var(--texto); border-radius: 999px; min-width: 26px; height: 26px; display: grid; place-items: center; font-size: .9rem; }
    .cesta.salto { animation: salto .4s; }
    @keyframes salto { 50% { transform: scale(1.18); } }

    /* Arreglos */
    .arreglos { display: grid; grid-template-columns: 1fr 1fr; gap: 50px; align-items: center; }
    .arreglos-visual {
      background: var(--amarillo); border-radius: 40% 60% 55% 45% / 50% 45% 55% 50%;
      aspect-ratio: 1; display: grid; place-items: center; font-size: clamp(5rem, 12vw, 7.5rem);
    }
    .arreglos h2 { text-align: left; }
    .lista-arreglos { list-style: none; margin: 22px 0 28px; }
    .lista-arreglos li { display: flex; justify-content: space-between; gap: 12px; padding: 12px 0; border-bottom: 2px dotted var(--verde); }
    .lista-arreglos strong { color: var(--verde-osc); white-space: nowrap; }

    /* Pasos */
    .pasos { counter-reset: paso; }
    .paso { text-align: center; }
    .paso::before {
      counter-increment: paso; content: counter(paso);
      display: grid; place-items: center; margin: 0 auto 14px; width: 60px; height: 60px;
      border-radius: 50%; background: var(--amarillo); border: 3px dashed var(--amarillo-osc);
      font-family: "Baloo 2", sans-serif; font-size: 1.6rem; font-weight: 800; color: var(--verde-osc);
    }
    .paso h3 { color: var(--verde-osc); font-size: 1.25rem; }
    .paso p { color: var(--texto-suave); }

    /* FAQ */
    .faq { max-width: 760px; margin: 0 auto; display: grid; gap: 14px; }
    .faq-item { background: #fff; border-radius: 22px; border: 3px solid var(--verde-claro); overflow: hidden; }
    .faq-pregunta {
      width: 100%; background: none; border: 0; padding: 18px 22px; text-align: left; cursor: pointer;
      font-family: inherit; font-size: 1.05rem; font-weight: 700; color: var(--texto);
      display: flex; justify-content: space-between; gap: 12px;
    }
    .faq-pregunta span { transition: transform .25s; }
    .faq-item.abierto .faq-pregunta span { transform: rotate(180deg); }
    .faq-respuesta { max-height: 0; overflow: hidden; transition: max-height .3s ease; color: var(--texto-suave); }
    .faq-respuesta p { padding: 0 22px 18px; }

    /* Contacto */
    .contacto-caja {
      background: #fff; border-radius: 36px; padding: 44px; box-shadow: var(--sombra);
      display: grid; grid-template-columns: 1fr 1.3fr; gap: 40px; border: 3px solid var(--verde);
    }
    .contacto-caja h2 { text-align: left; }
    .contacto-info { list-style: none; margin-top: 22px; }
    .contacto-info li { display: flex; gap: 12px; margin-bottom: 16px; align-items: flex-start; }
    .contacto-info .ico { width: 40px; height: 40px; flex-shrink: 0; border-radius: 50%; background: var(--verde-claro); display: grid; place-items: center; }
    form { display: grid; gap: 14px; }
    .fila { display: grid; grid-template-columns: 1fr 1fr; gap: 14px; }
    label { font-weight: 700; font-size: .92rem; display: block; margin-bottom: 4px; }
    input, select, textarea {
      width: 100%; padding: 12px 16px; border: 3px solid var(--verde-claro); border-radius: 18px;
      font: inherit; background: var(--amarillo-claro); color: var(--texto);
    }
    input:focus, select:focus, textarea:focus { outline: none; border-color: var(--verde-osc); background: #fff; }
    .error { color: #c2553d; font-size: .85rem; min-height: 1em; }
    .mensaje-ok { display: none; background: var(--verde-claro); color: var(--verde-osc); padding: 14px 18px; border-radius: 18px; font-weight: 700; }

    footer { background: var(--verde); padding: 40px 0; text-align: center; }
    footer .logo { justify-content: center; margin-bottom: 6px; }
    footer p { color: var(--texto); }

    /* Responsive */
    @media (max-width: 920px) {
      .grid-4 { grid-template-columns: repeat(2, 1fr); }
      .grid-3 { grid-template-columns: 1fr; }
      .hero .contenedor, .arreglos, .contacto-caja { grid-template-columns: 1fr; }
      .hero { text-align: center; }
      .hero p { margin-inline: auto; }
      .hero-botones { justify-content: center; }
      .arreglos-visual { max-width: 320px; margin: 0 auto; }
    }
    @media (max-width: 740px) {
      .menu-btn { display: block; }
      .nav ul {
        position: absolute; top: 72px; left: 0; right: 0; background: var(--amarillo-claro);
        flex-direction: column; gap: 4px; padding: 12px 16px; border-bottom: 3px dashed var(--verde); display: none;
      }
      .nav ul.abierto { display: flex; }
      .nav ul a { display: block; }
      .nav .btn { display: none; }
      .fila { grid-template-columns: 1fr; }
      .contacto-caja { padding: 28px 20px; }
      section { padding: 60px 0; }
    }
    @media (max-width: 520px) { .grid-4 { grid-template-columns: 1fr; } }
  </style>
</head>
<body>

  <header>
    <div class="contenedor nav">
      <a href="#inicio" class="logo">🐾 Patitas<span>&</span>Puntadas</a>
      <ul id="menu">
        <li><a href="#tienda">Tienda</a></li>
        <li><a href="#arreglos">Arreglos</a></li>
        <li><a href="#como-funciona">Cómo funciona</a></li>
        <li><a href="#faq">Dudas</a></li>
        <li><a href="#contacto">Contacto</a></li>
      </ul>
      <a href="#contacto" class="btn btn-amarillo">¡Escríbenos!</a>
      <button class="menu-btn" id="menuBtn" aria-label="Abrir menú">☰</button>
    </div>
  </header>

  <!-- Hero -->
  <section class="hero" id="inicio">
    <div class="contenedor">
      <div>
        <span class="insignia">🧶 Hecho con mucho cariño</span>
        <h1>Ropita y mimos para tus <em>peludos</em></h1>
        <p>Abriguitos, collares, camitas y accesorios para perros y gatos. Y si su prenda favorita se ha roto, te la arreglamos o ajustamos a su medida.</p>
        <div class="hero-botones">
          <a href="#tienda" class="btn btn-verde">Ver la tienda</a>
          <a href="#arreglos" class="btn btn-borde">Necesito un arreglo</a>
        </div>
      </div>
      <div class="hero-ilustracion" aria-hidden="true">
        <div class="burbuja"><div class="mascotas">🐶🐱</div></div>
        <span class="adorno a1">🧣</span>
        <span class="adorno a2">🦴</span>
        <span class="adorno a3">🎀</span>
        <span class="adorno a4">🧵</span>
      </div>
    </div>
    <svg class="ola" viewBox="0 0 1440 60" preserveAspectRatio="none" aria-hidden="true">
      <path d="M0,30 C240,60 480,0 720,30 C960,60 1200,0 1440,30 L1440,60 L0,60 Z" fill="#fffbe3"/>
    </svg>
  </section>

  <!-- Servicios -->
  <section id="servicios">
    <div class="contenedor">
      <p class="huellitas">🐾 🐾 🐾</p>
      <h2>Todo para que vayan monísimos</h2>
      <p class="subtitulo">Pensado para su comodidad, su tamaño y su personalidad.</p>
      <div class="grid grid-3">
        <article class="tarjeta">
          <div class="icono">🧥</div>
          <h3>Ropita</h3>
          <p>Abrigos, jerséis, chubasqueros y pijamas en tallas para mascotas pequeñas, medianas y grandes.</p>
        </article>
        <article class="tarjeta">
          <div class="icono">🎀</div>
          <h3>Accesorios</h3>
          <p>Collares, arneses, correas, pajaritas, bandanas y camitas suaves para descansar.</p>
        </article>
        <article class="tarjeta">
          <div class="icono">🪡</div>
          <h3>Arreglos y ajustes</h3>
          <p>Cosemos rotos, cambiamos cierres y adaptamos prendas a las medidas exactas de tu peludo.</p>
        </article>
      </div>
    </div>
  </section>

  <!-- Tienda -->
  <section class="verde" id="tienda">
    <div class="contenedor">
      <h2>Nuestra tiendita</h2>
      <p class="subtitulo">Elige, añádelo a tu cesta y te confirmamos talla y disponibilidad.</p>
      <div class="filtros" id="filtros">
        <button class="filtro activo" data-cat="todos">Todo</button>
        <button class="filtro" data-cat="perro">🐶 Perros</button>
        <button class="filtro" data-cat="gato">🐱 Gatos</button>
        <button class="filtro" data-cat="ropa">Ropa</button>
        <button class="filtro" data-cat="accesorio">Accesorios</button>
      </div>
      <div class="grid grid-4" id="listaProductos"></div>
    </div>
  </section>

  <!-- Arreglos -->
  <section id="arreglos">
    <div class="contenedor arreglos">
      <div class="arreglos-visual" aria-hidden="true">🧵</div>
      <div>
        <h2>Taller de arreglos</h2>
        <p style="color:var(--texto-suave)">¿Se ha descosido su abrigo favorito o el arnés le queda grande? Tráelo y le damos una segunda vida.</p>
        <ul class="lista-arreglos">
          <li>Coser rotos y descosidos <strong>desde 5 €</strong></li>
          <li>Cambio de velcro o cremallera <strong>desde 8 €</strong></li>
          <li>Ajuste de talla <strong>desde 10 €</strong></li>
          <li>Prenda a medida <strong>consultar</strong></li>
          <li>Bordado de nombre <strong>desde 6 €</strong></li>
        </ul>
        <a href="#contacto" class="btn btn-amarillo" id="pedirArreglo">Pedir presupuesto</a>
      </div>
    </div>
  </section>

  <!-- Cómo funciona -->
  <section class="verde" id="como-funciona">
    <div class="contenedor">
      <h2>¿Cómo funciona?</h2>
      <p class="subtitulo">Fácil, rápido y sin estrés para ti ni para tu mascota.</p>
      <div class="grid grid-4 pasos">
        <div class="paso"><h3>Cuéntanos</h3><p>Escríbenos qué quieres comprar o arreglar.</p></div>
        <div class="paso"><h3>Mide</h3><p>Te enviamos una guía sencilla para tomar sus medidas.</p></div>
        <div class="paso"><h3>Preparamos</h3><p>Reservamos la prenda o la arreglamos en el taller.</p></div>
        <div class="paso"><h3>¡A estrenar!</h3><p>Recógelo en tienda o te lo enviamos a casa.</p></div>
      </div>
    </div>
  </section>

  <!-- FAQ -->
  <section id="faq">
    <div class="contenedor">
      <h2>Preguntas frecuentes</h2>
      <p class="subtitulo">Si no encuentras tu respuesta, ¡pregúntanos!</p>
      <div class="faq">
        <div class="faq-item">
          <button class="faq-pregunta">¿Cómo sé qué talla necesita mi mascota? <span>▾</span></button>
          <div class="faq-respuesta"><p>Solo necesitas medir el largo de espalda (del cuello al inicio de la cola), el contorno de pecho y el de cuello. Te ayudamos a elegir con esos datos.</p></div>
        </div>
        <div class="faq-item">
          <button class="faq-pregunta">¿Cuánto tarda un arreglo? <span>▾</span></button>
          <div class="faq-respuesta"><p>Los arreglos sencillos suelen estar listos en 2-4 días. Las prendas a medida pueden tardar un poco más; te damos la fecha al hacer el presupuesto.</p></div>
        </div>
        <div class="faq-item">
          <button class="faq-pregunta">¿Arregláis prendas que no se compraron aquí? <span>▾</span></button>
          <div class="faq-respuesta"><p>¡Claro! Arreglamos cualquier prenda o accesorio de tela, sea de donde sea.</p></div>
        </div>
        <div class="faq-item">
          <button class="faq-pregunta">¿Hacéis envíos? <span>▾</span></button>
          <div class="faq-respuesta"><p>Sí, enviamos a domicilio. También puedes recoger tu pedido en nuestra tienda.</p></div>
        </div>
      </div>
    </div>
  </section>

  <!-- Contacto -->
  <section id="contacto" style="padding-top:20px">
    <div class="contenedor">
      <div class="contacto-caja">
        <div>
          <h2>¡Hablemos! 💌</h2>
          <p style="color:var(--texto-suave)">Cuéntanos qué necesita tu peludo y te respondemos lo antes posible.</p>
          <ul class="contacto-info">
            <li><span class="ico">📞</span><div><strong>Teléfono</strong><br>600 000 000</div></li>
            <li><span class="ico">✉️</span><div><strong>Email</strong><br>hola@tudominio.com</div></li>
            <li><span class="ico">📍</span><div><strong>Tienda</strong><br>Calle Ejemplo 5, Tu ciudad</div></li>
            <li><span class="ico">🕘</span><div><strong>Horario</strong><br>L-V 10:00–14:00 y 17:00–20:30 · S 10:00–14:00</div></li>
          </ul>
        </div>
        <form id="formContacto" novalidate>
          <div class="fila">
            <div>
              <label for="nombre">Tu nombre</label>
              <input type="text" id="nombre" name="nombre" placeholder="Tu nombre">
              <div class="error" data-error="nombre"></div>
            </div>
            <div>
              <label for="mascota">Nombre de tu mascota</label>
              <input type="text" id="mascota" name="mascota" placeholder="Ej.: Luna">
            </div>
          </div>
          <div class="fila">
            <div>
              <label for="email">Email</label>
              <input type="email" id="email" name="email" placeholder="tu@email.com">
              <div class="error" data-error="email"></div>
            </div>
            <div>
              <label for="telefono">Teléfono (opcional)</label>
              <input type="tel" id="telefono" name="telefono" placeholder="600 000 000">
            </div>
          </div>
          <div class="fila">
            <div>
              <label for="especie">Es un...</label>
              <select id="especie" name="especie">
                <option value="perro">🐶 Perro</option>
                <option value="gato">🐱 Gato</option>
              </select>
            </div>
            <div>
              <label for="tipo">Quiero...</label>
              <select id="tipo" name="tipo">
                <option value="compra">Comprar algo</option>
                <option value="arreglo">Un arreglo</option>
                <option value="medida">Una prenda a medida</option>
                <option value="otro">Otra cosa</option>
              </select>
            </div>
          </div>
          <div>
            <label for="mensaje">Mensaje</label>
            <textarea id="mensaje" name="mensaje" rows="4" placeholder="Cuéntanos un poquito más..."></textarea>
            <div class="error" data-error="mensaje"></div>
          </div>
          <button type="submit" class="btn btn-verde">Enviar mensaje 🐾</button>
          <div class="mensaje-ok" id="mensajeOk">¡Guau, miau! Hemos recibido tu mensaje. Te respondemos muy pronto 💚</div>
        </form>
      </div>
    </div>
  </section>

  <footer>
    <div class="contenedor">
      <a href="#inicio" class="logo">🐾 Patitas<span>&</span>Puntadas</a>
      <p>Ropa, accesorios y arreglos para perros y gatos</p>
      <p style="margin-top:6px;opacity:.75">© <span id="anio"></span> Patitas & Puntadas</p>
    </div>
  </footer>

  <a href="#contacto" class="cesta" id="cesta" aria-label="Ver cesta">🧺 Cesta <span class="contador" id="contador">0</span></a>

  <script>
    // Menú móvil
    const menu = document.getElementById('menu');
    document.getElementById('menuBtn').addEventListener('click', () => menu.classList.toggle('abierto'));
    menu.querySelectorAll('a').forEach(a => a.addEventListener('click', () => menu.classList.remove('abierto')));

    // Catálogo (edita esta lista con tus productos reales)
    const productos = [
      { nombre: 'Abriguito acolchado', especie: 'perro', tipo: 'ropa', icono: '🧥', precio: 24.9, tallas: 'XS · S · M · L', nuevo: true },
      { nombre: 'Jersey de lana suave', especie: 'perro', tipo: 'ropa', icono: '🧶', precio: 19.9, tallas: 'XS · S · M' },
      { nombre: 'Chubasquero amarillo', especie: 'perro', tipo: 'ropa', icono: '☔', precio: 17.5, tallas: 'S · M · L · XL' },
      { nombre: 'Pijamita de algodón', especie: 'gato', tipo: 'ropa', icono: '🌙', precio: 14.9, tallas: 'Única', nuevo: true },
      { nombre: 'Collar con cascabel', especie: 'gato', tipo: 'accesorio', icono: '🔔', precio: 7.5, tallas: 'Ajustable' },
      { nombre: 'Pajarita de fiesta', especie: 'gato', tipo: 'accesorio', icono: '🎀', precio: 6.9, tallas: 'Ajustable' },
      { nombre: 'Arnés acolchado', especie: 'perro', tipo: 'accesorio', icono: '🦮', precio: 22.0, tallas: 'S · M · L' },
      { nombre: 'Camita nube', especie: 'gato', tipo: 'accesorio', icono: '☁️', precio: 29.9, tallas: '50 cm · 70 cm' }
    ];

    const lista = document.getElementById('listaProductos');
    const euro = n => n.toLocaleString('es-ES', { style: 'currency', currency: 'EUR' });
    const cesta = [];

    function pintar(filtro) {
      const items = productos.filter(p => filtro === 'todos' || p.especie === filtro || p.tipo === filtro);
      lista.innerHTML = items.map(p => `
        <article class="tarjeta producto">
          <div class="img">
            <span class="para">${p.especie === 'perro' ? '🐶 Perro' : '🐱 Gato'}</span>
            ${p.nuevo ? '<span class="nuevo">¡Nuevo!</span>' : ''}
            ${p.icono}
          </div>
          <div class="info">
            <h3>${p.nombre}</h3>
            <p class="tallas">Tallas: ${p.tallas}</p>
            <div class="pie">
              <span class="precio">${euro(p.precio)}</span>
              <button class="btn-mini" data-nombre="${p.nombre}">+ Añadir</button>
            </div>
          </div>
        </article>`).join('');
    }
    pintar('todos');

    document.getElementById('filtros').addEventListener('click', e => {
      const b = e.target.closest('.filtro');
      if (!b) return;
      document.querySelectorAll('.filtro').forEach(f => f.classList.remove('activo'));
      b.classList.add('activo');
      pintar(b.dataset.cat);
    });

    // Cesta sencilla: añade productos y los pasa al formulario
    const cestaBtn = document.getElementById('cesta');
    const contador = document.getElementById('contador');
    lista.addEventListener('click', e => {
      const b = e.target.closest('[data-nombre]');
      if (!b) return;
      cesta.push(b.dataset.nombre);
      contador.textContent = cesta.length;
      cestaBtn.classList.remove('salto'); void cestaBtn.offsetWidth; cestaBtn.classList.add('salto');
      b.textContent = '¡Añadido! 💚';
      setTimeout(() => b.textContent = '+ Añadir', 1200);
    });
    cestaBtn.addEventListener('click', () => {
      if (!cesta.length) return;
      document.getElementById('tipo').value = 'compra';
      const resumen = {};
      cesta.forEach(n => resumen[n] = (resumen[n] || 0) + 1);
      document.getElementById('mensaje').value = 'Me interesa:\n' +
        Object.entries(resumen).map(([n, c]) => `- ${n} x${c}`).join('\n');
    });

    document.getElementById('pedirArreglo').addEventListener('click', () => {
      document.getElementById('tipo').value = 'arreglo';
    });

    // FAQ
    document.querySelectorAll('.faq-pregunta').forEach(p => {
      p.addEventListener('click', () => {
        const item = p.parentElement;
        const r = item.querySelector('.faq-respuesta');
        const abierto = item.classList.toggle('abierto');
        r.style.maxHeight = abierto ? r.scrollHeight + 'px' : 0;
      });
    });

    // Formulario
    const form = document.getElementById('formContacto');
    form.addEventListener('submit', e => {
      e.preventDefault();
      const d = Object.fromEntries(new FormData(form));
      const err = {};
      if (!d.nombre.trim()) err.nombre = 'Dinos tu nombre 🙂';
      if (!/^[^\s@]+@[^\s@]+\.[^\s@]+$/.test(d.email.trim())) err.email = 'Revisa el email.';
      if (d.mensaje.trim().length < 10) err.mensaje = 'Cuéntanos un poquito más (mín. 10 caracteres).';
      form.querySelectorAll('.error').forEach(el => el.textContent = err[el.dataset.error] || '');
      if (Object.keys(err).length) return;

      // Aquí conectarías el envío con tu backend o servicio de formularios
      console.log('Mensaje enviado:', d);
      form.reset();
      cesta.length = 0; contador.textContent = 0;
      const ok = document.getElementById('mensajeOk');
      ok.style.display = 'block';
      setTimeout(() => ok.style.display = 'none', 6000);
    });

    document.getElementById('anio').textContent = new Date().getFullYear();
  </script>
</body>
</html>
