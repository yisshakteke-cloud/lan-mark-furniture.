<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Mark Furniture - Luxury Interior & Furniture</title>

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
    font-size: 25px;
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
}

.btn:hover {
    background: #ffffff;
    color: #064d32;
    transform: translateY(-3px);
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

/* Collections & Services Section */
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
}

.card img {
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
}

.card:hover {
    transform: translateY(-12px);
    box-shadow: 0 20px 40px rgba(6,77,50,0.12);
    border-color: #c8e6c9;
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
    margin-bottom: 25px;
    font-weight: 700;
}

.contact-grid {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    gap: 30px;
    max-width: 900px;
    margin: 0 auto;
}

.contact-method {
    background: rgba(255,255,255,0.08);
    padding: 15px 25px;
    border-radius: 12px;
    font-size: 17px;
    min-width: 250px;
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
    header nav { display: none; }
    .menu { display: block; }
    .cards { grid-template-columns: 1fr; }
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
        <a href="#collections">ማሳያ ክፍል / Showroom</a>
        <a href="#contact">ያግኙን / Contact</a>
    </nav>

    <button class="menu">☰</button>
</header>

<!-- Free Delivery Banner -->
<div class="delivery-banner">
    🚚 የላቀ አገልግሎት — ማንኛውንም እቃ ሲያዙ ያሉበት ድረስ ያለምንም ተጨማሪ ክፍያ በነጻ እናደርሳለን! (Free Delivery Across Addis Ababa)
</div>

<section class="hero">
    <div class="hero-text">
        <h1>Crafting Luxury Spaces For Elite Living</h1>
        <p>በኢትዮጵያ ውስጥ ለቤትዎ፣ ለቢሮዎ እና ለቪላዎ የሚመጥኑ እጅግ ቅንጡ፣ ዘመናዊ እና ውብ የቤት ዕቃዎች በጥራትና በባለሙያ እንሰራለን።</p>
        <a href="#contact" class="btn">ትዕዛዝ ለመስጠት / Order Now</a>
    </div>
</section>

<!-- Process Section -->
<section id="process" class="process-section">
    <h2>የክብር ደንበኞቻችን የትዕዛዝ ሂደት</h2>
    <p class="process-subtitle">ለየት ያሉ የቤት ዕቃዎችን በጥራት እና በፍጥነት የምናመርትበት 4 ወርቃማ ደረጃዎች</p>
    
    <div class="process-grid">
        
        <!-- Step 1 -->
        <div class="process-card">
            <div class="step-number">1</div>
            <h3>ዲዛይን ማወቅ</h3>
            <div class="en-sub">Bespoke Design consultation</div>
            <p>የመጀመሪያው ደረጃ ከደንበኞቻችን ጋር በመመካከር በትክክል የሚፈልጉትን፣ ለቤታቸው የሚመጥነውን የፈርኒቸር ዲዛይንና መለኪያ በጥንቃቄ መለየት ነው።</p>
        </div>

        <!-- Step 2 -->
        <div class="process-card">
            <div class="step-number">2</div>
            <h3>3D ሞዴል ማውጣት</h3>
            <div class="en-sub">3D Visualization & Modeling</div>
            <p>የተመረጠውን ዲዛይን እጅግ ዘመናዊ የ 3D ማሳያ (3D Model) በማውጣት፣ ስራው ከመጀመሩ በፊት ለደንበኛው በምስል እናሳይዎታለን።</p>
        </div>

        <!-- Step 3 -->
        <div class="process-card">
            <div class="step-number">3</div>
            <h3>ትክክለኛ ዋጋ ማሳወቅ</h3>
            <div class="en-sub">Transparent Quotation</div>
            <p>የእቃው ዝርዝርና ዲዛይን ከጸደቀ በኋላ፣ ያለምንም የተደበቀ ክፍያ ትክክለኛውንና ተመጣጣኝ የሆነውን ዋጋ በግልጽ እናሳውቃለን።</p>
        </div>

        <!-- Step 4 -->
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

        <!-- Card 1: Sofa (New!) -->
        <div class="card">
            <img src="sofa.jpg" alt="Premium Sofa Set">
            <h3>የቅንጦት ሶፋ ስብስቦች</h3>
            <div class="en-title">Luxury Sofa & Lounge Sets</div>
            <p>በከፍተኛ ጥራት ከተመረጡ ውድ ጨርቆች እና ዘላቂ ስፖንጅዎች የተሰሩ፣ ለሳሎንዎ ልዩ ድምቀት እና ምቾት የሚሰጡ ሶፋዎች።</p>
        </div>

        <!-- Card 2: Bed (New!) -->
        <div class="card">
            <img src="bed.jpg" alt="Luxury Master Bed">
            <h3>ማራኪ የአልጋ ስብስቦች</h3>
            <div class="en-title">Premium Bedroom Masterpieces</div>
            <p>ለመኝታ ቤትዎ ንጉሳዊ ክብርን የሚያጎናጽፉ፣ ከጠንካራ እንጨት የተሰሩና ዘመናዊ ስታይል ያላቸው ውብ አልጋዎች።</p>
        </div>

        <!-- Card 3: TV Stand -->
        <div class="card">
            <img src="tv stand.jpg" alt="Modern TV Stand">
            <h3>ዘመናዊ የቲቪ ማስቀመጫዎች</h3>
            <div class="en-title">Premium TV Units & Consoles</div>
            <p>ለሳሎንዎ ዘመናዊ መልክ የሚሰጡ፣ ሽቦዎችን የሚደብቁ እና ተጨማሪ መደርደሪያዎች ያሏቸው የላቁ የቲቪ ስታንዶች።</p>
        </div>

        <!-- Card 4: Kitchen Cabinet -->
        <div class="card">
            <img src="kitchen cabinet .png" alt="Luxury Kitchen Cabinet">
            <h3>የተዋቡ የኩሽና ካቢኔቶች</h3>
            <div class="en-title">Bespoke Kitchen Cabinets</div>
            <p>የማብሰያ ክፍልዎን ሰፊ፣ ምቹ እና ማራኪ የሚያደርጉ፣ ውሃና ሙቀት የሚቋቋሙ ዘመናዊ የካቢኔት ስራዎች።</p>
        </div>

        <!-- Card 5: Dining Table -->
        <div class="card">
            <img src="diring teble.jpg" alt="Premium Dining Table">
            <h3>የምግብ ጠረጴዛ ስራዎች</h3>
            <div class="en-title">Elegant Dining Tables</div>
            <p>ከቤተሰብ እና ከወዳጅ ጋር የሚያሳልፉትን ጊዜ የሚያጣፍጡ፣ ከላቁ ማቴሪያሎች የተሰሩ ውብ የምግብ ጠረጴዛዎች።</p>
        </div>

        <!-- Card 6: Dressing Table (New!) -->
        <div class="card">
            <img src="drassing.jpg" alt="Premium Dressing Table">
            <h3>የልብስ መቀየሪያና ሜካፕ ጠረጴዛ</h3>
            <div class="en-title">Luxury Vanity & Dressing Tables</div>
            <p>ዘመናዊ መስተዋት እና ሰፊ የእቃ ማደራጃ መሳቢያዎች ያሏቸው፣ ለመኝታ ቤት ውበት የሚጨምሩ ድንቅ ስራዎች።</p>
        </div>

        <!-- Card 7: Table (New!) -->
        <div class="card">
            <img src="table.jpg" alt="Premium Office and Center Table">
            <h3>የማዕዘን እና የቢሮ ጠረጴዛዎች</h3>
            <div class="en-title">Executive Desks & Coffee Tables</div>
            <p>ለሳሎን ማጀቢያ የሚሆኑ ማራኪ የቡና ጠረጴዛዎች እንዲሁም ለስራ ቦታዎ ግርማ ሞገስ የሚሰጡ የቢሮ ጠረጴዛዎች።</p>
        </div>

        <!-- Card 8: Door -->
        <div class="card">
            <img src="door .jpg" alt="Premium Wooden Door">
            <h3>ጠንካራ የቤት በሮች</h3>
            <div class="en-title">Architectural Wooden Doors</div>
            <p>ለቤትዎ አስተማማኝ ጥበቃ እና ውጫዊ ውበት የሚሰጡ፣ ከተመረጡ ጠንካራ እንጨቶች የተሰሩ ፕሪሚየም በሮች።</p>
        </div>

        <!-- Card 9: Modern Lines -->
        <div class="card">
            <img src="horizontal line .png" alt="Modern Wall Slats">
            <h3>የጌጣጌጥ መስመሮች (ወረንቶዎች)</h3>
            <div class="en-title">Luxury Wall Slats & Design Lines</div>
            <p>ለቲቪ ጀርባ እና ለግድግዳ ማሳመሪያ የሚሆኑ፣ አሁን ላይ በዘመናዊ ቤቶች ውስጥ በስፋት የሚፈለጉ ማራኪ መስመሮች።</p>
        </div>

        <!-- Card 10: 3D Design (Updated with real image!) -->
        <div class="card">
            <img src="3D.jpg" alt="Real 3D Interior Design">
            <h3>የ 3D ዲዛይን እና የውስጥ ክፍል ማስዋብ</h3>
            <div class="en-title">Elite 3D Modeling & Interior Design</div>
            <p>ማንኛውም ስራ ከመጀመሩ በፊት በኮምፒውተር እውነተኛ እይታ (High-end 3D Render) አውጥተን መላውን የቤትዎን ክፍል እናስውባለን።</p>
        </div>

    </div>
</section>

<!-- Contact Section -->
<section id="contact" class="contact">
    <h2>ትዕዛዝ ለመስጠት እና እኛን ለማግኘት</h2>
    <div class="contact-grid">
        <div class="contact-method">📞 +251 991 710 545</div>
        <div class="contact-method">📞 +251 911 664 492</div>
        <div class="contact-method">📧 yisuteka@gmail.com</div>
        <div class="contact-method">Instagram: @lan_yisu</div>
        <div class="contact-method">Telegram: @lanyisu1</div>
    </div>
</section>

<footer>
    <p>© 2026 Mark Furniture. All Rights Reserved. Crafted with Luxury in Mind.</p>
</footer>

</body>
</html>
