<!DOCTYPE html>
<html lang="pt-BR">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Para Ling Ling — Uma Carta Digital</title>
<link rel="preconnect" href="https://fonts.googleapis.com">
<link href="https://fonts.googleapis.com/css2?family=Cormorant+Garamond:ital,wght@0,300;0,400;0,600;1,300;1,400&family=Lato:wght@300;400&family=Dancing+Script:wght@400;600&display=swap" rel="stylesheet">
<style>
  *, *::before, *::after { box-sizing: border-box; margin: 0; padding: 0; }

  :root {
    --black: #07000f;
    --deep: #0e0018;
    --purple: #7b2fff;
    --lilac: #c084fc;
    --pale: #e9d5ff;
    --white: #f8f0ff;
    --gold: #fde8c8;
  }

  html { scroll-behavior: smooth; }

  body {
    background: var(--black);
    color: var(--white);
    font-family: 'Lato', sans-serif;
    font-weight: 300;
    overflow-x: hidden;
  }

  /* ─── CANVAS / SKY ─── */
  #sky-canvas {
    position: fixed;
    top: 0; left: 0;
    width: 100%; height: 100%;
    z-index: 0;
    pointer-events: none;
  }

  /* ─── PETALS ─── */
  .petal {
    position: fixed;
    width: 10px; height: 10px;
    border-radius: 50% 0 50% 0;
    opacity: 0;
    pointer-events: none;
    z-index: 1;
    animation: fall linear infinite;
  }
  @keyframes fall {
    0%   { transform: translateY(-20px) rotate(0deg); opacity: 0; }
    10%  { opacity: .6; }
    90%  { opacity: .3; }
    100% { transform: translateY(110vh) rotate(720deg); opacity: 0; }
  }

  /* ─── GLOBAL SECTIONS ─── */
  section { position: relative; z-index: 2; }

  .container { max-width: 900px; margin: 0 auto; padding: 0 24px; }

  /* ─── HERO ─── */
  #hero {
    min-height: 100vh;
    display: flex; flex-direction: column;
    align-items: center; justify-content: center;
    text-align: center;
    padding: 40px 24px;
    position: relative;
  }

  .moon {
    width: min(260px, 65vw);
    height: min(260px, 65vw);
    border-radius: 50%;
    background: radial-gradient(circle at 35% 35%, #fff9f0, #fde8c8 40%, #e8c89a 70%, #c4955a);
    box-shadow:
      0 0 60px 20px rgba(253,232,200,.25),
      0 0 120px 50px rgba(253,232,200,.12),
      0 0 220px 90px rgba(200,160,100,.08);
    margin-bottom: 48px;
    position: relative;
    animation: moonFloat 6s ease-in-out infinite;
    flex-shrink: 0;
  }
  .moon::after {
    content: '';
    position: absolute; inset: -14px;
    border-radius: 50%;
    border: 1px solid rgba(253,232,200,.18);
    animation: haloBreath 4s ease-in-out infinite;
  }
  @keyframes moonFloat {
    0%,100% { transform: translateY(0); }
    50%      { transform: translateY(-14px); }
  }
  @keyframes haloBreath {
    0%,100% { transform: scale(1); opacity: .18; }
    50%      { transform: scale(1.06); opacity: .35; }
  }

  .hero-eyebrow {
    font-family: 'Dancing Script', cursive;
    font-size: clamp(14px, 3vw, 18px);
    color: var(--lilac);
    letter-spacing: .12em;
    margin-bottom: 16px;
    opacity: .8;
  }

  .hero-title {
    font-family: 'Cormorant Garamond', serif;
    font-size: clamp(28px, 6vw, 58px);
    font-weight: 300;
    line-height: 1.25;
    color: var(--white);
    max-width: 700px;
  }

  .hero-sub {
    font-size: clamp(13px, 2.5vw, 16px);
    color: var(--pale);
    opacity: .7;
    margin-top: 18px;
    max-width: 480px;
    line-height: 1.7;
  }

  .btn-start {
    margin-top: 40px;
    padding: 14px 40px;
    border: 1px solid rgba(192,132,252,.5);
    background: rgba(123,47,255,.12);
    color: var(--pale);
    font-family: 'Lato', sans-serif;
    font-size: 14px;
    letter-spacing: .18em;
    text-transform: uppercase;
    cursor: pointer;
    border-radius: 2px;
    transition: all .4s;
    backdrop-filter: blur(6px);
  }
  .btn-start:hover {
    background: rgba(123,47,255,.35);
    border-color: var(--lilac);
    color: #fff;
    box-shadow: 0 0 24px rgba(123,47,255,.4);
  }

  /* ─── SECTION HEADER ─── */
  .sec-header {
    text-align: center;
    padding: 100px 24px 60px;
  }
  .sec-header h2 {
    font-family: 'Cormorant Garamond', serif;
    font-size: clamp(26px, 5vw, 46px);
    font-weight: 300;
    color: var(--pale);
  }
  .sec-header p {
    margin-top: 16px;
    font-size: 15px;
    color: rgba(233,213,255,.55);
    max-width: 520px;
    margin-left: auto; margin-right: auto;
    line-height: 1.8;
  }
  .sec-line {
    width: 48px; height: 1px;
    background: linear-gradient(90deg, transparent, var(--lilac), transparent);
    margin: 20px auto 0;
  }

  /* ─── ABOUT CARDS ─── */
  #about { padding-bottom: 80px; }

  .cards-grid {
    display: grid;
    grid-template-columns: repeat(auto-fill, minmax(180px, 1fr));
    gap: 16px;
    padding: 0 24px;
    max-width: 900px;
    margin: 0 auto;
  }

  .about-card {
    background: rgba(123,47,255,.07);
    border: 1px solid rgba(192,132,252,.15);
    border-radius: 12px;
    padding: 22px 16px;
    text-align: center;
    backdrop-filter: blur(8px);
    transition: transform .3s, box-shadow .3s, border-color .3s;
  }
  .about-card:hover {
    transform: translateY(-4px);
    border-color: rgba(192,132,252,.45);
    box-shadow: 0 8px 32px rgba(123,47,255,.18);
  }
  .about-card .icon { font-size: 26px; margin-bottom: 10px; }
  .about-card .label {
    font-size: 13px;
    color: var(--pale);
    line-height: 1.5;
    font-weight: 300;
  }

  /* ─── TIMELINE ─── */
  #timeline { padding-bottom: 80px; }
  .timeline-wrap {
    max-width: 640px;
    margin: 0 auto;
    padding: 0 24px;
    position: relative;
  }
  .timeline-wrap::before {
    content: '';
    position: absolute;
    left: 38px;
    top: 0; bottom: 0;
    width: 1px;
    background: linear-gradient(180deg, transparent, rgba(192,132,252,.4) 10%, rgba(192,132,252,.4) 90%, transparent);
  }
  .tl-item {
    display: flex;
    gap: 24px;
    margin-bottom: 40px;
    position: relative;
  }
  .tl-dot {
    width: 14px; height: 14px;
    border-radius: 50%;
    background: var(--purple);
    border: 2px solid var(--lilac);
    flex-shrink: 0;
    margin-top: 5px;
    position: relative;
    z-index: 1;
    box-shadow: 0 0 12px rgba(123,47,255,.6);
  }
  .tl-content {}
  .tl-year {
    font-family: 'Dancing Script', cursive;
    font-size: 13px;
    color: var(--lilac);
    letter-spacing: .1em;
    margin-bottom: 4px;
  }
  .tl-title {
    font-family: 'Cormorant Garamond', serif;
    font-size: 20px;
    font-weight: 400;
    color: var(--pale);
    margin-bottom: 6px;
  }
  .tl-desc {
    font-size: 13px;
    color: rgba(233,213,255,.5);
    line-height: 1.7;
  }

  /* ─── POEMS ─── */
  #poems { padding-bottom: 80px; }
  /* ─── READING FORMAT ─── */
  #poems { padding-bottom: 80px; }
  .reading-wrap {
    max-width: 680px;
    margin: 0 auto;
    padding: 0 24px;
    display: flex;
    flex-direction: column;
    gap: 0;
  }
  .reading-block {
    padding: 50px 0 20px;
  }
  .reading-label {
    font-family: 'Dancing Script', cursive;
    font-size: 13px;
    color: var(--purple);
    letter-spacing: .1em;
    margin-bottom: 10px;
    opacity: .8;
  }
  .reading-title {
    font-family: 'Cormorant Garamond', serif;
    font-size: clamp(22px, 4vw, 34px);
    font-weight: 300;
    color: var(--pale);
    margin-bottom: 28px;
    line-height: 1.2;
  }
  .reading-body {
    font-family: 'Cormorant Garamond', serif;
    font-size: clamp(16px, 2.5vw, 19px);
    font-weight: 300;
    color: rgba(233,213,255,.78);
    line-height: 2.1;
    white-space: pre-wrap;
    font-style: italic;
  }
  .reading-divider {
    text-align: center;
    color: rgba(192,132,252,.35);
    font-size: 13px;
    letter-spacing: .3em;
    padding: 30px 0 10px;
  }

  /* ─── (legacy placeholder) ─── */
  .fp-title {
    font-family: 'Cormorant Garamond', serif;
    font-size: clamp(28px, 5vw, 44px);
    font-weight: 300;
    color: var(--pale);
    margin-bottom: 36px;
    line-height: 1.2;
  }
  .fp-body {
    font-family: 'Cormorant Garamond', serif;
    font-size: clamp(16px, 2.6vw, 20px);
    font-weight: 300;
    color: rgba(233,213,255,.8);
    line-height: 2.1;
    white-space: pre-wrap;
    font-style: italic;
    text-align: left;
  }

  /* ─── DESTINATIONS ─── */
  .destinations-box {
    max-width: 760px;
    margin: 0 auto;
    padding: 36px 32px;
    background: rgba(10,0,22,.6);
    border: 1px solid rgba(192,132,252,.18);
    border-radius: 20px;
    backdrop-filter: blur(12px);
    text-align: center;
  }
  .dest-subtitle {
    font-size: 14px;
    color: rgba(233,213,255,.55);
    margin-bottom: 22px;
    line-height: 1.6;
  }
  .dest-pills {
    display: flex;
    flex-wrap: wrap;
    gap: 12px;
    justify-content: center;
  }
  .dest-pill {
    padding: 10px 22px;
    border: 1px solid rgba(192,132,252,.45);
    border-radius: 50px;
    background: rgba(123,47,255,.12);
    color: var(--pale);
    font-size: 14px;
    font-family: 'Lato', sans-serif;
    font-weight: 300;
    letter-spacing: .04em;
    transition: all .3s;
    cursor: default;
  }
  .dest-pill:hover {
    background: rgba(123,47,255,.28);
    border-color: var(--lilac);
    box-shadow: 0 0 18px rgba(123,47,255,.25);
  }
  .dest-pill sup {
    font-size: 9px;
    color: var(--lilac);
    margin-left: 3px;
    opacity: .8;
  }
  .dest-pill--main {
    background: rgba(123,47,255,.22);
    border-color: rgba(192,132,252,.65);
    padding: 12px 36px;
    font-size: 15px;
  }
  .dest-pill--main:hover {
    background: rgba(123,47,255,.4);
  }

  @media (max-width: 540px) {
    .featured-poem-card { padding: 36px 22px; }
    .destinations-box { padding: 28px 18px; }
  }
  .dreams-text {
    max-width: 580px;
    margin: 0 auto 40px;
    padding: 0 24px;
    text-align: center;
    font-size: 15px;
    color: rgba(233,213,255,.6);
    line-height: 1.9;
  }
  /* ─── DREAMS ─── */
  #dreams { padding-bottom: 80px; }
  .world-map-container { max-width: 760px; margin: 0 auto; padding: 0 24px; }



  /* ─── DIARY / LETTERS ─── */
  #diary { padding-bottom: 80px; }
  .diary-entries {
    max-width: 680px;
    margin: 0 auto;
    padding: 0 24px;
    display: flex;
    flex-direction: column;
    gap: 32px;
  }
  .diary-entry {
    background: rgba(10,0,20,.55);
    border-left: 2px solid rgba(192,132,252,.35);
    border-radius: 0 12px 12px 0;
    padding: 28px 28px 28px 30px;
    backdrop-filter: blur(8px);
    transition: border-left-color .3s;
  }
  .diary-entry:hover { border-left-color: var(--lilac); }
  .diary-date {
    font-family: 'Dancing Script', cursive;
    font-size: 13px;
    color: var(--lilac);
    margin-bottom: 12px;
    opacity: .8;
  }
  .diary-text {
    font-family: 'Cormorant Garamond', serif;
    font-size: clamp(15px,2.5vw,18px);
    font-weight: 300;
    color: rgba(233,213,255,.75);
    line-height: 1.9;
    font-style: italic;
  }

  /* ─── MEMORIES ─── */
  #memories { padding-bottom: 80px; }
  .memories-list {
    max-width: 680px;
    margin: 0 auto;
    padding: 0 24px;
    display: flex;
    flex-direction: column;
    gap: 20px;
  }
  .memory-item {
    display: flex;
    align-items: flex-start;
    gap: 18px;
    padding: 22px 24px;
    background: rgba(123,47,255,.06);
    border: 1px solid rgba(192,132,252,.12);
    border-radius: 12px;
    backdrop-filter: blur(8px);
    transition: all .3s;
  }
  .memory-item:hover {
    background: rgba(123,47,255,.12);
    border-color: rgba(192,132,252,.3);
  }
  .memory-icon { font-size: 24px; flex-shrink: 0; margin-top: 2px; }
  .memory-text {
    font-family: 'Cormorant Garamond', serif;
    font-size: clamp(15px,2.5vw,18px);
    font-weight: 300;
    color: var(--pale);
    line-height: 1.7;
    font-style: italic;
  }

  /* ─── FINAL MESSAGE ─── */
  #final {
    padding: 100px 24px 120px;
    text-align: center;
    position: relative;
  }
  .final-title {
    font-family: 'Cormorant Garamond', serif;
    font-size: clamp(28px, 5vw, 48px);
    font-weight: 300;
    color: var(--pale);
    margin-bottom: 40px;
  }
  .final-letter {
    max-width: 580px;
    margin: 0 auto;
    font-family: 'Cormorant Garamond', serif;
    font-size: clamp(16px, 2.8vw, 20px);
    font-weight: 300;
    color: rgba(233,213,255,.75);
    line-height: 2.1;
    font-style: italic;
    white-space: pre-line;
  }
  .final-signature {
    margin-top: 50px;
    font-family: 'Dancing Script', cursive;
    font-size: clamp(18px,3vw,24px);
    color: var(--lilac);
    opacity: .7;
  }

  /* ─── FOOTER ─── */
  footer {
    position: relative;
    z-index: 2;
    text-align: center;
    padding: 50px 24px 60px;
    border-top: 1px solid rgba(192,132,252,.08);
  }
  .footer-quote {
    font-family: 'Cormorant Garamond', serif;
    font-size: clamp(13px, 2.3vw, 16px);
    font-style: italic;
    color: rgba(233,213,255,.35);
    max-width: 480px;
    margin: 0 auto;
    line-height: 1.8;
  }
  .footer-heart {
    font-size: 18px;
    color: var(--purple);
    margin-top: 20px;
    display: block;
    opacity: .5;
  }

  /* ─── REVEAL ─── */
  .reveal {
    opacity: 0;
    transform: translateY(28px);
    transition: opacity .7s ease, transform .7s ease;
  }
  .reveal.visible {
    opacity: 1;
    transform: translateY(0);
  }

  /* ─── MOBILE ─── */
  @media (max-width: 540px) {
    .cards-grid { grid-template-columns: repeat(2, 1fr); }
    .poems-grid { grid-template-columns: 1fr 1fr; }
    .modal-box { padding: 36px 22px; }
    .music-cards { grid-template-columns: 1fr; }
    .timeline-wrap::before { left: 34px; }
  }
  @media (max-width: 360px) {
    .poems-grid { grid-template-columns: 1fr; }
  }

  /* ─── BUQUÊ DE FLORES REALISTA DA IMAGEM ─── */
  .bouquet-wrapper {
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    margin: 80px auto 40px;
    position: relative;
    z-index: 20;
    text-align: center;
  }

  .luxurious-bouquet {
    position: relative;
    width: 280px;
    height: 280px;
    background: radial-gradient(circle, rgba(147, 51, 234, 0.4) 0%, rgba(15, 7, 27, 0) 70%);
    border-radius: 50%;
    display: flex;
    align-items: center;
    justify-content: center;
    cursor: pointer;
    transition: transform 0.4s cubic-bezier(0.175, 0.885, 0.32, 1.275);
    filter: drop-shadow(0 0 30px rgba(192, 132, 252, 0.5));
    user-select: none;
  }

  /* Criando as flores internas do buquê com gradientes roxos e lilás */
  .luxurious-bouquet::before {
    content: "💐";
    font-size: 140px;
    z-index: 2;
    animation: floatingBouquet 4s ease-in-out infinite alternate;
  }

  /* Brilho mágico de fundo igual ao da foto */
  .luxurious-bouquet::after {
    content: "";
    position: absolute;
    width: 220px;
    height: 220px;
    background: url('data:image/svg+xml;utf8,<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 100 100"><circle cx="50" cy="50" r="40" fill="none" stroke="%23c084fc" stroke-width="1" stroke-dasharray="2,4" opacity="0.6"/></svg>');
    background-size: contain;
    animation: rotateGlow 20s linear infinite;
    z-index: 1;
  }

  .luxurious-bouquet:hover {
    transform: scale(1.15);
    filter: drop-shadow(0 0 50px rgba(168, 85, 247, 0.9)) drop-shadow(0 0 20px rgba(255, 255, 255, 0.4));
  }

  .click-hint {
    font-family: 'Lato', sans-serif;
    font-size: 11px;
    color: var(--lilac);
    text-transform: uppercase;
    letter-spacing: 0.2em;
    margin-top: 20px;
    opacity: 0.7;
    animation: pulseHint 2s infinite;
  }

  /* Partículas da chuva de flores */
  .falling-flower-fx {
    position: fixed;
    z-index: 100000;
    pointer-events: none;
    user-select: none;
    will-change: transform, opacity;
  }

  @keyframes floatingBouquet {
    0% { transform: translateY(0px) rotate(0deg); }
    100% { transform: translateY(-10px) rotate(3deg); }
  }

  @keyframes rotateGlow {
    from { transform: rotate(0deg); }
    to { transform: rotate(360deg); }
  }

  @keyframes pulseHint {
    0%, 100% { opacity: 0.4; transform: scale(0.98); }
    50% { opacity: 0.9; transform: scale(1.02); }
  }

