---
layout: home
sitemap: true
---

<style>
  /* Contenedor principal con dos columnas */
  .container {
    display: flex;
    justify-content: space-between;
    flex-direction: column; /* Inicialmente, apila los elementos */
  }

  /* Panel izquierdo (texto) */
  .content {
    width: 100%;
    margin-bottom: 20px; /* Espacio inferior en móviles */
  }

  /* Panel derecho (imagen) */
  .image-panel {
    width: 100%;
    margin-bottom: 20px; /* Espacio inferior para la imagen */
  }

  .profile-pic {
    width: 100%; /* La imagen ocupa todo el ancho del panel */
    margin-bottom: 20px; /* Espaciado inferior para la imagen */
  }

  /* Diseño para pantallas más grandes (escritorio) */
  @media screen and (min-width: 600px) {
    .container {
      flex-direction: row; /* Alinea en filas (imagen y texto en columnas) */
    }

    .content {
      width: 65%; /* Ajusta el tamaño del panel de texto */
      margin-right: 20px; /* Espacio entre texto e imagen */
    }

    .image-panel {
      width: 30%; /* Ajusta el tamaño del panel de imagen */
      position: sticky; /* La imagen sigue el scroll */
      top: 20px; /* Distancia desde el borde superior */
    }
  }

  /* Alinea el texto dentro del contenido */
  .content p,
  .content ul {
    text-align: justify;
  }
</style>

<div class="container">
  <div class="image-panel">
    <img class="profile-pic" src="profile.jpg" alt="Profile Picture">
  </div>

  <div class="content">
    <p><strong>Hello, welcome to my personal website!</strong></p>
    <p> I am Andrey, a final-year Ph.D. in Economics student at the <a href="https://economia.uc3m.es/personal/ramos/" target="_blank">Universidad Carlos III de Madrid (UC3M).</a> I am writing my dissertation under the supervision of Prof. <a href="https://www.eco.uc3m.es/~jgonzalo/" target="_blank">Jesús Gonzalo.</a></p>
    <p>I will be on the <strong>Job Market 2024-2025.</strong> Find here my <a href="CV_AndreyRamos.pdf" target="_blank">CV</a>.</p>
    <p>My research interests lie at the intersection of <strong>time series econometrics, climate and environmental economics, and applied econometrics</strong>. In my Job Market Paper, I combine elements of physics theory from Energy Balance Models (EBMs) with recent advances in time series econometrics, to propose a quantitative methodology for studying heterogeneity in the evolution of the entire temperature distribution and its association with different climate drivers, including carbon dioxide (CO2). Estimation and forecasting/projection outcomes from this method can be incorporated into economic studies to quantify the economic consequences of climate change, while explicitly accounting for different forms of climate heterogeneity.</p>
    <ul><li>More research <a href="https://anramosr.github.io/research/" target="_blank">here.</a></li></ul>
    <ul><li>During spring 2024, I visited the Department of Economics and Business Economics at Aarhus University.</li></ul>
    <ul><li>My Job Market Paper was selected for a poster session at the <strong>ASSA 2025 Annual Meeting</strong>.</li></ul>
    <ul><li>Contact: <a href="mailto:anramosr@eco.uc3m.es">anramosr@eco.uc3m.es</a> or <a href="mailto:adramosr@gmail.com">adramosr@gmail.com</a>.</li></ul>
  </div>
</div>
