<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Multi-Agencies - Your Complete Business Solution</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600;700&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="css/style.css">
</head>
<body>
    <!-- Header/Navigation -->
    <header class="header">
        <div class="container">
            <nav class="navbar">
                <a href="index.html" class="logo">
                    <img src="images/logo.png" alt="Multi-Agencies Logo">
                </a>
                <div class="nav-links" id="navLinks">
                    <i class="fas fa-times" onclick="hideMenu()"></i>
                    <ul>
                        <li><a href="#home" class="active">Home</a></li>
                        <li><a href="#services">Services</a></li>
                        <li><a href="#about">About</a></li>
                        <li><a href="#portfolio">Portfolio</a></li>
                        <li><a href="#testimonials">Testimonials</a></li>
                        <li><a href="#contact">Contact</a></li>
                    </ul>
                </div>
                <i class="fas fa-bars" onclick="showMenu()"></i>
            </nav>
        </div>
    </header>

    <!-- Hero Section -->
    <section class="hero" id="home">
        <div class="container">
            <div class="hero-content">
                <h1>Your Complete Business Solution</h1>
                <p>We provide comprehensive services to help your business grow in the digital world.</p>
                <div class="hero-buttons">
                    <a href="#contact" class="btn btn-primary">Get Started</a>
                    <a href="#services" class="btn btn-secondary">Our Services</a>
                </div>
            </div>
            <div class="hero-image">
                <img src="images/hero-image.png" alt="Business Solutions">
            </div>
        </div>
    </section>

    <!-- Services Section -->
    <section class="services" id="services">
        <div class="container">
            <div class="section-header">
                <h2>Our Services</h2>
                <p>We offer a wide range of services to meet all your business needs</p>
            </div>
            <div class="services-grid">
                <div class="service-card">
                    <i class="fas fa-code"></i>
                    <h3>Web Development</h3>
                    <p>Custom websites tailored to your business needs with the latest technologies.</p>
                    <a href="#" class="read-more">Read More <i class="fas fa-arrow-right"></i></a>
                </div>
                <div class="service-card">
                    <i class="fas fa-mobile-alt"></i>
                    <h3>App Development</h3>
                    <p>Mobile applications for iOS and Android to reach your customers anywhere.</p>
                    <a href="#" class="read-more">Read More <i class="fas fa-arrow-right"></i></a>
                </div>
                <div class="service-card">
                    <i class="fas fa-chart-line"></i>
                    <h3>Digital Marketing</h3>
                    <p>Comprehensive strategies to increase your online presence and conversions.</p>
                    <a href="#" class="read-more">Read More <i class="fas fa-arrow-right"></i></a>
                </div>
                <div class="service-card">
                    <i class="fas fa-paint-brush"></i>
                    <h3>Graphic Design</h3>
                    <p>Creative designs that communicate your brand message effectively.</p>
                    <a href="#" class="read-more">Read More <i class="fas fa-arrow-right"></i></a>
                </div>
                <div class="service-card">
                    <i class="fas fa-search"></i>
                    <h3>SEO Services</h3>
                    <p>Improve your search engine rankings and drive more organic traffic.</p>
                    <a href="#" class="read-more">Read More <i class="fas fa-arrow-right"></i></a>
                </div>
                <div class="service-card">
                    <i class="fas fa-cloud"></i>
                    <h3>Cloud Solutions</h3>
                    <p>Secure and scalable cloud infrastructure for your business operations.</p>
                    <a href="#" class="read-more">Read More <i class="fas fa-arrow-right"></i></a>
                </div>
            </div>
        </div>
    </section>

    <!-- About Section -->
    <section class="about" id="about">
        <div class="container">
            <div class="about-content">
                <h2>About Multi-Agencies</h2>
                <p>We are a full-service digital agency dedicated to helping businesses of all sizes achieve their online goals. Our team of experts brings together diverse skills to provide comprehensive solutions.</p>
                <p>Founded in 2020, we've grown to serve clients across multiple industries, delivering measurable results and exceptional customer service.</p>
                <div class="stats">
                    <div class="stat-item">
                        <h3>150+</h3>
                        <p>Happy Clients</p>
                    </div>
                    <div class="stat-item">
                        <h3>200+</h3>
                        <p>Projects Completed</p>
                    </div>
                    <div class="stat-item">
                        <h3>95%</h3>
                        <p>Client Retention</p>
                    </div>
                </div>
            </div>
            <div class="about-image">
                <img src="images/about-image.jpg" alt="Our Team">
            </div>
        </div>
    </section>

    <!-- Portfolio Section -->
    <section class="portfolio" id="portfolio">
        <div class="container">
            <div class="section-header">
                <h2>Our Portfolio</h2>
                <p>Check out some of our recent work</p>
            </div>
            <div class="portfolio-filter">
                <button class="filter-btn active" data-filter="all">All</button>
                <button class="filter-btn" data-filter="web">Web Design</button>
                <button class="filter-btn" data-filter="app">App Development</button>
                <button class="filter-btn" data-filter="graphic">Graphic Design</button>
            </div>
            <div class="portfolio-grid">
                <div class="portfolio-item" data-category="web">
                    <img src="images/portfolio1.jpg" alt="E-commerce Website">
                    <div class="portfolio-overlay">
                        <h3>E-commerce Website</h3>
                        <p>Online store with custom features</p>
                        <a href="#" class="portfolio-link"><i class="fas fa-link"></i></a>
                    </div>
                </div>
                <div class="portfolio-item" data-category="app">
                    <img src="images/portfolio2.jpg" alt="Fitness App">
                    <div class="portfolio-overlay">
                        <h3>Fitness App</h3>
                        <p>Mobile application for workout tracking</p>
                        <a href="#" class="portfolio-link"><i class="fas fa-link"></i></a>
                    </div>
                </div>
                <div class="portfolio-item" data-category="graphic">
                    <img src="images/portfolio3.jpg" alt="Brand Identity">
                    <div class="portfolio-overlay">
                        <h3>Brand Identity</h3>
                        <p>Complete branding package</p>
                        <a href="#" class="portfolio-link"><i class="fas fa-link"></i></a>
                    </div>
                </div>
                <div class="portfolio-item" data-category="web">
                    <img src="images/portfolio4.jpg" alt="Corporate Website">
                    <div class="portfolio-overlay">
                        <h3>Corporate Website</h3>
                        <p>Professional business website</p>
                        <a href="#" class="portfolio-link"><i class="fas fa-link"></i></a>
                    </div>
                </div>
                <div class="portfolio-item" data-category="app">
                    <img src="images/portfolio5.jpg" alt="Food Delivery App">
                    <div class="portfolio-overlay">
                        <h3>Food Delivery App</h3>
                        <p>Restaurant ordering platform</p>
                        <a href="#" class="portfolio-link"><i class="fas fa-link"></i></a>
                    </div>
                </div>
                <div class="portfolio-item" data-category="graphic">
                    <img src="images/portfolio6.jpg" alt="Marketing Materials">
                    <div class="portfolio-overlay">
                        <h3>Marketing Materials</h3>
                        <p>Print and digital collateral</p>
                        <a href="#" class="portfolio-link"><i class="fas fa-link"></i></a>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Testimonials Section -->
    <section class="testimonials" id="testimonials">
        <div class="container">
            <div class="section-header">
                <h2>What Our Clients Say</h2>
                <p>Hear from businesses we've helped grow</p>
            </div>
            <div class="testimonial-slider">
                <div class="testimonial-slide active">
                    <div class="testimonial-content">
                        <i class="fas fa-quote-left"></i>
                        <p>"Working with Multi-Agencies transformed our online presence. Their team delivered beyond our expectations and provided ongoing support that's been invaluable."</p>
                        <div class="client-info">
                            <img src="images/client1.jpg" alt="Sarah Johnson">
                            <div>
                                <h4>Sarah Johnson</h4>
                                <span>CEO, TechSolutions</span>
                            </div>
                        </div>
                    </div>
                </div>
                <div class="testimonial-slide">
                    <div class="testimonial-content">
                        <i class="fas fa-quote-left"></i>
                        <p>"The mobile app they developed for our restaurant has increased our orders by 40%. Their attention to detail and user experience focus made all the difference."</p>
                        <div class="client-info">
                            <img src="images/client2.jpg" alt="Michael Chen">
                            <div>
                                <h4>Michael Chen</h4>
                                <span>Owner, TasteBuds</span>
                            </div>
                        </div>
                    </div>
                </div>
                <div class="testimonial-slide">
                    <div class="testimonial-content">
                        <i class="fas fa-quote-left"></i>
                        <p>"As a small business, we needed cost-effective solutions. Multi-Agencies understood our budget constraints and delivered exceptional value for money."</p>
                        <div class="client-info">
                            <img src="images/client3.jpg" alt="Emma Rodriguez">
                            <div>
                                <h4>Emma Rodriguez</h4>
                                <span>Founder, GreenThumb</span>
                            </div>
                        </div>
                    </div>
                </div>
                <div class="slider-controls">
                    <button class="slider-prev"><i class="fas fa-chevron-left"></i></button>
                    <button class="slider-next"><i class="fas fa-chevron-right"></i></button>
                </div>
                <div class="slider-dots">
                    <span class="dot active"></span>
                    <span class="dot"></span>
                    <span class="dot"></span>
                </div>
            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <section class="contact" id="contact">
        <div class="container">
            <div class="section-header">
                <h2>Get In Touch</h2>
                <p>Ready to start your project? Contact us today!</p>
            </div>
            <div class="contact-container">
                <div class="contact-info">
                    <div class="contact-item">
                        <i class="fas fa-map-marker-alt"></i>
                        <div>
                            <h3>Address</h3>
                            <p>123 Business Ave, Suite 456<br>New York, NY 10001</p>
                        </div>
                    </div>
                    <div class="contact-item">
                        <i class="fas fa-phone-alt"></i>
                        <div>
                            <h3>Phone</h3>
                            <p>+1 (555) 123-4567</p>
                        </div>
                    </div>
                    <div class="contact-item">
                        <i class="fas fa-envelope"></i>
                        <div>
                            <h3>Email</h3>
                            <p>info@multiagencies.com</p>
                        </div>
                    </div>
                    <div class="contact-item">
                        <i class="fas fa-clock"></i>
                        <div>
                            <h3>Working Hours</h3>
                            <p>Monday - Friday: 9am - 6pm<br>Saturday: 10am - 2pm</p>
                        </div>
                    </div>
                </div>
                <div class="contact-form">
                    <form id="contactForm">
                        <div class="form-group">
                            <input type="text" id="name" name="name" placeholder="Your Name" required>
                        </div>
                        <div class="form-group">
                            <input type="email" id="email" name="email" placeholder="Your Email" required>
                        </div>
                        <div class="form-group">
                            <input type="text" id="subject" name="subject" placeholder="Subject">
                        </div>
                        <div class="form-group">
                            <textarea id="message" name="message" placeholder="Your Message" required></textarea>
                        </div>
                        <button type="submit" class="btn btn-primary">Send Message</button>
                    </form>
                </div>
            </div>
        </div>
    </section>

    <!-- Newsletter Section -->
    <section class="newsletter">
        <div class="container">
            <div class="newsletter-content">
                <h3>Subscribe to Our Newsletter</h3>
                <p>Get the latest updates, news and offers directly to your inbox</p>
            </div>
            <form class="newsletter-form">
                <input type="email" placeholder="Enter your email" required>
                <button type="submit" class="btn btn-primary">Subscribe</button>
            </form>
        </div>
    </section>

    <!-- Footer -->
    <footer class="footer">
        <div class="container">
            <div class="footer-grid">
                <div class="footer-col">
                    <img src="images/logo-white.png" alt="Multi-Agencies Logo" class="footer-logo">
                    <p>Your complete business solution provider. We help businesses grow through innovative digital solutions.</p>
                    <div class="social-links">
                        <a href="#"><i class="fab fa-facebook-f"></i></a>
                        <a href="#"><i class="fab fa-twitter"></i></a>
                        <a href="#"><i class="fab fa-instagram"></i></a>
                        <a href="#"><i class="fab fa-linkedin-in"></i></a>
                    </div>
                </div>
                <div class="footer-col">
                    <h3>Quick Links</h3>
                    <ul>
                        <li><a href="#home">Home</a></li>
                        <li><a href="#services">Services</a></li>
                        <li><a href="#about">About Us</a></li>
                        <li><a href="#portfolio">Portfolio</a></li>
                        <li><a href="#contact">Contact</a></li>
                    </ul>
                </div>
                <div class="footer-col">
                    <h3>Services</h3>
                    <ul>
                        <li><a href="#">Web Development</a></li>
                        <li><a href="#">App Development</a></li>
                        <li><a href="#">Digital Marketing</a></li>
                        <li><a href="#">Graphic Design</a></li>
                        <li><a href="#">SEO Services</a></li>
                    </ul>
                </div>
                <div class="footer-col">
                    <h3>Contact Info</h3>
                    <ul>
                        <li><i class="fas fa-map-marker-alt"></i> 123 Business Ave, NY 10001</li>
                        <li><i class="fas fa-phone-alt"></i> +1 (555) 123-4567</li>
                        <li><i class="fas fa-envelope"></i> info@multiagencies.com</li>
                    </ul>
                </div>
            </div>
            <div class="footer-bottom">
                <p>&copy; 2023 Multi-Agencies. All Rights Reserved.</p>
                <div class="footer-links">
                    <a href="#">Privacy Policy</a>
                    <a href="#">Terms of Service</a>
                </div>
            </div>
        </div>
    </footer>

    <script src="js/script.js"></script>
</body>
</html>
/* Global Styles */
:root {
    --primary-color: #2563eb;
    --secondary-color: #1e40af;
    --accent-color: #3b82f6;
    --text-color: #333;
    --light-text: #6b7280;
    --bg-color: #f9fafb;
    --white: #ffffff;
    --black: #000000;
    --gray: #e5e7eb;
    --dark-gray: #4b5563;
    --box-shadow: 0 4px 6px -1px rgba