</style>
</head>
<body>

<canvas id="sky-canvas"></canvas>

<!-- HERO -->
<section id="hero">
  <div class="moon"></div>
  <p class="hero-eyebrow">✦ uma carta digital ✦</p>
  <h1 class="hero-title">Para a garota que mudou minha vida sem perceber.</h1>
  <p class="hero-sub">Algumas pessoas passam pela nossa vida. Outras deixam marcas para sempre.</p>
  <button class="btn-start" onclick="document.getElementById('about').scrollIntoView({behavior:'smooth'})">Começar a leitura</button>
</section>

<!-- ABOUT -->
<section id="about">
  <div class="sec-header reveal">
    <h2>Quem é Ling Ling?</h2>
    <div class="sec-line"></div>
    <p>Uma pessoa que carrega o mundo inteiro no olhar.</p>
  </div>
  <div class="cards-grid">
    <div class="about-card reveal"><div class="icon">🎵</div><div class="label">Ama BTS de coração</div></div>
    <div class="about-card reveal"><div class="icon">🎬</div><div class="label">Apaixonada por doramas</div></div>
    <div class="about-card reveal"><div class="icon">📚</div><div class="label">Devora livros</div></div>
    <div class="about-card reveal"><div class="icon">🐶</div><div class="label">Ama cachorros</div></div>
    <div class="about-card reveal"><div class="icon">💜</div><div class="label">Cor favorita: Roxo</div></div>
    <div class="about-card reveal"><div class="icon">✈️</div><div class="label">Sonha viajar pela Ásia</div></div>
    <div class="about-card reveal"><div class="icon">🌍</div><div class="label">Sonha conhecer o mundo</div></div>
    <div class="about-card reveal"><div class="icon">🍜</div><div class="label">Está sempre com fome</div></div>
    <div class="about-card reveal"><div class="icon">🌸</div><div class="label">Tem um jeito espontâneo</div></div>
    <div class="about-card reveal"><div class="icon">🌙</div><div class="label">Vive no próprio mundo</div></div>
    <div class="about-card reveal"><div class="icon">🦋</div><div class="label">Ama sua liberdade</div></div>
    <div class="about-card reveal"><div class="icon">⭐</div><div class="label">Nunca desiste facilmente</div></div>
  </div>
