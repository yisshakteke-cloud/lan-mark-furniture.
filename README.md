by                                   
                         margin: 0;
            color: #d7ccc8; /* ቀለል ያለ ቡናማ */
        }

        h2 {
            font-size: 2.5em;
            margin: 10px 0;
            font-weight: normal;
        }

        p {
            font-size: 1.2em;
            margin-top: 20px;
        }
    </style>
</head>
<body>

    <div class="container">
        <div class="logo-area">
            <!-- ፎቶህን ለማስገባት፡-
                 1. ፎቶህን "furniture.jpg" ብለህ ስም ስጠው
                 2. ከዚህ የHTML ፋይል ጋር በአንድ ፎልደር ውስጥ አስቀምጠው
                 3. ከታች ያለውን የፓዝ መስመር አስተካክል -->
            <img src="YOUR_IMAGE_PATH_HERE.jpg" alt="የአቦሌ ፈርኒቸር ማሳያ" class="furniture-pic">
        </div>
        
        
ይህ ስህተት (HTTP ERROR 400) አብዛኛውን ጊዜ የሚመጣው በስልክህ ፎቶዎችን ስትጭን ወይም ሴቭ ስታደርግ ኢንተርኔት ሲቋረጥ ወይም ገጹ ሲጨናነቅ ነው [Screenshot_20260709-180001.png]። ምንም አታስብ፣ በቀላሉ ማስተካከል ይቻላል!

ይህን ለማስተካከል እነዚህን 3 ቀላል ደረጃዎች ተከተል፦
asgbch

    </style>
</head>
<body>

    <!-- 1. የላይኛው አግድም ፎቶ (የጫንከው ስም) -->
    <img src="horizontal line .png" alt="Abole Furniture Premium Banner" class="hero-banner">

    <div class="container">
        <header>
            <h1 class="brand-english">Abole Furniture</h1>
            <h2 class="brand-amharic">አቦሌ ፈርኒቸር</h2>
        </header>

        <section>
            <h2 class="section-title">ስለ ድርጅታችን</h2>
            <div class="about-box">
                <p><strong>ጥራት እና ጥንካሬ መለያችን ነው!</strong> አቦሌ ፈርኒቸር ለቤትዎ፣ ለቢሮዎ እና ለተለያዩ ተቋማት የሚሆኑ ውብ፣ ዘመናዊ እና አስተማማኝ የቤት ዕቃዎችን በጥራት እና በጥንካሬ አምርቶ ያቀርባል።</p>
            </div>
        </section>

        <section>
            <h2 class="section-title">የምርቶቻችን ማሳያ</h2>
            <div class="gallery-grid">
                
                <!-- TV Stand -->
                <div class="gallery-item">
                    <img src="tv stand.jpg" alt="Modern TV Stand">
                    <div class="gallery-info"><h3>ዘመናዊ የቲቪ ስታንድ (TV Stand)</h3></div>
                </div>

                <!-- Dining Table -->
                <div class="gallery-item">
                    <img src="diring teble.jpg" alt="Luxury Dining Table">
                    <div class="gallery-info"><h3>የማዕድ ጠረጴዛዎች (Dining Table)</h3></div>
                </div>

                <!-- Door -->
                <div class="gallery-item">
                    <img src="door .jpg" alt="Luxury Door">
                    <div class="gallery-info"><h3>የቤት በሮች (Doors)</h3></div>
                </div>

                <!-- Kitchen Cabinet -->
                <div class="gallery-item">
                    <img src="kitchen cabinet .png" alt="Kitchen Cabinet">
                    <div class="gallery-info"><h3>የኩሽና ካቢኔቶች (Kitchen Cabinet)</h3></div>
                </div>

            </div>
        </section>

        <section>
            <h2 class="section-title">የደንበኞች አስተያየት</h2>
            <div class="reviews-container">
                <div class="review-card"><div class="stars">⭐⭐⭐⭐⭐</div><p class="review-text">"የአቦሌ ፈርኒቸር ዕቃዎች በጣም ጠንካራ እና ውብ ናቸው። ስራቸው ፍፁም ጥራት አለው!"</p></div>
                <div class="review-card"><div class="stars">⭐⭐⭐⭐⭐</div><p class="review-text">"በአቀጣጠራቸው እና በስራ ጥራታቸው በጣም ረክተናል። 5 ኮከብ ይገባቸዋል።"</p></div>
                <div class="review-card"><div class="stars">⭐⭐⭐⭐⭐</div><p class="review-text">"ዘመናዊ ዲዛይን ከጥንካሬ ጋር የሚፈልግ ሰው አቦሌ ጋር እንዲሄድ እመክራለሁ።"</p></div>
            </div>
        </section>
    </div>

    <footer>
        <div class="contact-grid">
            <div class="contact-method">
                <h3>📞 በስልክ ያግኙን</h3>
                <p>+251 911 664492</p>

