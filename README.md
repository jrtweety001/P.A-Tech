
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Jrtweety Tech Solutions</title>

<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600;700&display=swap" rel="stylesheet">

<style>
*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    font-family:'Poppins',sans-serif;
}

body{
    background:#f5f7fb;
    color:#333;
}

header{
    background:#0a192f;
    color:white;
    padding:20px 8%;
    display:flex;
    justify-content:space-between;
    align-items:center;
    position:sticky;
    top:0;
    z-index:1000;
}

.logo{
    font-size:28px;
    font-weight:700;
}

nav a{
    color:white;
    text-decoration:none;
    margin-left:25px;
    font-weight:500;
}

.hero{
    min-height:90vh;
    display:flex;
    align-items:center;
    justify-content:center;
    text-align:center;
    color:white;
    background:
    linear-gradient(rgba(0,0,0,.6),rgba(0,0,0,.6)),
    url('https://images.unsplash.com/photo-1516321318423-f06f85e504b3?auto=format&fit=crop&w=1600&q=80');
    background-size:cover;
    background-position:center;
}

.hero-content{
    max-width:900px;
}

.hero h1{
    font-size:55px;
    margin-bottom:20px;
}

.hero p{
    font-size:20px;
    margin-bottom:30px;
}

.btn{
    display:inline-block;
    background:#007bff;
    color:white;
    padding:15px 30px;
    border-radius:8px;
    text-decoration:none;
    margin:10px;
}

.btn:hover{
    background:#0056b3;
}

section{
    padding:80px 8%;
}

.section-title{
    text-align:center;
    margin-bottom:50px;
    font-size:40px;
}

.about{
    display:grid;
    grid-template-columns:1fr 1fr;
    gap:40px;
    align-items:center;
}

.about img{
    width:100%;
    border-radius:15px;
}

.services{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
    gap:25px;
}

.card{
    background:white;
    padding:30px;
    border-radius:15px;
    box-shadow:0 5px 20px rgba(0,0,0,.1);
    transition:.3s;
}

.card:hover{
    transform:translateY(-10px);
}

.card h3{
    margin-bottom:15px;
    color:#007bff;
}

.portfolio{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(300px,1fr));
    gap:25px;
}

.portfolio img{
    width:100%;
    border-radius:15px;
}

.contact{
    background:#0a192f;
    color:white;
    text-align:center;
}

.contact form{
    max-width:600px;
    margin:auto;
}

.contact input,
.contact textarea{
    width:100%;
    padding:15px;
    margin:10px 0;
    border:none;
    border-radius:8px;
}

.contact button{
    background:#007bff;
    color:white;
    border:none;
    padding:15px 30px;
    border-radius:8px;
    cursor:pointer;
}

footer{
    background:#06101f;
    color:white;
    text-align:center;
    padding:20px;
}

.whatsapp{
    position:fixed;
    bottom:20px;
    right:20px;
    background:#25d366;
    color:white;
    width:60px;
    height:60px;
    border-radius:50%;
    display:flex;
    justify-content:center;
    align-items:center;
    text-decoration:none;
    font-size:28px;
}

@media(max-width:768px){

.hero h1{
    font-size:35px;
}

.about{
    grid-template-columns:1fr;
}

nav{
    display:none;
}

}
</style>
</head>
<body>

<header>
<div class="logo">Jrtweety Tech Solutions</div>

<nav>
<a href="#home">Home</a>
<a href="#about">About</a>
<a href="#services">Services</a>
<a href="#portfolio">Portfolio</a>
<a href="#contact">Contact</a>
</nav>
</header>

<section class="hero" id="home">
<div class="hero-content">
<h1>Building Modern Websites, Cloud Solutions & Data-Driven Businesses</h1>

<p>
Professional Web Development, Cloud Engineering and Data Analytics Services.
</p>

<a href="#services" class="btn">Our Services</a>
<a href="#contact" class="btn">Contact Us</a>
</div>
</section>

<section id="about">
<h2 class="section-title">About Us</h2>

<div class="about">
<img src="https://images.unsplash.com/photo-1551434678-e076c223a692?auto=format&fit=crop&w=1200&q=80">

<div>
<h3>P.A Tech Solutions</h3>

<p>
We specialize in modern website development, cloud infrastructure deployment, data analytics, and digital transformation solutions.
</p>

<br>

<p>
Our mission is to help businesses grow through secure, scalable, and innovative technology solutions.
</p>
</div>
</div>
</section>

<section id="services">
<h2 class="section-title">Our Services</h2>

<div class="services">

<div class="card">
<h3>Web Development</h3>
<p>Professional business websites and web applications.</p>
</div>

<div class="card">
<h3>Cloud Engineering</h3>
<p>AWS, Azure and cloud deployment solutions.</p>
</div>

<div class="card">
<h3>Data Analytics</h3>
<p>Transforming business data into actionable insights.</p>
</div>

<div class="card">
<h3>IT Consulting</h3>
<p>Helping businesses leverage technology effectively.</p>
</div>

<div class="card">
<h3>Website Maintenance</h3>
<p>Security updates and performance optimization.</p>
</div>

<div class="card">
<h3>Business Automation</h3>
<p>Automating workflows and improving efficiency.</p>
</div>

</div>
</section>

<section id="portfolio">
<h2 class="section-title">Portfolio</h2>

<div class="portfolio">

<img src="https://images.unsplash.com/photo-1460925895917-afdab827c52f?auto=format&fit=crop&w=1000&q=80">

<img src="https://images.unsplash.com/photo-1551288049-bebda4e38f71?auto=format&fit=crop&w=1000&q=80">

<img src="https://images.unsplash.com/photo-1518770660439-4636190af475?auto=format&fit=crop&w=1000&q=80">

</div>
</section>

<section class="contact" id="contact">

<h2 class="section-title">Contact Us</h2>

<p>Phone: +234 806 309 0309</p>

<br>

<form>
<input type="text" placeholder="Your Name">
<input type="email" placeholder="Your Email">
<textarea rows="5" placeholder="Your Message"></textarea>
<button type="submit">Send Message</button>
</form>

</section>

<footer>
<p>© 2026 Jrtweety Tech Solutions. All Rights Reserved.</p>
</footer>

<a class="whatsapp"
href="https://wa.me/2348063090309"
target="_blank">
💬
</a>

<a class="tiktok"
href="https://www.tiktok.com/@jrtweety001?_r=1&_t=ZS-9744eP2AAc6"
target="-blank">
💬

</body>
</html>
