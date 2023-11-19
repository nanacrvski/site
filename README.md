<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Meu Portfólio - Matemática</title>
    <link href="https://fonts.googleapis.com/css2?family=Caveat:wght@400;700&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Caveat', sans-serif;
            margin: 0;
            padding: 0;
            background: url('https://www.arquiprojeto.art.br/wp-content/uploads/2022/02/floral-22.jpg') fixed;
            /* Substitua pelo caminho do seu papel de parede */
            background-size: cover;
            color: #333;
            /* Cor do texto escura */
        }

        header {
            background-color: #ff80ab;
            /* Cor de fundo rosa claro */
            color: #fff;
            /* Cor do texto branco */
            text-align: center;
            padding: 20px;
            border-bottom: 5px solid #e91e63;
            /* Cor de destaque mais escura */
        }

        nav {
            background-color: #ffcdd2;
            /* Cor de fundo rosa claro */
            text-align: center;
            padding: 10px;
            display: flex;
            justify-content: center;
            /* Centraliza os elementos horizontalmente */
        }

        nav a {
            text-decoration: none;
            color: #e91e63;
            /* Cor rosa mais escura */
            padding: 10px 20px;
            margin: 0 5px;
            border-radius: 15px;
            /* Bordas redondas */
            background-color: #fff4f8;
            /* Cor de fundo rosa claro */
            transition: background-color 0.3s ease, color 0.3s ease;
        }

        nav a:hover {
            background-color: #e91e63;
            /* Cor de fundo rosa mais escura ao passar o mouse */
            color: #fff;
            /* Cor do texto branco ao passar o mouse */
        }

        #btn-servicos {
            text-decoration: none;
            color: #e91e63;
            /* Cor rosa mais escura */
            padding: 10px 20px;
            margin: 0 5px;
            border-radius: 15px;
            /* Bordas redondas */
            background-color: #fff4f8;
            /* Cor de fundo rosa claro */
            transition: background-color 0.3s ease, color 0.3s ease;
            margin-bottom: 20px;
            /* Adicione margem na parte inferior para evitar sobreposição */
        }

        .container {
            padding: 20px;
            display: none;
            background-color: #fff4f8;
            /* Cor de fundo rosa mais claro */
            border-radius: 20px;
            /* Bordas redondas */
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
            /* Sombra suave */
            margin: 20px 0;
        }

        /* Adicionando estilo específico para cada seção */
        #conteudo-inicio {
            background-color: #fff4f8;
            /* Cor de fundo rosa mais claro */
        }

        #conteudo-conteudo1 {
            background-color: #f8bbd0;
            /* Cor de fundo rosa mais claro */
        }

        #conteudo-conteudo2 {
            background-color: #ffab91;
            /* Cor de fundo laranja claro */
        }

        #conteudo-conteudo3 {
            background-color: #ffccbc;
            /* Cor de fundo pêssego claro */
        }

        #conteudo-conteudo4 {
            background-color: #ffab91;
            /* Cor de fundo laranja claro */
        }

        #conteudo-servicos {
            background-color: #f8bbd0;
            /* Cor de fundo rosa mais claro */
        }

        .button {
            display: inline-block;
            padding: 10px 20px;
            color: #fff;
            /* Cor do texto branco */
            background-color: #e91e63;
            /* Cor de fundo rosa */
            text-decoration: none;
            border-radius: 20px;
            /* Bordas redondas */
            transition: background-color 0.3s ease;
        }

        .button:hover {
            background-color: #c2185b;
            /* Cor de fundo rosa mais escura ao passar o mouse */
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

        <p>A matriz inversa é uma operação importante na álgebra linear. Ela é usada em diversos contextos, incluindo criptografia. Na criptografia, as matrizes são utilizadas para transformar dados de forma a proteger a informação.</p>

        <p><strong>IMPORTANTE!</strong></p>
        <ol>
            <li>Se A e B são matrizes quadradas de mesma ordem, ambas inversíveis, então 𝐴 × 𝐵 é inversível e (𝐴 × 𝐵)ˆ−1 = 𝐵ˆ−1 × 𝐴ˆ−1.</li>
            <li>Nem toda matriz admite inversa.</li>
            <li>A inversa de uma matriz é única.</li>
        </ol>
        <p>Teorema: Uma matriz quadrada A admite inversa se, e somente se, 𝑑𝑒𝑡(𝐴) ≠ 0.</p>

        <p>As propriedades da matriz inversa garantem que seja possível reverter a transformação, permitindo a recuperação dos dados originais apenas com a matriz inversa correta.</p>

        <img src="https://static.preparaenem.com/conteudo_legenda/d41c6cf1bc5500915e432ff23fb9a7cc.jpg" alt="Matriz Inversa">
        <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQwOnhYFZTmTvi9B-gdpRY3RFLc67zyHqEwvg&usqp=CAU" alt="Criptografia">
    </div>
    <div class="container" id="conteudo-conteudo2" style="display: none;">
        <!-- Adicione informações e imagens para o conteúdo 2 aqui -->
    </div>
    <div class="container" id="conteudo-conteudo3" style="display: none;">
        <!-- Adicione informações e imagens para o conteúdo 3 aqui -->
    </div>
    <div class="container" id="conteudo-conteudo4" style="display: none;">
        <!-- Adicione informações e imagens para o conteúdo 4 aqui -->
    </div>
    <div class="container" id="conteudo-servicos" style="display: none;">
        <!-- Adicione informações e imagens para a autoavaliação aqui -->
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


