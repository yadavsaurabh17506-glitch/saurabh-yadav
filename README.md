<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Saurabh Portfolio</title>

<style>

body{
margin:0;
font-family:Arial;
background:#111;
color:white;
}

header{
text-align:center;
padding:40px;
background:black;
}

nav{
text-align:center;
background:#222;
padding:10px;
}

nav a{
color:white;
margin:15px;
text-decoration:none;
font-size:18px;
}

.hero{
text-align:center;
padding:80px 20px;
background:linear-gradient(45deg,#ff4b2b,#ff416c);
}

.hero h1{
font-size:50px;
}

.section{
padding:50px;
text-align:center;
}

.projects{
display:flex;
justify-content:center;
flex-wrap:wrap;
gap:20px;
}

.card{
background:#222;
padding:20px;
width:220px;
border-radius:10px;
}

.contact input{
padding:10px;
margin:10px;
width:250px;
border:none;
border-radius:5px;
}

button{
padding:10px 20px;
background:red;
color:white;
border:none;
cursor:pointer;
}

footer{
text-align:center;
padding:20px;
background:black;
}

</style>

</head>

<body>

<header>

<h1>Saurabh Yadav</h1>
<p>Web Developer | Video Editor</p>

</header>

<nav>

<a href="#">Home</a>
<a href="#">Projects</a>
<a href="#">Contact</a>

</nav>

<section class="hero">

<h1>I Build Websites</h1>
<p>Professional websites for businesses</p>

</section>

<section class="section">

<h2>My Projects</h2>

<div class="projects">

<div class="card">
<h3>Restaurant Website</h3>
<p>Modern restaurant design</p>
</div>

<div class="card">
<h3>Portfolio Website</h3>
<p>Personal branding website</p>
</div>

<div class="card">
<h3>Business Website</h3>
<p>Website for local businesses</p>
</div>

</div>

</section>

<section class="section contact">

<h2>Contact Me</h2>

<input type="text" placeholder="Your Name"><br>
<input type="email" placeholder="Email"><br>

<button>Send Message</button>

</section>

<footer>

<p>© 2026 Saurabh Portfolio</p>

</footer>

</body>
</html>
