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

/* ROSA CLARO PASTEL */
background:
linear-gradient(120deg,#ffe4f2,#ffd6ec,#fff0f8,#eaffea);

font-family:"Orbitron",sans-serif;
display:flex;
justify-content:center;
align-items:center;
}

.window{
width:700px;

/* ROSA CLARO */
background:
linear-gradient(135deg,#ffe0f0,#ffd1ea,#fff5fb);

border-radius:25px;
padding:15px;

box-shadow:
0 0 20px #ff9ad5,
0 0 10px #39ff14,
inset 0 0 15px #ffffff;
}

/* TOPO */

.top{
height:55px;

/* ROSA PASTEL COM BRILHO */
background:
linear-gradient(90deg,#ff9ad5,#ffd1ea);

border-radius:20px;

display:flex;
justify-content:center;
align-items:center;

font-size:22px;
color:#fff;
text-shadow:0 0 8px #ff4fa3;

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

/* ROSA + TOQUE VERDE SUAVE */
background:
radial-gradient(circle,#fff,#bfffd0);

border:2px solid #ff9ad5;
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

/* ROSA CLARO */
background:
linear-gradient(90deg,#ffb6dc,#ffd1ea);

color:#fff;
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

/* CONTEÚDO */

.content{
margin-top:15px;

background:
linear-gradient(130deg,#ffffff,#ffeaf5);

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
background:#ffb6dc;
color:white;
padding:8px;
border-radius:10px;
font-weight:bold;
}

h1{
color:#ff4fa3;
font-size:30px;
text-shadow:0 0 4px #ffd1ea;
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
background:#ffb6dc;
color:white;
display:flex;
align-items:center;
justify-content:center;
font-weight:bold;
box-shadow:0 0 8px #ffd1ea;
}

/* FOOTER */

.footer{
height:55px;
margin-top:15px;
border-radius:20px;

background:
linear-gradient(90deg,#ffb6dc,#ffd1ea);

display:flex;
align-items:center;
justify-content:center;

font-size:20px;
color:white;
text-shadow:0 0 8px #ff4fa3;
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
<img src="https://ih1.redbubble.net/image.5483471245.1357/flat,750x,075,f-pad,750x1000,f8f8f8.jpg">
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
<img src="https://images.rawpixel.com/image_800/cHJpdmF0ZS9sci9pbWFnZXMvd2Vic2l0ZS8yMDI1LTA4L3NyLWltYWdlLTIzMDcyMDI1LXdzOS1zLTUwMC1wb3N0ZXItbWV4b2xoeHcuanBn.jpg">
</div>

<div class="image">
<img src="https://i.pinimg.com/1200x/60/c8/f5/60c8f53cef8ebf5576593c5b13976cdd.jpg">
</div>

<div class="image">
<img src="https://i.pinimg.com/736x/29/3d/b6/293db6f3b9901c375ef8de2bbb71575d.jpg">
</div>

<div class="image">
<img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSWWYMfUV95T-rm4Z7eND42kDPnUdPqpnBFZGOoyjkjEg&s=10">
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
