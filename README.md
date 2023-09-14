<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Meu Site</title>
    <link rel="stylesheet" href="styles.css">
    <style>
        /* Estilos CSS aqui (mantive os estilos existentes) */
    </style>
</head>
<body>
    <header>
        <h1>Bem-vindo ao Meu Site</h1>
    </header>
    <nav>
        <a href="#" id="btn-inicio">Início</a>
        <a href="#" id="btn-sobre">Sobre</a>
        <a href="#" id="btn-servicos">Serviços</a>
        <a href="#" id="btn-contato">Contato</a>
    </nav>
    <div class="container" id="conteudo-inicio">
        <h2>Início</h2>
        <p>Esta é a página inicial do nosso site.</p>
    </div>
    <div class="container" id="conteudo-sobre" style="display: none;">
        <h2>Sobre Nós</h2>
        <p>Somos uma equipe de profissionais apaixonados por tecnologia e design.</p>
        <p>Nosso objetivo é criar soluções incríveis para nossos clientes.</p>
        <a href="#" class="button" id="btn-saiba-mais-sobre">Saiba Mais</a>
    </div>
    <div class="container" id="conteudo-servicos" style="display: none;">
        <h2>Serviços</h2>
        <p>Oferecemos uma variedade de serviços de alta qualidade.</p>
        <p>Entre em contato conosco para saber mais sobre nossos serviços.</p>
    </div>
    <div class="container" id="conteudo-contato" style="display: none;">
        <h2>Contato</h2>
        <p>Entre em contato conosco através do formulário abaixo:</p>
        <form>
            <label for="nome">Nome:</label>
            <input type="text" id="nome" name="nome"><br><br>
            <label for="email">Email:</label>
            <input type="text" id="email" name="email"><br><br>
            <textarea id="mensagem" name="mensagem" rows="4" cols="50" placeholder="Digite sua mensagem aqui..."></textarea><br><br>
            <input type="submit" value="Enviar">
        </form>
    </div>

    <script>
        // JavaScript para controlar a exibição das seções
        const btnInicio = document.getElementById('btn-inicio');
        const btnSobre = document.getElementById('btn-sobre');
        const btnServicos = document.getElementById('btn-servicos');
        const btnContato = document.getElementById('btn-contato');
        const conteudoInicio = document.getElementById('conteudo-inicio');
        const conteudoSobre = document.getElementById('conteudo-sobre');
        const conteudoServicos = document.getElementById('conteudo-servicos');
        const conteudoContato = document.getElementById('conteudo-contato');

        btnInicio.addEventListener('click', () => {
            conteudoInicio.style.display = 'block';
            conteudoSobre.style.display = 'none';
            conteudoServicos.style.display = 'none';
            conteudoContato.style.display = 'none';
        });

        btnSobre.addEventListener('click', () => {
            conteudoInicio.style.display = 'none';
            conteudoSobre.style.display = 'block';
            conteudoServicos.style.display = 'none';
            conteudoContato.style.display = 'none';
        });

        btnServicos.addEventListener('click', () => {
            conteudoInicio.style.display = 'none';
            conteudoSobre.style.display = 'none';
            conteudoServicos.style.display = 'block';
            conteudoContato.style.display = 'none';
        });

        btnContato.addEventListener('click', () => {
            conteudoInicio.style.display = 'none';
            conteudoSobre.style.display = 'none';
            conteudoServicos.style.display = 'none';
            conteudoContato.style.display = 'block';
        });
    </script>
</body>
</html>
