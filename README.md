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

background:
linear-gradient(120deg,#26136b,#9b61ff,#ff9ee8);

font-family:"Orbitron",sans-serif;

display:flex;
justify-content:center;
align-items:center;

}



.window{

width:700px;

background:
linear-gradient(#bda5ff,#5d45db);

border-radius:25px;

padding:15px;

box-shadow:
0 0 35px #ff9cff,
inset 0 0 20px white;

}



/* TOPO */


.top{

height:55px;

background:
linear-gradient(#f7b7ff,#7045ff);

border-radius:20px;

display:flex;

justify-content:center;

align-items:center;

font-size:22px;

color:white;

text-shadow:0 0 10px white;

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

background:
radial-gradient(circle,#ffb9ff,#783bd8);

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

background:
linear-gradient(#ff9de8,#7254ff);

color:white;

font-family:inherit;

cursor:pointer;

box-shadow:
inset 0 0 10px white;

}




.viewer{

background:#7654e8;

padding:8px 20px;

border-radius:20px;

color:white;

width:max-content;

font-size:14px;

}



/* CONTEUDO */


.content{

margin-top:15px;

background:
linear-gradient(130deg,#fff,#efdfff);

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

background:#7954e8;

color:white;

padding:8px;

border-radius:10px;

}



h1{

color:#6844d4;

font-size:30px;

}



p{

font-family:Arial;

color:#745acb;

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

border:3px solid #9d74ff;

overflow:hidden;

background:
linear-gradient(45deg,#ffb6ef,#7865ff);

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

background:#7955e8;

color:white;

display:flex;

align-items:center;

justify-content:center;

}




.footer{


height:55px;

margin-top:15px;

border-radius:20px;

background:
linear-gradient(#ffb2f5,#7654dd);


display:flex;

align-items:center;

justify-content:center;

font-size:20px;

color:white;

}




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



<h1>

▣ ana clara

</h1>


<p>

cigarro / cigarro / cigarro

</p>



<p>

aaaaaa.

<br><br>

aaaaaa

</p>



</div>




<br>



<div class="gallery">


<div class="image">

<img src="https://i.pinimg.com/736x/13/fc/6a/13fc6ac9deb3c55e2bdb73fec63041c4.jpg">

</div>



<div class="image">

<img src="https://www.shutterstock.com/image-photo/want-hello-kitty-drinking-cherry-260nw-2716768141.jpg">

</div>



<div class="image big-image">

<img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcR8wCVkqAerQuVBSceG0qY33jeozBod1Geo2nrLGYL9xZg26c8FgDjsx-An&s=10">

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

<img src="https://via.placeholder.com/300">

</div>



<div class="image">

<img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSWWYMfUV95T-rm4Z7eND42kDPnUdPqpnBFZGOoyjkjEg&s=10">

</div>



</div>




<br>




<div class="section">


<div class="section-title">

Before Following ⚠

</div>


<h2>

▣ anac

</h2>



<p>

.

<br>

<strong>

.

</strong>

<br>

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
