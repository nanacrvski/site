<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Dia dos Namorados</title>
    <link rel="stylesheet" href="css/style.css">
    <style>
        body {
            background-color: #fde6ea; /* Rosa claro */
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
            text-align: center;
        }
        h1 {
            color: #660066; /* Rosa escuro */
            margin-top: 0;
        }
        h2 {
            color: #ff1a75; /* Rosa brilhante */
        }
        p {
            line-height: 1.6;
            margin-bottom: 20px;
        }
        #gallery {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(200px, 1fr));
            grid-gap: 20px;
            justify-items: center;
            align-items: center;
            margin-top: 20px;
        }
        .image-container {
            position: relative;
            width: 100%;
            height: 0;
            padding-top: 100%;
            overflow: hidden;
            border-radius: 10px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1); /* Sombra suave */
        }
        .image-container img {
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            object-fit: cover;
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
            </div>
            <div class="image-container">
                <img src="caminho-da-imagem2.jpg" alt="Descrição da imagem 2">
            </div>
            <div class="image-container">
                <img src="caminho-da-imagem3.jpg" alt="Descrição da imagem 3">
            </div>
            <!-- Adicione mais imagens conforme necessário -->
        </section>
    </main>

    <footer>
        <p>Feito com ❤️ por [Seu Nome]</p>
    </footer>
</body>
</html>


