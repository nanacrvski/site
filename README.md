<!DOCTYPE html>
<html lang="pt-BR">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>Pink Cyber Profile</title>

<style>

@import url('https://fonts.googleapis.com/css2?family=Orbitron:wght@400;700&display=swap');


*{
    box-sizing:border-box;
    margin:0;
    padding:0;
    font-family:'Orbitron', sans-serif;
}


body{

    min-height:100vh;
    background:
    radial-gradient(circle,#ff8cff,#8b3dff,#241047);

    color:white;
    overflow-x:hidden;

}


/* estrelas */

body::before{

content:"";
position:fixed;
width:100%;
height:100%;

background-image:
radial-gradient(#fff 1px,transparent 1px);

background-size:40px 40px;
opacity:.2;

}



/* janela */

.container{

width:90%;
max-width:1100px;

margin:50px auto;

background:
rgba(255,255,255,.15);

border:3px solid #ff8cff;

border-radius:35px;

padding:25px;

box-shadow:

0 0 30px #ff3cff,
inset 0 0 40px #9d4cff;

backdrop-filter:blur(15px);

}



/* barra */

.top{

height:70px;

background:
linear-gradient(90deg,#ff5eea,#8d55ff);

border-radius:30px;

display:flex;

align-items:center;

justify-content:center;

font-size:30px;

box-shadow:0 0 20px pink;

}


.buttons{

display:flex;
justify-content:center;
gap:20px;
margin:25px;

}


button{

background:
linear-gradient(#ff9cf7,#8b4cff);

border:none;

padding:15px 35px;

border-radius:30px;

color:white;

font-size:16px;

cursor:pointer;

box-shadow:
0 0 15px #ff7cff;

}


button:hover{

transform:scale(1.1);

}



/* layout */


.content{

display:grid;

grid-template-columns:1fr 1fr;

gap:25px;

}



.card{

background:
rgba(255,255,255,.12);

border:2px solid #ff8cff;

border-radius:25px;

padding:25px;

box-shadow:
0 0 20px #b94cff;

}


.title{

font-size:25px;

color:#ffd1ff;

margin-bottom:20px;

}



/* perfil */


.profile{

display:flex;

align-items:center;

gap:20px;

}


.avatar{

width:130px;
height:130px;

border-radius:30px;

background:
linear-gradient(135deg,#ff7be9,#713cff);

display:flex;

align-items:center;

justify-content:center;

font-size:60px;

box-shadow:
0 0 25px pink;

}



/* imagens */


.gallery{

display:grid;

grid-template-columns:repeat(2,1fr);

gap:15px;

}


.gallery img{

width:100%;

height:130px;

object-fit:cover;

border-radius:20px;

border:3px solid #ff8cff;

box-shadow:
0 0 15px #ff55ff;

}



/* barra inferior */


.footer{

margin-top:25px;

background:
linear-gradient(90deg,#8c42ff,#ff55dd);

padding:20px;

border-radius:25px;

text-align:center;

}



.social a{

display:inline-block;

margin:10px;

padding:12px 20px;

background:#ff7be8;

border-radius:20px;

color:white;

text-decoration:none;

box-shadow:
0 0 15px pink;

}


@media(max-width:800px){

.content{

grid-template-columns:1fr;

}

}



</style>

</head>


<body>



<div class="container">


<div class="top">

✦ PINK CYBER WORLD ✦

</div>



<div class="buttons">

<button>HOME</button>
<button>PROJECTS</button>
<button>METRICS</button>

</div>




<div class="content">


<div>


<div class="card">


<div class="title">

💜 ABOUT ME

</div>


<div class="profile">


<div class="avatar">

☆


</div>


<div>

<h2>ANA CLARA</h2>

<p>
Digital creator ✦ student ✦ dreamer
</p>

<p>

♡ Welcome to my little pink universe ♡

</p>

</div>


</div>


</div>



<br>



<div class="card">

<div class="title">

🌸 INFORMATION

</div>


<p>

✦ Web designer<br><br>

✦ Creative projects<br><br>

✦ Technology lover<br><br>

✦ Pink aesthetic enthusiast

</p>


</div>


</div>





<div>


<div class="card">


<div class="title">

🪐 GALLERY

</div>


<div class="gallery">


<img src="https://picsum.photos/300/200?1">

<img src="https://picsum.photos/300/200?2">

<img src="https://picsum.photos/300/200?3">

<img src="https://picsum.photos/300/200?4">


</div>


</div>



<br>


<div class="card">


<div class="title">

💿 BEFORE FOLLOWING

</div>


<p>

Please respect this space ✨

<br><br>

I create, design and explore
new digital worlds.

</p>



</div>


</div>



</div>




<div class="footer">


<div class="social">


<a href="#">Instagram</a>

<a href="#">Github</a>

<a href="#">TikTok</a>


</div>


© 2026 Pink Cyber Profile


</div>



</div>


</body>
</html>
