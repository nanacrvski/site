<html lang="pt-br">

<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>site da anac</title>

<style>

@import url('https://fonts.googleapis.com/css2?family=Orbitron:wght@400;700&display=swap');

*{
box-sizing:border-box;
}

body{
margin:0;
min-height:100vh;

/* FUNDO SAKURA */
background:
linear-gradient(120deg, rgba(255,228,242,0.75), rgba(255,214,236,0.75), rgba(255,240,248,0.75)),
url("https://images.unsplash.com/photo-1490818387583-1baba5e638af?auto=format&fit=crop&w=1600&q=80");

background-size:cover;
background-position:center;
background-attachment:fixed;

font-family:"Orbitron",sans-serif;
display:flex;
justify-content:center;
align-items:center;
}

.window{
width:700px;

/* ROSA PASTEL SUAVE */
background:
linear-gradient(135deg,#ffe0f0,#ffd1ea,#fff5fb);

border-radius:25px;
padding:15px;

box-shadow:
0 0 18px #ff9ad5,
0 0 10px #ffc1e3,
inset 0 0 15px #ffffff;
}

/* TOPO */

.top{
height:55px;

/* ROSA PASTEL */
background:
linear-gradient(90deg,#ffb6dc,#ffd1ea,#ffe4f2);

border-radius:20px;

display:flex;
justify-content:center;
align-items:center;

font-size:22px;
color:#ffffff;
text-shadow:0 0 8px #ff9ad5;

position:relative;
}

.buttons{
position:absolute;
right:20px;
display:flex;
gap:10px;
}

.circle{
height:35px;
width:35px;
border-radius:50%;

/* ROSA CLARO */
background:
radial-gradient(circle,#ffffff,#ffd1ea);

border:2px solid #ffb6dc;
}

/* MENU */

.nav{
display:flex;
gap:12px;
margin:18px 10px;
}

.nav button{
flex:1;
border:none;
padding:12px;
border-radius:30px;

/* ROSA PASTEL */
background:
linear-gradient(90deg,#ffb6dc,#ffd1ea,#ffe4f2);

color:white;
font-family:inherit;
cursor:pointer;

box-shadow:
inset 0 0 10px #fff,
0 0 6px #ff9ad5;
}

.viewer{
background:#ffd1ea;
padding:8px 20px;
border-radius:20px;
color:#ff4fa3;
width:max-content;
font-size:14px;
font-weight:bold;
}

.content{
margin-top:15px;

background:
linear-gradient(130deg,#ffffff,#ffeaf5,#fff5fb);

border-radius:12px;
padding:20px;

display:grid;
grid-template-columns:1fr 1fr;
gap:15px;
}

.section{
background:white;
padding:12px;
border-radius:12px;
box-shadow:0 0 10px #ffb6dc;
}

.section-title{
background:linear-gradient(90deg,#ffb6dc,#ffd1ea);
color:white;
padding:8px;
border-radius:10px;
font-weight:bold;
}

h1{
color:#ff4fa3;
font-size:30px;
text-shadow:0 0 5px #ffd1ea;
}

p{
font-family:Arial;
color:#b3125c;
line-height:1.5;
}

/* IMAGENS */

.gallery{
display:grid;
grid-template-columns:1fr 1fr;
gap:8px;
}

.image{
height:110px;
border-radius:15px;

border:3px solid #ffd1ea;

overflow:hidden;

background:
linear-gradient(45deg,#ffd1ea,#ffe4f2);
}

.image img{
width:100%;
height:100%;
object-fit:cover;
display:block;
}

.big-image{
grid-column:span 2;
height:130px;
}

/* REDES */

.social{
display:flex;
gap:10px;
}

.social div{
width:40px;
height:40px;
border-radius:50%;
background:linear-gradient(90deg,#ffb6dc,#ffd1ea);
color:white;
display:flex;
align-items:center;
justify-content:center;
font-weight:bold;
box-shadow:0 0 8px #ffb6dc;
}

/* FOOTER */

.footer{
height:55px;
margin-top:15px;
border-radius:20px;

background:
linear-gradient(90deg,#ffb6dc,#ffd1ea,#ffe4f2);

display:flex;
align-items:center;
justify-content:center;

font-size:20px;
color:white;
text-shadow:0 0 8px #ff9ad5;
}

/* RESPONSIVO */

@media(max-width:700px){
.window{
width:95%;
}

.content{
grid-template-columns:1fr;
}
}

</style>

</head>

<body>

<div class="window">

<div class="top">
Ana Clara

<div class="buttons">
<div class="circle"></div>
<div class="circle"></div>
<div class="circle"></div>
</div>

</div>

<div class="nav">
<button>home</button>
<button>platforms</button>
<button>sobre mim</button>
</div>

<div class="viewer">
anac
</div>

<div class="content">

<div>

<div class="section">

<div class="section-title">
ⓘ | About Me
</div>

<h1>▣ ana clara</h1>

<p>rosa pastel kawaii 💗</p>

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
<img src="https://pics.craiyon.com/2023-10-30/f89e03c4f7e14049a856090721960807.webp">
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
<img src="https://media.craiyon.com/2023-11-02/27ad4af3fc794b0682971a0990f0e861.webp">
</div>

<div class="image">
<img src="https://images.steamusercontent.com/ugc/4105585931633010286/2BF23EB79F3ABF6F7721714F6DFC7F9027992548/?imw=637&imh=358&ima=fit&impolicy=Letterbox&imcolor=%23000000&letterbox=true">
</div>

<div class="image">
<img src="https://i.pinimg.com/236x/2f/fe/2b/2ffe2b8acd23a1e25442298be5711067.jpg">
</div>

</div>

<br>

<div class="section">

<div class="section-title">.</div>

<h2>▣ anac</h2>

<p>
.<br>
<strong>.</strong><br>
.
</p>

</div>

</div>

</div>

<div class="footer">
Ana Clara
</div>

</div>

</body>
</html>
