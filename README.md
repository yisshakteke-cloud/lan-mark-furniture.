
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Mark Furniture - Bespoke Luxury Interior & Furniture</title>

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
    scroll-behavior: smooth;
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
    height: 55px;
    display: block;
    background: white;
    padding: 4px;
    border-radius: 6px;
}

nav a {
    color: white;
    text-decoration: none;
    margin-left: 20px;
    font-size: 15px;
    font-weight: 500;
    transition: 0.3s;
}

nav a:hover {
    color: #c8e6c9;
}

.menu {
    display: none;
    background: none;
    border: none;
    color: white;
    font-size: 28px;
    cursor: pointer;
}

/* Free Delivery Banner */
.delivery-banner {
    background: #fff3cd;
    color: #856404;
    text-align: center;
    padding: 14px;
    font-size: 16px;
    font-weight: bold;
    border-bottom: 2px solid #ffeeba;
    letter-spacing: 0.5px;
}

/* Hero Section */
.hero {
    height: 75vh;
    background: linear-gradient(rgba(0,40,25,0.65), rgba(0,40,25,0.65)), url("horizontal line .png");
    background-size: cover;
    background-position: center;
    display: flex;
    align-items: center;
    padding: 0 8%;
}

.hero-text {
    color: white;
    max-width: 700px;
}

.hero-text h1 {
    font-size: 46px;
    margin-bottom: 15px;
    text-shadow: 2px 2px 5px rgba(0,0,0,0.4);
    font-weight: 800;
}

.hero-text p {
    font-size: 19px;
    margin-bottom: 35px;
    line-height: 1.6;
    color: #e8f5e9;
}

.btn {
    background: #0b7a4b;
    color: white;
    padding: 15px 35px;
    border-radius: 30px;
    text-decoration: none;
    font-weight: bold;
    box-shadow: 0 4px 15px rgba(0,0,0,0.3);
    transition: 0.3s;
    text-transform: uppercase;
    letter-spacing: 1px;
    display: inline-block;
}

.btn:hover {
    background: #ffffff;
    color: #064d32;
    transform: translateY(-3px);
}

/* About & Materials Section */
.about-section {
    padding: 90px 8%;
    background: #ffffff;
}

.about-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
    gap: 40px;
    align-items: center;
}

.about-text h2 {
    font-size: 36px;
    color: #064d32;
    margin-bottom: 15px;
    font-weight: 700;
}

.about-text p {
    font-size: 16px;
    color: #555;
    line-height: 1.7;
    margin-bottom: 20px;
}

.materials-box {
    background: #f4f7f5;
    padding: 30px;
    border-radius: 20px;
    border-left: 6px solid #0b7a4b;
}

.materials-box h3 {
    color: #064d32;
    margin-bottom: 15px;
    font-size: 22px;
}

.materials-box ul {
    list-style-type: none;
}

.materials-box ul li {
    margin-bottom: 12px;
    font-size: 15px;
    color: #444;
    display: flex;
    align-items: center;
}

.materials-box ul li::before {
    content: "✦";
    color: #0b7a4b;
    font-weight: bold;
    margin-right: 10px;
}

/* Process Section */
.process-section {
    padding: 90px 8%;
    background: #fdfdfd;
    text-align: center;
}

.process-section h2 {
    font-size: 36px;
    color: #064d32;
    margin-bottom: 10px;
    font-weight: 700;
}

.process-subtitle {
    font-size: 17px;
    color: #666;
    margin-bottom: 60px;
}

.process-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(240px, 1fr));
    gap: 30px;
}

.process-card {
    background: white;
    padding: 40px 25px;
    border-radius: 20px;
    box-shadow: 0 10px 40px rgba(0,0,0,0.04);
    border-top: 5px solid #064d32;
    transition: 0.3s;
}

.process-card:hover {
    transform: translateY(-8px);
    box-shadow: 0 20px 40px rgba(0,50,30,0.08);
}

.step-number {
    width: 50px;
    height: 50px;
    background: #064d32;
    color: white;
    border-radius: 50%;
    display: flex;
    align-items: center;
    justify-content: center;
    font-size: 22px;
    font-weight: bold;
    margin: 0 auto 25px auto;
    box-shadow: 0 4px 10px rgba(6,77,50,0.2);
}

.process-card h3 {
    font-size: 20px;
    color: #0b7a4b;
    margin-bottom: 5px;
}

.process-card .en-sub {
    font-size: 13px;
    color: #999;
    text-transform: uppercase;
    margin-bottom: 15px;
    font-weight: bold;
    letter-spacing: 1px;
}

.process-card p {
    font-size: 14.5px;
    color: #555;
    line-height: 1.6;
}

/* Video Showcase Section */
.video-section {
    padding: 80px 8%;
    background: #064d32;
    color: white;
    text-align: center;
}

.video-section h2 {
    font-size: 34px;
    margin-bottom: 15px;
}

.video-container {
    max-width: 800px;
    margin: 40px auto 0 auto;
    background: rgba(255, 255, 255, 0.1);
    padding: 15px;
    border-radius: 25px;
    box-shadow: 0 15px 35px rgba(0,0,0,0.3);
}