</section>

<!-- TIMELINE -->
<section id="timeline">
  <div class="sec-header reveal">
    <h2>Nossa História</h2>
    <div class="sec-line"></div>
  </div>
  <div class="timeline-wrap">
    <div class="tl-item reveal">
      <div class="tl-dot"></div>
      <div class="tl-content">
        <div class="tl-year">2024</div>
        <div class="tl-title">Quando nos conhecemos</div>
        <div class="tl-desc">O início de algo que eu não sabia ainda o quanto mudaria tudo.</div>
      </div>
    </div>
    <div class="tl-item reveal">
      <div class="tl-dot"></div>
      <div class="tl-content">
        <div class="tl-year">2024</div>
        <div class="tl-title">As conversas na escola</div>
        <div class="tl-desc">Horas que passavam rápido demais quando você estava por perto.</div>
      </div>
    </div>
    <div class="tl-item reveal">
      <div class="tl-dot"></div>
      <div class="tl-content">
        <div class="tl-year">2024</div>
        <div class="tl-title">As conversas sobre BTS</div>
        <div class="tl-desc">Você falava com os olhos brilhando. Eu aprendi a gostar só por causa disso.</div>
      </div>
    </div>
    <div class="tl-item reveal">
      <div class="tl-dot"></div>
      <div class="tl-content">
        <div class="tl-year">2024</div>
        <div class="tl-title">As conversas sobre doramas</div>
        <div class="tl-desc">Você me contava os enredos como se fossem histórias reais. Para mim, eram.</div>
      </div>
    </div>
    <div class="tl-item reveal">
      <div class="tl-dot"></div>
      <div class="tl-content">
        <div class="tl-year">2024</div>
        <div class="tl-title">Quando você colocou a cabeça no meu ombro</div>
        <div class="tl-desc">Um segundo que guardei para sempre. Simples assim.</div>
      </div>
    </div>
    <div class="tl-item reveal">
      <div class="tl-dot"></div>
      <div class="tl-content">
        <div class="tl-year">2024</div>
        <div class="tl-title">Os momentos segurando sua mão</div>
        <div class="tl-desc">Aprendi que às vezes não precisa de palavras.</div>
      </div>
    </div>
    <div class="tl-item reveal">
      <div class="tl-dot"></div>
      <div class="tl-content">
        <div class="tl-year">∞</div>
        <div class="tl-title">Os momentos simples que se tornaram lembranças eternas</div>
        <div class="tl-desc">Cada conversa boba, cada olhar, cada riso — tudo guardado aqui.</div>
      </div>
    </div>
  </div>
