<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Feliz Aniversário, camarada!❤️</title>

  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link href="https://fonts.googleapis.com/css2?family=DM+Serif+Display&family=Poppins:wght@300;400;500;600;700&display=swap" rel="stylesheet">

  <style>
    :root {
      --vinho: #310810;
      --vermelho: #a41632;
      --rosa: #ef536d;
      --dourado: #f4cb8b;
      --creme: #fff0e5;
    }

    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    html {
      scroll-behavior: smooth;
    }

    body {
      background: var(--vinho);
      color: var(--creme);
      font-family: 'Poppins', sans-serif;
      overflow-x: hidden;
    }

    button {
      font-family: inherit;
      cursor: pointer;
    }

    .hero {
      min-height: 100vh;
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
      text-align: center;
      padding: 70px 22px;
      position: relative;
      overflow: hidden;
      background:
        radial-gradient(ellipse at 50% 35%, #8e1831 0%, transparent 55%),
        linear-gradient(145deg, #21050b, #570d20 55%, #26060d);
    }

    .hero::before,
    .hero::after {
      content: "♥";
      position: absolute;
      color: rgba(255, 196, 164, 0.07);
      font-size: 280px;
      pointer-events: none;
    }

    .hero::before {
      top: -75px;
      left: -65px;
      transform: rotate(-20deg);
    }

    .hero::after {
      bottom: -100px;
      right: -65px;
      transform: rotate(20deg);
    }

    .eyebrow {
      color: var(--dourado);
      letter-spacing: 4px;
      text-transform: uppercase;
      font-size: 11px;
      font-weight: 600;
      margin-bottom: 22px;
    }

    .heart-icon {
      font-size: 52px;
      margin-bottom: 22px;
      animation: heartbeat 1.5s infinite;
      filter: drop-shadow(0 0 18px #ff526e66);
    }

    h1 {
      font-family: 'DM Serif Display', serif;
      font-weight: 400;
      font-size: clamp(43px, 9vw, 86px);
      line-height: 1.1;
      max-width: 900px;
      margin-bottom: 24px;
    }

    h1 span {
      color: var(--dourado);
      font-style: italic;
    }

    .hero-text {
      max-width: 540px;
      line-height: 1.9;
      color: #f5dce0;
      font-size: 15px;
      font-weight: 300;
      margin-bottom: 35px;
    }

    .button {
      border: none;
      border-radius: 40px;
      padding: 15px 25px;
      background: var(--dourado);
      color: #40101a;
      font-size: 13px;
      font-weight: 700;
      transition: .25s;
      box-shadow: 0 8px 30px #00000025;
    }

    .button:hover {
      transform: translateY(-4px);
      box-shadow: 0 12px 35px #f4cb8b35;
    }

    .button-outline {
      background: transparent;
      border: 1px solid #f4cb8b80;
      color: var(--creme);
    }

    .scroll-note {
      position: absolute;
      bottom: 24px;
      color: #f5dce099;
      font-size: 10px;
      letter-spacing: 2px;
    }

    section {
      padding: 95px 22px;
    }

    .section-inner {
      max-width: 950px;
      margin: auto;
      text-align: center;
    }

    .section-label {
      text-transform: uppercase;
      color: var(--rosa);
      font-size: 11px;
      font-weight: 700;
      letter-spacing: 3px;
      margin-bottom: 15px;
    }

    h2 {
      font-family: 'DM Serif Display', serif;
      font-size: clamp(34px, 6vw, 52px);
      font-weight: 400;
      margin-bottom: 20px;
    }

    .intro {
      max-width: 600px;
      margin: 0 auto 40px;
      color: #e8cbd0;
      line-height: 1.9;
      font-size: 14px;
    }

    .message-section {
      background: #fff0e5;
      color: #48101d;
    }

    .message-section .intro {
      color: #79515a;
    }

    .message-card {
      max-width: 650px;
      margin: auto;
      padding: 38px 28px;
      border: 1px solid #d9a8a055;
      background: #fffaf5;
      border-radius: 20px;
      box-shadow: 0 15px 45px #48101d0d;
    }

    .message-card .big-heart {
      font-size: 35px;
      margin-bottom: 20px;
    }

    .message-card p {
      font-size: 14px;
      line-height: 2;
      color: #68414b;
      margin-bottom: 16px;
    }

    .signature {
      font-family: 'DM Serif Display', serif;
      font-size: 25px;
      font-style: italic;
      color: #a41632;
      margin-top: 25px;
    }

    .surprise-section {
      background: linear-gradient(160deg, #4c0a1b, #26060d);
    }

    .gift {
      font-size: 90px;
      margin: 25px 0;
      display: inline-block;
      cursor: pointer;
      transition: .3s;
      filter: drop-shadow(0 12px 20px #00000030);
    }

    .gift:hover {
      transform: scale(1.12) rotate(-5deg);
    }

    .surprise-message {
      display: none;
      max-width: 560px;
      margin: 30px auto 0;
      padding: 30px 25px;
      border: 1px solid #f4cb8b66;
      border-radius: 18px;
      background: #ffffff08;
      animation: appear .7s ease;
    }

    .surprise-message.show {
      display: block;
    }

    .surprise-message p {
      color: #f5dce0;
      line-height: 1.9;
      font-size: 14px;
    }

    .surprise-message h3 {
      font-family: 'DM Serif Display', serif;
      color: var(--dourado);
      font-size: 29px;
      font-weight: 400;
      margin-bottom: 15px;
    }

    .reasons {
      background: #fff0e5;
      color: #48101d;
    }

    .reason-grid {
      display: grid;
      grid-template-columns: repeat(3, 1fr);
      gap: 18px;
      margin-top: 40px;
    }

    .reason {
      padding: 28px 18px;
      border: 1px solid #d9a8a066;
      border-radius: 17px;
      background: #fffaf5;
      transition: .25s;
    }

    .reason:hover {
      transform: translateY(-6px);
      box-shadow: 0 15px 35px #48101d12;
    }

    .reason .emoji {
      font-size: 32px;
      margin-bottom: 15px;
    }

    .reason h3 {
      font-size: 15px;
      margin-bottom: 10px;
    }

    .reason p {
      color: #79515a;
      font-size: 12px;
      line-height: 1.8;
    }

    .final-section {
      text-align: center;
      background:
        radial-gradient(ellipse at center, #7b112a 0%, #310810 70%);
      padding: 110px 22px;
    }

    .final-section h2 {
      color: var(--dourado);
    }

    .final-section p {
      color: #f5dce0;
      line-height: 1.9;
      max-width: 540px;
      margin: 0 auto 28px;
      font-size: 14px;
    }

    footer {
      background: #20050a;
      text-align: center;
      padding: 25px 15px;
      color: #d8aab2;
      font-size: 11px;
    }

    .floating-heart {
      position: fixed;
      bottom: -40px;
      z-index: 100;
      pointer-events: none;
      animation: floatUp linear forwards;
    }

    @keyframes heartbeat {
      0%, 100% { transform: scale(1); }
      12% { transform: scale(1.15); }
      24% { transform: scale(1); }
      36% { transform: scale(1.12); }
    }

    @keyframes floatUp {
      0% {
        transform: translateY(0) rotate(0deg);
        opacity: 1;
      }
      100% {
        transform: translateY(-110vh) rotate(35deg);
        opacity: 0;
      }
    }

    @keyframes appear {
      from {
        opacity: 0;
        transform: translateY(15px);
      }
      to {
        opacity: 1;
        transform: translateY(0);
      }
    }

    @media (max-width: 650px) {
      .reason-grid {
        grid-template-columns: 1fr;
      }

      section {
        padding: 75px 20px;
      }

      .message-card {
        padding: 30px 21px;
      }

      .eyebrow {
        letter-spacing: 2px;
      }
    }

    @media (prefers-reduced-motion: reduce) {
      *, *::before, *::after {
        animation-duration: 0.01ms !important;
        animation-iteration-count: 1 !important;
        scroll-behavior: auto !important;
      }
    }
  </style>
</head>

<body>

  <!-- ABERTURA -->
  <header class="hero">
    <div class="eyebrow">Um dia muito especial ❤️</div>
    <div class="heart-icon">♥</div>

    <h1>Feliz aniversário,<br><span>meu pai!</span></h1>

    <p class="hero-text">
     .
    </p>

    <button class="button" onclick="document.querySelector('#mensagem').scrollIntoView()">
      .
    </button>

    <div class="scroll-note">CONTINUE DESCENDO PARA DESCOBRIR</div>
  </header>

  <!-- CARTA -->
  <section class="message-section" id="mensagem">
    <div class="section-inner">
      <div class="section-label">Uma mensagem de coração</div>
      <h2>.</h2>

      <p class="intro">
        .
      </p>

      <div class="message-card">
        <div class="big-heart">❤️</div>

        <p>
          .
        </p>

        <p>
         .
        </p>

        <p>
          .
        </p>

        <p>
       .
        </p>

        <p>
         .
        </p>

        <div class="signature">.❤️</div>
      </div>
    </div>
  </section>

  <!-- PRESENTE INTERATIVO -->
  <section class="surprise-section">
    <div class="section-inner">
      <div class="section-label">Tem mais uma coisinha...</div>
      <h2>. 🎁</h2>

      <p class="intro">
        .
      </p>

      <div
        class="gift"
        id="gift"
        role="button"
        tabindex="0"
        aria-label="Abrir presente"
        onclick="openGift()"
        onkeydown="if(event.key === 'Enter' || event.key === ' '){event.preventDefault();openGift()}"
      >🎁</div>

      <div class="surprise-message" id="surprise">
        <h3>.a!</h3>
        <p>
       .
        </p>
        <p style="margin-top: 15px">
         .
          ❤️
        </p>
      </div>
    </div>
  </section>

  <!-- HOMENAGEM -->
  <section class="reasons">
    <div class="section-inner">
      <div class="section-label">Hoje e sempre</div>
      <h2>.o</h2>

      <p class="intro">
        T..
      </p>

      <div class="reason-grid">
        <div class="reason">
          <div class="emoji">❤️</div>
          <h3>Muito amor</h3>
          <p>
            .
          </p>
        </div>

        <div class="reason">
          <div class="emoji">✨</div>
          <h3>Muitos sonhos</h3>
          <p>
            .
          </p>
        </div>

        <div class="reason">
          <div class="emoji">🌹</div>
          <h3>Saúde e felicidade</h3>
          <p>
            Q.
          </p>
        </div>
      </div>
    </div>
  </section>

  <!-- FINAL -->
  <section class="final-section">
    <div class="section-label">Uma última coisa...</div>

    <h2. ❤️</h2>

    <p>
      .
    </p>

    <button class="button" onclick="celebrate()">
     .🎉
    </button>

    <p id="celebration" style="margin-top: 22px; display: none;">
      🎉 FELIZ ANIVERSÁRIO! 🎉<br>
      Que seu dia seja tão especial quanto você!
    </p>
  </section>

  <footer>
    .. ❤️
  </footer>

  <script>
    let giftOpened = false;

    function openGift() {
      const surprise = document.getElementById('surprise');
      const gift = document.getElementById('gift');

      surprise.classList.add('show');
      gift.textContent = '💝';

      if (!giftOpened) {
        giftOpened = true;
        celebrateHearts(30);
      }

      surprise.scrollIntoView({
        behavior: 'smooth',
        block: 'center'
      });
    }

    function celebrate() {
      const message = document.getElementById('celebration');

      message.style.display = 'block';
      celebrateHearts(45);
    }

    function celebrateHearts(amount) {
      const symbols = ['❤️', '💖', '💕', '💗', '✨', '🎉'];

      for (let i = 0; i < amount; i++) {
        setTimeout(() => {
          const heart = document.createElement('span');

          heart.className = 'floating-heart';
          heart.textContent =
            symbols[Math.floor(Math.random() * symbols.length)];

          heart.style.left = Math.random() * 100 + 'vw';
          heart.style.fontSize = (16 + Math.random() * 22) + 'px';
          heart.style.animationDuration = (3 + Math.random() * 4) + 's';

          document.body.appendChild(heart);

          heart.addEventListener('animationend', () => {
            heart.remove();
          }, { once: true });

        }, i * 65);
      }
    }
  </script>

</body>
</html>
```
