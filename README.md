<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>10 Meses Contigo ❤</title>

  <style>
    body {
      margin: 0;
      font-family: 'Arial', sans-serif;
      background: linear-gradient(#ff9a9e, #fad0c4);
      color: #fff;
      text-align: center;
      overflow-x: hidden;
    }

    /* PANTALLA DE INICIO */
    .intro {
      position: fixed;
      top: 0;
      left: 0;
      width: 100%;
      height: 100%;
      background: linear-gradient(#ff758c, #ff7eb3);
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
      z-index: 10;
      animation: fadeOut 2s ease forwards;
      animation-delay: 3s;
    }

    .intro h1 {
      font-size: 2.5em;
      animation: zoomIn 2s ease;
    }

    .intro p {
      font-size: 1.2em;
      margin-top: 10px;
    }

    @keyframes fadeOut {
      to {
        opacity: 0;
        visibility: hidden;
      }
    }

    @keyframes zoomIn {
      from {
        transform: scale(0.5);
        opacity: 0;
      }
      to {
        transform: scale(1);
        opacity: 1;
      }
    }

    /* CONTENIDO */
    .contenido {
      padding: 20px;
      margin-top: 40px;
    }

    .card {
      background: rgba(255, 255, 255, 0.2);
      border-radius: 20px;
      padding: 20px;
      margin: 20px auto;
      max-width: 700px;
      animation: slideUp 1.5s ease;
    }

    @keyframes slideUp {
      from {
        transform: translateY(50px);
        opacity: 0;
      }
      to {
        transform: translateY(0);
        opacity: 1;
      }
    }

    h2 {
      margin-bottom: 10px;
    }

    /* GALERÍA */
    .galeria {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(150px, 1fr));
      gap: 15px;
      margin-top: 20px;
    }

    .galeria img {
      width: 100%;
      border-radius: 15px;
      box-shadow: 0 5px 15px rgba(0,0,0,0.3);
      transition: transform 0.3s;
    }

    .galeria img:hover {
      transform: scale(1.05);
    }

    footer {
      margin: 40px 0;
      font-size: 1.1em;
    }
  </style>
</head>

<body>

  <!-- INTRO -->
  <div class="intro">
    <h1>10 Meses ❤</h1>
    <p>Una pequeña sorpresa para ti</p>
  </div>

  <!-- CONTENIDO -->
  <div class="contenido">

    <div class="card">
      <h2>Para ti, amor 💌</h2>
      <p>
        Estos 10 meses a tu lado han sido de los más bonitos de mi vida.  
        Gracias por acompañarme, por cuidarme y por hacerme sonreír incluso en los días difíciles.  
        Elegirte todos los días es lo más fácil del mundo.
      </p>
    </div>

    <div class="card">
      <h2>Nuestros momentos 📸</h2>

      <div class="galeria">
        <img src="foto1.jpg">
        <img src="foto2.jpg">
        <img src="foto3.jpg">
      </div>
    </div>

    <div class="card">
      <h2>Lo que siento por ti ❤</h2>
      <p>
        No sé qué nos depare el futuro, pero sí sé que quiero seguir construyéndolo contigo.  
        Gracias por ser tú, por ser mi lugar seguro y mi persona favorita.
      </p>
    </div>

    <footer>
      Con todo mi amor, <br>
      ❤ Siempre contigo
    </footer>

  </div>

</body>
</html>
