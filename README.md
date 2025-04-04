<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>DVision Painting and Renovation</title>
    <style>
        body { font-family: Arial, sans-serif; margin: 0; padding: 0; color: #333; opacity: 0; animation: fadeIn 1s forwards; }
        header { background: #1E3A8A; color: white; padding: 20px; text-align: center; }
        nav { text-align: center; padding: 10px; background: #f4f4f4; }
        nav a { 
            margin: 0 15px; 
            text-decoration: none; 
            color: #333; 
            font-weight: bold; 
            display: inline-block;
            transition: transform 0.3s ease, color 0.3s ease;
        }
        nav a:hover {
            color: #1E3A8A;
            transform: translateY(-3px);
        }
        section { padding: 40px; max-width: 900px; margin: auto; }
        .services, .portfolio, .testimonials { background: #f9f9f9; }
        .contact { text-align: center; }
        .portfolio-gallery { display: flex; flex-wrap: wrap; gap: 10px; justify-content: center; }
        .portfolio img { width: 300px; border-radius: 5px; box-shadow: 2px 2px 10px rgba(0, 0, 0, 0.1); }
        footer { background: #1E3A8A; color: white; text-align: center; padding: 10px; margin-top: 20px; }
        
        @keyframes fadeIn {
            from { opacity: 0; }
            to { opacity: 1; }
        }
    </style>
</head>
<body>
    <header>
        <h1>DVision Painting and Renovation</h1>
        <p>High-Quality Painting and Renovation Services in Chilliwack, Canada</p>
    </header>
    <nav>
        <a href="#about">About Us</a>
        <a href="#services">Services</a>
        <a href="#portfolio">Portfolio</a>
        <a href="#testimonials">Testimonials</a>
        <a href="#contact">Contact</a>
    </nav>
    <section id="about">
        <h2>About Us</h2>
        <p>With over 15 years of experience, DVision Painting and Renovation specializes in high-quality painting and renovation services. We are committed to excellence and customer satisfaction.</p>
    </section>
    <section id="services" class="services">
        <h2>Our Services</h2>
        <ul>
            <li>Residential and Commercial Painting</li>
            <li>Drywall Repair</li>
            <li>Minor Renovations</li>
        </ul>
    </section>
    <section id="portfolio" class="portfolio">
        <h2>Our Work</h2>
        <div class="portfolio-gallery">
            <img src="images/project1.jpg" alt="Painting Project 1">
            <img src="images/project2.jpg" alt="Renovation Project 2">
            <img src="images/project3.jpg" alt="Before and After">
        </div>
    </section>
    <section id="testimonials" class="testimonials">
        <h2>Testimonials</h2>
        <p>Client feedback and reviews will be displayed here.</p>
    </section>
    <section id="contact" class="contact">
        <h2>Contact Us</h2>
        <p>Email: info@dvisionpainting.com</p>
        <p>Phone: (Your Contact Number)</p>
        <p>Location: Chilliwack, Canada</p>
    </section>
    <footer>
        <p>&copy; 2025 DVision Painting and Renovation. All rights reserved.</p>
    </footer>
</body>
</html>
