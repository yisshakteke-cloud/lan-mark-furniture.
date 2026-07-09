

<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Mark Furniture</title>

<style>
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
}

body {
    background: #ffffff;
    color: #222;
}

/* Header */
header {
    width: 100%;
    padding: 20px 8%;
    display: flex;
    justify-content: space-between;
    align-items: center;
    background: #064d32;
    color: white;
}

.logo {
    font-size: 28px;
    font-weight: bold;
}

nav a {
    color: white;
    text-decoration: none;
    margin-left: 25px;
    font-size: 16px;
}

nav a:hover {
    color: #c8e6c9;
}

.menu {
    display: none;
    background: none;
    border: none;
    color: white;
    font-size: 25px;
}

/* Hero Section */
.hero {
    height: 75vh;
    /* የጫንከውን ረጅሙን አግድም ፎቶ እዚህ ባግራውንድ አደረግነው */
    background: linear-gradient(rgba(0,50,30,0.5), rgba(0,50,30,0.5)), url("horizontal line .png");
    background-size: cover;
    background-position: center;
    display: flex;
    align-items: center;
    padding: 0 8%;
}

.hero-text {
    color: white;
    max-width: 600px;
}

.hero-text h1 {
    font-size: 48px;
    margin-bottom: 20px;
}

.hero-text p {
    font-size: 20px;
    margin-bottom: 30px;
}

.btn {
    background: #0b7a4b;
    color: white;
    padding: 14px 30px;
    border-radius: 30px;
    text-decoration: none;
    font-weight: bold;
}

.btn:hover {
    background: #064d32;
}

/* Categories / Gallery */
.categories {
    padding: 70px 8%;
    text-align: center;
}

.categories h2 {
    font-size: 35px;
    color: #064d32;
    margin-bottom: 40px;
}

.cards {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
    gap: 30px;
    justify-content: center;
}

.card {
    background: #f5f5f5;
    padding: 20px;
    border-radius: 15px;
    box-shadow: 0 5px 15px rgba(0,0,0,0.05);
    transition: 0.3s;
    text-align: left;
}

.card img {
    width: 100%;
    height: 200px;
    object-fit: cover;
    border-radius: 10px;
    margin-bottom: 15px;
}

.card h3 {
    font-size: 20px;
    color: #064d32;
    margin-bottom: 8px;
}

.card p {
    font-size: 14px;
    color: #666;
}

.card:hover {
    transform: translateY(-10px);
    background: #e8f5e9; /* ቅድም የተቋረጠው ከለር እዚህ ተስተካክሏል */
}

/* Contact */
.contact {
    background: #064d32;
    color: white;
    padding: 60px 8%;
    text-align: center;
}

.contact h2 {
    font-size: 32px;
    margin-bottom: 20px;
}

.contact p {
    font-size: 18px;
    margin: 10px 0;
}

/* Footer */
footer {
    background: #043321;
    color: #a5d6a7;
    text-align: center;
    padding: 20px;
    font-size: 14px;
}

/* Responsive for Mobile */
@media (max-width: 768px) {
    .hero-text h1 { font-size: 32px; }
    .hero-text p { font-size: 16px; }
    header nav { display: none; }
    .menu { display: block; }
}
</style>

</head>
<body>

<header>
    <div class="logo">
        Mark Furniture
    </div>

    <nav>
        <a href="#">Home</a>
        <a href="#">Furniture</a>
        <a href="#contact">Contact</a>
    </nav>

    <button class="menu">☰</button>
</header>

<section class="hero">
    <div class="hero-text">
        <h1>Modern Furniture For Your Dream Home</h1>
        <p>Quality handmade furniture and interior solutions in Ethiopia.</p>
        <a href="#contact" class="btn">Contact Us</a>
    </div>
</section>

<section class="categories">
    <h2>Our Collections</h2>
    <div class="cards">

        <!-- Card 1: TV Stand -->
        <div class="card">
            <img src="tv stand.jpg" alt="TV Stand">
            <h3>TV Stand</h3>
            <p>Modern living room furniture and TV units.</p>
        </div>

        <!-- Card 2: Dining Table -->
        <div class="card">
            <img src="diring teble.jpg" alt="Dining Table">
            <h3>Dining Table</h3>
            <p>Comfortable and luxury dining table designs.</p>
        </div>

        <!-- Card 3: Kitchen Cabinet -->
        <div class="card">
            <img src="kitchen cabinet .png" alt="Kitchen Cabinet">
            <h3>Kitchen Cabinet</h3>
            <p>Custom modern kitchen cabinet solutions.</p>
        </div>

        <!-- Card 4: Doors -->
        <div class="card">
            <img src="door .jpg" alt="Door">
            <h3>Premium Doors</h3>
            <p>Strong and beautifully crafted wooden doors.</p>
        </div>

    </div>
</section>

<section id="contact" class="contact">
    <h2>Contact Mark Furniture</h2>
    <p>📞 +251 991 710 545</p>
    <p>📞 +251 911 664 492</p>
    <p>📧 yisuteka@gmail.com</p>
    <p>Instagram: @lan_yisu</p>
    <p>Telegram: @lanyisu1</p>
</section>

<footer>
    <p>© 2026 Mark Furniture. All Rights Reserved.</p>
</footer>

</body>
</html
