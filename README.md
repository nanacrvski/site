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
        <div id="btn-conteudo1">Sistemas</div>
        <div id="btn-conteudo2">Matriz Inversa e Criptografia</div>
        <div id="btn-conteudo3">Funções trigonométricas</div>
        <div id="btn-conteudo4">Análise combinatória</div>
        <div id="btn-servicos">Autoavaliação</div>
    </nav>
    <div class="container" id="conteudo-inicio">
        <h2 style="color: #c2185b;">Início</h2>
        <p>Olá! Meu nome é Ana Clara N. Cervinski, sou do
segundo ano do ensino médio, e faço técnico em mecatrônica, este é meu portfólio do terceiro trimestre de matemática de 2023. Aqui falarei sobre as matérias estudadas durante esses meses. Juntamente com uma reflexão sobre mim mesma, e uma autoavaliação. Este portfólio é de extrema relevância para minha avaliação acadêmica, e me ajudará a analisar minha trajetória na diciplina de matemática, orientada pela docente Valéria Lessa. Com essa avaliação poderei gerenciar minhas tarefas perante a diciplina.  </p>
    </div>
    <div class="container" id="conteudo-conteudo1" style="display: none;">
        <h2 style="color: #c2185b;">Sistemas</h2>
    </div>
    <div class="container" id="conteudo-conteudo2" style="display: none;">
        <h2 style="color: #c2185b;">Matriz Inversa e Criptografia</h2>
        <p>Dada uma matriz quadrada A de ordem n, chamamos de inversa de A uma matriz A⁻¹ tal que</p>
       <p>𝐴 ∙ 𝐴⁻¹ = 𝐴⁻¹ ∙ 𝐴 = I</p>
        <p>Onde 𝐼 é a matriz identidade de ordem n.</p>
        <p>No caso das matrizes de ordem 2, vemos que há um padrão na posição dos elementos da matriz original em relação à sua inversa. Portanto, podemos deixar esse método mais prático fazendo o seguinte:</p>
        <ol>
            <li>(1º) Calcular o determinante da matriz dada;</li>
            <li>(2º) Multiplicar 1/det(𝐴) pela matriz dada;</li>
            <li>(3º) Mudar de posição os elementos da diagonal principal;</li>
            <li>(4º) Multiplicar por (-1) os elementos da diagonal secundária.</li>
        </ol> 
        <img src="https://i.pinimg.com/736x/ff/14/c4/ff14c463cc4fef7171059ffff7ae3605.jpg" alt="Matriz Inversa">
        <p>A INVERSA DE UMA MATRIZ DE ORDEM 3 USANDO SISTEMAS</p>
        <p>Para encontrar a inversa de uma matriz de ordem 3, usamos o mesmo procedimento feito anteriormente, usando 𝐴 ∙ 𝐴⁻¹ = I.</p>
        <img src="https://i.pinimg.com/736x/25/95/f3/2595f393edeb157daa274bd3001ac6cb.jpg" alt="Matriz Inversa">
        <p>A INVERSA DE UMA MATRIZ DE ORDEM 3 USANDO DETERMINANTES – REGRA PRÁTICA</p>
        <ol>
            <li>Calcular o determinante de A.</li>
            <li>Repetir as duas primeiras colunas da matriz dada e, depois, repetir as duas primeiras linhas, ficando uma matriz 5x5.</li>
            <li>Cancelar a primeira linha e primeira coluna.</li>
            <li>Realizar o determinante de matrizes 2x2 dentro desta matriz grande, conforme o desenho.</li>
            <li>Esses determinantes irão compor uma nova matriz 3x3, chamada de Matriz Adjunta. Mas CUIDADO! Os determinantes da mesma linha irão compor os elementos da coluna da nova matriz. </li>
            <li>Dividir cada elemento da matriz adjunta pelo determinante de A e chegamos na matriz inversa.</li>
        </ol>
        <img src="https://i.pinimg.com/736x/29/3d/c9/293dc9898215c0875617ec9952d977fd.jpg" alt="Matriz Inversa">
        <p>A CRIPTOGRAFIA</p>
         <img src="https://i.pinimg.com/736x/05/25/fc/0525fc28b4abbde738c54e8bb2f4012a.jpg" alt="Descrição da imagem de serviços">
    </div>
    <div class="container" id="conteudo-conteudo3" style="display: none;">
        <h2 style="color: #c2185b;">Funções trigonométricas</h2>
        <p>Muitos fenômenos naturais, físicos e sociais têm comportamento cíclico ou periódico (que se repetem a cada determinado período), podendo ser modelados por funções trigonométricas.</p>
         <p>Essas funções têm amplas aplicações em física, engenharia, computação gráfica e muitas outras áreas.</p>
         <img src="https://i.pinimg.com/564x/84/1c/0f/841c0fd84a99f62a26c81bc8b5163ce2.jpg" alt="Descrição da imagem de serviços">
         <p>FUNÇÃO SENO</p>
         <p>É a função de ℝ em ℝ que a cada x ∈ ℝ faz corresponder o número real 𝑠𝑒𝑛(𝑥), ou seja, 𝑓: ℝ → ℝ 𝑥 → 𝑓(𝑥) = 𝑠𝑒𝑛(𝑥)</p>
    </div>
    <div class="container" id="conteudo-conteudo4" style="display: none;">
        <h2 style="color: #c2185b;">Análise combinatória</h2>
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

