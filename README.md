# Ex02 Commercial Website
## Date: 05-09-2026

## AIM
To create a commercial website using CSS Flexbox.

## ALGORITHM
### STEP 1
Create an HTML file (index.html)

### STEP 2
Create a CSS file (style.css)

### STEP 3
Include a navigation bar with links to different sections.

### STEP 4
Add structured sections for Homepage, Products / Services, About Us, Contact Details and User Account.

### STEP 5
Include social media links at the footer with copyright information.

### STEP 6
Define global styles for fonts, colors, and layout.

### STEP 7
Style the header, navigation bar, and sections.

### STEP 8
Use Flexbox for layout design.

### STEP 9
Add hover effects and transitions for interactivity.

### STEP 10
Add Images and Media.

### STEP 11
Use optimized images for a professional look.

### STEP 12
Open the HTML file in a browser to check layout and functionality.

### STEP 13
Fix styling issues and refine content placement.

### STEP 14
Deploy the website.

### STEP 15
Upload to GitHub Pages for free hosting.

## PROGRAM

### index.html
```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>NovaGear — Next-Gen Tech Store</title>
  <link rel="stylesheet" href="style.css" />
</head>
<body>

  <!-- Navigation Bar -->
  <header>
    <nav class="navbar">
      <div class="brand-logo">Nova<span>Gear</span></div>
      <ul class="nav-links">
        <li><a href="#home">Home</a></li>
        <li><a href="#products">Products</a></li>
        <li><a href="#about">About Us</a></li>
        <li><a href="#account">Account</a></li>
        <li><a href="#contact">Contact</a></li>
      </ul>
      <div class="nav-actions">
        <a href="#account" class="btn-sm">Sign In</a>
      </div>
    </nav>
  </header>

  <!-- Homepage / Hero Section -->
  <section id="home" class="hero-section">
    <div class="hero-container">
      <div class="hero-text">
        <span class="badge">New Season Release</span>
        <h1>Engineered for Peak Performance</h1>
        <p>Discover high-precision peripherals, intelligent audio hardware, and smart workspace essentials designed for modern creators.</p>
        <div class="hero-buttons">
          <a href="#products" class="btn btn-primary">Shop Catalog</a>
          <a href="#about" class="btn btn-outline">Explore Tech</a>
        </div>
      </div>
      <div class="hero-visual">
        <div class="visual-card">
          <div class="visual-badge">Featured</div>
          <h3>NovaPulse Pro Headset</h3>
          <p>Active Noise Cancellation • 60h Battery</p>
          <span class="price-tag">$199.99</span>
        </div>
      </div>
    </div>
  </section>

  <!-- Products / Services Section -->
  <section id="products" class="section products-section">
    <div class="container">
      <div class="section-header">
        <h2>Featured Products</h2>
        <p>Premium hardware built with industrial-grade reliability.</p>
      </div>

      <div class="product-flex-container">
        <!-- Product 1 -->
        <div class="product-card">
          <div class="product-img-box">
            <span class="product-tag">Bestseller</span>
            <div class="device-icon">&#127911;</div>
          </div>
          <div class="product-details">
            <h3>NovaPulse ANC</h3>
            <p>Lossless wireless audio with adaptive spatial acoustics.</p>
            <div class="card-bottom">
              <span class="price">$199.99</span>
              <button class="btn-cart">Add to Cart</button>
            </div>
          </div>
        </div>

        <!-- Product 2 -->
        <div class="product-card">
          <div class="product-img-box">
            <span class="product-tag">Flagship</span>
            <div class="device-icon">&#9000;</div>
          </div>
          <div class="product-details">
            <h3>Apex Mechanical Deck</h3>
            <p>Hot-swappable optical switches with CNC aluminum casing.</p>
            <div class="card-bottom">
              <span class="price">$149.99</span>
              <button class="btn-cart">Add to Cart</button>
            </div>
          </div>
        </div>

        <!-- Product 3 -->
        <div class="product-card">
          <div class="product-img-box">
            <span class="product-tag">New</span>
            <div class="device-icon">&#128433;</div>
          </div>
          <div class="product-details">
            <h3>Vortex Ultralight Mouse</h3>
            <p>Ultra-low latency sensor weighing just 48 grams.</p>
            <div class="card-bottom">
              <span class="price">$79.99</span>
              <button class="btn-cart">Add to Cart</button>
            </div>
          </div>
        </div>

        <!-- Product 4 -->
        <div class="product-card">
          <div class="product-img-box">
            <span class="product-tag">Popular</span>
            <div class="device-icon">&#128267;</div>
          </div>
          <div class="product-details">
            <h3>NovaHub 100W GaN</h3>
            <p>Multi-port fast charging station with smart thermal control.</p>
            <div class="card-bottom">
              <span class="price">$59.99</span>
              <button class="btn-cart">Add to Cart</button>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- About Us Section -->
  <section id="about" class="section about-section">
    <div class="container">
      <div class="about-flex">
        <div class="about-text-content">
          <h2>About NovaGear</h2>
          <p>Founded in 2024, NovaGear is dedicated to redefining desktop productivity and interactive electronics. We believe everyday tools should be durable, aesthetically refined, and accessible.</p>
          <div class="value-pillars">
            <div class="pillar">
              <h4>Precision Build</h4>
              <p>Aerospace-grade materials built for rigorous daily workflows.</p>
            </div>
            <div class="pillar">
              <h4>Sustainable Tech</h4>
              <p>100% recyclable packaging and modular serviceable designs.</p>
            </div>
          </div>
        </div>
        <div class="about-stats-box">
          <div class="stat-item">
            <span class="stat-num">50k+</span>
            <span class="stat-lbl">Active Users</span>
          </div>
          <div class="stat-item">
            <span class="stat-num">99.4%</span>
            <span class="stat-lbl">Satisfaction</span>
          </div>
          <div class="stat-item">
            <span class="stat-num">24/7</span>
            <span class="stat-lbl">Global Support</span>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- User Account Section -->
  <section id="account" class="section account-section">
    <div class="container">
      <div class="section-header">
        <h2>Member Portal</h2>
        <p>Manage your orders, warranties, and account preferences.</p>
      </div>
      <div class="account-flex-container">
        <!-- Sign In Form -->
        <div class="account-card">
          <h3>Customer Login</h3>
          <form class="account-form" onsubmit="event.preventDefault()">
            <div class="form-group">
              <label>Email Address</label>
              <input type="email" placeholder="user@novagear.com" required />
            </div>
            <div class="form-group">
              <label>Password</label>
              <input type="password" placeholder="••••••••" required />
            </div>
            <button type="submit" class="btn btn-primary btn-block">Sign In</button>
          </form>
        </div>

        <!-- Account Benefits -->
        <div class="account-card card-accent">
          <h3>Member Privileges</h3>
          <ul class="benefit-list">
            <li>&#10003; 2-Year Express Warranty Replacement</li>
            <li>&#10003; Free priority shipping on all hardware orders</li>
            <li>&#10003; Early access to quarterly product drops</li>
            <li>&#10003; Dedicated 24/7 enterprise technical support</li>
          </ul>
          <a href="#contact" class="btn btn-outline btn-block">Register New Account</a>
        </div>
      </div>
    </div>
  </section>

  <!-- Contact Details Section -->
  <section id="contact" class="section contact-section">
    <div class="container">
      <div class="section-header">
        <h2>Contact Details</h2>
        <p>Have questions about bulk orders or technical support? Connect with our team.</p>
      </div>
      <div class="contact-flex-container">
        <div class="contact-info-card">
          <h3>Headquarters</h3>
          <p><strong>NovaGear Technologies Inc.</strong></p>
          <p>Olympia Tech Park, Guindy</p>
          <p>Chennai, Tamil Nadu 600032, India</p>
          <div class="info-items">
            <p><strong>Email:</strong> support@novagear.com</p>
            <p><strong>Phone:</strong> +91 (44) 4500-1234</p>
            <p><strong>Hours:</strong> Mon - Sat: 9:00 AM - 6:00 PM IST</p>
          </div>
        </div>
        <div class="contact-form-card">
          <h3>Send a Direct Inquiry</h3>
          <form class="contact-form" onsubmit="event.preventDefault()">
            <div class="form-group">
              <label>Full Name</label>
              <input type="text" placeholder="Your Name" required />
            </div>
            <div class="form-group">
              <label>Email Address</label>
              <input type="email" placeholder="your.email@example.com" required />
            </div>
            <div class="form-group">
              <label>Message</label>
              <textarea rows="4" placeholder="How can we assist you?" required></textarea>
            </div>
            <button type="submit" class="btn btn-primary btn-block">Submit Message</button>
          </form>
        </div>
      </div>
    </div>
  </section>

  <!-- Footer with Social Media Links -->
  <footer class="footer">
    <div class="container footer-content">
      <div class="footer-top">
        <div class="footer-brand">Nova<span>Gear</span></div>
        <p>Modern hardware for digital artisans and engineers.</p>
      </div>
      <div class="footer-social-links">
        <a href="[https://github.com](https://github.com)" target="_blank" rel="noreferrer">GitHub</a>
        <a href="[https://linkedin.com](https://linkedin.com)" target="_blank" rel="noreferrer">LinkedIn</a>
        <a href="[https://x.com](https://x.com)" target="_blank" rel="noreferrer">X (Twitter)</a>
        <a href="[https://instagram.com](https://instagram.com)" target="_blank" rel="noreferrer">Instagram</a>
      </div>
      <div class="footer-bottom">
        <p>&copy; 2026 NovaGear Technologies. All rights reserved.</p>
      </div>
    </div>
  </footer>

</body>
</html>
```

