<!doctype html>
<html lang="en" dir="ltr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>JESMI - One Body</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com">
    <style>
        * { margin: 0; padding: 0; box-sizing: border-box; }
        body { font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif; color: #333; background-color: #f8f9fa; line-height: 1.6; }
        html { scroll-behavior: smooth; }
        
        nav { background: linear-gradient(135deg, #e63946 0%, #c1121f 100%); padding: 1rem 2rem; position: sticky; top: 0; z-index: 100; box-shadow: 0 2px 10px rgba(0,0,0,0.1); }
        nav ul { list-style: none; display: flex; gap: 2rem; justify-content: center; }
        nav a { color: white; text-decoration: none; font-weight: 500; cursor: pointer; transition: 0.3s; }

        .hero { background: linear-gradient(135deg, #e63946 0%, #c1121f 100%); color: white; padding: 6rem 2rem; text-align: center; }
        
        /* تحسين حاوية الشعار لضمان الظهور */
        .hero-logo { 
            width: 180px; 
            height: 180px; 
            background: white; 
            border-radius: 30px; 
            margin: 0 auto 2rem; 
            display: flex; 
            align-items: center; 
            justify-content: center; 
            overflow: hidden; 
            box-shadow: 0 15px 35px rgba(0,0,0,0.2);
            padding: 10px;
        }
        .hero-logo img {
            width: 100%;
            height: 100%;
            object-fit: contain;
            display: block;
        }

        .hero h1 { font-size: 4rem; margin-bottom: 0.5rem; letter-spacing: 2px; }
        .hero-subtitle { font-size: 1.3rem; margin-bottom: 2.5rem; opacity: 0.9; }

        .cta-button { display: inline-block; background-color: #ff6b6b; color: white; padding: 1.2rem 3.5rem; border-radius: 50px; text-decoration: none; font-size: 1.2rem; font-weight: 700; transition: 0.3s; box-shadow: 0 5px 15px rgba(0,0,0,0.2); }
        .cta-button:hover { background-color: #ff5252; transform: translateY(-3px); }

        .section { padding: 6rem 2rem; max-width: 900px; margin: 0 auto; text-align: center; }
        #platform { background: linear-gradient(145deg, #c1121f, #e63946); color: white; border-radius: 40px; padding: 5rem 3rem; }
        .concept-text { font-size: 1.5rem; font-weight: 300; font-style: italic; line-height: 2; }

        .contact-links { display: flex; flex-wrap: wrap; justify-content: center; gap: 1.5rem; margin-top: 2rem; }
        .contact-item { display: flex; align-items: center; gap: 0.8rem; background: white; padding: 1rem 2rem; border-radius: 50px; text-decoration: none; color: #333; font-weight: 600; box-shadow: 0 4px 15px rgba(0,0,0,0.05); transition: 0.3s; }
        .contact-item:hover { border-color: #e63946; transform: translateY(-3px); color: #e63946; }

        footer { background-color: #1a1a1a; color: rgba(255,255,255,0.6); padding: 4rem 2rem; text-align: center; }
    </style>
</head>
<body>

    <nav>
        <ul>
            <li><a href="#hero">Home</a></li>
            <li><a href="#about">About</a></li>
            <li><a href="#platform">Concept</a></li>
            <li><a href="#contact">Contact</a></li>
        </ul>
    </nav>

    <section id="hero" class="hero">
        <div class="hero-logo">
            <!-- تم استخدام الرابط المباشر للصورة -->
            <img src="https://i.postimg.cc/RCb0831Y/JESMI.gif" alt="JESMI Logo">
        </div>
        <h1>JESMI</h1>
        <p class="hero-subtitle">One Body - The Evolution of Digital Harmony</p>
        <a href="https://studio--studio-3908265938-96e20.us-central1.hosted.app" class="cta-button">Try Now</a>
    </section>

    <section id="about" class="section">
        <h2>About Us</h2>
        <p>JESMI is a philosophy. We believe technology should move like a single living organism—seamless, intuitive, and unified.</p>
    </section>

    <section class="section">
        <div id="platform">
            <h2>The Concept</h2>
            <p class="concept-text">"Beyond traditional interfaces lies a new dimension of interaction. A space where boundaries dissolve."</p>
        </div>
    </section>

    <section id="contact" class="section">
        <h2>Get in Touch</h2>
        <div class="contact-links">
            <a href="https://wa.me" target="_blank" class="contact-item"><i class="fab fa-whatsapp"></i> WhatsApp (EG)</a>
            <a href="https://wa.me" target="_blank" class="contact-item"><i class="fab fa-whatsapp"></i> WhatsApp (SD)</a>
            <a href="https://www.linkedin.com" target="_blank" class="contact-item"><i class="fab fa-linkedin"></i> LinkedIn</a>
        </div>
    </section>

    <footer><p>&copy; 2024 JESMI. All rights reserved.</p></footer>

</body>
</html>
