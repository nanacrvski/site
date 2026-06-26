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

/* ROSA GRADIENTE PRINCIPAL */
background:
linear-gradient(120deg,#ff4fa3,#ff8cc6,#ffd1ea);

font-family:"Orbitron",sans-serif;
display:flex;
justify-content:center;
align-items:center;
}

.window{
width:700px;

/* ROSA SOFT + PINK NEON */
background:
linear-gradient(#ffd1ea,#ff5fb2);

border-radius:25px;
padding:15px;

box-shadow:
0 0 35px #ff4fa3,
inset 0 0 20px #fff;
}

/* TOPO */

.top{
height:55px;

background:
linear-gradient(#ff9ad5,#ff4fa3);

border-radius:20px;

display:flex;
justify-content:center;
align-items:center;

font-size:22px;
color:white;
text-shadow:0 0 10px #fff;

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

/* ROSA NEON CIRCLES */
background:
radial-gradient(circle,#ffd1ea,#ff4fa3);

border:2px solid white;
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

/* BOTÕES ROSA GAMER */
background:
linear-gradient(#ff7bc2,#ff4fa3);

color:white;
font-family:inherit;
cursor:pointer;

box-shadow:
inset 0 0 10px #fff;
}

.viewer{
background:#ff5fb2;
padding:8px 20px;
border-radius:20px;
color:white;
width:max-content;
font-size:14px;
}

/* CONTEÚDO */

.content{
margin-top:15px;

background:
linear-gradient(130deg,#fff,#ffe3f3);

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
}

.section-title{
background:#ff4fa3;
color:white;
padding:8px;
border-radius:10px;
}

h1{
color:#ff4fa3;
font-size:30px;
}

p{
font-family:Arial;
color:#c2185b;
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

/* BORDA ROSA */
border:3px solid #ff7bc2;

overflow:hidden;

/* FUNDO ROSA */
background:
linear-gradient(45deg,#ffb6dc,#ff4fa3);
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
background:#ff4fa3;
color:white;
display:flex;
align-items:center;
justify-content:center;
}

/* FOOTER */

.footer{
height:55px;
margin-top:15px;
border-radius:20px;

/* FOOTER ROSA NEON */
background:
linear-gradient(#ff9ad5,#ff4fa3);

display:flex;
align-items:center;
justify-content:center;

font-size:20px;
color:white;
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

<p>cigarro / cigarro / cigarro</p>

<p>
aaaaaa.
<br><br>
aaaaaa
</p>

</div>

<br>

<div class="gallery">

<div class="image">
<img src="https://i.pinimg.com/1200x/c6/a8/54/c6a854f4eb2aade847ffc6a19d4309b7.jpg">
</div>

<div class="image">
<img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQ9F8BjC81NEoZ8vlFkH0BXTuST8WtWMqUpypP9TKzBkoDebE59sCwwv-A&s=10">
</div>

<div class="image big-image">
<img src="https://i.pinimg.com/736x/13/fc/6a/13fc6ac9deb3c55e2bdb73fec63041c4.jpg">
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
<img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRKC297Mx4AKSaseO3H_IoBZwSqPDkCQsr_9P1O3mstezMStQNPc9kusGY&s=10">
</div>

<div class="image">
<img src="https://i.pinimg.com/1200x/60/c8/f5/60c8f53cef8ebf5576593c5b13976cdd.jpg">
</div>

<div class="image">
<img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcR9G4EFM9mqpMqTThTJ9r_LSX58pyJ1NGeDmHnOQdRP9w&s=10">
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
