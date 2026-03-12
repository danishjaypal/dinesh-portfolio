# dinesh-portfolio
Dinesh Jaypal Portfolio | Future Full Stack Developer
<!DOCTYPE html>
<html lang="en">

<head>

<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>Dinesh jaypal Portfolio</title>

<style>

*{
margin:0;
padding:0;
box-sizing:border-box;
font-family:Arial;
}

html{
scroll-behavior:smooth;
}

body{
color:white;
background:linear-gradient(-45deg,#0f172a,#020617,#1e293b,#0ea5e9);
background-size:400% 400%;
animation:gradient 10s ease infinite;
}

@keyframes gradient{
0%{background-position:0% 50%;}
50%{background-position:100% 50%;}
100%{background-position:0% 50%;}
}

header{
display:flex;
justify-content:space-between;
padding:20px 60px;
background:rgba(0,0,0,0.3);
backdrop-filter:blur(10px);
position:sticky;
top:0;
}

nav a{
color:white;
margin-left:20px;
text-decoration:none;
}

.hero{
height:90vh;
display:flex;
justify-content:center;
align-items:center;
flex-direction:column;
text-align:center;
}

.profile{
width:160px;
border-radius:50%;
margin-bottom:20px;
border:4px solid white;
}

.hero h1{
font-size:50px;
}

.typing{
font-size:25px;
margin-top:10px;
color:#38bdf8;
}

button{
margin-top:20px;
padding:12px 25px;
border:none;
border-radius:10px;
background:linear-gradient(45deg,#22c55e,#38bdf8);
color:white;
cursor:pointer;
}

section{
padding:80px;
text-align:center;
}

.card{
background:rgba(255,255,255,0.1);
backdrop-filter:blur(10px);
padding:20px;
border-radius:15px;
margin:10px;
display:inline-block;
width:220px;
transition:0.3s;
}

.card:hover{
transform:scale(1.1) translateY(-10px);
}

.contact{
max-width:400px;
margin:auto;
}

.contact input,
.contact textarea{
width:100%;
padding:12px;
margin-top:10px;
border:none;
border-radius:8px;
}

footer{
text-align:center;
padding:20px;
background:rgba(0,0,0,0.4);
}

footer a{
color:#38bdf8;
margin:10px;
text-decoration:none;
}

</style>

</head>

<body>

<header>

<h2>DINESH JAYPAL</h2>

<nav>
<a href="#about">About</a>
<a href="#skills">Skills</a>
<a href="#projects">Projects</a>
<a href="#contact">Contact</a>
</nav>

</header>

<div class="hero">

<img src="C:\Users\ACER\Downloads/danish.jpeg" class="profile">

<h1>Hello I'mDINESH</h1>

<div class="typing" id="typing"></div>

<button>Hire Me</button>

</div>

<section id="about">

<h2>About Me</h2>

<p>
My name is Dinesh. I am learning Web Development and building modern websites.
</p>

</section>

<section id="skills">

<h2>Skills</h2>

<div>

<div class="card">HTML</div>
<div class="card">CSS</div>
<div class="card">JavaScript</div>
<div class="card">GitHub</div>

</div>

</section>

<section id="projects">

<h2>Projects</h2>

<div>

<div class="card">
<h3>Portfolio</h3>
<p>My personal portfolio website.</p>
</div>

<div class="card">
<h3>Landing Page</h3>
<p>Modern landing page.</p>
</div>

<div class="card">
<h3>Blog Layout</h3>
<p>Simple blog design.</p>
</div>

</div>

</section>

<section id="contact">

<h2>Contact Me</h2>

<div class="CONTACT ME">
<p>jaypaldinesh10@gmail.com</p>

<input type="text" placeholder="Your Name">

<input type="email" placeholder="Your Email">

<textarea placeholder="Message"></textarea>

<button>Send</button>

</div>

</section>

<footer>

<p>© 2026 Danish Developer</p>

<a href="https://www.facebook.com/share/1Bdg4s7ZUN/">facebook</a>
<a href="https://www.snapchat.com/add/dineshjaypal0?share_id=Tkekrx5UwxA&locale=en-GB">snapchat</a>
<a href="https://www.instagram.com/danish_jaypal?igsh=YXVybXB0OTc3dTI5">Instagram</a>

</footer>

<script>

const text = "Future Full Stack Developer 🚀";
let i = 0;

function typing(){

if(i < text.length){

document.getElementById("typing").innerHTML += text.charAt(i);

i++;

setTimeout(typing,100);

}

}

typing();

</script>

</body>
</html>
