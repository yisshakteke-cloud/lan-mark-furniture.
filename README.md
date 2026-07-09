<!DOCTYPE html>
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
    font-family: 'Segoe UI', Nyala, Tahoma, Geneva, Verdana, sans-serif;
}

body {
    background: #ffffff;
    color: #222;
}

/* Header */
header {
    width: 100%;
    padding: 15px 8%;
    display: flex;
    justify-content: space-between;
    align-items: center;
    background: #064d32;
    color: white;
    position: sticky;
    top: 0;
    z-index: 1000;
    box-shadow: 0 2px 10px rgba(0,0,0,0.1);
}

.logo img {
    height: 50px;
    display: block;
    background: white;
    padding: 3px;
    border-radius: 5px;
}

nav a {
    color: white;
    text-decoration: none;
    margin-left: 20px;
    font-size: 15px;
    font-weight: 500;
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
    height: 70vh;
    background: linear-gradient(rgba(0,50,30,0.6), rgba(0,50,30,0.6)), url("horizontal line .png");
    background-size: cover;
    background-position: center;
    display: flex;
    align-items: center;
    padding: 0 8%;
}

.hero-text {
    color: white;
    max-width: 650px;
}

.hero-text h1 {
    font-size: 42px;
    margin-bottom: 15px;
    text-shadow: 2px 2px 4px rgba(0,0,0,0.3);
}

.hero-text p {
    font-size: 18px;
    margin-bottom: 30px;
    line-height: 1.6;
}

.btn {
    background: #0b7a4b;
    color: white;
    padding: 14px 30px;
    border-radius: 30px;
    text-decoration: none;
    font-weight: bold;
    box-shadow: 0 4px 15px rgba(0,0,0,0.2);
    transition: 0.3s;
}

.btn:hover {
    background: #064d32;
    transform: translateY(-2px);
}

/* Free Delivery Banner */
.delivery-banner {
    background: #fff3cd;
    color: #856404;
    text-align: center;
    padding: 12px;
    font-size: 16px;
    font-weight: bold;
    border-bottom: 2px solid #ffeeba;
}

/* Process Section */
.process-section {
    padding: 80px 8%;
    background: #f9f9f9;
    text-align: center;
}

.process-section h2 {
    font-size: 32px;
    color: #064d32;
    margin-bottom: 10px;
}

.process-subtitle {
    font-size: 16px;
    color: #666;
    margin-bottom: 50px;
}

.process-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(240px, 1fr));
    gap: 25px;
}

.process-card {
    background: white;
    padding: 35px 25px;
    border-radius: 15px;
    box-shadow: 0 10px 30px rgba(0,0,0,0.05);
    border-top: 5px solid #064d32;
    transition: 0.3s;
}

.process-card:hover {
    transform: translateY(-5px);
    box-shadow: 0 15px 35px rgba(0,50,30,0.1);
}

.step-number {
    width: 45px;
    height: 45px;
    background: #064d32;
    color: white;
    border-radius: 50%;
    display: flex;
    align-items: center;
    justify-content: center;
    font-size: 20px;
    font-weight: bold;
    margin: 0 auto 20px auto;
}

.process-card h3 {
    font-size: 18px;
    color: #0b7a4b;
    margin-bottom: 5px;
}

.process-card .en-sub {
    font-size: 13px;
    color: #888;
    text-transform: uppercase;
    margin-bottom: 12px;
    font-weight: bold;
}

.process-card p {
    font-size: 14px;
    color: #555;
    line-height: 1.6;
}

/* Categories / Gallery */
.categories {
    padding: 80px 8%;
    text-align: center;
}

.categories h2 {
    font-size: 32px;
    color: #064d32;
    margin-bottom: 40px;
}

.cards {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
    gap: 30px;
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
    font-size: 19px;
    color: #064d32;
    margin-bottom: 2px;
}

.card .en-title {
    font-size: 13px;
    color: #888;
    margin-bottom: 8px;
    font-weight: 500;
}

.card p {
    font-size: 14px;
    color: #555;
    line-height: 1.5;
}

.card:hover {
    transform: translateY(-10px);
    background: #e8f5e9;
}

/* Contact */
.contact {
    background: #064d32;
    color: white;
    padding: 60px 8%;
    text-align: center;
}

.contact h2 {
    font-size: 30px;
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
    .hero-text h1 { font-size: 30px; }
    .hero-text p { font-size: 15px; }
    header nav { display: none; }
    .menu { display: block; }
}
</style>

</head>
<body>

