<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Magic City Smart Cleaners</title>
  <style>
    body { font-family: Arial, sans-serif; margin: 0; padding: 0; background: #f4f8f7; color: #333; }
    header { background: #4CAF50; color: white; padding: 1rem 2rem; text-align: center; }
    nav { background: #388E3C; display: flex; justify-content: center; gap: 2rem; padding: 1rem; }
    nav a { color: white; text-decoration: none; font-weight: bold; }
    section { padding: 2rem; max-width: 900px; margin: auto; }
    footer { background: #4CAF50; color: white; text-align: center; padding: 1rem; margin-top: 2rem; }
    .btn { background: #388E3C; color: white; padding: 0.75rem 1.5rem; text-decoration: none; display: inline-block; margin-top: 1rem; }
    .services { display: flex; flex-wrap: wrap; gap: 2rem; }
    .service-card { background: white; padding: 1rem; box-shadow: 0 2px 6px rgba(0,0,0,0.1); border-radius: 8px; flex: 1 1 40%; }
    @media(max-width: 600px) {
      .services { flex-direction: column; }
    }
  </style>
</head>
<body>

<header>
  <h1>Magic City Smart Cleaners</h1>
  <p>Where Magic Meets Clean</p>
</header>

<nav>
  <a href="#services">Services</a>
  <a href="#about">About</a>
  <a href="#contact">Contact</a>
  <a href="#quote">Get a Quote</a>
</nav>

<section id="services">
  <h2>Our Cleaning Services</h2>
  <div class="services">
    <div class="service-card">
      <h3>Deep Cleaning</h3>
      <p>Thorough top-to-bottom cleaning for homes and apartments. Ideal for seasonal refreshes.</p>
    </div>
    <div class="service-card">
      <h3>Move In/Out</h3>
      <p>Complete cleaning for new tenants or owners. Great for landlords or realtors.</p>
    </div>
    <div class="service-card">
      <h3>Regular Maintenance</h3>
      <p>Weekly, bi-weekly or monthly cleanings tailored to your home and schedule.</p>
    </div>
    <div class="service-card">
      <h3>Post-Construction</h3>
      <p>Specialized cleaning after renovations or new builds to remove dust and debris.</p>
    </div>
  </div>
</section>

<section id="about">
  <h2>About Us</h2>
  <p>Magic City Smart Cleaners is a locally-owned business proudly serving the Miami area. Our team is professional, punctual, and dedicated to making your home shine. We use eco-friendly products and offer flexible scheduling to meet your needs.</p>
</section>

<section id="contact">
  <h2>Contact Us</h2>
  <p><strong>Phone:</strong> (XXX) XXX-XXXX<br>
     <strong>Email:</strong> info@magiccitycleaners.com</p>
</section>

<section id="quote">
  <h2>Get a Free Quote</h2>
  <form>
    <label for="name">Name:</label><br>
    <input type="text" id="name" name="name" required><br><br>
    <label for="email">Email:</label><br>
    <input type="email" id="email" name="email" required><br><br>
    <label for="service">Service Needed:</label><br>
    <select id="service" name="service">
      <option>Deep Cleaning</option>
      <option>Move In/Out</option>
      <option>Regular Maintenance</option>
      <option>Post-Construction</option>
    </select><br><br>
    <label for="message">Additional Info:</label><br>
    <textarea id="message" name="message" rows="4"></textarea><br><br>
    <button type="submit" class="btn">Submit Request</button>
  </form>
</section>

<footer>
  <p>&copy; 2025 Magic City Smart Cleaners. All rights reserved.</p>
</footer>

</body>
</html># Mcsc
Cleaning services 
