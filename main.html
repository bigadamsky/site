<!DOCTYPE html>
<html lang="pl">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Portfolio — Wizytówka</title>
<link href="https://fonts.googleapis.com/css2?family=Cinzel:wght@400;600;900&family=Cormorant+Garamond:ital,wght@0,300;0,400;0,600;1,300;1,400&display=swap" rel="stylesheet">
<style>
  :root {
    --amber: #09090a;
    --amber-glow: #ffffff;
    --amber-dim: #000000;
    --dark-bg: #ffffff;
    --dark-card: rgba(14, 17, 15, 0.72);
    --glass: rgba(255,255,255,0.045);
    --glass-border: rgba(0, 0, 0, 0.18);
    --text-primary: #f0ead8;
    --text-dim: #000000;
    --fog: rgba(0, 0, 0, 0.06);
  }

  * { margin: 0; padding: 0; box-sizing: border-box; }

  html { scroll-behavior: smooth; }

  body {
    background: var(--dark-bg);
    color: var(--text-primary);
    font-family: 'Cormorant Garamond', serif;
    min-height: 100vh;
    overflow-x: hidden;
    cursor: default;
  }

  /* ── CANVAS BACKGROUND ── */
  #bg-canvas {
    position: fixed;
    inset: 0;
    z-index: 0;
    pointer-events: none;
  }

  /* ── GRAIN OVERLAY ── */
  body::before {
    content: '';
    position: fixed;
    inset: 0;
    z-index: 1;
    pointer-events: none;
    background-image: url("data:image/svg+xml,%3Csvg viewBox='0 0 512 512' xmlns='http://www.w3.org/2000/svg'%3E%3Cfilter id='n'%3E%3CfeTurbulence type='fractalNoise' baseFrequency='0.75' numOctaves='4' stitchTiles='stitch'/%3E%3C/filter%3E%3Crect width='100%25' height='100%25' filter='url(%23n)' opacity='0.07'/%3E%3C/svg%3E");
    background-size: 200px 200px;
    opacity: 0.55;
  }

  /* ── LAYOUT ── */
  .page {
    position: relative;
    z-index: 2;
    max-width: 780px;
    margin: 0 auto;
    padding: 0 24px 120px;
  }

  /* ── HEADER / HERO ── */
  .hero {
    min-height: 100vh;
    display: flex;
    flex-direction: column;
    justify-content: flex-end;
    padding-bottom: 64px;
    position: relative;
  }

  .hero-top {
    position: absolute;
    top: 28px;
    left: 0; right: 0;
    display: flex;
    justify-content: space-between;
    align-items: center;
    font-size: 11px;
    letter-spacing: 0.22em;
    text-transform: uppercase;
    color: var(--text-dim);
    opacity: 0;
    animation: fadeUp 1.2s 0.3s forwards;
  }

  .status-dot {
    width: 7px; height: 7px;
    background: var(--amber);
    border-radius: 50%;
    display: inline-block;
    margin-right: 8px;
    box-shadow: 0 0 10px var(--amber);
    animation: pulse 2.5s infinite;
  }

  @keyframes pulse {
    0%,100% { opacity: 1; box-shadow: 0 0 10px var(--amber); }
    50% { opacity: 0.5; box-shadow: 0 0 4px var(--amber-dim); }
  }

  .hero-name {
    font-family: 'Cinzel', serif;
    font-size: clamp(3.2rem, 9vw, 7rem);
    font-weight: 900;
    line-height: 0.92;
    letter-spacing: -0.01em;
    color: var(--text-primary);
    text-shadow: 0 0 80px rgba(0,0,0,0.18);
    opacity: 0;
    animation: fadeUp 1.4s 0.5s forwards;
  }

  .hero-name span {
    color: var(--amber);
    display: block;
  }

  .hero-tagline {
    margin-top: 20px;
    font-size: 1.2rem;
    font-weight: 300;
    font-style: italic;
    color: var(--text-dim);
    letter-spacing: 0.04em;
    max-width: 420px;
    line-height: 1.65;
    opacity: 0;
    animation: fadeUp 1.4s 0.8s forwards;
  }

  .hero-photo {
    margin-top: 32px;
    width: min(260px, 100%);
    aspect-ratio: 1 / 1;
    border-radius: 26px;
    overflow: hidden;
    border: 1px solid var(--glass-border);
    background: rgba(255,255,255,0.03);
    box-shadow: 0 0 38px rgba(0, 0, 0, 0.18);
    opacity: 0;
    animation: fadeUp 1.4s 0.9s forwards;
  }

  .hero-photo img {
    width: 100%;
    height: 100%;
    object-fit: cover;
    display: block;
  }

  .hero-cta {
    margin-top: 36px;
    display: flex;
    gap: 16px;
    flex-wrap: wrap;
    opacity: 0;
    animation: fadeUp 1.4s 1.1s forwards;
  }

  .btn {
    font-family: 'Cinzel', serif;
    font-size: 11px;
    letter-spacing: 0.2em;
    text-transform: uppercase;
    padding: 14px 32px;
    border: 1px solid var(--glass-border);
    background: var(--glass);
    color: var(--text-primary);
    cursor: pointer;
    text-decoration: none;
    display: inline-block;
    transition: all 0.35s ease;
    backdrop-filter: blur(12px);
    position: relative;
    overflow: hidden;
  }

  .btn::before {
    content: '';
    position: absolute;
    inset: 0;
    background: linear-gradient(135deg, transparent, rgba(200,137,42,0.08));
    opacity: 0;
    transition: opacity 0.35s;
  }

  .btn:hover {
    border-color: var(--amber);
    color: var(--amber);
    box-shadow: 0 0 28px rgba(255, 255, 255, 0.2), inset 0 0 20px rgba(200,137,42,0.04);
  }
  .btn:hover::before { opacity: 1; }

  .btn-primary {
    background: rgba(0, 0, 0, 0.12);
    border-color: rgba(0, 0, 0, 0.5);
    color: var(--amber-glow);
  }

  /* ── DIVIDER ── */
  .divider {
    display: flex;
    align-items: center;
    gap: 20px;
    margin: 72px 0 52px;
    opacity: 0;
    animation: fadeIn 1.2s 1.6s forwards;
  }

  .divider-line {
    flex: 1;
    height: 1px;
    background: linear-gradient(90deg, transparent, var(--glass-border), transparent);
  }

  .divider-symbol {
    color: var(--amber-dim);
    font-size: 18px;
    letter-spacing: 6px;
  }

  /* ── SECTION TITLES ── */
  .section-label {
    font-size: 10px;
    font-family: 'Cinzel', serif;
    letter-spacing: 0.3em;
    text-transform: uppercase;
    color: var(--amber-dim);
    margin-bottom: 8px;
  }

  .section-title {
    font-family: 'Cinzel', serif;
    font-size: clamp(1.6rem, 4vw, 2.4rem);
    font-weight: 600;
    color: var(--text-primary);
    margin-bottom: 32px;
  }

  /* ── GLASS CARD ── */
  .card {
    background: var(--dark-card);
    border: 1px solid var(--glass-border);
    backdrop-filter: blur(20px);
    -webkit-backdrop-filter: blur(20px);
    padding: 36px 40px;
    margin-bottom: 20px;
    position: relative;
    overflow: hidden;
    transition: border-color 0.4s, box-shadow 0.4s;
    opacity: 0;
    transform: translateY(24px);
  }

  .card::before {
    content: '';
    position: absolute;
    top: 0; left: 0; right: 0;
    height: 1px;
    background: linear-gradient(90deg, transparent, rgba(255, 255, 255, 0.4), transparent);
  }

  .card:hover {
    border-color: rgba(255, 255, 255, 0.35);
    box-shadow: 0 8px 48px rgba(0,0,0,0.4), 0 0 40px rgba(200,137,42,0.06);
  }

  .card.visible {
    animation: cardReveal 0.8s forwards;
  }

  @keyframes cardReveal {
    to { opacity: 1; transform: translateY(0); }
  }

  /* ── ABOUT ── */
  .about-text {
    font-size: 1.15rem;
    line-height: 1.85;
    color: var(--text-dim);
    font-weight: 300;
  }

  .about-text strong {
    color: var(--text-primary);
    font-weight: 600;
  }

  .about-text em {
    color: var(--amber);
    font-style: italic;
  }

  /* ── SKILLS ── */
  .skills-grid {
    display: grid;
    grid-template-columns: repeat(auto-fill, minmax(180px, 1fr));
    gap: 16px;
    margin-top: 12px;
  }

  .skill-item {
    padding: 20px 22px;
    border: 1px solid var(--glass-border);
    background: rgba(255,255,255,0.02);
    transition: all 0.35s;
    position: relative;
  }

  .skill-item:hover {
    border-color: rgba(0,0,0,0.18);
    background: rgba(255,255,255,0.05);
  }

  .skill-icon {
    font-size: 22px;
    margin-bottom: 12px;
    display: block;
    filter: grayscale(1) brightness(0.8);
  }

  .skill-name {
    font-family: 'Cinzel', serif;
    font-size: 11px;
    letter-spacing: 0.15em;
    text-transform: uppercase;
    color: var(--text-primary);
    margin-bottom: 6px;
  }

  .skill-desc {
    font-size: 0.82rem;
    color: var(--text-dim);
    line-height: 1.5;
  }

  .skill-bar {
    margin-top: 14px;
    height: 2px;
    background: rgba(255,255,255,0.06);
    position: relative;
    overflow: hidden;
  }

  .skill-fill {
    position: absolute;
    left: 0; top: 0; bottom: 0;
    background: linear-gradient(90deg, var(--amber-dim), var(--amber));
    width: 0;
    transition: width 1.4s cubic-bezier(0.16, 1, 0.3, 1);
  }

  /* ── PROJECTS ── */
  .project-card {
    display: grid;
    grid-template-columns: 1fr auto;
    gap: 24px;
    align-items: start;
  }

  .project-name {
    font-family: 'Cinzel', serif;
    font-size: 1.1rem;
    font-weight: 600;
    color: var(--text-primary);
    margin-bottom: 10px;
  }

  .project-desc {
    font-size: 0.95rem;
    line-height: 1.7;
    color: var(--text-dim);
    font-weight: 300;
  }

  .project-tags {
    display: flex;
    flex-wrap: wrap;
    gap: 8px;
    margin-top: 14px;
  }

  .tag {
    font-size: 10px;
    font-family: 'Cinzel', serif;
    letter-spacing: 0.12em;
    text-transform: uppercase;
    padding: 4px 12px;
    border: 1px solid rgba(255, 255, 255, 0.2);
    color: var(--amber-dim);
  }

  .project-year {
    font-family: 'Cinzel', serif;
    font-size: 2rem;
    font-weight: 900;
    color: rgba(248, 247, 246, 0.15);
    line-height: 1;
    white-space: nowrap;
    letter-spacing: -0.02em;
  }

  /* ── CONTACT ── */
  .contact-links {
    display: flex;
    flex-direction: column;
    gap: 0;
  }

  .contact-link {
    display: flex;
    align-items: center;
    justify-content: space-between;
    padding: 20px 0;
    border-bottom: 1px solid var(--glass-border);
    text-decoration: none;
    color: var(--text-primary);
    transition: all 0.3s;
    group: true;
  }

  .contact-link:last-child { border-bottom: none; }

  .contact-link:hover {
    color: var(--amber);
    padding-left: 8px;
  }

  .contact-link-label {
    font-family: 'Cinzel', serif;
    font-size: 0.85rem;
    letter-spacing: 0.15em;
    text-transform: uppercase;
  }

  .contact-link-value {
    font-size: 0.9rem;
    color: var(--text-dim);
    font-style: italic;
    transition: color 0.3s;
  }

  .contact-link:hover .contact-link-value {
    color: var(--amber-dim);
  }

  .contact-arrow {
    color: var(--amber-dim);
    font-size: 18px;
    transition: transform 0.3s;
  }

  .contact-link:hover .contact-arrow {
    transform: translateX(6px);
  }

  /* ── FOOTER ── */
  .footer {
    margin-top: 80px;
    padding-top: 32px;
    border-top: 1px solid var(--glass-border);
    display: flex;
    justify-content: space-between;
    align-items: center;
    font-size: 11px;
    letter-spacing: 0.15em;
    text-transform: uppercase;
    color: var(--text-dim);
    opacity: 0;
    animation: fadeIn 1.2s 2s forwards;
  }

  /* ── NAV (floating) ── */
  .nav {
    position: fixed;
    bottom: 30px;
    left: 72%;
    transform: translateX(-50%);
    z-index: 100;
    display: flex;
    gap: 2px;
    background: rgba(10, 12, 11, 0.82);
    border: 1px solid var(--glass-border);
    backdrop-filter: blur(24px);
    padding: 6px 8px;
    opacity: 0;
    animation: fadeUp 1s 1.5s forwards;
  }

  .nav-item {
    font-family: 'Cinzel', serif;
    font-size: 10px;
    letter-spacing: 0.18em;
    text-transform: uppercase;
    padding: 10px 18px;
    color: var(--text-dim);
    text-decoration: none;
    transition: all 0.3s;
    cursor: pointer;
    position: relative;
  }

  .nav-item::after {
    content: '';
    position: absolute;
    bottom: 6px;
    left: 50%; right: 50%;
    height: 1px;
    background: var(--amber);
    transition: left 0.3s, right 0.3s;
  }

  .nav-item:hover {
    color: var(--amber);
  }

  .nav-item:hover::after {
    left: 18px; right: 18px;
  }

  /* ── EMBER PARTICLES ── */
  .ember {
    position: fixed;
    width: 3px; height: 3px;
    border-radius: 50%;
    background: #000000;
    box-shadow: 0 0 6px 2px rgba(0, 0, 0, 0.6);
    pointer-events: none;
    z-index: 3;
    animation: emberFloat linear forwards;
    opacity: 0;
  }

  @keyframes emberFloat {
    0%   { opacity: 0; transform: translateY(0) scale(1); }
    15%  { opacity: 1; }
    85%  { opacity: 0.6; }
    100% { opacity: 0; transform: translateY(-120px) scale(0.2) translateX(var(--drift)); }
  }

  /* ── ANIMATIONS ── */
  @keyframes fadeUp {
    from { opacity: 0; transform: translateY(22px); }
    to   { opacity: 1; transform: translateY(0); }
  }

  @keyframes fadeIn {
    from { opacity: 0; }
    to   { opacity: 1; }
  }

  /* ── RESPONSIVE ── */
  @media (max-width: 600px) {
    .project-card { grid-template-columns: 1fr; }
    .project-year { font-size: 1.4rem; }
    .skills-grid { grid-template-columns: 1fr 1fr; }
    .card { padding: 28px 24px; }
    .nav-item { padding: 10px 12px; font-size: 9px; }
  }