</section>

<!-- POEMS READING -->
<section id="poems">
  <div class="sec-header reveal">
    <h2>Para Você</h2>
    <div class="sec-line"></div>
    <p>Palavras que não consegui dizer. Então escrevi.</p>
  </div>
  <div class="reading-wrap">

    <div class="reading-block reveal">
      <div class="reading-label">✦ Parte 1</div>
      <h3 class="reading-title">A Lua Que Eu Encontrei</h3>
      <div class="reading-body">Você sempre foi como a lua em uma noite silenciosa,
daquelas que iluminam o céu sem pedir atenção,
mas que acabam se tornando a única coisa que alguém consegue observar.

Seu cabelo escuro dançando com o vento,
seu jeito distante,
seus pensamentos perdidos em mundos que só você conhece.
Às vezes eu olhava para você e pensava
que existiam pessoas que nasceram para ser entendidas,
e outras que nasceram para ser admiradas.



Desde os tempos da escola,
quando tudo ainda parecia simples,
meus olhos procuravam você antes de qualquer outra pessoa.
Não importava quem estivesse ao redor,
era sua presença que fazia diferença.

Você é como uma flor cheia de espinhos.
Uma flor rara,
dessas que poucas pessoas têm coragem de segurar.
Mas eu nunca tive medo dos seus espinhos,
porque aprendi que eles não existem para ferir,
existem para proteger algo precioso.

Você tem seus sonhos,
suas histórias,
seus doramas,
seus livros,
suas músicas,
e esse jeito único de enxergar o mundo.

Às vezes parece uma criança sonhando acordada,
imaginando o destino sem se preocupar com a estrada.
E talvez seja exatamente isso que faz você ser tão especial.

Porque enquanto muitas pessoas aprendem a viver,
você nunca deixou de sonhar.</div>
    </div>

    <div class="reading-divider reveal">✦ &nbsp;&nbsp; ✦ &nbsp;&nbsp; ✦</div>

    <div class="reading-block reveal">
      <div class="reading-label">✦ Parte 2</div>
      <h3 class="reading-title">A Flor Que Eu Nunca Deixei de Amar</h3>
      <div class="reading-body">Eu sei que você ama a liberdade.

Sei que seu coração não gosta de correntes,
que você prefere o céu aberto aos caminhos marcados.
E talvez seja por isso que eu nunca tentei prender você.

Amar alguém também é entender
que algumas pessoas nasceram para voar.

Talvez você nunca sinta por mim
o que eu sinto por você.
Talvez eu seja apenas uma pequena página
em um livro enorme da sua vida.

Mas você se tornou um capítulo inteiro da minha.

Porque mesmo nos dias em que você parecia distante,
mesmo nos momentos em que o mundo parecia pesado,
eu continuava admirando você.

Não pela pessoa perfeita que alguns imaginam.
Mas pela pessoa real que você é.

Com seus medos,
suas mudanças de humor,
suas dúvidas,
seus sonhos impossíveis
e sua força para continuar seguindo em frente.

Se um dia alguém me perguntar
o que eu vi em você,
eu não vou falar da sua aparência,
nem do seu sorriso,
nem de nada que os olhos conseguem enxergar.

Vou dizer que vi uma lua iluminando a noite,
uma flor protegida por espinhos,
e uma garota que, sem perceber,
ocupou um espaço no meu coração que ninguém mais conseguiu ocupar.

E mesmo que o destino escolha caminhos diferentes,
mesmo que a vida nos leve para lugares distantes,
sempre vou guardar a lembrança da garota
que me ensinou que amar alguém
nem sempre significa possuir.

