
<html lang="es">
<head>
  <meta charset="UTF-8">
  <title></title>
  <style>
    /* Fondo de video */
    body, html {
      height: 100%;
      margin: 0;
      padding: 0;
      overflow: hidden;
    }
    .video-bg {
      position: fixed;
      top: 0; left: 0; min-width: 100vw; min-height: 100vh;
      width: 100vw; height: 100vh;
      object-fit: cover;
      z-index: -1;
    }
    /* Cuadro con texto y botones */
    .cuadro {
      position: absolute;
      top: 50%; left: 50%;
      transform: translate(-50%, -50%);
      background: rgba(255,255,255,0.87);
      padding: 2rem 2.5rem;
      border-radius: 16px;
      box-shadow: 0 8px 32px rgba(0,0,0,0.25);
      text-align: center;
    }
    .cuadro h2 {
      margin-top: 0;
    }
    .botones {
      margin-top: 1.5rem;
    }
    .botones a {
      display: inline-block;
      background: #437be8;
      color: #black ;
      padding: 0.7em 1.4em;
      border-radius: 6px;
      margin: 0 0.5em;
      text-decoration: none;
      font-weight: bold;
      transition: background 0.2s;
    }
    .botones a:hover {
      background: #2455b7;
    }
  </style>
</head>
<body>
  <!-- Fondo de video (reemplaza src por tu video o uno libre de derechos) -->
  <video class="video-bg" src="vip 01.mp4" autoplay loop muted playsinline></video>

  <!-- Cuadro con texto y botones -->
  <div class="cuadro">
    <h2>BIENVENIDO</h2>
     <h3>calzado 
     elegante </h3>
    <p> en nuestro catalogo tienes diferentes tipos y diseño de calzado ademas de ropa juvenil</p>
    <div class="botones">
      <a href="https://ice2606.github.io/elegante-01/" target="_blank">atras </a>
      <a href="https://github.com" target="_blank">zapatos</a>
       <a href="https://github.com" target="_blank">sandalias </a>
       <a href="https://github.com" target="_blank">chinelas </a>
       <a href="https://github.com" target="_blank">sandalias de tacon </a>
       <a href="https://github.com" target="_blank">ropa juvenil</a>
    </div>
  </div>
</body>
</html>
