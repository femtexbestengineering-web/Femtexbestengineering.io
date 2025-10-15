# Femtexbestengineering.io
This website showcases my electrical work, featuring expert installations, repairs, and renewable energy solutions like solar panel systems. My portfolio highlights safe, efficient, and high-quality projects for residential and commercial clients.
#  Femtex Engineering

**Professional Electrical Installations & Power Solutions**  
*Lighting the Future with Innovation*

---
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Femtex Engineering</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <!-- Navigation Bar -->
  <header>
    <nav class="navbar">
      <div class="logo">⚡ Femtex Engineering</div>
      <ul class="nav-links">
        <li><a href="#home">Home</a></li>
        <li><a href="#about">About</a></li>
        <li><a href="#services">Services</a></li>
        <li><a href="#projects">Projects</a></li>
        <li><a href="#contact">Contact</a></li>
      </ul>
    </nav>
  </header>

  <!-- Hero Section -->
  <section id="home" class="hero">
    <div class="hero-content">
      <h1>Professional Electrical Installations & Power Solutions</h1>
      <p>Lighting the Future with Innovation</p>
      <a href="#contact" class="btn">Get in Touch</a>
    </div>
  </section>

  <!-- About Section -->
  <section id="about" class="about">
    <h2>About Us</h2>
    <p>Femtex Engineering delivers reliable electrical installations and power systems designed for efficiency, safety, and performance. We serve homes, industries, and corporate clients with expert craftsmanship and innovative energy solutions.</p>
  </section>

  <!-- Services Section -->
  <section id="services" class="services">
    <h2>Our Services</h2>
    <div class="service-cards">
      <div class="card">
        <h3>Electrical Installations</h3>
        <p>Comprehensive wiring and installation for residential and industrial facilities.</p>
      </div>
      <div class="card">
        <h3>Power & Energy Solutions</h3>
        <p>Innovative and sustainable energy management systems.</p>
      </div>
      <div class="card">
        <h3>Maintenance & Repairs</h3>
        <p>On-call maintenance and electrical troubleshooting with guaranteed reliability.</p>
      </div>
    </div>
  </section>

  <!-- Projects Section -->
  <section id="projects" class="projects">
    <h2>Recent Projects</h2>
    <p>Showcasing our latest engineering projects — committed to excellence and innovation.</p>
    <div class="project-gallery">
      <div class="project-item">Project 1</div>
      <div class="project-item">Project 2</div>
      <div class="project-item">Project 3</div>
    </div>
  </section>

  <!-- Contact Section -->
  <section id="contact" class="contact">
    <h2>Contact Us</h2>
    <p>We’d love to work with you. Reach us through any of the following channels.</p>
    <ul>
      <li><strong>Phone:</strong> 08162994552 / 08162918085</li>
      <li><strong>Email:</strong> femtexbestengineering@gmail.com</li>
      <li><strong>WhatsApp:</strong> <a href="#">Chat on WhatsApp</a></li>
    </ul>
  </section>

  <!-- Footer -->
  <footer>
    <p>© 2025 Femtex Engineering | Lighting the Future with Innovation</p>
  </footer>
</body>
</html>
/* FEMTEX ENGINEERING STYLE */

* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  scroll-behavior: smooth;
  font-family: 'Poppins', sans-serif;
}

body {
  background: #0b0b0b;
  color: #f1f1f1;
}

/* Navbar */
.navbar {
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 20px 8%;
  background: #003300;
  position: sticky;
  top: 0;
  z-index: 1000;
}

.logo {
  font-size: 1.3em;
  font-weight: 600;
  color: #00ff66;
}

.nav-links {
  list-style: none;
  display: flex;
  gap: 20px;
}

.nav-links a {
  color: #ffffff;
  text-decoration: none;
  font-weight: 500;
  transition: 0.3s;
}

.nav-links a:hover {
  color: #00ff99;
}

/* Hero Section */
.hero {
  height: 100vh;
  background: linear-gradient(to right, rgba(0,0,0,0.7), rgba(0,128,0,0.5)), url('https://images.unsplash.com/photo-1581091012184-5c65b8c74d93?auto=format&fit=crop&w=1600&q=80');
  background-size: cover;
  background-position: center;
  display: flex;
  align-items: center;
  justify-content: center;
  text-align: center;
  color: #fff;
}

.hero h1 {
  font-size: 2em;
  margin-bottom: 10px;
  animation: fadeIn 2s ease-in-out;
}

.hero p {
  margin-bottom: 20px;
  font-size: 1.1em;
  opacity: 0.9;
}

.btn {
  padding: 10px 25px;
  background: #00ff66;
  color: #000;
  font-weight: 600;
  text-decoration: none;
  border-radius: 5px;
  transition: 0.3s;
}

.btn:hover {
  background: #00cc55;
  color: #fff;
}

/* Sections */
section {
  padding: 80px 10%;
  text-align: center;
}

h2 {
  color: #00ff99;
  margin-bottom: 20px;
}

/* Cards */
.service-cards {
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
  gap: 20px;
}

.card {
  background: #111;
  border: 1px solid #004d00;
  border-radius: 8px;
  width: 280px;
  padding: 25px;
  transition: transform 0.3s, border 0.3s;
}

.card:hover {
  transform: translateY(-10px);
  border: 1px solid #00ff66;
}

/* Projects */
.project-gallery {
  display: flex;
  justify-content: center;
  flex-wrap: wrap;
  gap: 15px;
}

.project-item {
  width: 250px;
  height: 150px;
  background: #222;
  border: 1px solid #004d00;
  border-radius: 5px;
  display: flex;
  justify-content: center;
  align-items: center;
  color: #ccc;
  transition: 0.3s;
}

.project-item:hover {
  background: #004d00;
  color: #fff;
}

/* Contact */
.contact ul {
  list-style: none;
  margin-top: 20px;
}

.contact li {
  margin: 10px 0;
  font-size: 1.1em;
}

.contact a {
  color: #00ff99;
  text-decoration: none;
}

.contact a:hover {
  text-decoration: underline;
}

/* Footer */
footer {
  background: #003300;
  padding: 20px;
  text-align: center;
  color: #bbb;
  font-size: 0.9em;
  margin-top: 40px;
}

/* Animation */
@keyframes fadeIn {
  from {opacity: 0; transform: translateY(20px);}
  to {opacity: 1; transform: translateY(0);}
}

/* Responsive */
@media (max-width: 768px) {
  .nav-links {
    display: none;
  }

  .service-cards, .project-gallery {
    flex-direction: column;
  }

  .card, .project-item {
    width: 100%;
  }
}

---

### 📞 Contact Us
📧 **femtexbestengineering@gmail.com**  
📱 **08162994552**, **08162918085**

Follow us on social media:  


---

© 2025 **Femtex Engineering**. All rights reserved.
