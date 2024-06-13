<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Dia dos Namorados</title>
    <link rel="stylesheet" href="css/style.css">
</head>
<body>
    <header>
        <h1>Feliz Dia dos Namorados!</h1>
    </header>

    <main>
        <section id="intro">
            <h2>Seu amor é único!</h2>
            <p>Adicione uma mensagem especial aqui.</p>
        </section>

        <section id="gallery">
            <!-- Espaço para fotos -->
            <img src="caminho-da-imagem1.jpg" alt="Descrição da imagem 1">
            <img src="caminho-da-imagem2.jpg" alt="Descrição da imagem 2">
            <img src="caminho-da-imagem3.jpg" alt="Descrição da imagem 3">
            <!-- Adicione mais imagens conforme necessário -->
        </section>
    </main>

    <footer>
        <p>Feito com ❤️ por [Seu Nome]</p>
    </footer>
</body>
</html>
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f8f8f8;
}

header {
    background-color: #ff69b4; /* rosa */
    color: white;
    padding: 20px;
    text-align: center;
}

main {
    max-width: 800px;
    margin: 20px auto;
    padding: 0 20px;
}

h1 {
    margin: 0;
}

#intro {
    margin-bottom: 30px;
}

#gallery {
    display: flex;
    flex-wrap: wrap;
    justify-content: space-between;
}

footer {
    text-align: center;
    padding: 20px;
    background-color: #ff69b4; /* rosa */
    color: white;
}