Às vezes significa apenas desejar,
todos os dias,
que ela seja feliz.</div>
    </div>

    <div class="reading-divider reveal">✦ &nbsp;&nbsp; ✦ &nbsp;&nbsp; ✦</div>

    <div class="reading-block reveal">
      <div class="reading-label">✦</div>
      <h3 class="reading-title">Lua e Flor</h3>
      <div class="reading-body">Você sempre me lembrou a lua.

Bonita, distante e impossível de ignorar.

Enquanto outras pessoas entravam e saíam da minha vida, você ficou.

Talvez sem perceber, ocupou um lugar que ninguém mais conseguiu ocupar.

Eu ainda lembro do dia em que você colocou a cabeça no meu ombro.

Minha mente, que nunca para de pensar, finalmente encontrou silêncio.

Por alguns instantes, tudo parecia estar exatamente onde deveria estar.

Você é como uma flor cheia de espinhos.

Nem sempre é fácil se aproximar, mas isso nunca me impediu.

Porque aprendi que algumas flores são especiais justamente por serem difíceis de alcançar.

Talvez você nunca entenda o tamanho do sentimento que carrego.

Talvez nossa história nunca seja aquilo que eu imaginei.

Mas existe uma coisa que sempre será verdade:

entre todas as pessoas que conheci, você foi a única que transformou simples momentos em lembranças que vou carregar para sempre.</div>
    </div>

    <div class="reading-divider reveal">✦ &nbsp;&nbsp; ✦ &nbsp;&nbsp; ✦</div>

    <div class="reading-block reveal">
      <div class="reading-label">✦</div>
      <h3 class="reading-title">O Seu Sorriso</h3>
      <div class="reading-body">Eu costumava pensar que faria você sorrir para que se apaixonasse por mim.

Mas aconteceu exatamente o contrário.

Cada vez que você sorria, era eu quem me apaixonava mais.

Talvez você nunca tenha percebido o efeito que causava.

Talvez para você fosse apenas mais um sorriso comum.

Mas para mim era o suficiente para transformar um dia ruim em um dia bom.

Você sempre viveu no seu próprio mundo.

Entre livros, doramas, músicas e sonhos de conhecer lugares distantes.

E eu gostava de ouvir cada detalhe.

Porque quando você falava dos seus sonhos, seus olhos brilhavam de um jeito diferente.

Eu não sei onde a vida vai levar você.

Talvez para bem longe daqui.

Mas espero que, onde quer que esteja, continue sorrindo daquele mesmo jeito.

Porque foi esse sorriso que fez uma pessoa comum como eu acreditar, por um momento, que o mundo podia ser um lugar mais bonito.</div>
    </div>

    <div class="reading-divider reveal">✦ &nbsp;&nbsp; ✦ &nbsp;&nbsp; ✦</div>

    <div class="reading-block reveal">
      <div class="reading-label">✦</div>
      <h3 class="reading-title">O Tempo Parou</h3>
      <div class="reading-body">Existem momentos que duram apenas alguns segundos.

Mas, de alguma forma, permanecem para sempre.

Para mim, foi quando segurei sua mão.

Foi quando você encostou a cabeça no meu ombro.

Momentos simples para qualquer pessoa.

Mas não para mim.

Porque quando estava perto de você, o tempo parecia mais lento.

As preocupações desapareciam.

Os problemas perdiam a importância.

E tudo que eu queria era continuar ali.

Talvez você nunca entenda o quanto esses pequenos momentos significaram.

Mas são eles que guardo com mais carinho.

Porque, no fim, não foram os grandes acontecimentos que fizeram eu me apaixonar.

Foram os detalhes.

E você sempre foi o detalhe mais bonito da minha vida.</div>
    </div>

    <div class="reading-divider reveal">✦ &nbsp;&nbsp; ✦ &nbsp;&nbsp; ✦</div>

    <div class="reading-block reveal">
      <div class="reading-label">✦</div>
      <h3 class="reading-title">Primeiro Amor</h3>
      <div class="reading-body">Dizem que o primeiro amor nunca é esquecido.

Talvez porque ele chegue sem avisar.

Talvez porque seja a primeira vez que alguém ocupa nossos pensamentos sem pedir permissão.

Eu não planejei gostar de você.

Na verdade, tentei não gostar.

Tentei seguir outros caminhos, conhecer outras pessoas e deixar esse sentimento para trás.

Mas toda vez que eu pensava ter conseguido, alguma lembrança sua aparecia.

Seu sorriso.

Seu jeito espontâneo.

Suas histórias contadas do nada.

E eu percebia que ainda era você.

Não sei o que o futuro guarda para nós.

Mas sei que, entre todas as pessoas que passaram pela minha vida, você foi a primeira que transformou carinho em amor.

E por isso, independentemente do tempo que passar, sempre terá um lugar especial dentro de mim.</div>
    </div>

    <div class="reading-divider reveal">✦ &nbsp;&nbsp; ✦ &nbsp;&nbsp; ✦</div>

    <div class="reading-block reveal">
      <div class="reading-label">✦</div>
      <h3 class="reading-title">Seu Próprio Mundo</h3>
      <div class="reading-body">Você sempre viveu no seu próprio mundo.

Um mundo cheio de sonhos, livros, músicas e lugares que ainda deseja conhecer.

Às vezes eu sentia que estava olhando para uma estrela.

Perto o suficiente para admirar.

Longe demais para alcançar.

Mas mesmo assim, eu nunca deixei de olhar.

Porque algumas pessoas são tão especiais que basta existir para iluminar a vida de alguém.</div>
    </div>

    <div class="reading-divider reveal">✦ &nbsp;&nbsp; ✦ &nbsp;&nbsp; ✦</div>

    <div class="reading-block reveal">
      <div class="reading-label">✦</div>
      <h3 class="reading-title">Flor de Espinhos</h3>
      <div class="reading-body">Você é a flor mais bonita que já encontrei.

Mas também a que possui mais espinhos.

Muitas pessoas teriam medo de se aproximar.

Eu nunca tive.

Porque aprendi que os espinhos fazem parte de você.

E se eu gosto da flor, preciso aceitar tudo o que vem com ela.

Até porque as flores mais raras nunca crescem em jardins fáceis.</div>
    </div>

    <div class="reading-divider reveal">✦ &nbsp;&nbsp; ✦ &nbsp;&nbsp; ✦</div>

    <div class="reading-block reveal">
      <div class="reading-label">✦</div>
      <h3 class="reading-title">Entre Sonhos</h3>
      <div class="reading-body">Você sonha em conhecer o mundo.

Em viajar, descobrir lugares novos e viver histórias que ainda nem aconteceram.

E sem perceber, fez nascer esse sonho dentro de mim também.

Talvez um dia nossos caminhos sejam diferentes.

Mas sempre vou lembrar que foi você quem me ensinou a olhar além do horizonte.