.video-placeholder {
    width: 100%;
    height: 400px;
    background: linear-gradient(rgba(0,0,0,0.5), rgba(0,0,0,0.5)), url("3D.jpg");
    background-size: cover;
    background-position: center;
    border-radius: 15px;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
}

.play-icon {
    font-size: 60px;
    cursor: pointer;
    background: #0b7a4b;
    width: 90px;
    height: 90px;
    border-radius: 50%;
    display: flex;
    align-items: center;
    justify-content: center;
    margin-bottom: 15px;
    box-shadow: 0 0 20px rgba(255,255,255,0.4);
    transition: 0.3s;
}

.play-icon:hover {
    transform: scale(1.1);
    background: #ffffff;
    color: #064d32;
}

/* Collections Section */
.categories {
    padding: 90px 8%;
    background: #f4f7f5;
    text-align: center;
}

.categories h2 {
    font-size: 38px;
    color: #064d32;
    margin-bottom: 15px;
    font-weight: 700;
}

.categories .section-desc {
    font-size: 16px;
    color: #555;
    margin-bottom: 55px;
    max-width: 700px;
    margin-left: auto;
    margin-right: auto;
}

.cards {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
    gap: 35px;
}

.card {
    background: #ffffff;
    padding: 24px;
    border-radius: 20px;
    box-shadow: 0 8px 25px rgba(0,0,0,0.03);
    transition: 0.4s ease;
    text-align: left;
    border: 1px solid #eef2ef;
    display: flex;
    flex-direction: column;
    justify-content: space-between;
}

.card-top img {
    width: 100%;
    height: 240px;
    object-fit: cover;
    border-radius: 14px;
    margin-bottom: 20px;
}

.card h3 {
    font-size: 21px;
    color: #064d32;
    margin-bottom: 3px;
    font-weight: 600;
}

.card .en-title {
    font-size: 13px;
    color: #0b7a4b;
    margin-bottom: 12px;
    font-weight: 600;
    text-transform: uppercase;
    letter-spacing: 1px;
}

.card p {
    font-size: 14.5px;
    color: #555;
    line-height: 1.6;
    margin-bottom: 20px;
}

/* Order Button inside Cards */
.card-btn {
    background: #064d32;
    color: white;
    text-decoration: none;
    padding: 12px;
    border-radius: 12px;
    text-align: center;
    font-weight: bold;
    font-size: 14px;
    display: block;
    transition: 0.3s;
    box-shadow: 0 4px 10px rgba(6,77,50,0.15);
}

.card-btn:hover {
    background: #0b7a4b;
    transform: translateY(-2px);
}

.card:hover {
    transform: translateY(-12px);
    box-shadow: 0 20px 40px rgba(6,77,50,0.12);
    border-color: #c8e6c9;
}

/* Testimonials Section */
.testimonials {
    padding: 90px 8%;
    background: #ffffff;
    text-align: center;
}

.testimonials h2 {
    font-size: 34px;
    color: #064d32;
    margin-bottom: 50px;
}

.testimonial-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
    gap: 30px;
}

.testimonial-card {
    background: #f4f7f5;
    padding: 35px 25px;
    border-radius: 20px;
    text-align: left;
    position: relative;
}

.testimonial-card .quote-mark {
    font-size: 50px;
    color: #c8e6c9;
    position: absolute;
    top: 10px;
    right: 20px;
    line-height: 1;
}

.testimonial-card p {
    font-size: 15px;
    color: #444;
    line-height: 1.6;
    margin-bottom: 20px;
    font-style: italic;
}

.testimonial-card h4 {
    color: #064d32;
    font-size: 16px;
}

.testimonial-card span {
    font-size: 13px;
    color: #777;
}

/* FAQ Section */
.faq-section {
    padding: 90px 8%;
    background: #f9f9f9;
}

.faq-section h2 {
    text-align: center;
    font-size: 34px;
    color: #064d32;
    margin-bottom: 50px;
}

.faq-container {
    max-width: 800px;
    margin: 0 auto;
}

.faq-item {
    background: white;
    margin-bottom: 15px;
    border-radius: 12px;
    box-shadow: 0 4px 15px rgba(0,0,0,0.02);
    overflow: hidden;
    border: 1px solid #eef2ef;
}

.faq-question {
    padding: 20px;
    font-size: 17px;
    font-weight: 600;
    color: #064d32;
    cursor: pointer;
    display: flex;
    justify-content: space-between;
    align-items: center;
}

.faq-question::after {
    content: '+';
    font-size: 22px;
    color: #0b7a4b;
    transition: 0.3s;
}

.faq-item.active .faq-question::after {
    content: '−';
}

.faq-answer {
    padding: 0 20px;
    max-height: 0;
    overflow: hidden;
    transition: max-height 0.3s ease-out;
    color: #555;
    font-size: 15px;
    line-height: 1.6;
}

.faq-item.active .faq-answer {
    padding: 0 20px 20px 20px;
}

/* Contact Section */
.contact {
    background: #064d32;
    color: white;
    padding: 80px 8%;
    text-align: center;
}

.contact h2 {
    font-size: 34px;
    margin-bottom: 10px;
    font-weight: 700;
}

