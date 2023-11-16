<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Meu Portfólio - Matemática</title>
    <link rel="stylesheet" href="styles.css">
    <style>
        body {
            font-family: 'Comic Sans MS', cursive, sans-serif; /* Fonte mais descontraída e fofa */
            background-color: #ffd6e6; /* Rosa claro */
            margin: 0;
            padding: 0;
        }

        header {
            background-color: #ff99cc; /* Rosa médio */
            color: #fff;
            padding: 20px 0;
            text-align: center;
            border-radius: 15px; /* Bordas arredondadas */
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1); /* Sombra suave */
        }

        nav {
            background-color: #ffb3d9; /* Rosa claro */
            color: #fff;
            text-align: center;
            padding: 10px 0;
            border-bottom: 2px solid #ff99cc; /* Rosa médio */
        }

        nav a {
            color: #fff;
            text-decoration: none;
            margin: 0 15px;
            font-weight: bold;
            font-size: 18px;
        }

        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 20px;
            background-color: #fff; /* Fundo branco */
            border-radius: 15px; /* Bordas arredondadas */
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1); /* Sombra suave */
            margin-top: 20px;
        }

        h1 {
            font-size: 36px;
            color: #ff6699; /* Rosa escuro */
            margin-bottom: 20px;
            font-family: 'Indie Flower', cursive; /* Fonte mais "fofinha" */
        }

        h2 {
            color: #ff6699; /* Rosa escuro */
        }

        p {
            font-size: 18px;
            line-height: 1.5;
            color: #666;
        }

        .button {
            display: inline-block;
            padding: 12px 24px;
            background-color: #ff6699; /* Rosa escuro */
            color: #fff;
            text-decoration: none;
            font-weight: bold;
            border-radius: 5px;
            transition: background-color 0.3s;
        }

        .button:hover {
            background-color: #ff99cc; /* Rosa médio */
        }
    </style>
</head>
<body>
    <header>
        <h1>Bem-vindo ao Meu Portfólio de Matemática</h1>
    </header>
    <nav>
        <a href="#" id="btn-inicio">Início</a>
        <a href="#" id="btn-conteudo1">Conteúdo 1</a>
        <a href="#" id="btn-conteudo2">Conteúdo 2</a>
        <a href="#" id="btn-conteudo3">Conteúdo 3</a>
        <a href="#" id="btn-conteudo4">Conteúdo 4</a>
        <a href="#" id="btn-servicos">Autoavaliação</a>
    </nav>
    <div class="container" id="conteudo-inicio">
        <h2>Início</h2>
        <p>Esta é a página inicial do nosso site.</p>
    </div>
    <div class="container" id="conteudo-conteudo1" style="display: none;">
        <h2>Conteúdo 1</h2>
        <p>Aqui apresentamos os principais conceitos do primeiro conteúdo do terceiro trimestre de matemática.</p>
        <!-- Adicione informações específicas sobre o Conteúdo 1 aqui -->
    </div>
    <div class="container" id="conteudo-conteudo2" style="display: none;">
        <h2>Conteúdo 2</h2>
        <p>Explore os desafios e aplicações do segundo conteúdo do terceiro trimestre de matemática.</p>
        <!-- Adicione informações específicas sobre o Conteúdo 2 aqui -->
    </div>
    <div class="container" id="conteudo-conteudo3" style="display: none;">
        <h2>Conteúdo 3</h2>
        <p>Descubra as teorias e práticas do terceiro conteúdo do terceiro trimestre de matemática.</p>
        <!-- Adicione informações específicas sobre o Conteúdo 3 aqui -->
    </div>
    <div class="container" id="conteudo-conteudo4" style="display: none;">
        <h2>Conteúdo 4</h2>
        <p>Analise os casos e estudos relacionados ao quarto conteúdo do terceiro trimestre de matemática.</p>
        <!-- Adicione informações específicas sobre o Conteúdo 4 aqui -->
    </div>
    <div class="container" id="conteudo-servicos" style="display: none;">
        <h2>Autoavaliação</h2>
        <p>Confira minha autoavaliação e meu progresso.</p>
        <a href="#" class="button" id="btn-saiba-mais-servicos">Saiba Mais</a>
    </div>

    <script>
        // JavaScript para controlar a exibição das seções
        const btnInicio = document.getElementById('btn-inicio');
        const btnConteudo1 = document.getElementById('btn-conteudo1');
        const btnConteudo2 = document.getElementById('btn-conteudo2');
        const btnConteudo3 = document.getElementById('btn-conteudo3');
        const btnConteudo4 = document.getElementById('btn-conteudo4');
        const btnServicos = document.getElementById('btn-servicos');
        const conteudoInicio = document.getElementById('conteudo-inicio');
        const conteudoConteudo1 = document.getElementById('conteudo-conteudo1');
        const conteudoConteudo2 = document.getElementById('conteudo-conteudo2');
        const conteudoConteudo3 = document.getElementById('conteudo-conteudo3');
        const conteudoConteudo4 = document.getElementById('conteudo-conteudo4');
        const conteudoServicos = document.getElementById('conteudo-servicos');

        btnInicio.addEventListener('click', () => {
            conteudoInicio.style.display = 'block';
            conteudoConteudo1.style.display = 'none';
            conte