<header>
    <div class="logo">
        <img src="logo.png" alt="Mark Furniture Logo">
    </div>

    <nav>
        <a href="#">ዋና ገጽ / Home</a>
        <a href="#process">አሰራራችን / Process</a>
        <a href="#collections">ምርቶች / Collections</a>
        <a href="#contact">ያግኙን / Contact</a>
    </nav>

    <button class="menu">☰</button>
</header>

<div class="delivery-banner">
    🚚 ነጻ ማመላለሻ (Free Delivery) — ማንኛውንም እቃ ሲያዙ ያሉበት ድረስ ያለምንም ተጨማሪ ክፍያ በነጻ እናደርሳለን!
</div>

<section class="hero">
    <div class="hero-text">
        <h1>Modern Furniture For Your Dream Home</h1>
        <p>በኢትዮጵያ ታማኝ እና ጥራት ያላቸው የቤትና የቢሮ ዕቃዎች፣ የክፍል ዲዛይን መፍትሔዎች በጥራት እና በጥንቃቄ እንሰራለን።</p>
        <a href="#contact" class="btn">ያግኙን / Contact Us</a>
    </div>
</section>

<section id="process" class="process-section">
    <h2>የአሰራር ሂደታችን</h2>
    <p class="process-subtitle">ለየት ያሉ የቤት ዕቃዎችን (Custom Works) በጥራት የምናመርትበት 4 ደረጃዎች</p>
    
    <div class="process-grid">
        
        <div class="process-card">
            <div class="step-number">1</div>
            <h3>ዲዛይን ማወቅ</h3>
            <div class="en-sub">Choose Design</div>
            <p>የመጀመሪያው ደረጃ ደንበኞቻችን በትክክል የሚፈልጉትን እና ለቤታቸው የሚስማማውን የፈርኒቸር ዲዛይንና መለኪያ በጥንቃቄ መለየት ነው።</p>
        </div>

        <div class="process-card">
            <div class="step-number">2</div>
            <h3>3D ሞዴል ማውጣት</h3>
            <div class="en-sub">3D Modeling</div>
            <p>የተመረጠውን ዲዛይን ዘመናዊ የ 3D ሞዴል በማውጣት፣ ስራው ከመጀመሩ በፊት ለደንበኛው በምስል እናሳይዎታለን።</p>
        </div>

        <div class="process-card">
            <div class="step-number">3</div>
            <h3>ዋጋ ማሳወቅ</h3>
            <div class="en-sub">Price Quotation</div>
            <p>የእቃው ዝርዝርና ዲዛይን ከጸደቀ በኋላ፣ ያለምንም የተደበቀ ክፍያ ትክክለኛውንና ተመጣጣኝ የሆነውን ዋጋ በግልጽ እናሳውቃለን።</p>
        </div>

        <div class="process-card">
            <div class="step-number">4</div>
            <h3>በ2 ሳምንት ማድረስ</h3>
            <div class="en-sub">2 Weeks Delivery</div>
            <p>ትዕዛዝዎን በከፍተኛ ጥራት አጠናቀን በ2 ሳምንት ባልሞላ ጊዜ ውስጥ ያሉበት ድረስ በፍጥነት እናስረክባለን።</p>
        </div>

    </div>
</section>

<section id="collections" class="categories">
    <h2>የምንሰራቸው ምርቶች (Our Collections)</h2>
    <div class="cards">

        <div class="card">
            <img src="tv stand.jpg" alt="TV Stand">
            <h3>የቲቪ ማስቀመጫ</h3>
            <div class="en-title">TV Stand</div>
            <p>ለሳሎንዎ ውበት የሚሰጡ ዘመናዊ እና የተዋቡ የቲቪ ስታንዶች።</p>
        </div>

        <div class="card">
            <img src="diring teble.jpg" alt="Dining Table">
            <h3>የምግብ ጠረጴዛ</h3>
            <div class="en-title">Dining Table</div>
            <p>ለቤተሰብዎ ምቾት የሚሰጡ የቅንጦት የምግብ ጠረጴዛ ዲዛይኖች።</p>
        </div>

        <div class="card">
            <img src="kitchen cabinet .png" alt="Kitchen Cabinet">
            <h3>የኩሽና ካቢኔት</h3>
            <div class="en-title">Kitchen Cabinet</div>
            <p>የማብሰያ ክፍልዎን ዘመናዊ የሚያደርጉ የካቢኔት ስራዎች።</p>
        </div>

        <div class="card">
            <img src="door .jpg" alt="Door">
            <h3>የቤት በሮች</h3>
            <div class="en-title">Premium Doors</div>
            <p>ጠንካራ እና ውብ ከሆኑ ምርጥ እንጨቶች የተሰሩ በሮች።</p>
        </div>

    </div>
</section>

<section id="contact" class="contact">
    <h2>ያግኙን / Contact Mark Furniture</h2>
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
</html>