.contact .location-text {
    font-size: 16px;
    color: #c8e6c9;
    margin-bottom: 40px;
}

.contact-grid {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    gap: 20px;
    max-width: 900px;
    margin: 0 auto;
}

/* Clickable Link Styling */
.contact-method {
    background: rgba(255,255,255,0.08);
    padding: 18px 30px;
    border-radius: 15px;
    font-size: 17px;
    min-width: 260px;
    color: white;
    text-decoration: none;
    display: inline-block;
    transition: 0.3s ease;
    border: 1px solid rgba(255,255,255,0.1);
    font-weight: 500;
}

.contact-method:hover {
    background: #ffffff;
    color: #064d32;
    transform: translateY(-5px);
    box-shadow: 0 10px 20px rgba(0,0,0,0.2);
}

/* Floating Chat Button */
.floating-chat {
    position: fixed;
    bottom: 25px;
    right: 25px;
    background: #24A1DE; /* Telegram Blue */
    color: white;
    width: 60px;
    height: 60px;
    border-radius: 50%;
    display: flex;
    align-items: center;
    justify-content: center;
    box-shadow: 0 5px 20px rgba(0,0,0,0.3);
    text-decoration: none;
    font-size: 28px;
    z-index: 9999;
    transition: 0.3s ease;
}

.floating-chat:hover {
    transform: scale(1.1) rotate(10deg);
    background: #0b7a4b; /* Changes to Mark Furniture Green on hover */
}

/* Footer */
footer {
    background: #043321;
    color: #a5d6a7;
    text-align: center;
    padding: 25px;
    font-size: 14px;
    border-top: 1px solid #05402a;
}

/* Responsive for Mobile */
@media (max-width: 768px) {
    .hero-text h1 { font-size: 32px; }
    .hero-text p { font-size: 16px; }
    
    header {
        position: relative;
    }
    
    header nav {
        display: none;
        flex-direction: column;
        position: absolute;
        top: 100%;
        left: 0;
        width: 100%;
        background: #064d32;
        padding: 20px;
        box-shadow: 0 8px 15px rgba(0,0,0,0.2);
        border-top: 1px solid rgba(255,255,255,0.1);
    }
    
    header nav.active {
        display: flex;
    }
    
    nav a {
        margin: 12px 0;
        margin-left: 0;
        display: block;
        font-size: 16px;
        text-align: center;
    }
    
    .menu { 
        display: block; 
    }
    
    .cards { grid-template-columns: 1fr; }
    .video-placeholder { height: 250px; }
}
</style>

</head>
<body>

<header>
    <div class="logo">
        <img src="logo.png" alt="Mark Furniture Logo">
    </div>

    <nav id="navMenu">
        <a href="#">ዋና ገጽ / Home</a>
        <a href="#about">ስለ እኛ / About Us</a>
        <a href="#process">አሰራራችን / Process</a>
        <a href="#collections">ማሳያ ክፍል / Showroom</a>
        <a href="#testimonials">አስተያየቶች / Reviews</a>
        <a href="#faq">ጥያቄዎች / FAQ</a>
        <a href="#contact">ያግኙን / Contact</a>
    </nav>

    <button class="menu" id="menuBtn">☰</button>
</header>

<!-- Hero Section -->
<section class="hero">
    <div class="hero-text">
        <h1>Crafting Luxury Spaces For Elite Living</h1>
        <p>በኢትዮጵያ ውስጥ ለቤትዎ፣ ለቢሮዎ እና ለቪላዎ የሚመጥኑ እጅግ ቅንጡ፣ ዘመናዊ እና ውብ የቤት ዕቃዎች በጥራትና በባለሙያ እንሰራለን።</p>
        <a href="#contact" class="btn">ትዕዛዝ ለመስጠት / Order Now</a>
    </div>
</section>

<!-- NEW: About Us & Material Quality Section -->
<section id="about" class="about-section">
    <div class="about-grid">
        <div class="about-text">
            <!-- Free Delivery Banner -->
<div class="delivery-banner">
    🚚 የላቀ አገልግሎት — ማንኛውንም እቃ ሲያዙ ያሉበት ድረስ ያለምንም ተጨማሪ ክፍያ በነጻ እናደርሳለን! (Free Delivery Across Addis Ababa)
