<html lang="pt-BR">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>♡</title>

<style>
@import url('https://fonts.googleapis.com/css2?family=Fredoka:wght@300;400;500&display=swap');

:root {
    --rosa-claro: #fff5fa;
    --rosa: #ffd6e8;
    --rosa-medio: #ffb6d5;
    --rosa-forte: #f58ab9;
    --rosa-escuro: #d96d9f;
    --branco: #ffffff;
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
    background: var(--rosa-claro);
    color: var(--rosa-escuro);
    font-family: 'Fredoka', sans-serif;
    overflow-x: hidden;
}

/* FUNDO */

.background {
    position: fixed;
    inset: 0;
    z-index: -2;

    background:
        linear-gradient(
            rgba(255, 240, 248, 0.25),
            rgba(255, 225, 240, 0.35)
        ),
        url("https://i.pinimg.com/736x/2e/6e/14/2e6e14261aadfde2c2dc7627aac2557f.jpg");

    background-size: cover;
    background-position: center;
    background-repeat: no-repeat;

}

.decoracao {
    position: fixed;
    color: #f8a8cc;
    opacity: .65;
    pointer-events: none;
    z-index: -1;
    animation: flutuar 5s ease-in-out infinite;
}

.decoracao:nth-child(1) {
    top: 15%;
    left: 5%;
    font-size: 28px;
}

.decoracao:nth-child(2) {
    top: 35%;
    right: 7%;
    font-size: 22px;
    animation-delay: 1s;
}

.decoracao:nth-child(3) {
    bottom: 15%;
    left: 9%;
    font-size: 32px;
    animation-delay: 2s;
}

.decoracao:nth-child(4) {
    top: 65%;
    right: 12%;
    font-size: 18px;
    animation-delay: 1.5s;
}

@keyframes flutuar {
    0%, 100% { transform: translateY(0) rotate(-5deg); }
    50% { transform: translateY(-18px) rotate(8deg); }
}

/* MENU */

header {
    width: 100%;
    padding: 22px 8%;
    display: flex;
    justify-content: space-between;
    align-items: center;
}

.logo {
    font-size: 28px;
    color: var(--rosa-forte);
}

.menu {
    display: flex;
    gap: 22px;
}

.menu a {
    color: var(--rosa-escuro);
    text-decoration: none;
    font-size: 14px;
    transition: .3s;
}

.menu a:hover {
    color: var(--rosa-forte);
    transform: translateY(-2px);
}

/* INÍCIO */

.inicio {
    min-height: 78vh;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    text-align: center;
    padding: 50px 20px 90px;
    position: relative;
}

.inicio h1 {
    font-size: clamp(45px, 8vw, 85px);
    font-weight: 500;
    color: var(--rosa-forte);
    letter-spacing: 3px;
    text-shadow: 3px 4px 0 #ffe0ed;
}

.inicio p {
    margin-top: 15px;
    font-size: 20px;
    color: #e9a0c0;
}

.botao {
    margin-top: 30px;
    padding: 13px 28px;
    border: 2px solid #ffc3dd;
    background: #ffe4f0;
    color: #d96d9f;
    border-radius: 30px;
    font-family: inherit;
    font-size: 16px;
    cursor: pointer;
    transition: .3s;
    box-shadow: 0 6px 15px #f7c9de66;
}

.botao:hover {
    transform: translateY(-4px) scale(1.04);
    background: #ffd3e6;
}

/* BALÕES */

.baloes {
    position: absolute;
    bottom: 10px;
    left: 0;
    right: 0;
    height: 210px;
    pointer-events: none;
    overflow: hidden;
}

