<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Mark Furniture</title>

<link rel="stylesheet" href="style.css">

</head>

<body>

<header>
    <div class="logo">
        Mark Furniture
    </div>

    <nav>
        <a href="#">Home</a>
        <a href="#">Furniture</a>
        <a href="#">Gallery</a>
        <a href="#">About</a>
        <a href="#">Contact</a>
    </nav>

    <button class="menu">☰</button>
</header>


<section class="hero">

<div class="hero-text">
<h1>Modern Furniture For Your Dream Home</h1>

<p>
Quality handmade furniture and interior solutions in Ethiopia.
</p>

<a href="#contact" class="btn">
Contact Us
</a>

</div>

</section>


<section class="categories">

<h2>Our Collections</h2>

<div class="cards">

<div class="card">
<h3>Sofa</h3>
<p>Modern living room furniture</p>
</div>

<div class="card">
<h3>Bedroom</h3>
<p>Comfortable bedroom designs</p>
</div>

<div class="card">
<h3>Kitchen Cabinet</h3>
<p>Custom kitchen solutions</p>
</div>

</div>

</section>


<section id="contact" class="contact">

<h2>Contact Mark Furniture</h2>

<p>📞 +251 991 710 545</p>
<p>📞 +251 911 664 492</p>
<p>📧 yisuteka@gmail.com</p>

<p>
Instagram: @lan_yisu
</p>

<p>
Telegram: @lanyisu1
</p>

</section>


<footer>

<p>
© 2026 Mark Furniture. All Rights Reserved.
</p>

</footer>


<script src="script.js"></script>

</body>
</html>
style.css
*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    font-family: 'Poppins', sans-serif;
}

body{
    background:#ffffff;
    color:#222;
}


/* Header */

header{
    width:100%;
    padding:20px 8%;
    display:flex;
    justify-content:space-between;
    align-items:center;
    background:#064d32;
    color:white;
}

.logo{
    font-size:28px;
    font-weight:bold;
}

nav a{
    color:white;
    text-decoration:none;
    margin-left:25px;
    font-size:16px;
}

nav a:hover{
    color:#c8e6c9;
}

.menu{
    display:none;
    background:none;
    border:none;
    color:white;
    font-size:25px;
}


/* Hero */

.hero{
    height:80vh;
    background:
    linear-gradient(
    rgba(0,50,30,0.6),
    rgba(0,50,30,0.6)
    ),
    url("images/furniture.jpg");

    background-size:cover;
    background-position:center;

    display:flex;
    align-items:center;
    padding:0 8%;
}


.hero-text{
    color:white;
    max-width:600px;
}

.hero-text h1{
    font-size:48px;
    margin-bottom:20px;
}

.hero-text p{
    font-size:20px;
    margin-bottom:30px;
}


.btn{
    background:#0b7a4b;
    color:white;
    padding:14px 30px;
    border-radius:30px;
    text-decoration:none;
}


/* Categories */

.categories{
    padding:70px 8%;
    text-align:center;
}

.categories h2{
    font-size:35px;
    color:#064d32;
    margin-bottom:40px;
}


.cards{
    display:flex;
    gap:30px;
    justify-content:center;
}


.card{
    width:300px;
    padding:40px 20px;
    border-radius:15px;
    background:#f5f5f5;
    transition:0.3s;
}


.card:hover{
    transform:translateY(-10px);
    background:#e8f5e9;
}


.card h3{
    color:#064d32;
    margin-bottom:15px;
}


/* Contact */

.contact{
    background:#064d32;
    color:white;
    text-align:center;
    padding:60px 20px;
}

.contact h2{
    margin-bottom:25px;
}

.contact p{
    margin:10px;
}


/* Footer */

footer{
    background:#032619;
    color:white;
    text-align:center;
    padding:20px;
}



/* Mobile */

@media(max-width:768px){

nav{
    display:none;
}

.menu{
    display:block;
}


.hero-text h1{
    font-size:32px;
}


.cards{
    flex-direction:column;
    align-items:center;
}


.card{
    width:90%;
}

}