</div>
            <h2>ስለ ማርክ ፈርኒቸር (About Us)</h2>
            <p>ማርክ ፈርኒቸር በፈርኒቸር ማምረት እና በውስጥ ክፍል ማስዋብ (Interior Design) ዘርፍ ለረጅም ዓመታት ያካበተውን ልምድ በመጠቀም፣ ለደንበኞቹ እጅግ ዘመናዊ እና ጥራት ያላቸውን ምርቶች ያቀርባል። ዘመናዊ ማሽነሪዎችን በመጠቀምና እያንዳንዱን ዝርዝር ነገር በጥንቃቄ በመስራት የቤትዎ ግርማ ሞገስ እንድናድግ እናደርጋለን።</p>
            <p>የእኛ ልዩ መለያ ደንበኞቻችን የሚፈልጉትን ዲዛይን ሙሉ በሙሉ በ 3D እይታ አውጥተን፣ ከመመረቱ በፊት በትክክል እንዴት እንደሚያምር ማሳየት መቻላችን ነው።</p>
        </div>
        <div class="materials-box">
            <h3>የማቴሪያል ጥራት ዋስትና (Premium Materials)</h3>
            <p style="font-size: 14.5px; color: #666; margin-bottom: 15px;">ለምርቶቻችን ዘላቂነት ስንል ከፍተኛ ጥራት ያላቸውን ግብዓቶች ብቻ እንጠቀማለን፦</p>
            <ul>
                <li>የውሃና ሙቀት መቋቋም የሚችሉ የላቁ ላሚኔሽኖች (Waterproof Lamination)</li>
                <li>ጠንካራና ታዋቂ የሀገር ውስጥ እና የውጭ ሀገር እንጨቶች</li>
                <li>ለረጅም ጊዜ ጥንካሬያቸውን የማይለቁ ምርጥ ስፖንጅና ጨርቆች</li>
                <li>ጭረት እና ስብራትን የሚቋቋሙ ፕሪሚየም ማያያዣዎች (Hardware)</li>
            </ul>
        </div>
    </div>
</section>

<!-- Process Section -->
<section id="process" class="process-section">
    <h2>የክብር ደንበኞቻችን የትዕዛዝ ሂደት</h2>
    <p class="process-subtitle">ለየት ያሉ የቤት ዕቃዎችን በጥራት እና በፍጥነት የምናመርትበት 4 ወርቃማ ደረጃዎች</p>
    
    <div class="process-grid">
        <div class="process-card">
            <div class="step-number">1</div>
            <h3>ዲዛይን ማወቅ</h3>
            <div class="en-sub">Bespoke Design consultation</div>
            <p>የመጀመሪያው ደረጃ ከደንበኞቻችን ጋር በመመካከር በትክክል የሚፈልጉትን፣ ለቤታቸው የሚመጥነውን የፈርኒቸር ዲዛይንና መለኪያ በጥንቃቄ መለየት ነው።</p>
        </div>
        <div class="process-card">
            <div class="step-number">2</div>
            <h3>3D ሞዴል ማውጣት</h3>
            <div class="en-sub">3D Visualization & Modeling</div>
            <p>የተመረጠውን ዲዛይን እጅግ ዘመናዊ የ 3D ማሳያ (3D Model) በማውጣት፣ ስራው ከመጀመሩ በፊት ለደንበኛው በምስል እናሳይዎታለን።</p>
        </div>
        <div class="process-card">
            <div class="step-number">3</div>
            <h3>ትክክለኛ ዋጋ ማሳወቅ</h3>
            <div class="en-sub">Transparent Quotation</div>
            <p>የእቃው ዝርዝርና ዲዛይን ከጸደቀ በኋላ፣ ያለምንም የተደበቀ ክፍያ ትክክለኛውንና ተመጣጣኝ የሆነውን ዋጋ በግልጽ እናሳውቃለን።</p>
        </div>
        <div class="process-card">
            <div class="step-number">4</div>
            <h3>በ2 ሳምንት ማድረስ</h3>
            <div class="en-sub">Guaranteed 2-Week Delivery</div>
            <p>ትዕዛዝዎን በከፍተኛ ጥራትና ጥንቃቄ አጠናቀን በ2 ሳምንት ባልሞላ ሙሉ ጊዜ ውስጥ ያሉበት ድረስ በፍጥነት እናስረክባለን።</p>
        </div>
    </div>
