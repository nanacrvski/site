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

        nav a {
            text-decoration: none;
            color: #e91e63;
            padding: 10px 20px;
            margin: 0 5px;
            border-radius: 15px;
            background-color: #fff4f8;
            transition: background-color 0.3s ease, color 0.3s ease;
        }

        nav a:hover {
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
            height: auto;
            border-radius: 10px;
            margin-top: 10px;
        }

        .container ol {
            margin-bottom: 10px;
        }

        .container li {
            margin-bottom: 5px;
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
        <p>Dada uma matriz quadrada A de ordem n, chamamos de inversa de A uma matriz A⁻¹ tal que</p>
        <p>𝐴 ∙ 𝐴⁻¹ = 𝐴⁻¹ ∙ 𝐴 = I</p>
         <p>onde 𝐼 é a matriz identidade de ordem n.</p>
        <p>No caso das matrizes de ordem 2, vemos que há um padrão na posição dos elementos da matriz original em relação à sua inversa. Portanto, podemos deixar esse método mais prático fazendo o seguinte:</p>
        <ol>
            <li>(1º) Calcular o determinante da matriz dada;</li>
            <li>(2º) Multiplicar 1/det(𝐴) pela matriz dada;</li>
            <li>(3º) Mudar de posição os elementos da diagonal principal;</li>
            <li>(4º) Multiplicar por (-1) os elementos da diagonal secundária.</li>
        </ol> 
        <img src="https://static.preparaenem.com/conteudo_legenda/d41c6cf1bc5500915e432ff23fb9a7cc.jpg" alt="Matriz Inversa">
        <p>A INVERSA DE UMA MATRIZ DE ORDEM 3 USANDO SISTEMAS</p>
         <p>Para encontrar a inversa de uma matriz de ordem 3 usamos mesmo o
procedimento feito anteriormente, usando 𝐴 ∙ 𝐴⁻¹ = I</p>
        <img src="https://static.preparaenem.com/conteudo_legenda/d41c6cf1bc5500915e432ff23fb9a7cc.jpg" alt="Matriz Inversa">
         <p>A A INVERSA DE UMA MATRIZ DE ORDEM 3 USANDO DETERMINANTES – REGRA PRÁTICA</p>
          <ol>
            <li> Calcular o determinante de A.
            <li> Repetir as duas primeiras colunas da matriz dada e, depois, repetir as duas primeiras linhas, ficando uma matriz 5x5.
            <li> Cancelar a primeira linha e primeira coluna.
            <li> Realizar o determinante de matrizes 2x2 dentro desta matriz grande, conforme o desenho.
            <li> Esses determinantes irão compor uma nova matriz 3x3, chamada de Matriz Adjunta. Mas CUIDADO! Os determinantes da mesma linha irão compor os elementos da coluna da nova matriz.
           6) Dividir cada elemento da matriz adjunta pelo determinante de A e chegamos na matriz inversa.</li>
        <img src="https://static.preparaenem.com/conteudo_legenda/d41c6cf1bc5500915e432ff23fb9a7cc.jpg" alt="Matriz Inversa">
    <div class="container" id="conteudo-conteudo2" style="display: none;">
        <h2 style="color: #c2185b;">Funções Trigonométricas</h2>
        <p>As funções trigonométricas são fundamentais na matemática, especialmente na trigonometria. Elas descrevem as relações entre os ângulos de um triângulo e as medidas dos seus lados. As principais funções trigonométricas são seno, cosseno e tangente.</p>
        <p>Essas funções têm amplas aplicações em física, engenharia, computação gráfica e muitas outras áreas.</p>
        <img src="caminho/para/sua/imagem2.jpg" alt="Funções Trigonométricas">
    </div>
    <div class="container" id="conteudo-conteudo3" style="display: none;">
        <h2 style="color: #c2185b;">Análise Combinatória</h2>
        <p>A análise combinatória é um ramo da matemática que estuda métodos de contagem e organização de elementos. Envolve a análise e a resolução de problemas relacionados à combinação e arranjo de objetos.</p>
        <p>Essa área é amplamente utilizada em situações que envolvem contagem de possibilidades, como em jogos, probabilidades e otimização.</p>
        <img src="caminho/para/sua/imagem3.jpg" alt="Análise Combinatória">
    </div>
    <div class="container" id="conteudo-conteudo4" style="display: none;">
        <h2 style="color: #c2185b;">Conteúdo 4</h2>
        <p>Este é um espaço reservado para informações sobre o quarto conteúdo do terceiro trimestre de matemática.</p>
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

