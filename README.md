<html lang="pt-br">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Site da Anac</title>

  <style>
    @import url('https://fonts.googleapis.com/css2?family=Fredoka:wght@400;500;700&family=Press+Start+2P&family=Pixelify+Sans:wght@400;700&display=swap');

    * {
      box-sizing: border-box;
    }

    body {
      margin: 0;
      min-height: 100vh;
      background:
        linear-gradient(
          120deg,
          rgba(0, 0, 0, 0.82),
          rgba(40, 26, 34, 0.76),
          rgba(0, 0, 0, 0.82)
        ),
        url("https://i.pinimg.com/736x/2e/6e/14/2e6e14261aadfde2c2dc7627aac2557f.jpg");
      background-size: cover;
      background-position: center;
      background-attachment: fixed;
      font-family: "Fredoka", sans-serif;
      display: flex;
      justify-content: center;
      align-items: center;
    }

    .window {
      width: 700px;
      padding: 15px;
      background: linear-gradient(
        135deg,
        #090909,
        #1c171a,
        #30252b
      );
      border: 2px solid #f2b8d1;
      border-radius: 25px;
      box-shadow:
        0 0 18px rgba(242, 184, 209, 0.75),
        0 0 10px rgba(255, 218, 234, 0.65),
        inset 0 0 15px rgba(255, 218, 234, 0.15);
    }

    /* TOPO */

    .top {
      height: 55px;
      background: linear-gradient(
        90deg,
        #111111,
        #dca4bd,
        #f2bfd5,
        #dca4bd,
        #111111
      );
      border: 1px solid #ffd8e8;
      border-radius: 20px;
      display: flex;
      justify-content: center;
      align-items: center;
      position: relative;
      color: #ffffff;
      font-size: 22px;
      text-shadow:
        0 0 5px #2b1821,
        0 0 8px #f2b8d1;
    }

    .buttons {
      position: absolute;
      right: 20px;
      display: flex;
      gap: 10px;
    }

   .circle {
  width: 35px;
  height: 35px;
  border: 1px solid #e7c7d5;
  border-radius: 50%;
  background: #f6dfe9;
  cursor: pointer;
  box-shadow:
    inset 0 1px 2px rgba(255,255,255,0.35),
    0 1px 3px rgba(0,0,0,0.08);
  transition: .2s;
}

.circle:hover {
  background: #fae9f0;
}
    /* MENU */

    .nav {
      display: flex;
      gap: 12px;
      margin: 18px 10px;
    }

    .nav button {
      flex: 1;
      padding: 12px;
      border: 1px solid #f4c6da;
      border-radius: 30px;
      background: linear-gradient(
        90deg,
        #121212,
        #dca4bd,
        #f2bfd5,
        #dca4bd,
        #121212
      );
      color: white;
      font-family: inherit;
      cursor: pointer;
      box-shadow:
        inset 0 0 10px rgba(255, 255, 255, 0.35),
        0 0 6px rgba(242, 184, 209, 0.7);
    }

    .viewer {
      width: max-content;
      padding: 8px 20px;
      border: 1px solid #e7abc5;
      border-radius: 20px;
      background: #171315;
      color: #f4bfd6;
      font-size: 14px;
      font-weight: bold;
      box-shadow: 0 0 7px rgba(242, 184, 209, 0.45);
    }

    .content {
      margin-top: 15px;
      padding: 20px;
      background: linear-gradient(
        130deg,
        #090909,
        #201a1d,
        #372a30
      );
      border: 1px solid #dca4bd;
      border-radius: 12px;
      display: grid;
      grid-template-columns: 1fr 1fr;
      gap: 15px;
    }

    .section {
      padding: 12px;
      background: linear-gradient(
        145deg,
        #0d0d0d,
        #251e21
      );
      border: 1px solid #dfabc2;
      border-radius: 12px;
      box-shadow: 0 0 10px rgba(242, 184, 209, 0.55);
    }

    .section-title {
      padding: 8px;
      background: linear-gradient(
        90deg,
        #151515,
        #dca4bd,
        #efbcd2
      );
      border-radius: 10px;
      color: white;
      font-weight: bold;
    }

    h1,
    h2 {
      color: #f1b7d0;
      text-shadow: 0 0 5px rgba(242, 184, 209, 0.65);
    }

    h1 {
      font-size: 30px;
    }

    p {
      color: #f5d7e4;
      font-family: Arial, sans-serif;
      line-height: 1.5;
    }

    /* IMAGENS ORIGINAIS */

    .gallery {
      display: grid;
      grid-template-columns: 1fr 1fr;
      gap: 8px;
    }

    .image {
      height: 110px;
      overflow: hidden;
      background: linear-gradient(
        45deg,
        #161616,
        #e3aec5
      );
      border: 3px solid #e8b0c9;
      border-radius: 15px;
    }

    .image img {
      width: 100%;
      height: 100%;
      object-fit: cover;
      display: block;
    }

    .big-image {
      grid-column: span 2;
      height: 130px;
    }

    /* REDES */

    .social {
      display: flex;
      gap: 10px;
    }

    .social div {
      width: 40px;
      height: 40px;
      border: 1px solid #f6cade;
      border-radius: 50%;
      background: linear-gradient(
        135deg,
        #1a1718,
        #dca4bd,
        #f0b9d1
      );
      color: white;
      display: flex;
      align-items: center;
      justify-content: center;
      font-weight: bold;
      box-shadow: 0 0 8px rgba(242, 184, 209, 0.65);
    }

    /* RODAPÉ */

    .footer {
      height: 55px;
      margin-top: 15px;
      background: linear-gradient(
        90deg,
        #111111,
        #dca4bd,
        #f2bfd5,
        #dca4bd,
        #111111
      );
      border: 1px solid #ffd8e8;
      border-radius: 20px;
      display: flex;
      align-items: center;
      justify-content: center;
      color: white;
      font-size: 20px;
      text-shadow:
        0 0 5px #2b1821,
        0 0 8px #f2b8d1;
    }

    @media (max-width: 700px) {
      .window {
        width: 95%;
      }

      .content {
        grid-template-columns: 1fr;
      }
    }
  </style>