HTML
<!DOCTYPE html>
<html lang="am">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Abole Furniture | አቦሌ ፈርኒቸር</title>
    <style>
        /* Base Styles */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background-color: #23130B; /* Luxury Dark Leather Brown */
            color: #F4EAE1; /* Cream Text */
            line-height: 1.6;
        }

        /* 1. Top Horizontal Picture (Hero Banner) */
        .hero-banner {
            width: 100%;
            height: 450px;
            object-fit: cover;
            display: block;
            border-bottom: 4px solid #D4AF37; /* Gold Accent */
        }

        /* Container */
        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 40px 20px;
        }

        /* Header Section */
        header {
            text-align: center;
            padding: 40px 0;
        }

        .brand-english {
            font-size: 3.5rem;
            font-weight: 700;
            color: #D4AF37; /* Luxury Gold */
            text-transform: uppercase;
            letter-spacing: 2px;
        }

        .brand-amharic {
            font-size: 2.8rem;
            font-weight: 600;
            margin-bottom: 10px;
        }

        /* Section Titles */
        .section-title {
            font-size: 2.2rem;
            color: #D4AF37;
            text-align: center;
            margin-top: 40px;
            margin-bottom: 30px;
            position: relative;
        }

        .section-title::after {
            content: '';
            display: block;
            width: 80px;
            height: 3px;
            background-color: #D4AF37;
            margin: 10px auto 0 auto;
        }

        /* About Section (ስለ ድርጅቱ) */
        .about-box {
            background-color: #311B10; 
            padding: 30px;
            border-radius: 8px;
            border-left: 5px solid #D4AF37;
            text-align: center;
            font-size: 1.3rem;
            max-width: 800px;
            margin: 0 auto 40px auto;
        }

        /* Gallery Grid (የምርቶች ማሳያ) */
        .gallery-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 25px;
            margin-bottom: 50px;
        }

        .gallery-item {
            background-color: #311B10;
            border-radius: 8px;
            overflow: hidden;
            border: 1px solid #422516;
            transition: transform 0.3s ease;
        }

        .gallery-item:hover {
            transform: translateY(-5px);
        }

        .gallery-item img {
            width: 100%;
            height: 250px;
            object-fit: cover;
        }

        .gallery-info {
            padding: 15px;
            text-align: center;
        }

        .gallery-info h3 {
            color: #D4AF37;
            font-size: 1.2rem;
        }

        /* Testimonials (የደንበኞች አስተያየት) */
        .reviews-container {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
            gap: 20px;
            margin-bottom: 50px;
        }

        .review-card {
            background-color: #1A0E08;
            padding: 25px;
            border-radius: 8px;
            border: 1px dashed #D4AF37;
            text-align: center;
        }

        .stars {
            color: #FFD700;
            font-size: 1.4rem;
            margin-bottom: 10px;
        }

        .review-text {
            font-style: italic;
            color: #DCD0C4;
        }

        /* Contact & Footer */
        footer {
            background-color: #130A05;
            border-top: 4px solid #D4AF37;
            padding: 50px 20px;
            text-align: center;
        }

        .contact-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 30px;
            max-width: 1000px;
            margin: 0 auto 30px auto;
        }

        .contact-method h3 {
            color: #D4AF37;
            margin-bottom: 10px;
            font-size: 1.3rem;
        }

        .contact-method p, .contact-method a {
            color: #F4EAE1;
            text-decoration: none;
            font-size: 1.1rem;
            display: block;
            margin-bottom: 5px;
        }

        .contact-method a:hover {
            color: #D4AF37;
        }

        .footer-bottom {
            margin-top: 30px;
            font-size: 0.9rem;
            color: #8C7665;
        }

        /* Responsive Styles */
        @media (max-width: 768px) {
            .hero-banner { height: 250px; }
            .brand-english { font-size: 2.3rem; }
            .brand-amharic { font-size: 1.9rem; }
        }
    </style>