</style>
</head>
<body>

<canvas id="bg-canvas"></canvas>

<!-- FLOATING NAV -->
<nav class="nav">
  <a class="nav-item" href="#hero">Start</a>
  <a class="nav-item" href="#about">O mnie</a>
  <a class="nav-item" href="#skills">Umiejętności</a>
  <a class="nav-item" href="#projects">Projekty</a>
  <a class="nav-item" href="#contact">Kontakt</a>
</nav>

<main class="page">

  <!-- HERO -->
  <section class="hero" id="hero">
    <div class="hero-top">
      <span><span class="status-dot"></span>Dostępny do współpracy</span>
      <span>Portfolio 2026</span>
    </div>

    <div class="hero-name">
      Stanisław<span>Adamski</span>
    </div>
    <p class="hero-tagline">
      Tworzę strony internetowe, portfolia i identyfikacje wizualne dla marek, które chcą się wyróżnić.
    </p>
    <div class="hero-photo">
      <img src="zdjecie.jpeg" alt="">
    </div>
    <div class="hero-cta">
      <a class="btn btn-primary" href="#projects">Zobacz projekty</a>
      <a class="btn" href="#contact">Napisz do mnie</a>
    </div>
  </section>

  <!-- ABOUT -->
  <section id="about">
    <div class="divider">
      <div class="divider-line"></div>
      <span class="divider-symbol">✦ ✦ ✦</span>
      <div class="divider-line"></div>
    </div>

    <div class="section-label">Kim jestem</div>
    <div class="section-title">O mnie</div>

    <div class="card">
      <p class="about-text">
        Jestem <strong>projektantem i deweloperem</strong> z pasją do tworzenia rzeczy, które wyróżniają się na tle innych. 
        Przez ostatnie <em>2 lata</em> pomagam markom i startupom budować produkty, 
        które nie tylko działają sprawnie, ale i pozostawiają trwałe wrażenie.<br><br>
        Wierzę, że <strong>dobry design to nie ornament</strong> — to fundament każdego produktu. 
        Łączę intuicję wizualną z technicznym rzemiosłem, by efekt zawsze przekraczał oczekiwania.
      </p>
    </div>
  </section>

  <!-- SKILLS -->
  <section id="skills">
    <div class="divider">
      <div class="divider-line"></div>
      <span class="divider-symbol">✦ ✦ ✦</span>
      <div class="divider-line"></div>
    </div>

    <div class="section-label"></div>
    <div class="section-title">Zainteresowania</div>

    <div class="card">
      <div class="skills-grid">
        <div class="skill-item">
          <span class="skill-icon">💰</span>
          <div class="skill-name">Trading</div>
          <div class="skill-desc">Indeksy, akcje, forex, ETF</div>
          <div class="skill-bar"><div class="skill-fill" data-width="92"></div></div>
        </div>
        <div class="skill-item">
          <span class="skill-icon">🏋️‍♂️</span>
          <div class="skill-name">Siłownia</div>
          <div class="skill-desc">5 lat doświadczenia</div>
          <div class="skill-bar"><div class="skill-fill" data-width="100"></div></div>
        </div>
        <div class="skill-item">
          <span class="skill-icon">👨‍💻</span>
          <div class="skill-name">Programowanie</div>
          <div class="skill-desc">HTML, Python, CSS</div>
          <div class="skill-bar"><div class="skill-fill" data-width="90"></div></div>
        </div>

        </div>
      </div>
    </div>
  </section>

  <!-- PROJECTS -->
  <section id="projects">
    <div class="divider">
      <div class="divider-line"></div>
      <span class="divider-symbol">✦ ✦ ✦</span>
      <div class="divider-line"></div>
    </div>

    <div class="section-label">Realizacje</div>
    <div class="section-title">Moje Projkety</div>

    <div class="card">
      <div class="project-card">
        <div>
          <div class="project-name">Projekt Beast</div>
          <div class="project-desc">Prowadzenie trenigowe moich podopiecznych</div>
          <div class="project-tags">
            <span class="tag">GYM</span>
            <span class="tag">DIET</span>
            <span class="tag">TRANSFORMATION</span>
          </div>
        </div>
        <div class="project-year">1</div>
      </div>
    </div>

    <div class="card">
      <div class="project-card">
        <div>
          <div class="project-name">Projekt Web Development</div>
          <div class="project-desc">Obecny projekt mający na celu polepszenie umiejetności programowania storn internetowych jak i wsparcie klientów</div>
          <div class="project-tags">
            <span class="tag">Branding</span>
            <span class="tag">WWW</span>
            <span class="tag">HTML</span>
          </div>
        </div>
        <div class="project-year">2</div>
      </div>
    </div>

    <div class="card">
      <div class="project-card">
        <div>
          <div class="project-name">Trading</div>
          <div class="project-desc">Kursy tradingowe edukujące w jaki sposób działa rynek finansowy</div>
          <div class="project-tags">
            <span class="tag">Forex</span>
            <span class="tag">Stocks</span>
            <span class="tag">CFD</span>
          </div>
        </div>
        <div class="project-year">3</div>
      </div>
    </div>
  </section>

  <!-- CONTACT -->
  <section id="contact">
    <div class="divider">
      <div class="divider-line"></div>
      <span class="divider-symbol">✦ ✦ ✦</span>
      <div class="divider-line"></div>
    </div>

    <div class="section-label">Kontakt</div>
    <div class="section-title">Porozmawiajmy</div>

    <div class="card">
      <div class="contact-links">
        <a class="contact-link" href="mailto:adamskistas@gmail.com">
          <span class="contact-link-label">Email</span>
          <span class="contact-link-value">adamskistas@gmail.com</span>
          <span class="contact-arrow">→</span>
        </a>

        <a class="contact-link" href="https://discord.gg/K6jVFthQvW" target="_blank">
          <span class="contact-link-label">Discord</span>
          <span class="contact-link-value">xshin00</span>
          <span class="contact-arrow">→</span>
        </a>
      </div>
    </div>
  </section>

  <!-- FOOTER -->
  <footer class="footer">
    <span>© 2026 Stanisław Adamski</span>
    <span>Designed & Coded by Me</span>
  </footer>

