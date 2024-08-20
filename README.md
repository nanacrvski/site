<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ana + Lipe</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            background-color: #ffe6f2;
            color: #ff99cc;
            margin: 0;
            padding: 0;
        }

        header {
            background-color: #ff66b2;
            color: white;
            text-align: center;
            padding: 20px;
            font-size: 2.5em;
            font-family: 'Comic Sans MS', cursive, sans-serif;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }

        .container {
            max-width: 800px;
            margin: 20px auto;
            padding: 20px;
            background-color: white;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }

        .post {
            margin-bottom: 20px;
            padding: 20px;
            background-color: #ffe6f2;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }

        .post-title {
            font-size: 1.8em;
            color: #ff66b2;
        }

        .post-content {
            font-size: 1.2em;
            color: #ff99cc;
        }

        .footer {
            text-align: center;
            padding: 20px;
            background-color: #ff66b2;
            color: white;
            font-size: 1em;
            border-top-left-radius: 10px;
            border-top-right-radius: 10px;
        }

        .balloon {
            width: 30px;
            height: 50px;
            background-color: #ff66b2;
            border-radius: 50% 50% 50% 50%;
            position: relative;
            display: inline-block;
            margin: 5px;
        }

        .balloon:before {
            content: '';
            position: absolute;
            left: 50%;
            bottom: -20px;
            width: 2px;
            height: 20px;
            background-color: #ff66b2;
            transform: translateX(-50%);
        }

        .heart {
            width: 30px;
            height: 30px;
            background-color: #ff3399;
            position: relative;
            transform: rotate(-45deg);
            display: inline-block;
            margin: 5px;
        }

        .heart:before, .heart:after {
            content: '';
            width: 30px;
            height: 30px;
            background-color: #ff3399;
            position: absolute;
            border-radius: 50%;
        }

        .heart:before {
            top: -15px;
            left: 0;
        }

        .heart:after {
            top: 0;
            left: 15px;
        }
    </style>
</head>
<body>
    <header>
        Ana + Lipe
    </header>

    <div class="container">
        <div class="post">
            <div class="post-title">Nosso Primeiro Encontro</div>
            <div class="post-content">
                Aqui você pode compartilhar a história do primeiro encontro de vocês, como se sentiram e o que fizeram. Um dia para nunca esquecer!
            </div>
        </div>

        <div class="post">
            <div class="post-title">Viagem dos Sonhos</div>
            <div class="post-content">
                Um relato sobre a viagem mais incrível que vocês fizeram juntos. As lembranças e aventuras que compartilharam.
            </div>
        </div>
    </div>

    <div class="footer">
        <div class="balloon"></div>
        <div class="heart"></div>
        <div class="balloon"></div>
        <div class="heart"></div>
        <div class="balloon"></div>
        <p>Com amor, Ana</p>
    </div>
</body>
</html>