E acreditar que existe muito mais esperando por nós.</div>
    </div>

    <div class="reading-divider reveal">✦ &nbsp;&nbsp; ✦ &nbsp;&nbsp; ✦</div>

    <div class="reading-block reveal">
      <div class="reading-label">✦</div>
      <h3 class="reading-title">Ainda É Você</h3>
      <div class="reading-body">O mais engraçado é que eu já tentei esquecer você.

Mais de uma vez.

Achei que o tempo faria isso por mim.

Mas o tempo passou.

As estações mudaram.

As pessoas mudaram.

E no final, ainda era você.

Talvez porque algumas pessoas não passam pela nossa vida.

Elas ficam.</div>
    </div>

    <div class="reading-divider reveal">✦ &nbsp;&nbsp; ✦ &nbsp;&nbsp; ✦</div>

    <div class="reading-block reveal">
      <div class="reading-label">✦</div>
      <h3 class="reading-title">Se Você Soubesse</h3>
      <div class="reading-body">Se você soubesse quantas vezes pensei em dizer tudo o que sinto.

Se soubesse quantas palavras ficaram presas na minha garganta.

Talvez entendesse algumas coisas.

Ou talvez não.

Mas existe uma verdade que nunca mudou:

Entre todas as histórias que vivi, você continua sendo a minha favorita.</div>
    </div>

    <div class="reading-divider reveal">✦ &nbsp;&nbsp; ✦ &nbsp;&nbsp; ✦</div>

    <div class="reading-block reveal">
      <div class="reading-label">✦</div>
      <h3 class="reading-title">Seus Olhos</h3>
      <div class="reading-body">Existem pessoas que chamam atenção pela beleza.

Você chama atenção pelo jeito que olha.

Porque quando seus olhos encontram os meus, por alguns segundos, parece que o mundo fica mais silencioso.

E mesmo depois de tanto tempo, ainda sinto a mesma coisa.

Como se fosse a primeira vez.</div>
    </div>

    <div class="reading-divider reveal">✦ &nbsp;&nbsp; ✦ &nbsp;&nbsp; ✦</div>

    <div class="reading-block reveal">
      <div class="reading-label">✦</div>
      <h3 class="reading-title">Saudade</h3>
      <div class="reading-body">A saudade mais estranha não é a de quem foi embora.

É a de quem continua aqui.

Porque às vezes você está distante, perdida no seu próprio mundo.

E mesmo sabendo que está bem, sinto falta de conversar com você.

Sinto falta da sua presença.

Sinto falta de você.</div>
    </div>

    <div class="reading-divider reveal">✦ &nbsp;&nbsp; ✦ &nbsp;&nbsp; ✦</div>

    <div class="reading-block reveal">
      <div class="reading-label">✦</div>
      <h3 class="reading-title">Lua Cheia</h3>
      <div class="reading-body">Toda vez que olho para uma lua bonita, lembro de você.

Não porque vocês sejam iguais.

Mas porque as duas possuem a mesma característica.

São impossíveis de ignorar.

Mesmo quando estão longe.

Mesmo quando parecem inalcançáveis.

Mesmo quando não percebem que alguém está olhando.</div>
    </div>

    <div class="reading-divider reveal">✦ &nbsp;&nbsp; ✦ &nbsp;&nbsp; ✦</div>

    <div class="reading-block reveal">
      <div class="reading-label">✦</div>
      <h3 class="reading-title">O Que Ficou</h3>
      <div class="reading-body">O tempo levou muitas coisas.

Levou momentos, pessoas e histórias.

Mas não levou as lembranças que tenho de você.

Elas continuam aqui.

Guardadas no mesmo lugar onde nasceram.

Dentro do meu coração.</div>
    </div>

    <div class="reading-divider reveal">✦ &nbsp;&nbsp; ✦ &nbsp;&nbsp; ✦</div>

    <div class="reading-block reveal">
      <div class="reading-label">✦</div>
      <h3 class="reading-title">Seu Sorriso Outra Vez</h3>
      <div class="reading-body">Existem milhares de motivos para gostar de alguém.

Mas confesso que um dos meus favoritos sempre foi seu sorriso.

Porque ele aparece de repente.

Sem avisar.

E quando aparece, consegue melhorar o meu dia sem fazer esforço algum.</div>
    </div>

    <div class="reading-divider reveal">✦ &nbsp;&nbsp; ✦ &nbsp;&nbsp; ✦</div>

    <div class="reading-block reveal">
      <div class="reading-label">✦</div>
      <h3 class="reading-title">Liberdade</h3>
      <div class="reading-body">Você sempre gostou de liberdade.

Nunca foi do tipo que gosta de correntes ou promessas.

E eu admiro isso.

Porque algumas pessoas nasceram para voar.

E mesmo que eu não possa voar ao seu lado para sempre, fico feliz por ter acompanhado uma parte da sua jornada.</div>
    </div>

    <div class="reading-divider reveal">✦ &nbsp;&nbsp; ✦ &nbsp;&nbsp; ✦</div>

    <div class="reading-block reveal">
      <div class="reading-label">✦</div>
      <h3 class="reading-title">Simples Assim</h3>
      <div class="reading-body">Talvez eu nunca encontre as palavras perfeitas para explicar o que sinto.

Mas se precisasse resumir tudo em uma única frase, seria simples:

Eu gosto de você.

Mais do que deveria.

Mais do que planejei.

E muito mais do que consigo demonstrar.</div>
    </div>

    <div class="reading-divider reveal">✦ &nbsp;&nbsp; ✦ &nbsp;&nbsp; ✦</div>

    <div class="reading-block reveal">
      <div class="reading-label">✦</div>
      <h3 class="reading-title">Conversas Bobas</h3>
      <div class="reading-body">Engraçado como minhas lembranças favoritas não são momentos grandiosos.

São conversas sem sentido.

Risadas aleatórias.

Assuntos que ninguém mais acharia interessantes.

Mas quando eram com você, se tornavam especiais.</div>
    </div>

    <div class="reading-divider reveal">✦ &nbsp;&nbsp; ✦ &nbsp;&nbsp; ✦</div>

    <div class="reading-block reveal">
      <div class="reading-label">✦</div>
      <h3 class="reading-title">Destino</h3>
      <div class="reading-body">Não sei se existe destino.

Não sei se as pessoas estão destinadas a se encontrar.

Mas se existe, agradeço por ter cruzado seu caminho.

Porque minha vida seria muito diferente se eu nunca tivesse conhecido você.</div>
    </div>

    <div class="reading-divider reveal">✦ &nbsp;&nbsp; ✦ &nbsp;&nbsp; ✦</div>

    <div class="reading-block reveal">
      <div class="reading-label">✦</div>
      <h3 class="reading-title">Mesmo Assim</h3>
      <div class="reading-body">Eu conheço seus defeitos.

Conheço suas ausências.

Conheço seus silêncios.

E mesmo assim continuo aqui.

