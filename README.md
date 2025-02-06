from IPython.display import HTML

html_code = """
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
      padding: 20px;
      text-align: center;
    }

    header h1 {
      margin: 0;
      font-size: 2.5rem;
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
    }

    /* Footer */
    footer {
      background-color: #12531e;
      color: #ffffff;
      text-align: center;
      padding: 10px;
      position: fixed;
      bottom: 0;
      width: 100%;
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
        <div