</head>
<body>

    <!-- 1. የላይኛው ረጅሙ አግድም ፎቶ (Horizontal Banner) -->
    <img src="horizontal line .png" alt="Abole Furniture Premium Banner" class="hero-banner">

    <div class="container">
        
        <!-- Header Brand Name -->
        <header>
            <h1 class="brand-english">Abole Furniture</h1>
            <h2 class="brand-amharic">አቦሌ ፈርኒቸር</h2>
        </header>

        <!-- 2. ስለ ድርጅቱ (About Us) -->
        <section>
            <h2 class="section-title">ስለ ድርጅታችን</h2>
            <div class="about-box">
                <p><strong>ጥራት እና ጥንካሬ መለያችን ነው!</strong> አቦሌ ፈርኒቸር ለቤትዎ፣ ለቢሮዎ እና ለተለያዩ ተቋማት የሚሆኑ ውብ፣ ዘመናዊ እና አስተማማኝ የቤት ዕቃዎችን በጥራት እና በጥንካሬ አምርቶ ያቀርባል።</p>
            </div>
        </section>

        <!-- 3. የምርቶች ማሳያ (Product Gallery) -->
        <section>
            <h2 class="section-title">የምርቶቻችን ማሳያ</h2>
            <div class="gallery-grid">
                
                <!-- Item 1: TV Stand -->
                <div class="gallery-item">
                    <img src="tv stand.jpg" alt="Modern TV Stand - አቦሌ ፈርኒቸር">
                    <div class="gallery-info">
                        <h3>ዘመናዊ የቲቪ ስታንድ (TV Stand)</h3>
                    </div>
                </div>

                <!-- Item 2: Dining Table -->
                <div class="gallery-item">
                    <img src="diring teble.jpg" alt="Luxury Dining Table - አቦሌ ፈርኒቸር">
                    <div class="gallery-info">
                        <h3>የማዕድ ጠረጴዛዎች (Dining Table)</h3>
                    </div>
                </div>

                <!-- Item 3: Door -->
                <div class="gallery-item">
                    <img src="door .jpg" alt="Luxury Door - አቦሌ ፈርኒቸር">
                    <div class="gallery-info">
                        <h3>የቤት በሮች (Doors)</h3>
                    </div>
                </div>

                <!-- Item 4: Kitchen Cabinet -->
                <div class="gallery-item">
                    <img src="kitchen cabinet .png" alt="Kitchen Cabinet - አቦሌ ፈርኒቸር">
                    <div class="gallery-info">
                        <h3>የኩሽና ካቢኔቶች (Kitchen Cabinet)</h3>
                    </div>
                </div>

            </div>
        </section>

        <!-- 4. የደንበኞች አስተያየት (Testimonials) -->
        <section>
            <h2 class="section-title">የደንበኞች አስተያየት</h2>
            <div class="reviews-container">
                
                <div class="review-card">
                    <div class="stars">⭐⭐⭐⭐⭐</div>
                    <p class="review-text">"የአቦሌ ፈርኒቸር ዕቃዎች በጣም ጠንካራ እና ውብ ናቸው። ስራቸው ፍፁም ጥራት አለው!"</p>
                </div>

                <div class="review-card">
                    <div class="stars">⭐⭐⭐⭐⭐</div>
                    <p class="review-text">"በአቀጣጠራቸው እና በስራ ጥራታቸው በጣም ረክተናል። 5 ኮከብ ይገባቸዋል።"</p>
                </div>

                <div class="review-card">
                    <div class="stars">⭐⭐⭐⭐⭐</div>
                    <p class="review-text">"ዘመናዊ ዲዛይን ከጥንካሬ ጋር የሚፈልግ ሰው አቦሌ ጋር እንዲሄድ እመክራለሁ።"</p>
                </div>

            </div>
        </section>

    </div>

    <!-- 5. አድራሻ እና መገናኛ (Contact Info) -->
    <footer>
        <div class="contact-grid">
            
            <!-- Phones -->
            <div class="contact-method">
                <h3>📞 በስልክ ያግኙን</h3>
                <p>+251 911 664492</p>
                <p>+251 991 710545</p>
            </div>

            <!-- Telegram -->
            <div class="contact-method">
                <h3>✈️ ቴሌግራም (Telegram)</h3>
                <a href="https://t.me/lanyisu" target="_blank">@lanyisu</a>
                <a href="https://t.me/lanyisu1" target="_blank">@lanyisu1</a>
            </div>

            <!-- Instagram -->
            <div class="contact-method">
                <h3>📸 ኢንስታግራም (Instagram)</h3>
                <a href="https://instagram.com/lanyisu" target="_blan
            k">@lanyisu</a>
            </div>

        </div>

        <div class="footer-bottom">
            <p>&copy; 2026 አቦሌ ፈርኒቸር (Abole Furniture). መብቱ በህግ የተጠበቀ ነው።</p>
        </div>
    </footer>

</body>

</html>
<section id="reviews">

<h2 style="text-align:center;">የደንበኞች አስተያየት</h2>

<div class="products">

<div class="card">
<div class="star">★★★★★</div>
<p>
"በጣም ጥሩ የኩሽና ካቢኔት ሰርተውልናል።
ጥራቱ እና ዲዛይኑ ደስ ያሰኛል።"
</p>
</div>


<div class="card">
<div class="star">★★★★★</div>
<p>
"የAbole Furniture ስራ በጥንካሬና
በዘመናዊ አቀራረብ የተለየ ነው።"
</p>
</div>

</div>

</section>


<section id="contact" class="contact">

<h2>ያግኙን</h2>

<p>📞 +251 911 664 492</p>
<p>📞 +251 991 710 545</p>

<br>

<p>Telegram:</p>
<p>@lanyisu</p>
<p>@lanyisu1</p>

<br>

<p>Instagram:</p>
<p>@lanyisu</p>

</section>


<footer>

<p>
© 2026 Abole Furniture | All Rights Reserved
</p>

</footer>


</body>
</html>
