<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>POLS</title>

  <!-- Fuente Printvetica -->
  <style>
    @font-face {
      font-family: 'Printvetica';
      src: url('/fonts/Printvetica.woff2') format('woff2');
    }
  </style>

  <!-- Google Font: Patrick Hand -->
  <link href="https://fonts.googleapis.com/css2?family=Patrick+Hand&display=swap" rel="stylesheet">

  <style>
    body {
      margin: 0;
      padding: 0;
      background: white;
      color: black;
      font-family: 'Patrick Hand', cursive;
    }

    header {
      display: flex;
      justify-content: space-between;
      align-items: center;
      padding: 1rem 2rem;
    }

    .logo {
      font-family: 'Printvetica', sans-serif;
      font-size: 1.5rem;
      font-weight: bold;
    }

    nav {
      display: flex;
      gap: 1.5rem;
      position: relative;
    }

    .dropdown {
      position: relative;
    }

    .dropdown-content {
      display: none;
      position: absolute;
      background-color: white;
      min-width: 160px;
      box-shadow: 0px 4px 8px rgba(0,0,0,0.1);
      z-index: 1;
      padding: 0.5rem;
    }

    .dropdown:hover .dropdown-content {
      display: block;
    }

    .dropdown-subcontent {
      display: none;
      position: absolute;
      left: 100%;
      top: 0;
      background-color: white;
      padding: 0.5rem;
      box-shadow: 0px 4px 8px rgba(0,0,0,0.1);
    }

    .dropdown-content .dropdown:hover .dropdown-subcontent {
      display: block;
    }

    a {
      text-decoration: none;
      color: black;
      display: block;
      margin: 0.3rem 0;
    }

    main {
      text-align: center;
      padding: 4rem 2rem;
    }

    .title {
      font-family: 'Printvetica', sans-serif;
      font-size: 6rem;
      margin-bottom: 2rem;
    }

    .pictograma {
      width: 80px;
      margin: 2rem auto;
      display: block;
      transition: transform 0.3s ease;
    }

    .pictograma:hover {
      transform: rotate(10deg) scale(1.1);
    }

    h2 {
      font-size: 2rem;
    }

    section {
      padding: 4rem 2rem;
      border-top: 1px solid #ccc;
    }

    section h3 {
      font-size: 1.8rem;
      margin-bottom: 1rem;
    }
  </style>
</head>
<body>

  <header>
    <div class="logo">POLS</div>
    <nav>
      <div class="dropdown">
        <span>SHOP ONLINE</span>
        <div class="dropdown-content">
          <div class="dropdown">
            <a href="#remeras">Remeras</a>
            <a href="#pantalones">Pantalones</a>
            <a href="#buzos">Buzos</a>
            <a href="#camperas">Camperas</a>
            <a href="#blazers">Blazers</a>
            <a href="#accesorios">Accesorios</a>
          </div>
        </div>
      </div>
      <a href="#talles">GUÍA DE TALLES</a>
    </nav>
  </header>

  <main>
    <h1 class="title">POLS</h1>

    <a href="#shop">
      <img src="https://raw.githubusercontent.com/Polero7070/POLSMYMIND/ab7c602d7ff2b30cdbeb64461746155944bf1eee/Untitled-3.svg" alt="Pictograma" class="pictograma">
    </a>

    <h2>¿DÓNDE ESTÁ POLS?</h2>
  </main>

  <!-- SECCIONES SHOP -->
  <section id="shop">
    <h3>SHOP ONLINE</h3>
    <p>Explorá nuestras colecciones exclusivas.</p>
  </section>

  <section id="remeras">
    <h3>Remeras</h3>
    <p>Aquí irán las fotos de remeras.</p>
  </section>

  <section id="pantalones">
    <h3>Pantalones</h3>
    <p>Aquí irán las fotos de jeans y joggings.</p>
  </section>

  <section id="buzos">
    <h3>Buzos</h3>
    <p>Aquí irán las fotos de buzos.</p>
  </section>

  <section id="camperas">
    <h3>Camperas</h3>
    <p>Aquí irán las fotos de camperas.</p>
  </section>

  <section id="blazers">
    <h3>Blazers</h3>
    <p>Aquí irán las fotos de blazers.</p>
  </section>

  <section id="accesorios">
    <h3>Accesorios</h3>
    <p>Aquí irán las fotos de guantes, gorros, etc.</p>
  </section>

  <section id="talles">
    <h3>Guía de Talles</h3>
    <p>Tabla de medidas por prenda.</p>
  </section>

</body>
</html>
