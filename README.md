# JJ-Tree-Services
Tree Services and Landscaping 
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>GreenLeaf | Professional Tree & Landscaping Services</title>
    <style>
        :root { --primary: #2d5a27; --secondary: #f4f4f4; --accent: #f39c12; }
        body { font-family: 'Segoe UI', sans-serif; margin: 0; line-height: 1.6; color: #333; }
        header { background: var(--primary); color: white; padding: 1rem 5%; display: flex; justify-content: space-between; align-items: center; position: sticky; top: 0; z-index: 1000; }
        .nav-links a { color: white; text-decoration: none; margin-left: 20px; font-weight: bold; }
        .hero { background: linear-gradient(rgba(0,0,0,0.5), rgba(0,0,0,0.5)), url('https://unsplash.com'); height: 60vh; background-size: cover; display: flex; flex-direction: column; justify-content: center; align-items: center; color: white; text-align: center; padding: 20px; }
        .cta-button { background: var(--accent); color: white; padding: 12px 30px; text-decoration: none; border-radius: 5px; font-weight: bold; margin-top: 20px; transition: 0.3s; }
        .cta-button:hover { background: #d35400; }
        .services { padding: 50px 5%; display: grid; grid-template-columns: repeat(auto-fit, minmax(250px, 1fr)); gap: 30px; background: var(--secondary); }
        .service-card { background: white; padding: 20px; border-radius: 8px; box-shadow: 0 4px 6px rgba(0,0,0,0.1); text-align: center; }
        footer { background: #222; color: #ccc; text-align: center; padding: 20px; }
    </style>
</head>
<body>

<header>
    <div class="logo"><strong>GreenLeaf</strong> Services</div>
    <nav class="nav-links">
        <a href="#services">Services</a>
        <a href="#contact">Free Estimate</a>
    </nav>
</header>

<section class="hero">
    <h1>Expert Care for Your Outdoor Space</h1>
    <p>Tree Removal • Landscape Design • Seasonal Maintenance</p>
    <a href="#contact" class="cta-button">Get a Free Quote</a>
</section>

<section id="services" class="services">
    <div class="service-card">
        <h3>Tree Removal</h3>
        <p>Safe and efficient removal of hazardous or unwanted trees.</p>
    </div>
    <div class="service-card">
        <h3>Pruning & Trimming</h3>
        <p>Maintain the health and beauty of your trees and shrubs.</p>
    </div>
    <div class="service-card">
        <h3>Lawn & Garden</h3>
        <p>Professional sod installation, mulching, and bed design.</p>
    </div>
</section>

<section id="contact" style="padding: 50px 5%; text-align: center;">
    <h2>Request Your Free Estimate</h2>
    <p>Call us at <strong>(555) 123-4567</strong> or fill out the form below.</p>
    <!-- Simple form structure -->
    <form style="max-width: 500px; margin: 0 auto; display: grid; gap: 10px;">
        <input type="text" placeholder="Your Name" style="padding: 10px;">
        <input type="email" placeholder="Your Email" style="padding: 10px;">
        <textarea placeholder="Tell us about your project..." style="padding: 10px; height: 100px;"></textarea>
        <button type="submit" class="cta-button" style="border: none; cursor: pointer;">Submit Request</button>
    </form>
</section>

<footer>
    <p>&copy; 2024 GreenLeaf Tree & Landscaping. Licensed and Insured.</p>
</footer>

</body>
</html>