</section>
<!-- Collections & Services Section -->
<section id="collections" class="categories">
    <h2>የቅንጦት ምርቶች እና አገልግሎቶች ማሳያ</h2>
    <p class="section-desc">ከምርጥ እንጨቶች እና ዘመናዊ ግብዓቶች የተሰሩ የፈርኒቸር ስብስቦች ለላቀ የትዕዛዝ ስራ (Our Premium Showcase)</p>
    
    <div class="cards">

        <!-- Card 1: Sofa -->
        <div class="card">
            <div class="card-top">
                <img src="sofa.jpg" alt="Premium Sofa Set">
                <h3>የቅንጦት ሶፋ ስብስቦች</h3>
                <div class="en-title">Luxury Sofa & Lounge Sets</div>
                <p>በከፍተኛ ጥራት ከተመረጡ ውድ ጨርቆች እና ዘላቂ ስፖንጅዎች የተሰሩ፣ ለሳሎንዎ ልዩ ድምቀት እና ምቾት የሚሰጡ ሶፋዎች።</p>
            </div>
            <a href="https://t.me/lanyisu1?text=ሰላም%20ማርክ%20ፈርኒቸር፣%20የሶፋ%20ስብስቦችን%20ማዘዝ%20ወይም%20ዋጋ%20ጠይቅ%20ፈልጌ%20ነበር።" target="_blank" class="card-btn">በቴሌግራም እዘዝ / Order via TG</a>
        </div>

        <!-- Card 2: Bed -->
        <div class="card">
            <div class="card-top">
                <img src="bed.jpg" alt="Luxury Master Bed">
                <h3>ማራኪ የአልጋ ስብስቦች</h3>
                <div class="en-title">Premium Bedroom Masterpieces</div>
                <p>ለመኝታ ቤትዎ ንጉሳዊ ክብርን የሚያጎናጽፉ፣ ከጠንካራ እንጨት የተሰሩና ዘመናዊ ስታይል ያላቸው ውብ አልጋዎች።</p>
            </div>
            <a href="https://t.me/lanyisu1?text=ሰላም%20ማርክ%20ፈርኒቸር፣%20የአልጋ%20ስብስቦችን%20ማዘዝ%20ወይም%20ዋጋ%20ጠይቅ%20ፈልጌ%20ነበር።" target="_blank" class="card-btn">በቴሌግራም እዘዝ / Order via TG</a>
        </div>

        <!-- Card 3: TV Stand -->
        <div class="card">
            <div class="card-top">
                <img src="tv stand.jpg" alt="Modern TV Stand">
                <h3>ዘመናዊ የቲቪ ማስቀመጫዎች</h3>
                <div class="en-title">Premium TV Units & Consoles</div>
                <p>ለሳሎንዎ ዘመናዊ መልክ የሚሰጡ፣ ሽቦዎችን የሚደብቁ እና ተጨማሪ መደርደሪያዎች ያሏቸው የላቁ የቲቪ ስታንዶች።</p>
            </div>
            <a href="https://t.me/lanyisu1?text=ሰላም%20ማርክ%20ፈርኒቸር፣%20የቲቪ%20ማስቀመጫዎችን%20ማዘዝ%20ወይም%20ዋጋ%20ጠይቅ%20ፈልጌ%20ነበር።" target="_blank" class="card-btn">በቴሌግራም እዘዝ / Order via TG</a>
        </div>

        <!-- Card 4: Kitchen Cabinet -->
        <div class="card">
            <div class="card-top">
                <img src="kitchen cabinet .png" alt="Luxury Kitchen Cabinet">
                <h3>የተዋቡ የኩሽና ካቢኔቶች</h3>
                <div class="en-title">Bespoke Kitchen Cabinets</div>
                <p>የማብሰያ ክፍልዎን ሰፊ፣ ምቹ እና ማራኪ የሚያደርጉ፣ ውሃና ሙቀት የሚቋቋሙ ዘመናዊ የካቢኔት ስራዎች።</p>
            </div>
            <a href="https://t.me/lanyisu1?text=ሰላም%20ማርክ%20ፈርኒቸር፣%20የኩሽና%20ካቢኔት%20ስራዎችን%20ማዘዝ%20ወይም%20ዋጋ%20ጠይቅ%20ፈልጌ%20ነበር።" target="_blank" class="card-btn">በቴሌግራም እዘዝ / Order via TG</a>
        </div>

        <!-- Card 5: Dining Table -->
        <div class="card">
            <div class="card-top">
                <img src="diring teble.jpg" alt="Premium Dining Table">
                <h3>የምግብ ጠረጴዛ ስራዎች</h3>
                <div class="en-title">Elegant Dining Tables</div>
                <p>ከቤተሰብ እና ከወዳጅ ጋር የሚያሳልፉትን ጊዜ የሚያጣፍጡ፣ ከላቁ ማቴሪያሎች የተሰሩ ውብ የምግብ ጠረጴዛዎች።</p>
            </div>
            <a href="https://t.me/lanyisu1?text=ሰላም%20ማርክ%20ፈርኒቸር፣%20የምግብ%20ጠረጴዛዎችን%20ማዘዝ%20ወይም%20ዋጋ%20ጠይቅ%20ፈልጌ%20ነበር።" target="_blank" class="card-btn">በቴሌግራም እዘዝ / Order via TG</a>
        </div>

        <!-- Card 6: Dressing Table -->
        <div class="card">
            <div class="card-top">
                <img src="drassing.jpg" alt="Premium Dressing Table">
                <h3>የልብስ መቀየሪያና ሜካፕ ጠረጴዛ</h3>
                <div class="en-title">Luxury Vanity & Dressing Tables</div>
                <p>ዘመናዊ መስተዋት እና ሰፊ የእቃ ማደራጃ መሳቢያዎች ያሏቸው፣ ለመኝታ ቤት ውበት የሚጨምሩ ድንቅ ስራዎች።</p>
            </div>
            <a href="https://t.me/lanyisu1?text=ሰላም%20ማርክ%20ፈርኒቸር፣%20የልብስ%20መቀየሪያና%20ሜካፕ%20ጠረጴዛዎች%20ማዘዝ%20ወይም%20ዋጋ%20ጠይቅ%20ፈልጌ%20ነበር።" target="_blank" class="card-btn">በቴሌግራም እዘዝ / Order via TG</a>
        </div>

        <!-- Card 7: Table -->
        <div class="card">
            <div class="card-top">
                <img src="table.jpg" alt="Premium Office and Center Table">
                <h3>የማዕዘን እና የቢሮ ጠረጴዛዎች</h3>
                <div class="en-title">Executive Desks & Coffee Tables</div>
                <p>ለሳሎን ማጀቢያ የሚሆኑ ማራኪ የቡና ጠረጴዛዎች እንዲሁም ለስራ ቦታዎ ግርማ ሞገስ የሚሰጡ የቢሮ ጠረጴዛዎች።</p>
            </div>
            <a href="https://t.me/lanyisu1?text=ሰላም%20ማርክ%20ፈርኒቸር፣%20የቢሮና%20የማዕዘን%20ጠረጴዛዎችን%20ማዘዝ%20ወይም%20ዋጋ%20ጠይቅ%20ፈልጌ%20ነበር።" target="_blank" class="card-btn">በቴሌግራም እዘዝ / Order via TG</a>
        </div>

        <!-- Card 8: Door -->
        <div class="card">
            <div class="card-top">
                <img src="door .jpg" alt="Premium Wooden Door">
                <h3>ጠንካራ የቤት በሮች</h3>
                <div class="en-title">Architectural Wooden Doors</div>
                <p>ለቤትዎ አስተማማኝ ጥበቃ እና ውጫዊ ውበት የሚሰጡ፣ ከተመረጡ ጠንካራ እንጨቶች የተሰሩ ፕሪሚየም በሮች።</p>
            </div>
            <a href="https://t.me/lanyisu1?text=ሰላም%20ማርክ%20ፈርኒቸር፣%20ጠንካራ%20የቤት%20በሮችን%20ማዘዝ%20ወይም%20ዋጋ%20ጠይቅ%20ፈልጌ%20ነበር።" target="_blank" class="card-btn">በቴሌግራም እዘዝ / Order via TG</a>
        </div>

        <!-- Card 9: Modern Lines -->
        <div class="card">
            <div class="card-top">
                <img src="horizontal line .png" alt="Modern Wall Slats">
                <h3>የጌጣጌጥ መስመሮች (ወረንቶዎች)</h3>
                <div class="en-title">Luxury Wall Slats & Design Lines</div>
                <p>ለቲቪ ጀርባ እና ለግድግዳ ማሳመሪያ የሚሆኑ፣ አሁን ላይ በዘመናዊ ቤቶች ውስጥ በስፋት የሚፈለጉ ማራኪ መስመሮች።</p>
            </div>
            <a href="https://t.me/lanyisu1?text=ሰላም%20ማርክ%20ፈርኒቸር፣%20የጌጣጌጥ%20መስመሮች%20(ወረንቶዎች)%20ማዘዝ%20ወይም%20ዋጋ%20ጠይቅ%20ፈልጌ%20ነበር።" target="_blank" class="card-btn">በቴሌግራም እዘዝ / Order via TG</a>
        </div>

        <!-- Card 10: 3D Design -->
        <div class="card">
            <div class="card-top">
                <img src="3D.jpg" alt="Real 3D Interior Design">
                <h3>የ 3D ዲዛይን እና የውስጥ ክፍል ማስዋብ</h3>
                <div class="en-title">Elite 3D Modeling & Interior Design</div>
                <p>ማንኛውም ስራ ከመጀመሩ በፊት በኮምፒውተር እውነተኛ እይታ (High-end 3D Render) አውጥተን መላውን የቤትዎን ክፍል እናስውባለን።</p>
            </div>
            <a href="https://t.me/lanyisu1?text=ሰላም%20ማርክ%20ፈርኒቸር፣%20የ3D%20ዲዛይንና%20ኢንቴሪየር%20ስራዎችን%20ማዘዝ%20ወይም%20ዋጋ%20ጠይቅ%20ፈልጌ%20ነበር።" target="_blank" class="card-btn">በቴሌግራም እዘዝ / Order via TG</a>
        </div>

    </div>