### style.css
```css
/* --- Global Styles & Reset --- */
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

:root {
  --primary: #4f46e5;
  --primary-hover: #4338ca;
  --dark: #0f172a;
  --dark-surface: #1e293b;
  --text-main: #334155;
  --text-light: #64748b;
  --bg-light: #f8fafc;
  --white: #ffffff;
  --border: #e2e8f0;
  --radius: 10px;
  --transition: all 0.25s ease-in-out;
}

body {
  font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Oxygen, Ubuntu, Cantarell, sans-serif;
  color: var(--text-main);
  background-color: var(--white);
  line-height: 1.6;
  scroll-behavior: smooth;
}

.container {
  max-width: 1100px;
  margin: 0 auto;
  padding: 0 1.5rem;
}

.section {
  padding: 5rem 0;
}

.section-header {
  text-align: center;
  margin-bottom: 3.5rem;
}

.section-header h2 {
  font-size: 2.2rem;
  color: var(--dark);
  margin-bottom: 0.5rem;
}

.section-header p {
  color: var(--text-light);
  font-size: 1.05rem;
}

/* --- Navigation Bar (Flexbox) --- */
header {
  position: sticky;
  top: 0;
  background-color: rgba(255, 255, 255, 0.95);
  backdrop-filter: blur(10px);
  border-bottom: 1px solid var(--border);
  z-index: 1000;
}

.navbar {
  display: flex;
  justify-content: space-between;
  align-items: center;
  max-width: 1100px;
  margin: 0 auto;
  padding: 1.1rem 1.5rem;
}

.brand-logo {
  font-size: 1.4rem;
  font-weight: 800;
  color: var(--dark);
}

.brand-logo span {
  color: var(--primary);
}

.nav-links {
  display: flex;
  list-style: none;
  gap: 2rem;
  align-items: center;
}

.nav-links a {
  text-decoration: none;
  color: var(--text-main);
  font-weight: 500;
  font-size: 0.95rem;
  transition: var(--transition);
}

.nav-links a:hover {
  color: var(--primary);
}

.nav-actions {
  display: flex;
  align-items: center;
}

.btn-sm {
  text-decoration: none;
  background-color: var(--primary);
  color: var(--white);
  padding: 0.5rem 1.2rem;
  border-radius: 6px;
  font-size: 0.875rem;
  font-weight: 600;
  transition: var(--transition);
}

.btn-sm:hover {
  background-color: var(--primary-hover);
}

/* --- Buttons --- */
.btn {
  display: inline-block;
  padding: 0.8rem 1.8rem;
  border-radius: 6px;
  font-weight: 600;
  text-decoration: none;
  font-size: 0.95rem;
  cursor: pointer;
  border: 2px solid transparent;
  transition: var(--transition);
  text-align: center;
}

.btn-primary {
  background-color: var(--primary);
  color: var(--white);
}

.btn-primary:hover {
  background-color: var(--primary-hover);
  transform: translateY(-2px);
}

.btn-outline {
  border-color: var(--border);
  color: var(--dark);
  background-color: transparent;
}

.btn-outline:hover {
  border-color: var(--dark);
  background-color: var(--dark);
  color: var(--white);
  transform: translateY(-2px);
}

.btn-block {
  display: block;
  width: 100%;
}

/* --- Hero Section (Flexbox) --- */
.hero-section {
  background: linear-gradient(135deg, #f8fafc 0%, #eef2ff 100%);
  padding: 6rem 1.5rem;
}

.hero-container {
  max-width: 1100px;
  margin: 0 auto;
  display: flex;
  align-items: center;
  justify-content: space-between;
  gap: 3rem;
  flex-wrap: wrap;
}

.hero-text {
  flex: 1 1 500px;
}

.badge {
  display: inline-block;
  background-color: #e0e7ff;
  color: var(--primary);
  font-size: 0.8rem;
  font-weight: 700;
  padding: 0.35rem 0.8rem;
  border-radius: 50px;
  margin-bottom: 1.2rem;
  text-transform: uppercase;
}

.hero-text h1 {
  font-size: 3rem;
  line-height: 1.15;
  color: var(--dark);
  margin-bottom: 1.2rem;
  font-weight: 800;
}

.hero-text p {
  font-size: 1.1rem;
  color: var(--text-light);
  margin-bottom: 2rem;
  max-width: 520px;
}

.hero-buttons {
  display: flex;
  gap: 1rem;
  flex-wrap: wrap;
}

.hero-visual {
  flex: 1 1 360px;
  display: flex;
  justify-content: center;
}

.visual-card {
  background: var(--dark);
  color: var(--white);
  padding: 3rem 2rem;
  border-radius: var(--radius);
  box-shadow: 0 20px 25px -5px rgba(0, 0, 0, 0.2);
  width: 100%;
  max-width: 360px;
  position: relative;
  transition: var(--transition);
}

.visual-card:hover {
  transform: translateY(-5px);
}

.visual-badge {
  color: #818cf8;
  font-size: 0.8rem;
  font-weight: 700;
  text-transform: uppercase;
  margin-bottom: 0.5rem;
}

.visual-card h3 {
  font-size: 1.6rem;
  margin-bottom: 0.5rem;
}

.visual-card p {
  color: #94a3b8;
  font-size: 0.95rem;
  margin-bottom: 1.8rem;
}

.price-tag {
  font-size: 1.5rem;
  font-weight: 700;
  color: #38bdf8;
}

/* --- Products Section (Flexbox) --- */
.products-section {
  background-color: var(--white);
}

.product-flex-container {
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
  gap: 2rem;
}

.product-card {
  flex: 1 1 230px;
  max-width: 260px;
  background-color: var(--white);
  border: 1px solid var(--border);
  border-radius: var(--radius);
  display: flex;
  flex-direction: column;
  justify-content: space-between;
  overflow: hidden;
  transition: var(--transition);
}

.product-card:hover {
  transform: translateY(-6px);
  box-shadow: 0 12px 24px -4px rgba(15, 23, 42, 0.08);
  border-color: #cbd5e1;
}

.product-img-box {
  background-color: var(--bg-light);
  height: 180px;
  display: flex;
  align-items: center;
  justify-content: center;
  position: relative;
}

.device-icon {
  font-size: 4rem;
}

.product-tag {
  position: absolute;
  top: 10px;
  left: 10px;
  background: var(--white);
  padding: 0.2rem 0.6rem;
  border-radius: 4px;
  font-size: 0.75rem;
  font-weight: 700;
  color: var(--primary);
  border: 1px solid var(--border);
}

.product-details {
  padding: 1.4rem;
  display: flex;
  flex-direction: column;
  flex-grow: 1;
  justify-content: space-between;
}

.product-details h3 {
  font-size: 1.15rem;
  color: var(--dark);
  margin-bottom: 0.4rem;
}

.product-details p {
  color: var(--text-light);
  font-size: 0.85rem;
  margin-bottom: 1.2rem;
}

.card-bottom {
  display: flex;
  justify-content: space-between;
  align-items: center;
  margin-top: auto;
}

.price {
  font-size: 1.15rem;
  font-weight: 700;
  color: var(--dark);
}

.btn-cart {
  background-color: var(--primary);
  color: var(--white);
  border: none;
  padding: 0.5rem 0.9rem;
  border-radius: 6px;
  font-size: 0.8rem;
  font-weight: 600;
  cursor: pointer;
  transition: var(--transition);
}

.btn-cart:hover {
  background-color: var(--primary-hover);
}

/* --- About Section (Flexbox) --- */
.about-section {
  background-color: var(--bg-light);
}

.about-flex {
  display: flex;
  align-items: center;
  justify-content: space-between;
  gap: 3rem;
  flex-wrap: wrap;
}

.about-text-content {
  flex: 1 1 500px;
}

.about-text-content h2 {
  font-size: 2.2rem;
  color: var(--dark);
  margin-bottom: 1rem;
}

.about-text-content p {
  color: var(--text-light);
  margin-bottom: 2rem;
}

.value-pillars {
  display: flex;
  gap: 2rem;
  flex-wrap: wrap;
}

.pillar {
  flex: 1 1 200px;
}

.pillar h4 {
  color: var(--dark);
  margin-bottom: 0.4rem;
}

.pillar p {
  font-size: 0.9rem;
  margin-bottom: 0;
}

.about-stats-box {
  flex: 1 1 320px;
  display: flex;
  flex-direction: column;
  gap: 1.2rem;
}

.stat-item {
  background: var(--white);
  padding: 1.5rem;
  border-radius: var(--radius);
  border: 1px solid var(--border);
  display: flex;
  flex-direction: column;
  align-items: center;
  text-align: center;
}

.stat-num {
  font-size: 2.2rem;
  font-weight: 800;
  color: var(--primary);
}

.stat-lbl {
  font-size: 0.9rem;
  color: var(--text-light);
  font-weight: 500;
}

/* --- User Account Section (Flexbox) --- */
.account-section {
  background-color: var(--white);
}

.account-flex-container {
  display: flex;
  justify-content: center;
  gap: 2.5rem;
  flex-wrap: wrap;
}

.account-card {
  flex: 1 1 350px;
  max-width: 460px;
  background-color: var(--white);
  border: 1px solid var(--border);
  border-radius: var(--radius);
  padding: 2.5rem;
}

.account-card h3 {
  font-size: 1.4rem;
  color: var(--dark);
  margin-bottom: 1.5rem;
}

.account-form {
  display: flex;
  flex-direction: column;
  gap: 1.2rem;
}

.form-group {
  display: flex;
  flex-direction: column;
  gap: 0.4rem;
}

.form-group label {
  font-size: 0.875rem;
  font-weight: 600;
  color: var(--dark);
}

.form-group input,
.form-group textarea {
  padding: 0.75rem 1rem;
  border: 1px solid var(--border);
  border-radius: 6px;
  font-family: inherit;
  font-size: 0.95rem;
  outline: none;
  transition: var(--transition);
}

.form-group input:focus,
.form-group textarea:focus {
  border-color: var(--primary);
  box-shadow: 0 0 0 3px rgba(79, 70, 229, 0.1);
}

.card-accent {
  background-color: #f8fafc;
  display: flex;
  flex-direction: column;
  justify-content: space-between;
}

.benefit-list {
  list-style: none;
  display: flex;
  flex-direction: column;
  gap: 1rem;
  margin-bottom: 2rem;
}

.benefit-list li {
  color: var(--text-main);
  font-size: 0.95rem;
}

/* --- Contact Details Section (Flexbox) --- */
.contact-section {
  background-color: var(--bg-light);
}

.contact-flex-container {
  display: flex;
  gap: 2.5rem;
  flex-wrap: wrap;
  justify-content: center;
}

.contact-info-card,
.contact-form-card {
  flex: 1 1 380px;
  max-width: 500px;
  background: var(--white);
  border: 1px solid var(--border);
  border-radius: var(--radius);
  padding: 2.5rem;
}

.contact-info-card h3,
.contact-form-card h3 {
  font-size: 1.4rem;
  color: var(--dark);
  margin-bottom: 1rem;
}

.info-items {
  margin-top: 1.5rem;
  display: flex;
  flex-direction: column;
  gap: 0.75rem;
}

.contact-form {
  display: flex;
  flex-direction: column;
  gap: 1.2rem;
}

/* --- Footer (Flexbox) --- */
.footer {
  background-color: var(--dark);
  color: #94a3b8;
  padding: 4rem 1.5rem 2rem;
}

.footer-content {
  display: flex;
  flex-direction: column;
  align-items: center;
  gap: 2rem;
  text-align: center;
}

.footer-brand {
  font-size: 1.5rem;
  font-weight: 800;
  color: var(--white);
  margin-bottom: 0.3rem;
}

.footer-brand span {
  color: #818cf8;
}

.footer-social-links {
  display: flex;
  gap: 1.8rem;
  flex-wrap: wrap;
}

.footer-social-links a {
  color: #94a3b8;
  text-decoration: none;
  font-size: 0.95rem;
  font-weight: 500;
  transition: var(--transition);
}

.footer-social-links a:hover {
  color: var(--white);
}

.footer-bottom {
  border-top: 1px solid var(--dark-surface);
  padding-top: 2rem;
  width: 100%;
  font-size: 0.85rem;
}

/* --- Responsive Media Queries --- */
@media (max-width: 768px) {
  .navbar {
    flex-direction: column;
    gap: 1rem;
  }
  .nav-links {
    gap: 1.2rem;
    flex-wrap: wrap;
    justify-content: center;
  }
  .hero-text h1 {
    font-size: 2.4rem;
  }
}
```

## OUTPUT

<img width="1899" height="864" alt="Screenshot 2026-09-05 134050" src="https://github.com/user-attachments/assets/e20409ea-0489-4dc1-b28a-cd5f031295ce" />
<img width="1892" height="997" alt="Screenshot 2026-09-05 134101" src="https://github.com/user-attachments/assets/388b2de1-f4c5-46fc-8ac2-61417dbe5150" />
<img width="1910" height="1000" alt="Screenshot 2026-09-05 134109" src="https://github.com/user-attachments/assets/543d089d-06f2-4704-a2df-a9b8d7fea423" />

## RESULT
The program for creating commercial website using CSS Flexbox is executed successfully.
