<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>Hotel New Deenar | Luxury Kerala Beef Restaurant</title>

<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600;700&family=Cinzel:wght@600&display=swap" rel="stylesheet">

<style>
*{margin:0;padding:0;box-sizing:border-box;font-family:'Poppins',sans-serif}
html{scroll-behavior:smooth}

body{background:#0e0e0e;color:#eee}

/* NAVBAR */
nav{
background:rgba(20,0,0,0.95);
display:flex;
justify-content:space-between;
align-items:center;
padding:18px 70px;
position:fixed;
width:100%;
z-index:1000;
backdrop-filter:blur(10px)
}

.logo{
font-family:'Cinzel',serif;
color:#ffd700;
font-size:26px
}

nav a{
color:#eee;
margin-left:30px;
text-decoration:none;
font-weight:500;
transition:.3s
}

nav a:hover{color:#ffd700}

/* HERO */
.hero{
height:100vh;
background:url('https://images.unsplash.com/photo-1555992336-03a23c6a1f2b') center/cover no-repeat;
display:flex;
align-items:center;
justify-content:center;
text-align:center;
position:relative
}

.hero::before{
content:"";
position:absolute;
top:0;left:0;
width:100%;height:100%;
background:linear-gradient(to bottom, rgba(0,0,0,.7), rgba(90,0,0,.85))
}

.hero-content{
position:relative;
max-width:750px
}

.hero h1{
font-family:'Cinzel',serif;
font-size:64px;
color:#ffd700;
margin-bottom:20px
}

.hero p{font-size:22px;margin-bottom:30px}

.btn{
background:#ffd700;
color:#5a0000;
padding:16px 32px;
border-radius:40px;
text-decoration:none;
font-weight:700;
margin:8px;
display:inline-block;
transition:.3s
}

.btn:hover{background:white}

/* SECTIONS */
section{padding:110px 80px}

.dark{background:#111}
.light{background:#1a0000}

h2{
text-align:center;
font-size:42px;
margin-bottom:60px;
font-family:'Cinzel',serif;
color:#ffd700
}

/* GRID */
.grid{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(260px,1fr));
gap:30px
}

.card{
background:#1b1b1b;
padding:35px;
border-radius:16px;
text-align:center;
transition:.4s;
border:1px solid rgba(255,215,0,.2)
}

.card:hover{
transform:translateY(-12px);
box-shadow:0 18px 40px rgba(255,215,0,.15)
}

.card h3{color:#ffd700;margin-bottom:12px}

/* MENU GALLERY */
.menu-img{
width:100%;
border-radius:14px;
margin-bottom:15px
}

/* CONTACT */
.contact{
text-align:center;
font-size:19px;
line-height:2
}

/* FOOTER */
footer{
background:#000;
color:#aaa;
text-align:center;
padding:35px
}

/* WHATSAPP */
.whatsapp{
position:fixed;
bottom:20px;
right:20px;
background:#25D366;
color:white;
padding:18px;
border-radius:50%;
font-size:22px;
text-decoration:none;
box-shadow:0 6px 18px rgba(0,0,0,.5)
}

/* MOBILE */
@media(max-width:768px){
nav{padding:15px 20px}
.hero h1{font-size:36px}
section{padding:80px 20px}
}
</style>
</head>

<body>

<!-- NAVBAR -->
<nav>
<div class="logo">Hotel New Deenar</div>
<div>
<a href="#about">About</a>
<a href="#specials">Specials</a>
<a href="#experience">Experience</a>
<a href="#contact">Visit</a>
</div>
</nav>

<!-- HERO -->
<div class="hero">
<div class="hero-content">
<h1>Authentic Kerala Beef Excellence</h1>
<p>Luxury Dining • Traditional Recipes • Unforgettable Taste</p>

<a class="btn" href="#specials">Explore Menu</a>
<a class="btn" href="#contact">Reserve Table</a>
</div>
</div>

<!-- ABOUT -->
<section id="about" class="dark">
<h2>Our Story</h2>
<div class="contact">
Hotel New Deenar is a premium destination for authentic Kerala beef cuisine.
Our chefs bring generations of culinary heritage to your plate using fresh
spices, slow cooking, and traditional methods that preserve true flavors.
</div>
</section>

<!-- SPECIALS -->
<section id="specials" class="light">
<h2>Signature Specials</h2>

<div class="grid">

<div class="card">
<img class="menu-img" src="https://images.unsplash.com/photo-1604908176997-431c7e1c5d4c">
<h3>Palli Curry Beef</h3>
<p>Rich, spicy Kerala-style beef curry slow-cooked with aromatic masalas.</p>
</div>

<div class="card">
<img class="menu-img" src="https://images.unsplash.com/photo-1544025162-d76694265947">
<h3>Palli Katt</h3>
<p>A bold specialty dish packed with deep flavors and authentic preparation.</p>
</div>

<div class="card">
<img class="menu-img" src="https://images.unsplash.com/photo-1604908177522-402b4d8a6c18">
<h3>Kerala Parotta & Beef</h3>
<p>Flaky parotta served with perfectly spiced beef curry.</p>
</div>

</div>
</section>

<!-- EXPERIENCE -->
<section id="experience" class="dark">
<h2>The Deenar Experience</h2>

<div class="grid">
<div class="card"><h3>Authentic Kerala Taste</h3></div>
<div class="card"><h3>Premium Ingredients</h3></div>
<div class="card"><h3>Freshly Cooked Daily</h3></div>
<div class="card"><h3>Family Dining Ambience</h3></div>
<div class="card"><h3>Quick Service</h3></div>
<div class="card"><h3>Affordable Luxury</h3></div>
</div>

</section>

<!-- CONTACT -->
<section id="contact" class="light">
<h2>Visit Us</h2>

<div class="contact">
<strong>Hotel New Deenar</strong><br>
Address: Your Hotel Address Here<br>
Phone: +91 XXXXX XXXXX<br>
WhatsApp: +91 XXXXX XXXXX<br>
Open Daily: 7 AM — 11 PM
</div>

</section>

<footer>
© 2026 Hotel New Deenar — Luxury Kerala Beef Restaurant
</footer>

<a class="whatsapp" href="https://wa.me/91XXXXXXXXXX" target="_blank">💬</a>

</body>
</html>