</section>

<!-- NEW: Customer Testimonials Section -->
<section id="testimonials" class="testimonials">
    <h2>የክብር ደንበኞቻችን ምስክርነት (Testimonials)</h2>
    <div class="testimonial-grid">
        <div class="testimonial-card">
            <div class="quote-mark">“</div>
            <p>ለአዲሱ ቤታችን የኩሽና ካቢኔት እና ሶፋ ያሰራነው እዚህ ነው። ስራው ከመጀመሩ በፊት በ 3D ያሳዩን እይታ እና በተጨባጭ የተሰራው እቃ አንድ አይነት ነው! በጥራታቸው በጣም ረክተናል።</p>
            <h4>ዮናስ አልሙ</h4>
            <span>አዲስ አበባ፣ ቪላ ባለቤት</span>
        </div>
        <div class="testimonial-card">
            <div class="quote-mark">“</div>
            <p>የቲቪ ስታንድ እና የጌጣጌጥ ግድግዳ መስመሮች አሰርቻለሁ። በ2 ሳምንት ውስጥ በነጻ ትራንስፖርት ያሉበት ድረስ ማድረሳቸው እና የፊኒሺንግ ጥራታቸው እጅግ አስደንቆኛል። ለሁሉም ሰው እመክራቸዋለሁ።</p>
            <h4>ሄለን ተስፋዬ</h4>
            <span>አፓርትመንት ነዋሪ</span>
        </div>
    </div>
</section>

