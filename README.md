<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Dia dos Namorados</title>
    <link rel="stylesheet" href="css/style.css">
    <style>
        body {
            background-color: #ffe6e6; /* Rosa claro */
            font-family: Arial, sans-serif;
            color: #333; /* Cor do texto */
            padding: 0;
            margin: 0;
        }
        header {
            background-color: #ff99cc; /* Rosa médio */
            padding: 20px;
            text-align: center;
        }
        main {
            padding: 20px;
        }
        h1 {
            color: #660066; /* Rosa escuro */
        }
        h2 {
            color: #ff1a75; /* Rosa brilhante */
        }
        p {
            line-height: 1.6;
        }
        #gallery {
            display: flex;
            flex-wrap: wrap;
            justify-content: space-around;
        }
        .image-container {
            width: 200px; /* Tamanho das imagens */
            margin-bottom: 20px;
            text-align: center;
        }
        .image-container img {
            max-width: 100%;
            border-radius: 10px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1); /* Sombra suave */
        }
        footer {
            background-color: #ff99cc; /* Rosa médio */
            padding: 20px;
            text-align: center;
            position: fixed;
            bottom: 0;
            width: 100%;
        }
    </style>
</head>
<body>
    <header>
        <h1>Feliz Dia dos Namorados!</h1>
    </header>

    <main>
        <section id="intro">
            <h2>Meu Amor por Você é Infinito</h2>
            <p>Em cada batida do meu coração, encontro o ritmo do seu.</p>
        </section>

        <section id="gallery">
            <!-- Espaço para fotos -->
            <div class="image-container">
                <img src="caminho-da-imagem1.jpg" alt="Descrição da imagem 1">
                <div class="image-overlay"></div>
            </div>
            <div class="image-container">
                <img src="caminho-da-imagem2.jpg" alt="Descrição da imagem 2">
                <div class="image-overlay"></div>
            </div>
            <div class="image-container">
                <img src="caminho-da-imagem3.jpg" alt="Descrição da imagem 3">
                <div class="image-overlay"></div>
            </div>
            <!-- Adicione mais imagens conforme necessário -->
        </section>
    </main>

    <footer>
        <p>Feito com ❤️ por [Seu Nome]</p>
    </footer>
</body>
</html>


