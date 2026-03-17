<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Marcus Portfolio</title>

<style>

*{
margin:0;
padding:0;
box-sizing:border-box;
font-family:Arial, sans-serif;
}

body{
background:#f6eee7;
color:#222;
}

/* NAVBAR */

nav{
display:flex;
justify-content:space-between;
align-items:center;
padding:20px 60px;
background:#f1c4c8;
}

nav h2{
font-weight:bold;
}

nav ul{
display:flex;
gap:30px;
list-style:none;
}

nav a{
text-decoration:none;
color:black;
font-weight:500;
}

/* HERO */

.hero{
display:flex;
justify-content:space-between;
align-items:center;
padding:80px 60px;
flex-wrap:wrap;
}

.hero-text{
max-width:500px;
}

.hero-text h1{
font-size:40px;
margin-bottom:10px;
}

.hero-text span{
color:#e63946;
font-weight:bold;
}

.hero-text p{
margin:10px 0 20px 0;
color:#555;
}

button{
padding:12px 25px;
border:none;
background:#000;
color:white;
cursor:pointer;
border-radius:5px;
}

/* IMAGE CARD */

.hero-img{
background:white;
padding:10px;
border-radius:10px;
box-shadow:0 5px 15px rgba(0,0,0,0.1);
}

.hero-img img{
width:260px;
border-radius:10px;
}

/* SECTIONS */

section{
padding:60px;
}

h2{
margin-bottom:20px;
}

/* SKILLS */

.skills{
display:flex;
gap:20px;
flex-wrap:wrap;
}

.card{
background:white;
padding:20px;
border-radius:10px;
box-shadow:0 4px 10px rgba(0,0,0,0.1);
width:200px;
}

/* PROJECTS */

.projects{
display:flex;
gap:20px;
flex-wrap:wrap;
}

.project{
background:white;
padding:20px;
border-radius:10px;
box-shadow:0 4px 10px rgba(0,0,0,0.1);
width:250px;
}

footer{
text-align:center;
padding:20px;
background:#eee;
}

</style>
</head>

<body>

<!-- NAVBAR -->

<nav>
<h2>&lt;Marcus/&gt;</h2>

<ul>
<li><a href="#about">About</a></li>
<li><a href="#skills">Skills</a></li>
<li><a href="#projects">Projects</a></li>
<li><a href="#contact">Contact</a></li>
</ul>

</nav>

<!-- HERO -->

<div class="hero">

<div class="hero-text">

<h1>Hi, I'm Marcus</h1>

<h3><span>Creative Digital Creator</span></h3>

<p>
Graphic Designer • Social Media Manager • Video Editor
</p>

<button onclick="document.getElementById('projects').scrollIntoView({behavior:'smooth'})">
View my work
</button>

</div>

<div class="hero-img">
<img src="https://picsum.photos/300/400">
</div>

</div>

<!-- ABOUT -->

<section id="about">

<h2>About Me</h2>

<p>
I help brands grow online through creative designs, engaging social media
content, and high-quality video editing. I enjoy turning ideas into
visual content that connects with people.
</p>

</section>

<!-- SKILLS -->

<section id="skills">

<h2>My Skills</h2>

<div class="skills">

<div class="card">🎨 Graphic Design</div>
<div class="card">📱 Social Media Management</div>
<div class="card">🎬 Video Editing</div>
<div class="card">🖌 Branding</div>
<div class="card">📊 Content Strategy</div>

</div>

</section>

<!-- PROJECTS -->

<section id="projects">

<h2>My Projects</h2>

<div class="projects">

<div class="project">
<h3>Social Media Campaign</h3>
<p>Designed and managed posts that increased engagement.</p>
</div>

<div class="project">
<h3>Brand Graphics</h3>
<p>Created logos, posters, and digital graphics.</p>
</div>

<div class="project">
<h3>Video Editing Project</h3>
<p>Edited promotional and social media videos.</p>
</div>

</div>

</section>

<!-- CONTACT -->

<section id="contact">

<h2>Contact</h2>

<p>Email: genmarcussmendoza@email.com</p>
<p>Instagram: <a href="https://instagram.com/m4rcvsssz" target="_blank">m4rcvsssz</a></p>

</section>

<footer>
©2026 Marcus Portfolio
</footer>

</body>
</html>