<!-- NEW: FAQ Section -->
<section id="faq" class="faq-section">
    <h2>በተደጋጋሚ የሚጠየቁ ጥያቄዎች (FAQ)</h2>
    <div class="faq-container">
        <div class="faq-item">
            <div class="faq-question">የራሳችንን የተለየ ዲዛይን ብናመጣ ትሰራላችሁ?</div>
            <div class="faq-answer">አዎ፣ ሙሉ በሙሉ የትኛውንም ያመጡትን ዲዛይን የእርስዎን ቤት ልኬት መሰረት አድርገን በጥራት እንሰራለን። በተጨማሪም ስራው ከመጀመሩ በፊት በ3D አውጥተን እናሳየዎታለን።</div>
        </div>
        <div class="faq-item">
            <div class="faq-question">የክፍያ አፈጻጸማችሁ እንዴት ነው?</div>
            <div class="faq-answer">ትዕዛዝ በሚሰጡበት ጊዜ ለጥሬ ዕቃ ግዢ የሚሆን የተወሰነ መቶኛ ቅድመ ክፍያ (Advance Payment) የሚከፈል ሲሆን፣ ቀሪውን ክፍያ ሙሉ ስራው አልቆ ያሉበት ድረስ በነጻ አድርሰን እቃውን ሲረከቡ የሚፈጽሙት ይሆናል።</div>
        </div>
        <div class="faq-item">
            <div class="faq-question">ከአዲስ አበባ ውጪ ያሉ ከተሞች ላይ ትዕዛዝ ትቀበላላችሁ?</div>
            <div class="faq-answer">አዎ፣ ከአዲስ አበባ ውጪ ላሉ ከተሞች ትዕዛዝ እንቀበላለን። ነገር ግን የነጻ ማመላለሻ (Free Delivery) አገልግሎታችን ለአዲስ አበባ ዙሪያ ብቻ ሲሆን፣ ከከተማ ውጪ ላሉት በተመጣጣኝ የትራንስፖርት ክፍያ እናደርሳለን።</div>
        </div>
    </div>
</section>

<!-- Contact Section (Updated with Location Layout) -->
<section id="contact" class="contact">
    <h2>ትዕዛዝ ለመስጠት እና እኛን ለማግኘት</h2>
    <p class="location-text">📍 አድራሻችን፦ አዲስ አበባ፣ ኢትዮጵያ (ዋናው ዎርክሾፕ እና ማሳያ ቦታ)</p>
    <div class="contact-grid">
        <a href="tel:+251991710545" class="contact-method">📞 +251 991 710 545</a>
        <a href="tel:+251911664492" class="contact-method">📞 +251 911 664 492</a>
        <a href="mailto:yisuteka@gmail.com" class="contact-method">📧 yisuteka@gmail.com</a>
        <a href="https://instagram.com/lan_yisu" target="_blank" class="contact-method">Instagram: @lan_yisu</a>
        <a href="https://t.me/lanyisu1" target="_blank" class="contact-method">Telegram: @lanyisu1</a>
    </div>
</section>

<!-- NEW: Floating Telegram Chat Button -->
<a href="https://t.me/lanyisu1" target="_blank" class="floating-chat" title="Chat on Telegram">✈</a>

<footer>
    <p>© 2026 Mark Furniture. All Rights Reserved. Crafted with Luxury in Mind.</p>
</footer>

<!-- JavaScript for Hamburger Menu & FAQ Accordion -->
<script>
    // Hamburger Menu Logic
    const menuBtn = document.getElementById('menuBtn');
    const navMenu = document.getElementById('navMenu');

    menuBtn.addEventListener('click', () => {
        navMenu.classList.toggle('active');
    });

    const navLinks = document.querySelectorAll('#navMenu a');
    navLinks.forEach(link => {
        link.addEventListener('click', () => {
            navMenu.classList.remove('active');
        });
    });

    // FAQ Accordion Logic
    const faqQuestions = document.querySelectorAll('.faq-question');
    faqQuestions.forEach(question => {
        question.addEventListener('click', () => {
            const item = question.parentElement;
            const answer = question.nextElementSibling;
            
            // Toggle active class
            item.classList.toggle('active');
            
            if (item.classList.contains('active')) {
                answer.style.maxHeight = answer.scrollHeight + "px";
            } else {
                answer.style.maxHeight = "0";
            }
        });
    });
</script>
<!-- ======================================================== -->
<!-- አዲስ፡ የአስተያየት እና የኮከብ (5-Star Rating) መስጫ ክፍል -->
<!-- ======================================================== -->
<section id="user-feedback" class="feedback-section">
    <div class="feedback-container">
        <h2>እርስዎም አስተያየትዎን ያጋሩን (Leave a Review)</h2>
        <p>የእርስዎ አስተያየት ለእኛ ትልቅ ዋጋ አለው። እባክዎ የ5 ኮከብ ደረጃ እና አጭር አስተያየት ይተውልን።</p>
        
        <form id="feedbackForm">
            <!-- Star Rating System -->
            <div class="rating-stars">
                <span class="star" data-value="1">★</span>
                <span class="star" data-value="2">★</span>
                <span class="star" data-value="3">★</span>
                <span class="star" data-value="4">★</span>
                <span class="star" data-value="5">★</span>
            </div>
            <!-- Hidden input to store rating value -->
            <input type="hidden" id="selectedRating" value="0">
            
            <!-- Input Fields -->
            <input type="text" id="reviewerName" placeholder="የእርስዎ ስም (Your Name)" required>
            <textarea id="reviewerComment" rows="4" placeholder="የእርስዎ አስተያየት (Your Comment...)" required></textarea>
            
            <button type="submit" class="submit-feedback-btn">አስተያየት አቅርብ / Submit Review</button>
        </form>

        <!-- Display Area for Submitted Comments -->
        <div class="submitted-comments-box">
            <h3>የደንበኞች የቅርብ ጊዜ አስተያየቶች</h3>
            <div id="commentsDisplayList">
                <!-- አዳዲስ አስተያየቶች በጃቫስክሪፕት አማካኝነት እዚህ ውስጥ ይገባሉ -->
            </div>
        </div>
    </div>
