<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Kuso Clothing</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Kuso Clothing</h1>
        <nav>
            <ul>
                <li><a href="#products">Products</a></li>
                <li><a href="#contact">Contact</a></li>
                <li><a href="#subscribe">Subscribe</a></li>
            </ul>
        </nav>
    </header>

    <!-- Product Gallery Section -->
    <section id="products" class="product-gallery">
        <h2>Our Products</h2>
        <div class="product">
            <img src="https://via.placeholder.com/300x400" alt="Product 1">
            <h3>Black T-Shirt</h3>
            <p>Stylish and comfortable black T-shirt.</p>
            <span>Price: $25</span>
        </div>
        <div class="product">
            <img src="https://via.placeholder.com/300x400" alt="Product 2">
            <h3>Grey Hoodie</h3>
            <p>Perfect for chilly days, available in all sizes.</p>
            <span>Price: $45</span>
        </div>
        <div class="product">
            <img src="https://via.placeholder.com/300x400" alt="Product 3">
            <h3>Casual Jacket</h3>
            <p>Modern jacket for everyday use.</p>
            <span>Price: $80</span>
        </div>
    </section>

    <!-- Contact Form Section -->
    <section id="contact">
        <h2>Contact Us</h2>
        <form>
            <label for="name">Name:</label>
            <input type="text" id="name" name="name" required>

            <label for="email">Email:</label>
            <input type="email" id="email" name="email" required>

            <label for="message">Message:</label>
            <textarea id="message" name="message" rows="4" required></textarea>

            <button type="submit">Send Message</button>
        </form>
    </section>

    <!-- Newsletter Subscription Section -->
    <section id="subscribe">
        <h2>Subscribe to our Newsletter</h2>
        <form>
            <label for="newsletter-email">Email:</label>
            <input type="email" id="newsletter-email" name="newsletter-email" required>

            <button type="submit">Subscribe</button>
        </form>
    </section>

    <footer>
        <p>&copy; 2024 Kuso Clothing. All Rights Reserved.</p>
    </footer>

    <script src="script.js"></script>
</body>
</html>
![image](https://github.com/user-attachments/assets/9c34f7b9-fe5d-4119-962a-456c9a6c0ebe)