</main>

<script>
/* ── CANVAS: misty forest + fire glow ── */
(function(){
  const canvas = document.getElementById('bg-canvas');
  const ctx = canvas.getContext('2d');
  let W, H;

  function resize(){
    W = canvas.width  = window.innerWidth;
    H = canvas.height = window.innerHeight;
  }
  resize();
  window.addEventListener('resize', resize);

  // Fog particles
  const fogs = Array.from({length: 7}, () => ({
    x: Math.random() * 1.4 - 0.2,
    y: 0.2 + Math.random() * 0.7,
    r: 0.25 + Math.random() * 0.3,
    a: 0.03 + Math.random() * 0.04,
    speed: (Math.random() - 0.5) * 0.00008,
  }));

  // Fire embers
  const embers = Array.from({length: 40}, () => newEmber(true));

  function newEmber(init){
    return {
      x: 0.35 + Math.random() * 0.3,
      y: init ? Math.random() : 0.78 + Math.random() * 0.1,
      size: 1 + Math.random() * 2.5,
      vx: (Math.random() - 0.5) * 0.001,
      vy: -(0.0004 + Math.random() * 0.0008),
      life: 1,
      decay: 0.003 + Math.random() * 0.005,
    };
  }

  function draw(){
    ctx.clearRect(0, 0, W, H);

    // Dark radial base
    const bg = ctx.createRadialGradient(W*0.5, H*0.3, 0, W*0.5, H*0.5, W*0.9);
    bg.addColorStop(0,   'rgba(30,22,10,0.7)');
    bg.addColorStop(0.5, 'rgba(10,13,12,0.8)');
    bg.addColorStop(1,   'rgba(5,7,6,0.95)');
    ctx.fillStyle = bg;
    ctx.fillRect(0, 0, W, H);

    // Neutral fire glow (bottom)
    const fire = ctx.createRadialGradient(W*0.5, H*0.85, 0, W*0.5, H*0.85, W*0.45);
    fire.addColorStop(0,   'rgba(140,140,140,0.14)');
    fire.addColorStop(0.4, 'rgba(90,90,90,0.05)');
    fire.addColorStop(1,   'rgba(0,0,0,0)');
    ctx.fillStyle = fire;
    ctx.fillRect(0, 0, W, H);

    // Fog blobs
    fogs.forEach(f => {
      f.x += f.speed;
      if(f.x > 1.3) f.x = -0.3;
      if(f.x < -0.3) f.x = 1.3;
      const g = ctx.createRadialGradient(
        W*f.x, H*f.y, 0,
        W*f.x, H*f.y, W*f.r
      );
      g.addColorStop(0,   `rgba(130,130,130,${f.a})`);
      g.addColorStop(0.5, `rgba(80,80,80,${f.a*0.4})`);
      g.addColorStop(1,   'rgba(0,0,0,0)');
      ctx.fillStyle = g;
      ctx.fillRect(0, 0, W, H);
    });

    // Embers
    embers.forEach((e, i) => {
      e.x += e.vx;
      e.y += e.vy;
      e.life -= e.decay;
      if(e.life <= 0) { embers[i] = newEmber(false); return; }

      ctx.save();
      ctx.globalAlpha = e.life * 0.9;
      ctx.beginPath();
      ctx.arc(W*e.x, H*e.y, e.size, 0, Math.PI*2);
      ctx.fillStyle = 'rgba(0, 0, 0, 0.9)';
      ctx.shadowColor = 'rgba(0, 0, 0, 0.8)';
      ctx.shadowBlur = 8;
      ctx.fill();
      ctx.restore();
    });

    requestAnimationFrame(draw);
  }
  draw();
})();

