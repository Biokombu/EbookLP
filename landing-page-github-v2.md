<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>No More Bottles! - Natural Perfume Making Guide</title>
  <!-- Fuentes elegantes desde Google Fonts -->
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Cormorant+Garamond:ital,wght@0,400;0,600;1,400&family=Montserrat:wght@300;400;500&display=swap" rel="stylesheet">
  
  <style>
    :root {
      --purple-deep: #1a0329;
      --purple-vibrant: #4a126d;
      --purple-glow: #6b1b9a;
      --text-light: #f3e9f8;
      --gold-accent: #d4af37;
    }

    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
    }

    body {
      font-family: 'Montserrat', sans-serif;
      background: linear-gradient(135deg, #0a0112 0%, var(--purple-deep) 50%, #000000 100%);
      color: var(--text-light);
      line-height: 1.8;
      overflow-x: hidden;
    }

    /* Layout principal: 2 Columnas */
    .landing-layout {
      display: flex;
      min-height: 100vh;
    }

    /* Columna Izquierda: Lateral Rústico Botánico */
    .sidebar-botanical {
      width: 40%;
      position: sticky;
      top: 0;
      height: 100vh;
      background-image: url('1771051981256 (1).png'); /* Asegúrate de que esta imagen esté en tu repo */
      background-size: cover;
      background-position: center left;
      border-right: 1px solid rgba(255, 255, 255, 0.1);
      box-shadow: 10px 0 30px rgba(0, 0, 0, 0.5);
    }

    /* Columna Derecha: Contenido del Ebook y Texto */
    .main-content {
      width: 60%;
      padding: 4rem 5%;
      background: linear-gradient(180deg, rgba(42, 8, 69, 0.85) 0%, rgba(10, 1, 18, 0.95) 100%);
    }

    /* Hero & Portada */
    .hero-section {
      text-align: center;
      margin-bottom: 4rem;
      padding-bottom: 3rem;
      border-bottom: 1px solid rgba(212, 175, 55, 0.2);
    }

    .book-cover {
      max-width: 320px;
      width: 100%;
      height: auto;
      border-radius: 8px;
      box-shadow: 0 15px 35px rgba(0, 0, 0, 0.7), 0 0 25px rgba(107, 27, 154, 0.4);
      margin-bottom: 2rem;
      transition: transform 0.3s ease;
    }

    .book-cover:hover {
      transform: translateY(-5px);
    }

    h1 {
      font-family: 'Cormorant Garamond', serif;
      font-size: 3rem;
      font-weight: 600;
      letter-spacing: 2px;
      color: #ffffff;
      margin-bottom: 0.5rem;
      text-shadow: 0 2px 10px rgba(0, 0, 0, 0.5);
    }

    .subtitle {
      font-family: 'Cormorant Garamond', serif;
      font-size: 1.4rem;
      font-style: italic;
      color: var(--gold-accent);
      margin-bottom: 1.5rem;
    }

    .author {
      font-size: 0.9rem;
      text-transform: uppercase;
      letter-spacing: 3px;
      opacity: 0.8;
    }

    /* Bloques de Texto */
    .section-card {
      background: rgba(255, 255, 255, 0.03);
      backdrop-filter: blur(10px);
      border: 1px solid rgba(212, 175, 55, 0.15);
      border-radius: 12px;
      padding: 2.5rem;
      margin-bottom: 3rem;
      box-shadow: 0 8px 25px rgba(0, 0, 0, 0.3);
    }

    h2 {
      font-family: 'Cormorant Garamond', serif;
      font-size: 2.2rem;
      color: var(--gold-accent);
      margin-bottom: 1.2rem;
      font-weight: 400;
      letter-spacing: 1px;
    }

    p {
      font-size: 1.05rem;
      font-weight: 300;
      margin-bottom: 1.2rem;
      color: #e2d5ed;
    }

    p strong {
      color: #ffffff;
      font-weight: 500;
    }

    em {
      font-family: 'Cormorant Garamond', serif;
      font-size: 1.2rem;
      color: var(--gold-accent);
      font-style: italic;
    }

    /* Adaptación para pantallas pequeñas / móviles */
    @media (max-width: 900px) {
      .landing-layout {
        flex-direction: column;
      }
      .sidebar-botanical {
        width: 100%;
        height: 300px;
        position: relative;
      }
      .main-content {
        width: 100%;
        padding: 2rem 1.5rem;
      }
      h1 {
        font-size: 2.2rem;
      }
    }
  </style>
</head>
<body>

  <div class="landing-layout">
    
    <!-- Lateral Izquierdo: Tablero Rústico Botánico -->
    <div class="sidebar-botanical"></div>

    <!-- Contenido Principal: Púrpura con la portada y el texto -->
    <main class="main-content">
      
      <!-- Cabecera con la Portada -->
      <section class="hero-section">
        <img src="1000003282.png" alt="No More Bottles Cover" class="book-cover">
        <h1>No More Bottles!</h1>
        <p class="subtitle">Natural Perfume Making Guide</p>
        <p class="author">By Blue Kolmer</p>
      </section>

      <!-- Bloque 1 -->
      <section class="section-card">
        <h2>1. The Wake-Up Call</h2>
        <p><strong>Your skin is your body's largest organ—it drinks in whatever you put on it.</strong></p>
        <p>Commercial perfumes rely on synthetic fixatives, phthalates, and hidden chemical cocktails masked under the generic term <em>"parfum"</em>. These endocrine disruptors interfere with your hormones and health every single day.</p>
        <p>It’s time to break free from mass-produced corporate bottles and choose 100% clean, botanical ingredients.</p>
      </section>

      <!-- Bloque 2 -->
      <section class="section-card">
        <h2>2. The Botanical Heart</h2>
        <p><strong>Master the alchemy of Ylang Ylang, Rose, and natural blending.</strong></p>
        <p>In <em>No More Bottles!</em>, you’ll unlock the secrets of the olfactory pyramid. Learn how delicate top notes like Bergamot dance with rich, sensual heart notes like Ylang Ylang and Rose of Alexandria.</p>
        <p>Discover easy, step-by-step home techniques to formulate unisex, emotionally grounding fragrances without expensive laboratory equipment.</p>
      </section>

      <!-- Bloque 3 -->
      <section class="section-card">
        <h2>3. Longevity &amp; The Artisan Opportunity</h2>
        <p><strong>Pure essential oils last longer and smell richer than synthetic cheap fixatives.</strong></p>
        <p>Grounded by deep Vetiver roots and warm Benzoin resins, natural perfumes evolve beautifully on your skin throughout the day.</p>
        <p>Beyond personal wellness, this is the ultimate homestead skill. Micro-batch, transparent, local artisan perfumery is the booming trend for the coming years. Turn your passion into a trusted local craft or boutique brand.</p>
      </section>

    </main>

  </div>

</body>
</html>