</head>

<body>
  <div class="window">
    <div class="top">
      Ana Clara

      <div class="buttons">
        <div class="circle" id="minimizar"></div>
        <div class="circle" id="restaurar"></div>
        <div class="circle" id="fechar"></div>
      </div>
    </div>

    <div class="nav">
      <button id="btnEu">eu</button>
      <button id="btnArtes">artes</button>
      <button id="btnRedes">redes</button>
    </div>

    <div class="viewer">anac</div>

    <div class="content">
      <div>
        <div class="section">
          <div class="section-title">ⓘ | сигарета</div>

          <h1>▣ ana clara</h1>

          <p>oiiiii 💗</p>

          <p>
            aaaaaa.
            <br><br>
            aaaaaa
          </p>
        </div>

        <br>

        <div class="gallery">
          <div class="image">
            <img src="https://i.pinimg.com/474x/d8/a9/f3/d8a9f34eed4cbfbf19261395d4166004.jpg">
          </div>

          <div class="image">
            <img src="https://i.ebayimg.com/images/g/8j0AAOSwU-plOF5h/s-l1200.jpg">
          </div>

          <div class="image big-image">
            <img src="https://images2.alphacoders.com/121/1212645.jpg">
          </div>
        </div>
      </div>

      <div>
        <div class="social">
          <div>◎</div>
          <div>▶</div>
          <div>♪</div>
        </div>

        <br>

        <div class="gallery">
          <div class="image">
            <img src="https://i.pinimg.com/736x/29/3d/b6/293db6f3b9901c375ef8de2bbb71575d.jpg">
          </div>

          <div class="image">
            <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRq3jqSkOdfXctz78kooqhL1WeSMm6oNmVZsQ&s">
          </div>

          <div class="image">
            <img src="https://images.steamusercontent.com/ugc/4105585931633010286/2BF23EB79F3ABF6F7721714F6DFC7F9027992548/?imw=637&imh=358&ima=fit&impolicy=Letterbox&imcolor=%23000000&letterbox=true">
          </div>

          <div class="image">
            <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcR2jQg4ljrjbx2feMUvFpEOwPL3DigEk0EHJg&s">
          </div>
        </div>

        <br>

        <div class="section">
          <div class="section-title">.</div>

          <h2>▣ anac</h2>

          <p>
            .
            <br>
            <strong>.</strong>
            <br>
            .
          </p>
        </div>
      </div>
    </div>

    <div class="footer">Ana Clara</div>
  </div>

  <script>
    const viewer = document.querySelector(".viewer");
    const content = document.querySelector(".content");

    document.getElementById("btnEu").onclick = function () {
      viewer.textContent = "Sobre Mim";
    };

    document.getElementById("btnArtes").onclick = function () {
      viewer.textContent = "Artes";
    };

    document.getElementById("btnRedes").onclick = function () {
      viewer.textContent = "Redes Sociais";
    };

    document.getElementById("minimizar").onclick = function () {
      content.style.display = "none";
    };

    document.getElementById("restaurar").onclick = function () {
      content.style.display = "grid";
    };

    document.getElementById("fechar").onclick = function () {
      document.querySelector(".window").style.display = "none";
    };
  </script>
</body>
</html>