/* ── SCROLL REVEAL ── */
(function(){
  const cards = document.querySelectorAll('.card');
  const observer = new IntersectionObserver((entries) => {
    entries.forEach((entry, i) => {
      if(entry.isIntersecting){
        setTimeout(() => {
          entry.target.classList.add('visible');
          // Animate skill bars
          entry.target.querySelectorAll('.skill-fill').forEach(bar => {
            bar.style.width = bar.dataset.width + '%';
          });
        }, 120 * (Array.from(cards).indexOf(entry.target) % 4));
        observer.unobserve(entry.target);
      }
    });
  }, { threshold: 0.12 });

  cards.forEach(c => observer.observe(c));
})();

/* ── DOM EMBER SPARKS on hover ── */
document.querySelectorAll('.btn, .nav-item').forEach(el => {
  el.addEventListener('mouseenter', function(e){
    for(let i = 0; i < 4; i++){
      const spark = document.createElement('div');
      spark.className = 'ember';
      const rect = el.getBoundingClientRect();
      spark.style.left = (rect.left + Math.random() * rect.width) + 'px';
      spark.style.top  = (rect.bottom - 4) + 'px';
      spark.style.setProperty('--drift', (Math.random() - 0.5) * 40 + 'px');
      spark.style.animationDuration = (0.8 + Math.random() * 0.8) + 's';
      spark.style.animationDelay    = (Math.random() * 0.25) + 's';
      document.body.appendChild(spark);
      spark.addEventListener('animationend', () => spark.remove());
    }
  });
});
</script>
</body>
</html>
