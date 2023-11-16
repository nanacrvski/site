<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Meu Portfólio - Matemática</title>
    <link rel="stylesheet" href="styles.css">
    <style>
        body {
            font-family: 'Arial', sans-serif;
            margin: 0;
            padding: 0;
            background-color: #fff; /* Cor de fundo branca */
            color: #333; /* Cor do texto escura */
        }

        header {
            background-color: #e91e63; /* Cor de fundo rosa */
            color: #fff; /* Cor do texto branco */
            text-align: center;
            padding: 20px;
        }

        nav {
            background-color: #f8bbd0; /* Cor de fundo rosa claro */
            text-align: center;
            padding: 10px;
        }

        nav a {
            text-decoration: none;
            color: #333; /* Cor do texto escura */
            padding: 10px 20px;
            margin: 0 5px;
            border-radius: 5px;
            background-color: #fff; /* Cor de fundo branca */
        }

        .container {
            padding: 20px;
            display: none;
        }

        /* Adicionando estilo específico para cada seção */
        #conteudo-inicio {
            background-color: #fce4ec; /* Cor de fundo rosa claro */
        }

        #conteudo-conteudo1 {
            background-color: #f48fb1; /* Cor de fundo rosa mais escuro */
        }

        #conteudo-conteudo2 {
            background-color: #ec407a; /* Cor de fundo rosa médio */
        }

        #conteudo-conteudo3 {
            background-color: #d81b60; /* Cor de fundo rosa mais escuro */
        }

        #conteudo-conteudo4 {
            background-color: #c2185b; /* Cor de fundo rosa mais escuro */
        }

        #conteudo-servicos {
            background-color: #f48fb1; /* Cor de fundo rosa mais escuro */
        }

        .button {
            display: inline-block;
            padding: 10px 20px;
            color: #fff; /* Cor do texto branco */
            background-color: #e91e63; /* Cor de fundo rosa */
            text-decoration: none;
            border-radius: 5px;
            transition: background-color 0.3s ease;
        }

        .button:hover {
            background-color: #c2185b; /* Cor de fundo rosa mais escura ao passar o mouse */
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
            // Adicione mais conteúdos se necessário
            conteudoInicio.style.display = 'block';
            conteudoConteudo1.style.display = 'none';
           



