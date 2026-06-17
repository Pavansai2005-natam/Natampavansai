<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Pavan Sai | Portfolio</title>

<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600;700&display=swap" rel="stylesheet">

<style>
*{
margin:0;
padding:0;
box-sizing:border-box;
font-family:'Poppins',sans-serif;
}

html{
scroll-behavior:smooth;
}

body{
background:#0f172a;
color:white;
line-height:1.6;
}

nav{
position:fixed;
top:0;
width:100%;
background:rgba(15,23,42,0.95);
padding:15px 10%;
display:flex;
justify-content:space-between;
align-items:center;
z-index:1000;
}

.logo{
font-size:24px;
font-weight:700;
color:#38bdf8;
}

nav ul{
display:flex;
list-style:none;
gap:25px;
}

nav ul li a{
color:white;
text-decoration:none;
transition:.3s;
}

nav ul li a:hover{
color:#38bdf8;
}

section{
padding:100px 10%;
}

.hero{
min-height:100vh;
display:flex;
flex-direction:column;
justify-content:center;
}

.hero h1{
font-size:60px;
}

.hero h1 span{
color:#38bdf8;
}

.hero p{
margin-top:15px;
font-size:20px;
max-width:700px;
color:#cbd5e1;
}

.btn{
display:inline-block;
margin-top:25px;
padding:12px 25px;
background:#38bdf8;
color:black;
text-decoration:none;
font-weight:600;
border-radius:8px;
}

.section-title{
font-size:38px;
margin-bottom:30px;
color:#38bdf8;
}

.about p{
max-width:850px;
color:#cbd5e1;
}

.skills-grid{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(180px,1fr));
gap:20px;
}

.skill{
background:#1e293b;
padding:20px;
border-radius:12px;
text-align:center;
transition:.3s;
}

.skill:hover{
transform:translateY(-5px);
background:#334155;
}

.projects-grid{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(300px,1fr));
gap:25px;
}

.project{
background:#1e293b;
padding:25px;
border-radius:15px;
transition:.3s;
}

.project:hover{
transform:translateY(-8px);
}

.project h3{
color:#38bdf8;
margin-bottom:10px;
}

.education-card{
background:#1e293b;
padding:25px;
border-radius:15px;
max-width:700px;
}

.contact p{
margin-bottom:10px;
}

footer{
text-align:center;
padding:30px;
background:#020617;
color:#94a3b8;
}

@media(max-width:768px){

.hero h1{
font-size:40px;
}

nav{
flex-direction:column;
gap:10px;
}

nav ul{
flex-wrap:wrap;
justify-content:center;
}
}
</style>
</head>
<body>

<nav>
<div class="logo">Pavan Sai</div>

<ul>
<li><a href="#about">About</a></li>
<li><a href="#skills">Skills</a></li>
<li><a href="#projects">Projects</a></li>
<li><a href="#education">Education</a></li>
<li><a href="#contact">Contact</a></li>
</ul>
</nav>

<section class="hero">
<h1>Hi, I'm <span>Pavan Sai</span></h1>

<p>
Computer Science Engineering Student | Aspiring Full Stack Developer

Passionate about building modern web applications, solving real-world problems,
and continuously learning new technologies.
</p>

<a href="#projects" class="btn">View My Work</a>
</section>

<section id="about" class="about">
<h2 class="section-title">About Me</h2>

<p>
I am a Computer Science Engineering student at MBU College, Tirupati,
currently entering my final year. I have a strong interest in web development,
software engineering, and creating user-friendly digital experiences.

I enjoy learning modern technologies, working on projects, and improving my
problem-solving skills. My goal is to start my career as a software developer
and contribute to innovative products that make a real impact.
</p>
</section>

<section id="skills">
<h2 class="section-title">Skills</h2>

<div class="skills-grid">

<div class="skill">HTML5</div>
<div class="skill">CSS3</div>
<div class="skill">JavaScript</div>
<div class="skill">React.js</div>
<div class="skill">Python</div>
<div class="skill">Java</div>
<div class="skill">MySQL</div>
<div class="skill">Git & GitHub</div>

</div>
</section>

<section id="projects">
<h2 class="section-title">Projects</h2>

<div class="projects-grid">

<div class="project">
<h3>Portfolio Website</h3>
<p>
Developed a responsive personal portfolio website showcasing skills,
education, and project work using modern web technologies.
</p>
</div>

<div class="project">
<h3>Task Management Application</h3>
<p>
Built a task tracking platform with features for creating,
updating, and managing daily tasks efficiently.
</p>
</div>

<div class="project">
<h3>Student Information System</h3>
<p>
Created a web-based system to manage student details,
records, and academic information.
</p>
</div>

<div class="project">
<h3>Weather Dashboard</h3>
<p>
Designed an application that fetches and displays weather
information through API integration.
</p>
</div>

</div>
</section>

<section id="education">
<h2 class="section-title">Education</h2>

<div class="education-card">
<h3>B.Tech - Computer Science Engineering</h3>
<p>MBU College, Tirupati</p>
<p>Final Year Student</p>
</div>
</section>

<section id="contact" class="contact">
<h2 class="section-title">Contact</h2>

<p>📧 natampavansai2005@gmail.com</p>
<p>📱 8519956483</p>
<p>📍 Tirupati, Andhra Pradesh, India</p>

<a class="btn" href="mailto:natampavansai2005@gmail.com">
Hire Me
</a>
</section>

<footer>
© 2026 Pavan Sai | Portfolio Website
</footer>

</body>
</html>
