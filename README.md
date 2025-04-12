<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Muzamil | Developer Portfolio</title>
  <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap" rel="stylesheet">
  <style>
    body {
      margin: 0;
      font-family: 'Roboto', sans-serif;
      background: #0b0c2a;
      color: #fff;
    }
    header {
      background: #121438;
      padding: 20px 40px;
      display: flex;
      justify-content: space-between;
      align-items: center;
    }
    header h1 {
      margin: 0;
      color: #00bfff;
    }
    nav a {
      color: #fff;
      margin: 0 15px;
      text-decoration: none;
      font-weight: bold;
    }
    .hero {
      display: flex;
      align-items: center;
      justify-content: space-between;
      padding: 60px 40px;
      background: #101234;
    }
    .hero-text h2 {
      font-size: 36px;
      margin-bottom: 10px;
    }
    .hero-text p {
      color: #ccc;
    }
    . radius img {
      width: 200px;
      border-radius: 5px;
    }
    .section {
      padding: 5px;
      background: #0b0c2a;
    }
    .section h3 {
      font-size: 28px;
      color: #00bfff;
      margin-bottom: 20px;
    }
    .projects, .services {
      display: flex;
      gap: 20px;
      flex-wrap: wrap;
    }
    .card {
      background: #1a1c4e;
      padding: 20px;
      border-radius: 10px;
      flex: 1 1 250px;
    }
    .card img {
      max-width: 100%;
      border-radius: 10px;
    }
    .contact-form input, .contact-form textarea {
      width: 100%;
      padding: 10px;
      margin-top: 10px;
      border: none;
      border-radius: 5px;
    }
    .contact-form button {
      margin-top: 15px;
      padding: 12px 25px;
      background: #00bfff;
      border: none;
      color: #fff;
      font-weight: bold;
      border-radius: 5px;
      cursor: pointer;
    }
    footer {
      text-align: center;
      padding: 20px;
      background: #121438;
      color: #ccc;
    }
  </style>
</head>
<body>
  <header>
    <h1>Muzamil</h1>
    <nav>
      <a href="#about">About</a>
      <a href="#projects">Projects</a>
      <a href="#services">Services</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>  <section class="hero">
    <div class="hero-text">
      <h2>Hey! I'm Muzamil</h2>
      <p>I am a Front-End Developer passionate about UI/UX design and web development.</p>
    </div>
    <img src="https://res.cloudinary.com/dxjkbpmgm/image/upload/v1744384921/IMG_20250411_202120_wx6x6n.png" alt="Muzamil photo">
  </section>  <section class="section" id="projects">
    <h3>My Recent Projects</h3>
    <div class="projects">
      <div class="card">
        <img src="https://res.cloudinary.com/dxjkbpmgm/image/upload/v1744384921/IMG_20250411_202120_wx6x6n.png" alt="Project 1">
        <p>Digital Graphic App Design</p>
      </div>
      <div class="card">
        <img src="https://res.cloudinary.com/dxjkbpmgm/image/upload/v1744384921/IMG_20250411_202120_wx6x6n.png" alt="Project 2">
        <p>Crypto Dashboard UI</p>
      </div>
    </div>
  </section>  <section class="section" id="services">
    <h3>Services I Provide</h3>
    <div class="services">
      <div class="card">
        <p>Website Design</p>
      </div>
      <div class="card">
        <p>SEO Marketing</p>
      </div>
      <div class="card">
        <p>App UI/UX Design</p>
      </div>
    </div>
  </section>  <section class="section" id="contact">
    <h3>Let’s Discuss Your Project</h3>
    <div class="contact-form">
      <input type="text" placeholder="Your Name">
      <input type="email" placeholder="Your Email">
      <input type="text" placeholder="Subject">
      <textarea rows="5" placeholder="Your Message"></textarea>
      <button>Send Message</button>
    </div>
  </section>  <footer>
    <p>&copy; 2025 Muzamil. All rights reserved.</p>
  </footer>
</body>