Porque gostar de alguém nunca foi sobre enxergar apenas qualidades.

É sobre escolher ficar mesmo conhecendo as imperfeições.</div>
    </div>

    <div class="reading-divider reveal">✦ &nbsp;&nbsp; ✦ &nbsp;&nbsp; ✦</div>

    <div class="reading-block reveal">
      <div class="reading-label">✦</div>
      <h3 class="reading-title">Obrigado</h3>
      <div class="reading-body">Talvez nossa história nunca seja como imaginei.

Talvez ela nem tenha um final feliz.

Mas ainda assim sou grato.

Grato pelos sorrisos.

Pelas conversas.

Pelas lembranças.

E principalmente por você ter existido na minha vida.

Porque algumas pessoas passam pela nossa história.

Outras deixam marcas.

Você deixou sonhos.

Deixou saudades.

Deixou momentos que continuam vivos mesmo depois do tempo passar.

E por isso, independentemente do caminho que a vida escolher para nós,

obrigado.</div>
    </div>

  </div>
</section>

<!-- DREAMS -->
<section id="dreams">
  <div class="sec-header reveal">
    <h2>Os Sonhos Que Você Me Ensinou a Ter</h2>
    <div class="sec-line"></div>
  </div>
  <p class="dreams-text reveal">Antes de você, eu nunca pensava muito sobre o mundo. Aos poucos, seus sonhos se misturaram aos meus. Hoje, quando penso no futuro, lembro dos lugares que você queria conhecer.</p>
  <div class="destinations-box reveal">
    <p class="dest-subtitle">Países e destinos marcados no coração para visitar e explorar:</p>
    <div class="dest-pills">
      <span class="dest-pill">📍 Coreia do Sul <sup>KR</sup></span>
      <span class="dest-pill">📍 Japão <sup>JP</sup></span>
      <span class="dest-pill">📍 Tailândia <sup>TH</sup></span>
      <span class="dest-pill">🌐 Europa</span>
      <span class="dest-pill">🌐 Américas</span>
    </div>
    <div class="dest-pills" style="margin-top:14px;">
      <span class="dest-pill dest-pill--main">✈️ Conhecer o Mundo</span>
    </div>
  </div>
</section>

<!-- DIARY -->
<section id="diary">
  <div class="sec-header reveal">
    <h2>Páginas de Diário</h2>
    <div class="sec-line"></div>
    <p>Pensamentos que escrevi em noites de saudade.</p>
  </div>
  <div class="diary-entries">
    <div class="diary-entry reveal">
      <div class="diary-date">🌙</div>
      <div class="diary-text">Você entrou na minha vida sem pedir licença e acabou ficando.</div>
    </div>
    <div class="diary-entry reveal">
      <div class="diary-date">💜</div>
      <div class="diary-text">Algumas pessoas são especiais. Você é inesquecível.</div>
    </div>
    <div class="diary-entry reveal">
      <div class="diary-date">🌸</div>
      <div class="diary-text">Seu sorriso sempre foi meu lugar favorito.</div>
    </div>
    <div class="diary-entry reveal">
      <div class="diary-date">⭐</div>
      <div class="diary-text">Talvez você nunca saiba o quanto significou para mim.</div>
    </div>
    <div class="diary-entry reveal">
      <div class="diary-date">🌙</div>
      <div class="diary-text">Eu procurava você em todos os lugares sem perceber.</div>
    </div>
    <div class="diary-entry reveal">
      <div class="diary-date">💜</div>
      <div class="diary-text">Você transformou momentos simples em lembranças eternas.</div>
    </div>
    <div class="diary-entry reveal">
      <div class="diary-date">🌸</div>
      <div class="diary-text">Meu coração escolheu você muito antes de eu perceber.</div>
    </div>
    <div class="diary-entry reveal">
      <div class="diary-date">⭐</div>
      <div class="diary-text">A lua me lembra você: bonita, distante e impossível de ignorar.</div>
    </div>
    <div class="diary-entry reveal">
      <div class="diary-date">🌙</div>
      <div class="diary-text">Você foi meu primeiro amor e continua sendo minha lembrança favorita.</div>
    </div>
    <div class="diary-entry reveal">
      <div class="diary-date">💜</div>
      <div class="diary-text">Mesmo no silêncio, você continua presente nos meus pensamentos.</div>
    </div>
    <div class="diary-entry reveal">
      <div class="diary-date">🌸</div>
      <div class="diary-text">Você me ensinou a sonhar com lugares que eu nunca imaginei conhecer.</div>
    </div>
    <div class="diary-entry reveal">
      <div class="diary-date">⭐</div>
      <div class="diary-text">Algumas histórias não precisam de um final para serem importantes.</div>
    </div>
    <div class="diary-entry reveal">
      <div class="diary-date">🌙</div>
      <div class="diary-text">Seu nome mora em pensamentos que o tempo nunca levou.</div>
    </div>
    <div class="diary-entry reveal">
      <div class="diary-date">💜</div>
      <div class="diary-text">Entre bilhões de pessoas, meu coração encontrou você.</div>
    </div>
    <div class="diary-entry reveal">
      <div class="diary-date">🌸</div>
      <div class="diary-text">Se eu pudesse guardar apenas uma lembrança, escolheria qualquer momento ao seu lado.</div>
    </div>
    <div class="diary-entry reveal">
      <div class="diary-date">✨</div>
      <div class="diary-text">Não sei se você vai ler algum dia. Mas fiz este site porque você merecia mais do que uma mensagem qualquer. Você sempre mereceu mais.</div>
    </div>
    <div class="diary-entry reveal">
      <div class="diary-date">🎬</div>
      <div class="diary-text">Me contou sobre o último dorama que assistiu com tanto entusiasmo que eu quis assistir só para poder falar sobre ele com você. Nunca cheguei a contar isso.</div>
    </div>
  </div>
</section>

<!-- MEMORIES -->
<section id="memories">
  <div class="sec-header reveal">
    <h2>Momentos Que Nunca Esqueci</h2>
    <div class="sec-line"></div>
  </div>
  <div class="memories-list">
    <div class="memory-item reveal">
      <span class="memory-icon">🌙</span>
      <span class="memory-text">Quando você colocou a cabeça no meu ombro — e o tempo parou completamente.</span>
    </div>
    <div class="memory-item reveal">
      <span class="memory-icon">🤝</span>
      <span class="memory-text">Quando segurou minha mão sem dizer nada — e não precisava dizer nada mesmo.</span>
    </div>
    <div class="memory-item reveal">
      <span class="memory-icon">💬</span>
      <span class="memory-text">Quando falávamos de coisas sem sentido por horas — e eram as melhores horas.</span>
    </div>
    <div class="memory-item reveal">
      <span class="memory-icon">✨</span>
      <span class="memory-text">Quando você sorria — do jeito espontâneo, sem querer, de repente — e eu ficava sem palavras.</span>
    </div>
    <div class="memory-item reveal">
      <span class="memory-icon">💜</span>
      <span class="memory-text">Quando eu esquecia todos os meus problemas perto de você — como se o mundo ficasse menor e mais simples.</span>
    </div>
  </div>