.balao {
    position: absolute;
    bottom: -130px;
    width: 64px;
    height: 80px;
    border-radius: 50% 50% 45% 45%;
    display: flex;
    justify-content: center;
    align-items: center;
    font-size: 22px;
    color: #d96d9f;
    background: linear-gradient(135deg, #ffe1ef, #ffb8d7);
    box-shadow: inset -7px -6px 12px #ee8eb744,
                inset 6px 5px 12px #ffffffaa,
                0 5px 15px #f7b8d866;
    animation: subir 10s linear infinite;
}

.balao::after {
    content: "";
    position: absolute;
    bottom: -9px;
    width: 12px;
    height: 12px;
    background: #ffb8d7;
    clip-path: polygon(50% 100%, 0 0, 100% 0);
}

.balao::before {
    content: "";
    position: absolute;
    width: 1px;
    height: 50px;
    background: #eaa4c5;
    bottom: -59px;
}

.balao:nth-child(1) { left: 10%; animation-delay: 0s; }
.balao:nth-child(2) { left: 28%; animation-delay: 3s; background: #ffeaf3; }
.balao:nth-child(3) { left: 48%; animation-delay: 1s; }
.balao:nth-child(4) { left: 70%; animation-delay: 4s; background: #ffd0e4; }
.balao:nth-child(5) { left: 88%; animation-delay: 2s; }

@keyframes subir {
    0% { transform: translateY(0) rotate(-5deg); }
    100% { transform: translateY(-390px) rotate(10deg); }
}

/* SEÇÕES */

section {
    padding: 75px 8%;
}

.titulo {
    text-align: center;
    font-size: 34px;
    font-weight: 400;
    color: var(--rosa-forte);
    margin-bottom: 35px;
}

.linha {
    width: 65px;
    height: 4px;
    border-radius: 5px;
    background: var(--rosa-medio);
    margin: -20px auto 40px;
}

/* GALERIA */

.galeria {
    display: grid;
    grid-template-columns: repeat(3, minmax(0, 1fr));
    gap: 22px;
    max-width: 1050px;
    margin: auto;
}

.foto {
    position: relative;
    min-height: 240px;
    background: linear-gradient(145deg, #ffe5f0, #ffd1e5);
    border: 5px solid white;
    border-radius: 24px;
    overflow: hidden;
    box-shadow: 0 8px 25px #e9a4c533;
    transition: transform .3s, box-shadow .3s;
}

.foto:hover {
    transform: translateY(-7px) rotate(1deg);
    box-shadow: 0 12px 30px #e9a4c566;
}

.foto img {
    width: 100%;
    height: 100%;
    min-height: 240px;
    object-fit: cover;
    display: block;
}

.foto.vazia {
    display: flex;
    justify-content: center;
    align-items: center;
}

.foto.vazia::after {
    content: "";
    position: absolute;
    inset: 12px;
    border: 2px dashed #f3a4c8;
    border-radius: 15px;
    pointer-events: none;
}

/* CARTÕES */

.cartoes {
    display: grid;
    grid-template-columns: repeat(3, minmax(0, 1fr));
    gap: 22px;
    max-width: 1000px;
    margin: auto;
}

.cartao {
    min-height: 180px;
    background: #ffffffb8;
    border: 2px solid #ffe0ed;
    border-radius: 25px;
    padding: 25px;
    display: flex;
    justify-content: center;
    align-items: center;
    box-shadow: 0 8px 20px #e9a4c522;
    transition: .3s;
}

.cartao:hover {
    transform: translateY(-6px);
    background: #fff;
}

.cartao span {
    font-size: 35px;
    color: var(--rosa-forte);
}

/* ÁREA DECORATIVA */

.decorativa {
    max-width: 1000px;
    margin: 30px auto;
    min-height: 230px;
    border-radius: 35px;
    background: linear-gradient(120deg, #ffe2ef, #ffd0e5, #fff0f7);
    border: 3px solid white;
    box-shadow: 0 10px 30px #e9a4c533;
    display: flex;
    justify-content: center;
    align-items: center;
    overflow: hidden;
    position: relative;
}

.decorativa::before,
.decorativa::after {
    content: "♡";
    position: absolute;
    font-size: 100px;
    color: #ffffff70;
    animation: flutuar 5s ease-in-out infinite;
}

.decorativa::before {
    left: 12%;
}

.decorativa::after {
    right: 12%;
    animation-delay: 2s;
}

/* RODAPÉ */

footer {
    padding: 35px 20px;
    text-align: center;
    color: #dc92b5;
    background: #ffeaf3;
    font-size: 18px;
}

footer span {
    color: var(--rosa-forte);
}

/* BOTÃO DE CORAÇÕES */

#efeitos {
    position: fixed;
    inset: 0;
    overflow: hidden;
    pointer-events: none;
    z-index: 10;
}

.coracao {
    position: absolute;
    bottom: -30px;
    color: #f58ab9;
    font-size: 24px;
    animation: coracaoSubir 3s ease-out forwards;
}

@keyframes coracaoSubir {
    0% { transform: translateY(0) scale(.5) rotate(0); opacity: 0; }
    15% { opacity: 1; }
    100% { transform: translateY(-100vh) scale(1.4) rotate(35deg); opacity: 0; }
}

/* RESPONSIVIDADE */

@media (max-width: 700px) {
    header {
        padding: 18px 5%;
    }

    .menu {
        gap: 12px;
    }

    .menu a {
        font-size: 12px;
    }

    .inicio {
        min-height: 75vh;
    }

    .inicio p {
        font-size: 17px;
    }

    section {
        padding: 55px 6%;
    }

    .galeria {
        grid-template-columns: repeat(2, minmax(0, 1fr));
        gap: 13px;
    }

    .foto,
    .foto img {
        min-height: 170px;
    }

    .cartoes {
        grid-template-columns: 1fr;
    }

    .cartao {
        min-height: 120px;
    }

    .titulo {
        font-size: 28px;
    }
}

@media (max-width: 380px) {
    .menu {
        gap: 8px;
    }

    .menu a {
        font-size: 11px;
    }

    .galeria {
        grid-template-columns: 1fr;
    }
}
</style>
</head>

<body>

<div class="background"></div>

<div class="decoracao">♡</div>
<div class="decoracao">✧</div>
<div class="decoracao">♡</div>
<div class="decoracao">✿</div>

<header>
    <div class="logo">ana</div>

    <nav class="menu">
        <a href="#inicio">Início</a>
        <a href="#fotos">Fotos</a>
        <a href="#detalhes">Detalhes</a>
    </nav>
</header>

<main>

    <section class="inicio" id="inicio">
        <h1>♡</h1>
        <p>.</p>

        <button class="botao" onclick="soltarCoracoes()">
            ♡
        </button>

        <div class="baloes">
            <div class="balao">.</div>
            <div class="balao">.</div>
            <div class="balao">.</div>
            <div class="balao">.</div>
            <div class="balao">.</div>
        </div>
    </section>

    <section id="fotos">
        <h2 class="titulo">♡</h2>
        <div class="linha"></div>

        <div class="galeria">

            <!-- FOTO 1: substitua pelo caminho da imagem -->
            <div class="foto vazia">
                <!-- <img src="imagens/foto1.jpg" alt="Foto 1"> -->
            </div>

            <!-- FOTO 2 -->
            <div class="foto vazia">
                <!-- <img src="imagens/foto2.jpg" alt="Foto 2"> -->
            </div>

            <!-- FOTO 3 -->
            <div class="foto vazia">
                <!-- <img src="imagens/foto3.jpg" alt="Foto 3"> -->
            </div>

            <!-- FOTO 4 -->
            <div class="foto vazia">
                <!-- <img src="imagens/foto4.jpg" alt="Foto 4"> -->
            </div>

            <!-- FOTO 5 -->
            <div class="foto vazia">
                <!-- <img src="imagens/foto5.jpg" alt="Foto 5"> -->
            </div>

            <!-- FOTO 6 -->
            <div class="foto vazia">
                <!-- <img src="imagens/foto6.jpg" alt="Foto 6"> -->
            </div>

        </div>
    </section>

    <section id="detalhes">
        <h2 class="titulo">♡</h2>
        <div class="linha"></div>

        <div class="cartoes">
            <div class="cartao"><span>♡</span></div>
            <div class="cartao"><span>✿</span></div>
            <div class="cartao"><span>✧</span></div>
        </div>

        <div class="decorativa"></div>
    </section>

</main>

<footer>
    <span>♡</span> . <span>♡</span>
</footer>

<div id="efeitos"></div>

<script>
function soltarCoracoes() {
    const area = document.getElementById('efeitos');

    for (let i = 0; i < 24; i++) {
        const coracao = document.createElement('div');

        coracao.className = 'coracao';
        coracao.textContent = Math.random() > 0.5 ? '♡' : '♥';

        coracao.style.left = Math.random() * 100 + '%';
        coracao.style.animationDelay = Math.random() * 1.2 + 's';
        coracao.style.fontSize = (16 + Math.random() * 24) + 'px';

        area.appendChild(coracao);

        setTimeout(() => coracao.remove(), 4500);
    }
}
</script>

</body>
</html>
```
