<!DOCTYPE html>
<html lang="en">
<head>

<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>Alex Carter | Developer Portfolio</title>


<style>

*{
margin:0;
padding:0;
box-sizing:border-box;
font-family:'Segoe UI',sans-serif;
}


html{
scroll-behavior:smooth;
}


body{

background:#080808;
color:white;

}



/* NAVBAR */

header{

position:fixed;
width:100%;
background:#080808cc;
backdrop-filter:blur(10px);
z-index:10;

}


nav{

display:flex;
justify-content:space-between;
align-items:center;
padding:25px 10%;

}


.logo{

font-size:35px;
color:#00ffff;

}


ul{

display:flex;
gap:30px;
list-style:none;

}


ul a{

color:white;
text-decoration:none;
transition:.3s;

}


ul a:hover{

color:#00ffff;

}





/* HERO */


.hero{

height:100vh;
display:flex;
align-items:center;
justify-content:space-around;
padding:0 10%;

}


.hero-text{

max-width:600px;

}


.hero h1{

font-size:60px;

}


.hero span{

color:#00ffff;

}


.hero h2{

margin-top:15px;

}


.hero p{

margin:25px 0;
font-size:18px;
color:#aaa;

}


button,
.contact-btn{

display:inline-block;
padding:15px 35px;

background:#00ffff;
color:black;

border:none;
border-radius:30px;

font-weight:bold;
cursor:pointer;

text-decoration:none;

transition:.3s;

}


button:hover,
.contact-btn:hover{

transform:scale(1.05);

}



/* CIRCLE */


.circle{

width:300px;
height:300px;

border-radius:50%;

background:
linear-gradient(45deg,#00ffff,#7b2cff);

display:flex;
align-items:center;
justify-content:center;

animation:float 4s infinite;

}


.code{

font-size:80px;

}


@keyframes float{

50%{

transform:translateY(-20px);

}

}





/* SECTIONS */


section{

padding:100px 10%;
text-align:center;

}


section h2{

font-size:40px;
margin-bottom:30px;

}


section p{

max-width:800px;
margin:auto;
color:#aaa;
font-size:18px;

}




/* CARDS */


.cards{

display:flex;
justify-content:center;
gap:30px;
flex-wrap:wrap;

}



.card{

background:#111;

width:300px;

padding:30px;

border-radius:20px;

border:1px solid #222;

transition:.3s;

}



.card:hover{

transform:translateY(-10px);

border-color:#00ffff;

}


.card h3{

color:#00ffff;

}


.card p{

margin-top:15px;

}




.project a{

display:block;
margin-top:20px;

color:#00ffff;
text-decoration:none;

}



/* CONTACT */


#contact{

padding-bottom:120px;

}




/* FOOTER */


footer{

background:#050505;

padding:30px;

text-align:center;

color:#777;

}





/* MOBILE */


@media(max-width:800px){


.hero{

flex-direction:column;
text-align:center;
padding-top:120px;

}


.hero h1{

font-size:40px;

}


.circle{

margin-top:50px;

}


nav{

flex-direction:column;
gap:20px;

}


}

</style>


</head>



<body>




<header>

<nav>

<h2 class="logo">AC.</h2>


<ul>

<li><a href="#about">About</a></li>

<li><a href="#skills">Skills</a></li>

<li><a href="#projects">Projects</a></li>

<li><a href="#contact">Contact</a></li>

</ul>


</nav>

</header>





<section class="hero">


<div class="hero-text">


<h1>
Hi, I'm <span>Alex Carter</span>
</h1>


<h2>
Full Stack Developer & Technology Enthusiast
</h2>



<p>

I create modern websites, applications and digital experiences
focused on performance, design and innovation.

</p>



<button onclick="scrollProjects()">

Explore My Work

</button>



</div>




<div class="circle">

<div class="code">

&lt;/&gt;

</div>

</div>


</section>







<section id="about">


<h2>About Me</h2>


<p>

I am a passionate developer who loves building creative solutions
with technology. My goal is to transform ideas into efficient,
beautiful and functional digital products.

</p>


</section>







<section id="skills">


<h2>My Skills</h2>


<div class="cards">


<div class="card">

<h3>Frontend</h3>

<p>
HTML, CSS, JavaScript, React
</p>

</div>




<div class="card">

<h3>Backend</h3>

<p>
Python, Node.js, Databases
</p>

</div>





<div class="card">

<h3>Tools</h3>

<p>
Git, GitHub, Linux, Docker
</p>

</div>


</div>


</section>









<section id="projects">


<h2>Featured Projects</h2>



<div class="cards">





<div class="card project">


<h3>AI Assistant</h3>


<p>

A smart assistant powered by artificial intelligence.

</p>


<a href="#">
View Project →

</a>


</div>







<div class="card project">


<h3>Cyber Security Lab</h3>


<p>

A practical environment for learning cybersecurity.

</p>


<a href="#">
View Project →

</a>


</div>







<div class="card project">


<h3>Smart Dashboard</h3>


<p>

A responsive dashboard with data visualization.

</p>


<a href="#">
View Project →

</a>


</div>




</div>


</section>









<section id="contact">


<h2>Contact</h2>


<p>

Interested in working together?

</p>


<br>


<a class="contact-btn" href="mailto:alex@email.com">

Send Email

</a>


</section>






<footer>

<p>

© 2026 Alex Carter. Built with passion and code.

</p>

</footer>







<script>


function scrollProjects(){

document
.querySelector("#projects")
.scrollIntoView({

behavior:"smooth"

});

}



</script>




</body>

</html>
