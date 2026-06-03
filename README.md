# kkoparka.github.io

<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>DAKENN - Game App Create</title>

<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Orbitron:wght@400;600;700&family=Inter:wght@300;400;500;600&display=swap" rel="stylesheet">

<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css">

<style>

*{
    margin:0;
    padding:0;
    box-sizing:border-box;
}

body{
    background:#050505;
    color:white;
    font-family:'Inter',sans-serif;
    overflow-x:hidden;
}

html{
    scroll-behavior:smooth;
}

section{
    padding:120px 10%;
}

.container{
    max-width:1400px;
    margin:auto;
}

/* Background Glow */

body::before{
    content:'';
    position:fixed;
    width:800px;
    height:800px;
    background:radial-gradient(circle, rgba(0,150,255,.18), transparent 70%);
    top:-300px;
    right:-200px;
    z-index:-1;
}

body::after{
    content:'';
    position:fixed;
    width:700px;
    height:700px;
    background:radial-gradient(circle, rgba(0,100,255,.12), transparent 70%);
    bottom:-300px;
    left:-250px;
    z-index:-1;
}

/* Header */

.hero{
    min-height:100vh;
    display:flex;
    align-items:center;
    justify-content:center;
    text-align:center;
}

.logo{
    width:450px;
    max-width:90%;
    margin-bottom:30px;
}

.hero h1{
    font-family:'Orbitron',sans-serif;
    font-size:4rem;
    letter-spacing:8px;
    margin-bottom:15px;
}

.hero p{
    font-size:1.3rem;
    color:#a5cfff;
    text-transform:uppercase;
    letter-spacing:4px;
}

/* Mission Section */

.mission{
    text-align:center;
}

.mission h2{
    font-family:'Orbitron',sans-serif;
    font-size:4rem;
    line-height:1.2;
    max-width:1000px;
    margin:auto;
    background:linear-gradient(90deg,#ffffff,#7cc6ff);
    -webkit-background-clip:text;
    -webkit-text-fill-color:transparent;
}

.mission p{
    margin-top:30px;
    color:#bdbdbd;
    font-size:1.2rem;
}

/* About */

.about{
    display:grid;
    grid-template-columns:1fr 1fr;
    gap:80px;
    align-items:center;
}

.about h2{
    font-family:'Orbitron',sans-serif;
    font-size:3rem;
    margin-bottom:25px;
}

.about p{
    color:#cfcfcf;
    line-height:1.8;
    font-size:1.1rem;
}

.about img{
    width:100%;
    border-radius:24px;
    border:1px solid rgba(255,255,255,.08);
    box-shadow:0 0 40px rgba(0,150,255,.15);
}

/* Footer */

footer{
    padding:80px 10%;
    text-align:center;
    border-top:1px solid rgba(255,255,255,.08);
}

.footer-logo{
    width:220px;
    margin-bottom:30px;
}

.contact-btn{
    display:inline-block;
    padding:16px 34px;
    border-radius:999px;
    text-decoration:none;
    color:white;
    border:1px solid #3fa8ff;
    margin-bottom:40px;
    transition:.3s;
}

.contact-btn:hover{
    background:#3fa8ff;
}

.socials{
    display:flex;
    justify-content:center;
    gap:35px;
}

.socials a{
    color:white;
    font-size:2rem;
    transition:.3s;
}

.socials a:hover{
    color:#56b4ff;
    transform:translateY(-3px);
}

/* Mobile */

@media(max-width:900px){

    .hero h1{
        font-size:2.5rem;
    }

    .mission h2{
        font-size:2.5rem;
    }

    .about{
        grid-template-columns:1fr;
        text-align:center;
    }

    .about h2{
        font-size:2.2rem;
    }
}

</style>
</head>
<body>

<!-- HERO -->

<section class="hero">
    <div class="container">
        <img src="logo.png" alt="DAKENN Logo" class="logo">

        <h1>DAKENN</h1>

        <p>Game • App • Create</p>
    </div>
</section>

<!-- MISSION -->

<section class="mission">
    <div class="container">
        <h2>We Make Apps We Use Ourselves</h2>

        <p>
            Building useful software, engaging games, and digital experiences
            that solve real problems and bring people together.
        </p>
    </div>
</section>

<!-- ABOUT -->

<section>
    <div class="container about">

        <div>
            <h2>Who Are We</h2>

            <p>
                DAKENN is a small independent studio focused on creating
                software and games with purpose. We believe the best products
                come from building solutions we genuinely want to use ourselves.
                Every project is driven by curiosity, craftsmanship, and a
                passion for creating experiences that people enjoy returning to.
            </p>
        </div>

        <div>
            <img src="team.png" alt="DAKENN Team">
        </div>

    </div>
</section>

<!-- FOOTER -->

<footer>

    <img src="logo.png" alt="DAKENN Logo" class="footer-logo">

    <br>

    <a href="mailto:contact@dakenn.com" class="contact-btn">
        Contact Us
    </a>

    <div class="socials">

        <a href="https://www.apple.com/app-store/" target="_blank">
            <i class="fa-brands fa-apple"></i>
        </a>

        <a href="https://play.google.com/store" target="_blank">
            <i class="fa-brands fa-google-play"></i>
        </a>

        <a href="https://instagram.com" target="_blank">
            <i class="fa-brands fa-instagram"></i>
        </a>

    </div>

</footer>

</body>
</html>