</section>

<!-- FINAL -->
<section id="final">
  <h2 class="final-title reveal">Se Um Dia Você Ler Isso</h2>
  <p class="final-letter reveal">Talvez você nunca sinta por mim o que eu sinto por você.
Talvez nossa história nunca tenha o final que imaginei.

Mas isso não muda o fato de que você foi uma das pessoas mais importantes da minha vida.

Não fiz este site esperando mudar alguma coisa.
Fiz porque algumas pessoas merecem mais do que uma simples mensagem.

E para mim, você sempre foi uma dessas pessoas.</p>
  <p class="final-signature reveal">— com carinho, para sempre 💜</p>

  <!-- BUQUÊ INTERATIVO GIGANTE E BRILHANTE IGUAL À IMAGEM -->
  <div class="bouquet-wrapper reveal">
    <div class="luxurious-bouquet" onclick="dispararChuvaMágica(event)"></div>
    <p class="click-hint">(clique no buquê)</p>
  </div>

</section>

<!-- FOOTER -->
<footer>
  <p class="footer-quote">"Da garota que parecia a lua iluminando uma noite escura, para sempre guardada nas minhas lembranças."</p>
  <span class="footer-heart">✦ ✦ ✦</span>
</footer>

<script>
// ─── CANVAS SKY ───
const canvas = document.getElementById('sky-canvas');
const ctx = canvas.getContext('2d');
let W, H, stars = [], shootingStars = [];

function resize() {
  W = canvas.width = window.innerWidth;
  H = canvas.height = window.innerHeight;
  buildStars();
}

function buildStars() {
  stars = [];
  for (let i = 0; i < 220; i++) {
    stars.push({
      x: Math.random() * W,
      y: Math.random() * H,
      r: Math.random() * 1.2 + 0.2,
      alpha: Math.random(),
      speed: Math.random() * 0.004 + 0.002,
      phase: Math.random() * Math.PI * 2
    });
  }
}

function drawSky(t) {
  // gradient background
  const g = ctx.createLinearGradient(0, 0, 0, H);
  g.addColorStop(0, '#07000f');
  g.addColorStop(0.5, '#0e0018');
  g.addColorStop(1, '#130022');
  ctx.fillStyle = g;
  ctx.fillRect(0, 0, W, H);

  // stars
  stars.forEach(s => {
    s.alpha = 0.3 + 0.5 * Math.abs(Math.sin(t * s.speed + s.phase));
    ctx.beginPath();
    ctx.arc(s.x, s.y, s.r, 0, Math.PI * 2);
    ctx.fillStyle = `rgba(220,200,255,${s.alpha})`;
    ctx.fill();
  });

  // occasional shooting star
  if (Math.random() < 0.004) {
    shootingStars.push({ x: Math.random() * W * 0.7, y: Math.random() * H * 0.4, len: 80 + Math.random() * 60, alpha: 1 });
  }
  shootingStars = shootingStars.filter(s => s.alpha > 0);
  shootingStars.forEach(s => {
    const grd = ctx.createLinearGradient(s.x, s.y, s.x + s.len, s.y + s.len * 0.4);
    grd.addColorStop(0, `rgba(220,200,255,${s.alpha})`);
    grd.addColorStop(1, 'rgba(220,200,255,0)');
    ctx.strokeStyle = grd;
    ctx.lineWidth = 1;
    ctx.beginPath();
    ctx.moveTo(s.x, s.y);
    ctx.lineTo(s.x + s.len, s.y + s.len * 0.4);
    ctx.stroke();
    s.x += 3; s.y += 1.5; s.alpha -= 0.025;
  });
}

let raf;
function loop(t) {
  drawSky(t * 0.001);
  raf = requestAnimationFrame(loop);
}
window.addEventListener('resize', resize);
resize();
requestAnimationFrame(loop);

// ─── PETALS ───
const petalColors = ['#c084fc','#a855f7','#e9d5ff','#d8b4fe','#f0abfc'];
for (let i = 0; i < 18; i++) {
  const p = document.createElement('div');
  p.className = 'petal';
  const size = 6 + Math.random() * 8;
  p.style.cssText = `
    left:${Math.random()*100}vw;
    width:${size}px; height:${size}px;
    background:${petalColors[Math.floor(Math.random()*petalColors.length)]};
    animation-duration:${10 + Math.random()*14}s;
    animation-delay:${Math.random()*12}s;
    opacity:0;
  `;
  document.body.appendChild(p);
}

// ─── REVEAL ON SCROLL ───
const revealEls = document.querySelectorAll('.reveal');
const io = new IntersectionObserver((entries) => {
  entries.forEach(e => {
    if (e.isIntersecting) { e.target.classList.add('visible'); io.unobserve(e.target); }
  });
}, { threshold: 0.12 });
revealEls.forEach(el => io.observe(el));

// ─── CHUVA MÁGICA DE FLORES DO BUQUÊ ───
function dispararChuvaMágica(event) {
  const floresLista = ['🌸', '💜', '✨', '🌹', '🌷', '🍇', '🔮', '🦋', '💐'];
  const quantidade = 50;
  
  // Efeito de pulso rápido no clique
  const bq = event.currentTarget;
  bq.style.transform = 'scale(0.95)';
  setTimeout(() => { bq.style.transform = ''; }, 200);

  for (let i = 0; i < quantidade; i++) {
    setTimeout(() => {
      const f = document.createElement('div');
      f.className = 'falling-flower-fx';
      f.innerText = floresLista[Math.floor(Math.random() * floresLista.length)];
      
      const posX = Math.random() * 100;
      f.style.left = posX + 'vw';
      f.style.top = '-40px';
      
      const tam = Math.random() * 25 + 20; // 20px a 45px (bem visível)
      f.style.fontSize = tam + 'px';
      f.style.opacity = Math.random() * 0.4 + 0.6;
      f.style.filter = `drop-shadow(0 0 ${Math.random() * 10 + 5}px rgba(192, 132, 252, 0.8))`;
      
      const tempo = Math.random() * 2 + 2.5; // queda suave de 2.5s a 4.5s
      f.style.transition = `transform ${tempo}s linear, opacity ${tempo}s ease-out`;
      
      document.body.appendChild(f);
      
      setTimeout(() => {
        const descX = posX + (Math.random() * 20 - 10);
        const rot = Math.random() * 720 - 360;
        f.style.transform = `translate(${descX - posX}vw, 105vh) rotate(${rot}deg)`;
        f.style.opacity = '0';
      }, 40);
      
      setTimeout(() => { f.remove(); }, tempo * 1000 + 100);
    }, i * 40);
  }
}

</script>
</body>
</html>
