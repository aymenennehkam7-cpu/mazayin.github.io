<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Mazayin Restaurant - Authentic Moroccan fine dining experience in the heart of the city">
    <title>Mazayin Restaurant | Authentic Moroccan Cuisine</title>
    <link rel="stylesheet" href="style.css">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Cormorant+Garamond:wght@300;400;500;600;700&family=Montserrat:wght@300;400;500;600&display=swap" rel="stylesheet">
</head>
<body>
    <!-- Navigation Header -->
    <header class="header" id="header">
        <nav class="navbar">
            <div class="container">
                <div class="nav-wrapper">
                    <div class="logo">
                        <a href="#home">MAZAYIN</a>
                    </div>
                    <button class="mobile-toggle" id="mobileToggle" aria-label="Toggle navigation">
                        <span></span>
                        <span></span>
                        <span></span>
                    </button>
                    <ul class="nav-menu" id="navMenu">
                        <li><a href="#home" class="nav-link">Home</a></li>
                        <li><a href="#about" class="nav-link">About</a></li>
                        <li><a href="#menu" class="nav-link">Menu</a></li>
                        <li><a href="#gallery" class="nav-link">Gallery</a></li>
                        <li><a href="#contact" class="nav-link">Contact</a></li>
                        <li><a href="#reservation" class="btn-reserve">Reserve Table</a></li>
                    </ul>
                </div>
            </div>
        </nav>
    </header>

    <!-- Hero Section -->
    <section class="hero" id="home">
        <div class="hero-overlay"></div>
        <div class="hero-content">
            <h1 class="hero-title">Experience Authentic Moroccan Cuisine</h1>
            <p class="hero-subtitle">A journey through the flavors and traditions of Morocco</p>
            <div class="hero-buttons">
                <a href="#reservation" class="btn btn-primary">Book a Table</a>
                <a href="#menu" class="btn btn-secondary">View Menu</a>
            </div>
        </div>
        <div class="hero-scroll">
            <span>Scroll Down</span>
            <div class="scroll-indicator"></div>
        </div>
    </section>

    <!-- About Section -->
    <section class="about" id="about">
        <div class="container">
            <div class="about-grid">
                <div class="about-image">
                    <img src="https://via.placeholder.com/600x700?text=Mazayin+Interior" alt="Mazayin Restaurant Interior">
                    <div class="about-badge">
                        <span class="badge-text">Since 2015</span>
                    </div>
                </div>
                <div class="about-content">
                    <span class="section-label">Our Story</span>
                    <h2 class="section-title">Welcome to Mazayin</h2>
                    <p class="about-text">
                        Mazayin is more than just a restaurant—it's a celebration of Moroccan heritage and culinary artistry. 
                        Founded in 2015, we've been bringing the authentic tastes of Morocco to discerning diners who appreciate 
                        the rich tapestry of North African cuisine.
                    </p>
                    <p class="about-text">
                        Our chefs use traditional cooking methods passed down through generations, combined with the finest locally-sourced 
                        ingredients and authentic Moroccan spices imported directly from Marrakech. Every dish tells a story of our culture, 
                        our passion, and our commitment to excellence.
                    </p>
                    <div class="about-features">
                        <div class="feature-item">
                            <h3>Traditional Recipes</h3>
                            <p>Authentic dishes from family recipes</p>
                        </div>
                        <div class="feature-item">
                            <h3>Premium Ingredients</h3>
                            <p>Fresh, locally sourced produce</p>
                        </div>
                        <div class="feature-item">
                            <h3>Expert Chefs</h3>
                            <p>Trained in Moroccan culinary arts</p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Menu Section -->
    <section class="menu" id="menu">
        <div class="container">
            <div class="section-header">
                <span class="section-label">Discover</span>
                <h2 class="section-title">Our Menu</h2>
                <p class="section-description">Explore our carefully curated selection of authentic Moroccan dishes</p>
            </div>

            <div class="menu-categories">
                <button class="category-btn active" data-category="all">All Dishes</button>
                <button class="category-btn" data-category="starters">Starters</button>
                <button class="category-btn" data-category="mains">Main Courses</button>
                <button class="category-btn" data-category="desserts">Desserts</button>
                <button class="category-btn" data-category="beverages">Beverages</button>
            </div>

            <div class="menu-grid">
                <!-- Starters -->
                <div class="menu-item" data-category="starters">
                    <div class="menu-item-image">
                        <img src="https://via.placeholder.com/400x300?text=Harira+Soup" alt="Harira Soup">
                    </div>
                    <div class="menu-item-content">
                        <div class="menu-item-header">
                            <h3>Harira Soup</h3>
                            <span class="price">$8</span>
                        </div>
                        <p class="menu-item-description">Traditional Moroccan soup with tomatoes, lentils, chickpeas, and aromatic spices</p>
                    </div>
                </div>

                <div class="menu-item" data-category="starters">
                    <div class="menu-item-image">
                        <img src="https://via.placeholder.com/400x300?text=Zaalouk" alt="Zaalouk">
                    </div>
                    <div class="menu-item-content">
                        <div class="menu-item-header">
                            <h3>Zaalouk</h3>
                            <span class="price">$9</span>
                        </div>
                        <p class="menu-item-description">Smoky eggplant and tomato salad with garlic, olive oil, and Moroccan spices</p>
                    </div>
                </div>

                <div class="menu-item" data-category="starters">
                    <div class="menu-item-image">
                        <img src="https://via.placeholder.com/400x300?text=Briouats" alt="Briouats">
                    </div>
                    <div class="menu-item-content">
                        <div class="menu-item-header">
                            <h3>Briouats</h3>
                            <span class="price">$12</span>
                        </div>
                        <p class="menu-item-description">Crispy phyllo pastries filled with spiced meat or cheese, served with honey</p>
                    </div>
                </div>

                <!-- Main Courses -->
                <div class="menu-item" data-category="mains">
                    <div class="menu-item-image">
                        <img src="https://via.placeholder.com/400x300?text=Lamb+Tagine" alt="Lamb Tagine">
                        <span class="menu-badge">Chef's Special</span>
                    </div>
                    <div class="menu-item-content">
                        <div class="menu-item-header">
                            <h3>Lamb Tagine with Prunes</h3>
                            <span class="price">$28</span>
                        </div>
                        <p class="menu-item-description">Slow-cooked lamb with caramelized prunes, almonds, and aromatic spices</p>
                    </div>
                </div>

                <div class="menu-item" data-category="mains">
                    <div class="menu-item-image">
                        <img src="https://via.placeholder.com/400x300?text=Chicken+Tagine" alt="Chicken Tagine">
                    </div>
                    <div class="menu-item-content">
                        <div class="menu-item-header">
                            <h3>Chicken Tagine with Preserved Lemon</h3>
                            <span class="price">$24</span>
                        </div>
                        <p class="menu-item-description">Tender chicken with olives, preserved lemons, and saffron</p>
                    </div>
                </div>

                <div class="menu-item" data-category="mains">
                    <div class="menu-item-image">
                        <img src="https://via.placeholder.com/400x300?text=Couscous+Royale" alt="Couscous Royale">
                    </div>
                    <div class="menu-item-content">
                        <div class="menu-item-header">
                            <h3>Couscous Royale</h3>
                            <span class="price">$32</span>
                        </div>
                        <p class="menu-item-description">Traditional seven-vegetable couscous with lamb, chicken, and merguez sausage</p>
                    </div>
                </div>

                <div class="menu-item" data-category="mains">
                    <div class="menu-item-image">
                        <img src="https://via.placeholder.com/400x300?text=Pastilla" alt="Pastilla">
                        <span class="menu-badge">Signature</span>
                    </div>
                    <div class="menu-item-content">
                        <div class="menu-item-header">
                            <h3>Pastilla</h3>
                            <span class="price">$26</span>
                        </div>
                        <p class="menu-item-description">Sweet and savory phyllo pie with pigeon, almonds, cinnamon, and powdered sugar</p>
                    </div>
                </div>

                <div class="menu-item" data-category="mains">
                    <div class="menu-item-image">
                        <img src="https://via.placeholder.com/400x300?text=Grilled+Fish" alt="Grilled Fish">
                    </div>
                    <div class="menu-item-content">
                        <div class="menu-item-header">
                            <h3>Chermoula Grilled Fish</h3>
                            <span class="price">$30</span>
                        </div>
                        <p class="menu-item-description">Fresh sea bass marinated in chermoula sauce with herbs and spices</p>
                    </div>
                </div>

                <div class="menu-item" data-category="mains">
                    <div class="menu-item-image">
                        <img src="https://via.placeholder.com/400x300?text=Kefta+Tagine" alt="Kefta Tagine">
                    </div>
                    <div class="menu-item-content">
                        <div class="menu-item-header">
                            <h3>Kefta Tagine</h3>
                            <span class="price">$22</span>
                        </div>
                        <p class="menu-item-description">Spiced meatballs in rich tomato sauce with eggs and fresh herbs</p>
                    </div>
                </div>

                <!-- Desserts -->
                <div class="menu-item" data-category="desserts">
                    <div class="menu-item-image">
                        <img src="https://via.placeholder.com/400x300?text=Baklava" alt="Baklava">
                    </div>
                    <div class="menu-item-content">
                        <div class="menu-item-header">
                            <h3>Moroccan Baklava</h3>
                            <span class="price">$8</span>
                        </div>
                        <p class="menu-item-description">Layers of phyllo pastry with honey, almonds, and orange blossom water</p>
                    </div>
                </div>

                <div class="menu-item" data-category="desserts">
                    <div class="menu-item-image">
                        <img src="https://via.placeholder.com/400x300?text=Msemen" alt="Msemen">
                    </div>
                    <div class="menu-item-content">
                        <div class="menu-item-header">
                            <h3>Msemen with Honey</h3>
                            <span class="price">$7</span>
                        </div>
                        <p class="menu-item-description">Flaky Moroccan pancakes served warm with honey and butter</p>
                    </div>
                </div>

                <div class="menu-item" data-category="desserts">
                    <div class="menu-item-image">
                        <img src="https://via.placeholder.com/400x300?text=Orange+Salad" alt="Orange Salad">
                    </div>
                    <div class="menu-item-content">
                        <div class="menu-item-header">
                            <h3>Orange Salad with Cinnamon</h3>
                            <span class="price">$6</span>
                        </div>
                        <p class="menu-item-description">Fresh oranges with cinnamon, orange blossom water, and dates</p>
                    </div>
                </div>

                <!-- Beverages -->
                <div class="menu-item" data-category="beverages">
                    <div class="menu-item-image">
                        <img src="https://via.placeholder.com/400x300?text=Mint+Tea" alt="Mint Tea">
                    </div>
                    <div class="menu-item-content">
                        <div class="menu-item-header">
                            <h3>Traditional Mint Tea</h3>
                            <span class="price">$5</span>
                        </div>
                        <p class="menu-item-description">Fresh mint leaves steeped with green tea and sweetened to perfection</p>
                    </div>
                </div>

                <div class="menu-item" data-category="beverages">
                    <div class="menu-item-image">
                        <img src="https://via.placeholder.com/400x300?text=Fresh+Juice" alt="Fresh Juice">
                    </div>
                    <div class="menu-item-content">
                        <div class="menu-item-header">
                            <h3>Fresh Orange Juice</h3>
                            <span class="price">$6</span>
                        </div>
                        <p class="menu-item-description">Freshly squeezed Moroccan oranges</p>
                    </div>
                </div>

                <div class="menu-item" data-category="beverages">
                    <div class="menu-item-image">
                        <img src="https://via.placeholder.com/400x300?text=Almond+Milk" alt="Almond Milk">
                    </div>
                    <div class="menu-item-content">
                        <div class="menu-item-header">
                            <h3>Almond Milk</h3>
                            <span class="price">$7</span>
                        </div>
                        <p class="menu-item-description">Traditional almond milk with orange blossom water and honey</p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Gallery Section -->
    <section class="gallery" id="gallery">
        <div class="container">
            <div class="section-header">
                <span class="section-label">Ambiance</span>
                <h2 class="section-title">Our Gallery</h2>
                <p class="section-description">Step into our world and experience the authentic Moroccan atmosphere</p>
            </div>

            <div class="gallery-grid">
                <div class="gallery-item gallery-item-large">
                    <img src="https://via.placeholder.com/800x600?text=Restaurant+Interior" alt="Restaurant Interior">
                    <div class="gallery-overlay">
                        <span>Interior Design</span>
                    </div>
                </div>
                <div class="gallery-item">
                    <img src="https://via.placeholder.com/400x600?text=Moroccan+Decor" alt="Moroccan Decor">
                    <div class="gallery-overlay">
                        <span>Moroccan Decor</span>
                    </div>
                </div>
                <div class="gallery-item">
                    <img src="https://via.placeholder.com/400x600?text=Traditional+Seating" alt="Traditional Seating">
                    <div class="gallery-overlay">
                        <span>Traditional Seating</span>
                    </div>
                </div>
                <div class="gallery-item">
                    <img src="https://via.placeholder.com/400x300?text=Tagine+Dish" alt="Tagine Dish">
                    <div class="gallery-overlay">
                        <span>Authentic Cuisine</span>
                    </div>
                </div>
                <div class="gallery-item">
                    <img src="https://via.placeholder.com/400x300?text=Dining+Area" alt="Dining Area">
                    <div class="gallery-overlay">
                        <span>Dining Experience</span>
                    </div>
                </div>
                <div class="gallery-item gallery-item-wide">
                    <img src="https://via.placeholder.com/800x300?text=Restaurant+View" alt="Restaurant View">
                    <div class="gallery-overlay">
                        <span>Panoramic View</span>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Reservation Section -->
    <section class="reservation" id="reservation">
        <div class="container">
            <div class="reservation-content">
                <div class="reservation-info">
                    <span class="section-label">Make a Reservation</span>
                    <h2 class="section-title">Book Your Table</h2>
                    <p class="reservation-text">
                        Experience an unforgettable evening at Mazayin. Reserve your table now and let us take you 
                        on a culinary journey through Morocco.
                    </p>
                    <div class="reservation-features">
                        <div class="feature">
                            <svg width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2">
                                <path d="M12 2v20M17 5H9.5a3.5 3.5 0 0 0 0 7h5a3.5 3.5 0 0 1 0 7H6"/>
                            </svg>
                            <span>Private dining available</span>
                        </div>
                        <div class="feature">
                            <svg width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2">
                                <circle cx="12" cy="12" r="10"/>
                                <polyline points="12 6 12 12 16 14"/>
                            </svg>
                            <span>Open 7 days a week</span>
                        </div>
                        <div class="feature">
                            <svg width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2">
                                <path d="M21 15a2 2 0 0 1-2 2H7l-4 4V5a2 2 0 0 1 2-2h14a2 2 0 0 1 2 2z"/>
                            </svg>
                            <span>Special occasions welcome</span>
                        </div>
                    </div>
                </div>
                <div class="reservation-form-wrapper">
                    <form class="reservation-form" id="reservationForm">
                        <div class="form-group">
                            <input type="text" id="name" name="name" placeholder="Your Name" required>
                        </div>
                        <div class="form-group">
                            <input type="email" id="email" name="email" placeholder="Email Address" required>
                        </div>
                        <div class="form-group">
                            <input type="tel" id="phone" name="phone" placeholder="Phone Number" required>
                        </div>
                        <div class="form-row">
                            <div class="form-group">
                                <input type="date" id="date" name="date" required>
                            </div>
                            <div class="form-group">
                                <input type="time" id="time" name="time" required>
                            </div>
                        </div>
                        <div class="form-group">
                            <select id="guests" name="guests" required>
                                <option value="">Number of Guests</option>
                                <option value="1">1 Guest</option>
                                <option value="2">2 Guests</option>
                                <option value="3">3 Guests</option>
                                <option value="4">4 Guests</option>
                                <option value="5">5 Guests</option>
                                <option value="6">6 Guests</option>
                                <option value="7+">7+ Guests</option>
                            </select>
                        </div>
                        <div class="form-group">
                            <textarea id="message" name="message" placeholder="Special Requests (Optional)" rows="4"></textarea>
                        </div>
                        <button type="submit" class="btn btn-primary btn-full">Confirm Reservation</button>
                    </form>
                </div>
            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <section class="contact" id="contact">
        <div class="container">
            <div class="contact-grid">
                <div class="contact-info">
                    <span class="section-label">Get in Touch</span>
                    <h2 class="section-title">Visit Us</h2>
                    <p class="contact-description">
                        We're located in the heart of the city, ready to welcome you to an authentic Moroccan experience.
                    </p>
                    
                    <div class="contact-details">
                        <div class="contact-item">
                            <div class="contact-icon">
                                <svg width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2">
                                    <path d="M21 10c0 7-9 13-9 13s-9-6-9-13a9 9 0 0 1 18 0z"/>
                                    <circle cx="12" cy="10" r="3"/>
                                </svg>
                            </div>
                            <div class="contact-content">
                                <h3>Address</h3>
                                <p>123 Moroccan Avenue<br>Downtown District<br>City, State 12345</p>
                            </div>
                        </div>

                        <div class="contact-item">
                            <div class="contact-icon">
                                <svg width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2">
                                    <path d="M22 16.92v3a2 2 0 0 1-2.18 2 19.79 19.79 0 0 1-8.63-3.07 19.5 19.5 0 0 1-6-6 19.79 19.79 0 0 1-3.07-8.67A2 2 0 0 1 4.11 2h3a2 2 0 0 1 2 1.72 12.84 12.84 0 0 0 .7 2.81 2 2 0 0 1-.45 2.11L8.09 9.91a16 16 0 0 0 6 6l1.27-1.27a2 2 0 0 1 2.11-.45 12.84 12.84 0 0 0 2.81.7A2 2 0 0 1 22 16.92z"/>
                                </svg>
                            </div>
                            <div class="contact-content">
                                <h3>Phone</h3>
                                <p>+1 (555) 123-4567<br>+1 (555) 987-6543</p>
                            </div>
                        </div>

                        <div class="contact-item">
                            <div class="contact-icon">
                                <svg width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2">
                                    <circle cx="12" cy="12" r="10"/>
                                    <polyline points="12 6 12 12 16 14"/>
                                </svg>
                            </div>
                            <div class="contact-content">
                                <h3>Hours</h3>
                                <p>Monday - Thursday: 5:00 PM - 10:00 PM<br>
                                   Friday - Saturday: 5:00 PM - 11:00 PM<br>
                                   Sunday: 4:00 PM - 9:00 PM</p>
                            </div>
                        </div>

                        <div class="contact-item">
                            <div class="contact-icon">
                                <svg width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2">
                                    <path d="M4 4h16c1.1 0 2 .9 2 2v12c0 1.1-.9 2-2 2H4c-1.1 0-2-.9-2-2V6c0-1.1.9-2 2-2z"/>
                                    <polyline points="22,6 12,13 2,6"/>
                                </svg>
                            </div>
                            <div class="contact-content">
                                <h3>Email</h3>
                                <p>info@mazayinrestaurant.com<br>reservations@mazayinrestaurant.com</p>
                            </div>
                        </div>
                    </div>

                    <div class="social-links">
                        <a href="#" aria-label="Facebook" class="social-link">
                            <svg width="24" height="24" viewBox="0 0 24 24" fill="currentColor">
                                <path d="M18 2h-3a5 5 0 0 0-5 5v3H7v4h3v8h4v-8h3l1-4h-4V7a1 1 0 0 1 1-1h3z"/>
                            </svg>
                        </a>
                        <a href="#" aria-label="Instagram" class="social-link">
                            <svg width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2">
                                <rect x="2" y="2" width="20" height="20" rx="5" ry="5"/>
                                <path d="M16 11.37A4 4 0 1 1 12.63 8 4 4 0 0 1 16 11.37z"/>
                                <line x1="17.5" y1="6.5" x2="17.51" y2="6.5"/>
                            </svg>
                        </a>
                        <a href="#" aria-label="Twitter" class="social-link">
                            <svg width="24" height="24" viewBox="0 0 24 24" fill="currentColor">
                                <path d="M23 3a10.9 10.9 0 0 1-3.14 1.53 4.48 4.48 0 0 0-7.86 3v1A10.66 10.66 0 0 1 3 4s-4 9 5 13a11.64 11.64 0 0 1-7 2c9 5 20 0 20-11.5a4.5 4.5 0 0 0-.08-.83A7.72 7.72 0 0 0 23 3z"/>
                            </svg>
                        </a>
                        <a href="#" aria-label="TripAdvisor" class="social-link">
                            <svg width="24" height="24" viewBox="0 0 24 24" fill="currentColor">
                                <path d="M12 2C6.48 2 2 6.48 2 12s4.48 10 10 10 10-4.48 10-10S17.52 2 12 2zm0 18c-4.41 0-8-3.59-8-8s3.59-8 8-8 8 3.59 8 8-3.59 8-8 8zm3.5-9c.83 0 1.5-.67 1.5-1.5S16.33 8 15.5 8 14 8.67 14 9.5s.67 1.5 1.5 1.5zm-7 0c.83 0 1.5-.67 1.5-1.5S9.33 8 8.5 8 7 8.67 7 9.5 7.67 11 8.5 11zm3.5 6.5c2.33 0 4.31-1.46 5.11-3.5H6.89c.8 2.04 2.78 3.5 5.11 3.5z"/>
                            </svg>
                        </a>
                    </div>
                </div>

                <div class="contact-map">
                    <img src="https://via.placeholder.com/600x500?text=Map+Location" alt="Mazayin Restaurant Location Map">
                </div>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="footer">
        <div class="container">
            <div class="footer-content">
                <div class="footer-brand">
                    <h3>MAZAYIN</h3>
                    <p>Authentic Moroccan Cuisine</p>
                </div>
                <div class="footer-links">
                    <a href="#home">Home</a>
                    <a href="#about">About</a>
                    <a href="#