</section>

<style>
.feedback-section {
    padding: 90px 8%;
    background: #fdfdfd;
    border-top: 1px solid #eef2ef;
    text-align: center;
}
.feedback-container {
    max-width: 700px;
    margin: 0 auto;
}
.feedback-container h2 {
    font-size: 32px;
    color: #064d32;
    margin-bottom: 10px;
    font-weight: 700;
}
.feedback-container p {
    color: #666;
    margin-bottom: 30px;
    font-size: 15px;
}
#feedbackForm {
    background: white;
    padding: 35px;
    border-radius: 20px;
    box-shadow: 0 10px 35px rgba(0,0,0,0.03);
    border: 1px solid #eef2ef;
    margin-bottom: 50px;
}
.rating-stars {
    margin-bottom: 20px;
}
.star {
    font-size: 38px;
    color: #ccc;
    cursor: pointer;
    transition: 0.2s;
    margin: 0 5px;
    display: inline-block;
}
.star:hover,
.star.hovered,
.star.selected {
    color: #ffc107; /* Gold Color */
}
#reviewerName, #reviewerComment {
    width: 100%;
    padding: 14px;
    margin-bottom: 15px;
    border: 1px solid #cccccc;
    border-radius: 10px;
    font-size: 15px;
    outline: none;
    transition: 0.3s;
}
#reviewerName:focus, #reviewerComment:focus {
    border-color: #064d32;
    box-shadow: 0 0 8px rgba(6,77,50,0.1);
}
.submit-feedback-btn {
    background: #064d32;
    color: white;
    border: none;
    padding: 15px 30px;
    font-size: 16px;
    font-weight: bold;
    border-radius: 10px;
    cursor: pointer;
    width: 100%;
    transition: 0.3s;
    text-transform: uppercase;
    letter-spacing: 0.5px;
}
.submit-feedback-btn:hover {
    background: #0b7a4b;
}

/* Comments Display Style */
.submitted-comments-box {
    text-align: left;
    margin-top: 20px;
}
.submitted-comments-box h3 {
    color: #064d32;
    font-size: 20px;
    margin-bottom: 20px;
    border-bottom: 2px solid #eef2ef;
    padding-bottom: 8px;
}
.single-comment {
    background: #f4f7f5;
    padding: 20px;
    border-radius: 12px;
    margin-bottom: 15px;
    border-left: 5px solid #0b7a4b;
    box-shadow: 0 2px 8px rgba(0,0,0,0.01);
}
.single-comment .comment-header {
    display: flex;
    justify-content: space-between;
    align-items: center;
    margin-bottom: 8px;
}
.single-comment .comment-name {
    font-weight: bold;
    color: #064d32;
    font-size: 15.5px;
}
.single-comment .comment-stars {
    color: #ffc107;
    font-size: 16px;
    letter-spacing: 2px;
}
.single-comment .comment-text {
    font-size: 14.5px;
    color: #444;
    line-height: 1.6;
}
</style>

<script>
document.addEventListener('DOMContentLoaded', () => {
    const stars = document.querySelectorAll('.star');
    const ratingInput = document.getElementById('selectedRating');
    const feedbackForm = document.getElementById('feedbackForm');
    const commentsDisplayList = document.getElementById('commentsDisplayList');

    // 1. Star Rating Interactive Logic
    stars.forEach(star => {
        star.addEventListener('click', () => {
            const value = star.getAttribute('data-value');
            ratingInput.value = value;
            
            stars.forEach(s => {
                
                    <p class="comment-text">${c.text}</p>
                </div>
            `;
        });
    }

    // Initial render
    renderComments();

    // 3. Form Submission Logic
    feedbackForm.addEventListener('submit', (e) => {
        e.preventDefault();
        const name = document.getElementById('reviewerName').value.trim();
        const comment = document.getElementById('reviewerComment').value.trim();
        const rating = parseInt(ratingInput.value);

        if(rating === 0) {
            alert("እባክዎ መጀመሪያ ከኮከቦቹ ላይ ደረጃ (Rating) ይምረጡ!");
            return;
        }

        // Add new review to the top of the array
        localComments.unshift({ name: name, rating: rating, text: comment });
        
        // Save back to local storage
        localStorage.setItem('markFurnitureReviews', JSON.stringify(localComments));
        
        // Re-render list and reset form
        renderComments();
        feedbackForm.reset();
        stars.forEach(s => s.classList.remove('selected'));
        ratingInput.value = "0";
    });
});
</script>

</body>
</html>
