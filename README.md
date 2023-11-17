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
            background: url('caminho/para/seu/papel-de-parede.jpg') fixed; /* Substitua pelo caminho do seu papel de parede */
            background-size: cover;
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
            display: flex;
            justify-content: center; /* Centraliza os elementos horizontalmente */
        }

        nav a {
            text-decoration: none;
            color: #e91e63; /* Cor rosa mais escura */
            padding: 10px 20px;
            margin: 0 5px;
            border-radius: 15px; /* Bordas redondas */
            background-color: #fff4f8; /* Cor de fundo rosa claro */
            transition: background-color 0.3s ease, color 0.3s ease;
        }

        nav a:hover {
            background-color: #e91e63; /* Cor de fundo rosa mais escura ao passar o mouse */
            color: #fff; /* Cor do texto branco ao passar o mouse */
        }

        #btn-servicos {
            text-decoration: none;
            color: #e91e63; /* Cor rosa mais escura */
            padding: 10px 20px;
            margin: 0 5px;
            border-radius: 15px; /* Bordas redondas */
            background-color: #fff4f8; /* Cor de fundo rosa claro */
            transition: background-color 0.3s ease, color 0.3s ease;
            margin-bottom: 20px; /* Adicione margem na parte inferior para evitar sobreposição */
        }

        .container {
            padding: 20px;
            display: none;
            background-color: #fff4f8; /* Cor de fundo rosa mais claro */
            border-radius: 20px; /* Bordas redondas */
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1); /* Sombra suave */
            margin: 20px 0;
        }

        /* Adicionando estilo específico para cada seção */
        #conteudo-inicio {
            background-color: #fff4f8; /* Cor de fundo rosa mais claro */
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
            border-radius: 20px; /* Bordas redondas */
            transition: background-color 0.3s ease;
        }

        .button:hover {
            background-color: #c2185b; /* Cor de fundo rosa mais escura ao passar o mouse */
        }
    </style>
</head>
<body>
    <header>
        <h1 style="color: #fff;">Bem-vindo ao Meu Portfólio de Matemática</h1>
    </header>
    <nav>
        <a href="#" id="btn-inicio">Início</a>
        <a href="#" id="btn-conteudo1">Matriz Inversa e Criptografia</a>
        <a href="#" id="btn-conteudo2">Funções Trigonométricas</a>
        <a href="#" id="btn-conteudo3">Análise Combinatória</a>
        <a href="#" id="btn-conteudo4">Conteúdo 4</a>
        <a href="#" id="btn-servicos">Autoavaliação</a>
    </nav>
    <div class="container" id="conteudo-inicio">
        <h2 style="color: #c2185b;">Início</h2>
        <p>Esta é a página inicial do nosso site.</p>
    </div>
    <div class="container" id="conteudo-conteudo1" style="display: none;">
        <h2 style="color: #c2185b;">Matriz Inversa e Criptografia</h2>
        <p>Aqui apresentamos os principais conceitos do primeiro conteúdo do terceiro trimestre de matemática.</p>
        <img src="caminho/para/sua/imagem1.jpg" alt="Descrição da imagem 1">
    </div>
    <div class="container" id="conteudo-conteudo2" style="display: none;">
        <h2 style="color: #c2185b;">Funções Trigonométricas</h2>
        <p>Explore os desafios e aplicações do segundo conteúdo do terceiro trimestre de matemática.</p>
        <img src="caminho/para/sua/imagem2.jpg" alt="Descrição da imagem 2">
    </div>
    <div class="container" id="conteudo-conteudo3" style="display: none;">
        <h2 style="color: #c2185b;">Análise Combinatória</h2>
        <p>Descubra as teorias e práticas do terceiro conteúdo do terceiro trimestre de matemática.</p>
        <img src="caminho/para/sua/imagem3.jpg" alt="Descrição da imagem 3">
    </div>
    <div class="container" id="conteudo-conteudo4" style="display: none;">
        <h2 style="color: #c2185b;">Conteúdo 4</h2>
        <p>Analise os casos e estudos relacionados ao quarto conteúdo do terceiro trimestre de matemática.</p>
        <img src="caminho/para/sua/imagem4.jpg" alt="Descrição da imagem 4">
    </div>
    <div class="container" id="conteudo-servicos" style="display: none;">
        <h2 style="color: #c2185b;">Autoavaliação</h2>
        <p>Confira minha autoavaliação e meu progresso.</p>
        <img src="caminho/para/sua/imagem-servicos.jpg" alt="Descrição da imagem de serviços">
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



