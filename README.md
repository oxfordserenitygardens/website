<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Oxford Serenity Gardens</title>
  <style>
    /* General Styles */
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      background-color: #ffffff;
      color: #12531e;
      line-height: 1.6;
    }

    h1, h2, h3 {
      color: #12531e;
    }

    a {
      color: #12531e;
      text-decoration: none;
    }

    a:hover {
      text-decoration: underline;
    }

    /* Header */
    header {
      background-color: #12531e;
      color: #ffffff;
      padding: 40px 20px;
      text-align: center;
    }

    header h1 {
      margin: 0;
      font-size: 2.5rem;
    }

    header p {
      font-size: 1.2rem;
      margin: 10px 0 0;
    }

    /* Navigation */
    nav {
      display: flex;
      justify-content: center;
      background-color: #12531e;
      padding: 10px;
    }

    nav a {
      color: #ffffff;
      margin: 0 15px;
      font-weight: bold;
      font-size: 1.1rem;
    }

    /* Main Content */
    .container {
      padding: 20px;
      max-width: 1200px;
      margin: 0 auto;
    }

    .services, .about, .contact {
      margin-bottom: 40px;
    }

    .services h2, .about h2, .contact h2 {
      text-align: center;
      margin-bottom: 20px;
      font-size: 2rem;
    }

    .service-list {
      display: flex;
      flex-wrap: wrap;
      justify-content: space-around;
    }

    .service-item {
      background-color: #f0f0f0;
      border: 1px solid #12531e;
      border-radius: 10px;
      padding: 20px;
      margin: 10px;
      width: 30%;
      text-align: center;
      transition: transform 0.3s ease;
    }

    .service-item:hover {
      transform: scale(1.05);
    }

    .service-item h3 {
      margin: 0 0 10px;
      font-size: 1.5rem;
    }

    .service-item p {
      margin: 0;
      font-size: 1rem;
    }

    /* Footer */
    footer {
      background-color: #12531e;
      color: #ffffff;
      text-align: center;
      padding: 20px;
      margin-top: 40px;
    }

    footer p {
      margin: 0;
      font-size: 1rem;
    }
  </style>
</head>
<body>
  <header>
    <h1>Oxford Serenity Gardens</h1>
    <p>Your Trusted Garden Maintenance Service in Oxfordshire</p>
  </header>

  <nav>
    <a href="#services">Services</a>
    <a href="#about">About Us</a>
    <a href="#contact">Contact</a>
  </nav>

  <div class="container">
    <!-- Services Section -->
    <section id="services" class="services">
      <h2>Our Services</h2>
      <div class="service-list">
        <div class="service-item">
          <h3>Lawn Trim</h3>
          <p>Keep your lawn neat and tidy with our professional trimming service.</p>
        </div>
        <div class="service-item">
          <h3>Hedge Trimming</h3>
          <p>Perfectly trimmed hedges for a polished look.</p>
        </div>
        <div class="service-item">
          <h3>Garden Tidy Up</h3>
          <p>We'll transform your garden into a serene space.</p>
        </div>
        <div class="service-item">
          <h3>Patio Jet Wash</h3>
          <p>Restore your patio to its former glory with our jet wash service.</p>
        </div>
        <div class="service-item">
          <h3>Garden Waste Disposal</h3>
          <p>Efficient and eco-friendly waste disposal for your garden.</p>
        </div>
        <div class="service-item">
          <h3>Deweeding</h3>
          <p>Say goodbye to unwanted weeds in your garden.</p>
        </div>
        <div class="service-item">
          <h3>Planting</h3>
          <p>Let us help you plant new life in your garden.</p>
        </div>
      </div>
    </section>

    <!-- About Section -->
    <section id="about" class="about">
      <h2>About Us</h2>
      <p>Oxford Serenity Gardens is a locally owned and operated garden maintenance company based in Oxford, serving the entire county of Oxfordshire. We are passionate about creating beautiful, serene outdoor spaces for our clients. Our team of experienced professionals is dedicated to providing top-quality services tailored to your needs.</p>
    </section>

    <!-- Contact Section -->
    <section id="contact" class="contact">
      <h2>Contact Us</h2>
      <p>Ready to transform your garden? Get in touch with us today!</p>
      <p>Email: <a href="mailto:info@oxfordserenitygardens.com">info@oxfordserenitygardens.com</a></p>
      <p>Phone: <a href="tel:+441865123456">+44 1865 123456</a></p>
    </section>
  </div>

  <footer>
    <p>&copy; 2023 Oxford Serenity Gardens. All rights reserved.</p>
  </footer>
</body>
</html>
