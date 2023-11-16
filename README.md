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
            background-color: #fce4ec; /* Cor de fundo rosa claro */
            color: #333; /* Cor do texto escura */
        }

        header {
            background-color: #ff80ab; /* Cor de fundo rosa claro */
            color: #fff; /* Cor do texto branco */
            text-align: center;
            padding: 20px;
            border-bottom: 5px solid #e91e63; /* Cor de destaque mais escura */
        }

        nav {
            background-color: #ffcdd2; /* Cor de fundo rosa claro */
            text-align: center;
            padding: 10px;
        }

        nav a {
            text-decoration: none;
            color: #e91e63; /* Cor rosa mais escura */
            padding: 10px 20px;
            margin: 0 5px;
            border-radius: 5px;
            background-color: #fff; /* Cor de fundo branca */
            transition: background-color 0.3s ease, color 0.3s ease;
        }

        nav a:hover {
            background-color: #e91e63; /* Cor de fundo rosa mais escura ao passar o mouse */
            color: #fff; /* Cor do texto branco ao passar o mouse */
        }

        .container {
            padding: 20px;
            display: none;
            background-color: #fff; /* Cor de fundo branca */
            border-radius: 10px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1); /* Sombra suave */
            margin: 20px 0;
        }

        /* Adicionando estilo específico para cada seção */
        #conteudo-inicio {
            background-color: #fce4ec; /* Cor de fundo rosa claro */
        }

        #conteudo-conteudo1 {
            background-color: #f8bbd0; /* Cor de fundo rosa mais claro */
        }

        #conteudo-conteudo2 {
            background-color: #ffab91; /* Cor de fundo laranja claro */
        }

        #conteudo-conteudo3 {
            background-color: #ffccbc; /* Cor de fundo pêssego claro */
        }

        #conteudo-conteudo4 {
            background-color: #ffab91; /* Cor de fundo laranja claro */
        }

        #conteudo-servicos {
            background-color: #f8bbd0; /* Cor de fundo rosa mais claro */
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
        <h1 style="color: #c2185b;">Bem-vindo ao Meu Portfólio de Matemática</h1>
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
        <h2 style="color: #c2185b;">Início</h2>
        <p>Esta é a página inicial do nosso site.</p>
         <img src=data:image/jpeg;base64,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
    </div>
    <div class="container" id="conteudo-conteudo1" style="display: none;">
        <h2 style="color: #c2185b;">Conteúdo 1</h2>
        <p>Aqui apresentamos os principais conceitos do primeiro conteúdo do terceiro trimestre de matemática.</p>
        <!-- Adicione informações específicas sobre o Conteúdo 1 aqui -->
    </div>
    <div class="container" id="conteudo-conteudo2" style="display: none;">
        <h2 style="color: #c2185b;">Conteúdo 2</h2>
        <p>Explore os desafios e aplicações do segundo conteúdo do terceiro trimestre de matemática.</p>
        <!-- Adicione informações específicas sobre o Conteúdo 2 aqui -->
    </div>
    <div class="container" id="conteudo-conteudo3" style="display: none;">
        <h2 style="color: #c2185b;">Conteúdo 3</h2>
        <p>Descubra as teorias e práticas do terceiro conteúdo do terceiro trimestre de matemática.</p>
        <!-- Adicione informações específicas sobre o Conteúdo 3 aqui -->
    </div>
    <div class="container" id="conteudo-conteudo4" style="display: none;">
        <h2 style="color: #c2185b;">Conteúdo 4</h2>
        <p>Analise os casos e estudos relacionados ao quarto conteúdo do terceiro trimestre de matemática.</p>
        <!-- Adicione informações específicas sobre o Conteúdo 4 aqui -->
    </div>
    <div class="container" id="conteudo-servicos" style="display: none;">
        <h2 style="color: #c2185b;">Autoavaliação</h2>
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
            conteudoConteudo2.style.display = 'none';
            conteudoConteudo3.style.display = 'none';
            conteudoConteudo4.style.display = 'none';
            conteudoServicos.style.display = 'none';
        });

        btnConteudo1.addEventListener('click', () => {
            conteudoInicio.style.display = 'none';
            conteudoConteudo1.style.display = 'block';
            conteudoConteudo2.style.display = 'none';
            conteudoConteudo3.style.display = 'none';
            conteudoConteudo4.style.display = 'none';
            conteudoServicos.style.display = 'none';
        });

        btnConteudo2.addEventListener('click', () => {
            conteudoInicio.style.display = 'none';
            conteudoConteudo1.style.display = 'none';
            conteudoConteudo2.style.display = 'block';
            conteudoConteudo3.style.display = 'none';
            conteudoConteudo4.style.display = 'none';
            conteudoServicos.style.display = 'none';
        });

        btnConteudo3.addEventListener('click', () => {
            conteudoInicio.style.display = 'none';
            conteudoConteudo1.style.display = 'none';
            conteudoConteudo2.style.display = 'none';
            conteudoConteudo3.style.display = 'block';
            conteudoConteudo4.style.display = 'none';
            conteudoServicos.style.display = 'none';
        });

        btnConteudo4.addEventListener('click', () => {
            conteudoInicio.style.display = 'none';
            conteudoConteudo1.style.display = 'none';
            conteudoConteudo2.style.display = 'none';
            conteudoConteudo3.style.display = 'none';
            conteudoConteudo4.style.display = 'block';
            conteudoServicos.style.display = 'none';
        });

        btnServicos.addEventListener('click', () => {
            conteudoInicio.style.display = 'none';
            conteudoConteudo1.style.display = 'none';
            conteudoConteudo2.style.display = 'none';
            conteudoConteudo3.style.display = 'none';
            conteudoConteudo4.style.display = 'none';
            conteudoServicos.style.display = 'block';
        });
    </script>
</body>
</html>

