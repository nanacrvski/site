<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Meu Portfólio - Matemática</title>
    <link href="https://fonts.googleapis.com/css2?family=Caveat:wght@400;700&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.3/css/all.min.css">
    <style>
        body {
            font-family: 'Caveat', sans-serif;
            font-size: 16px;
            line-height: 1.6;
            margin: 0;
            padding: 0;
            background: url('https://wallpapercave.com/wp/wp5247710.png') fixed;
            background-size: cover;
            color: #333;
        }

        header {
            background-color: #ff80ab;
            color: #fff;
            text-align: center;
            padding: 20px;
            border-bottom: 5px solid #e91e63;
        }

        nav {
            background-color: #ffcdd2;
            text-align: center;
            padding: 10px;
            display: flex;
            justify-content: center;
        }

        nav div {
            text-decoration: none;
            color: #e91e63;
            padding: 10px 20px;
            margin: 0 5px;
            border-radius: 15px;
            background-color: #fff4f8;
            transition: background-color 0.3s ease, color 0.3s ease;
            cursor: pointer;
        }

        nav div:hover {
            background-color: #e91e63;
            color: #fff;
        }

        .container {
            padding: 20px;
            display: none;
            background-color: #fff4f8;
            border-radius: 20px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
            margin: 20px 0;
        }

        .container img {
            max-width: 100%;
            max-height: 100%;
            border-radius: 10px;
            margin-top: 10px;
        }

        #conteudo-inicio {
            background-color: #fff4f8;
        }

        #conteudo-conteudo1 {
            background-color: #f8bbd0;
        }

        #conteudo-conteudo2 {
            background-color: #ffab91;
        }

        #conteudo-conteudo3 {
            background-color: #ffccbc;
        }

        #conteudo-conteudo4 {
            background-color: #ffab91;
        }

        #conteudo-servicos {
            background-color: #f8bbd0;
        }

        .button {
            display: inline-block;
            padding: 10px 20px;
            color: #fff;
            background-color: #e91e63;
            text-decoration: none;
            border-radius: 20px;
            transition: background-color 0.3s ease;
            cursor: pointer;
        }

        .button:hover {
            background-color: #c2185b;
        }
    </style>
</head>

<body>
    <header>
        <h1 style="color: #fff;">Bem-vindo ao Meu Portfólio de Matemática</h1>
    </header>
    <nav>
        <div id="btn-inicio">Início</div>
        <div id="btn-conteudo1">Matriz Inversa e Criptografia</div>
        <div id="btn-conteudo2">Funções Trigonométricas</div>
        <div id="btn-conteudo3">Análise Combinatória</div>
        <div id="btn-conteudo4">Conteúdo 4</div>
        <div id="btn-servicos">Autoavaliação</div>
    </nav>
    <div class="container" id="conteudo-inicio">
        <h2 style="color: #c2185b;">Início</h2>
        <p>Esta é a página inicial do nosso site.</p>
    </div>
    <div class="container" id="conteudo-conteudo1" style="display: none;">
        <h2 style="color: #c2185b;">Matriz Inversa e Criptografia</h2>
        <p>Dada uma matriz quadrada A de ordem n, chamamos de inversa de A uma matriz A⁻¹ tal que</p>
        <!-- Conteúdo restante da seção 1 -->
    </div>
    <div class="container" id="conteudo-conteudo2" style="display: none;">
        <h2 style="color: #c2185b;">Funções Trigonométricas</h2>
        <p>Muitos fenômenos naturais, físicos e sociais têm comportamento cíclico ou periódico (que se repetem a cada determinado período), podendo ser modelados por funções trigonométricas.</p>
        <!-- Conteúdo restante da seção 2 -->
    </div>
    <div class="container" id="conteudo-conteudo3" style="display: none;">
        <h2 style="color: #c2185b;">Análise Combinatória</h2>
        <p>A análise combinatória é um ramo da matemática que estuda métodos de contagem e organização de elementos.</p>
        <!-- Conteúdo restante da seção 3 -->
    </div>
    <div class="container" id="conteudo-conteudo4" style="display: none;">
        <h2 style="color: #c2185b;">Conteúdo 4</h2>
        <p>Este é um espaço reservado para informações sobre o quarto conteúdo do terceiro trimestre de matemática.</p>
        <!-- Conteúdo restante da seção 4 -->
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

