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
            background-color: #f8f0f4; /* Cor de fundo rosa claro */
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
            display: flex;
            align-items: center;
        }

        nav a img {
            margin-right: 10px;
            max-width: 20px; /* Ajuste o tamanho conforme necessário */
            max-height: 20px; /* Ajuste o tamanho conforme necessário */
        }

        .container {
            padding: 20px;
            display: none;
            background-color: #fff; /* Cor de fundo branca */
            border-radius: 10px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1); /* Sombra suave */
            margin: 20px 0;
        }

        /* Adicionando estilo específico para cada seção ... (código anterior) */

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
        <a href="#" id="btn-inicio">
            <img src="caminho/para/imagem1.jpg" alt="Ícone Início"> Início
        </a>
        <a href="#" id="btn-conteudo1">
            <img src="caminho/para/imagem2.jpg" alt="Ícone Conteúdo 1"> Conteúdo 1
        </a>
        <!-- Adicione imagens aos demais botões conforme necessário -->
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
    <!-- Adicione mais seções conforme necessário -->
    <script>
        // JavaScript para controlar a exibição das seções ... (código anterior)
    </script>
</body>
</html>

