# Brandstuff-website.
-<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>BrandStuff.in - Your Brand's Destination</title>
    <link rel="stylesheet" href="style.css">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;600;700&display=swap" rel="stylesheet">
</head>
<body>

    <header class="header">
        <div class="container">
            <a href="#" class="logo">BrandStuff.in</a>
            <nav class="main-nav">
                <ul>
                    <li><a href="#home">Home</a></li>
                    <li><a href="#products">Products</a></li>
                    <li><a href="#about">About</a></li>
                    <li><a href="#contact">Contact</a></li>
                </ul>
            </nav>
        </div>
    </header>

    <main>
        <section id="home" class="hero">
            <div class="container">
                <h1>Premium Quality, Branded For You.</h1>
                <p>Discover our exclusive collection of high-quality merchandise.</p>
                <a href="#products" class="cta-button">Shop Now</a>
            </div>
        </section>

        <section id="products" class="products-section">
            <div class="container">
                <h2>Featured Products</h2>
                <div class="product-grid">
                    <div class="product-card">
                        <img src="https://picsum.photos/400/300?random=1" alt="Branded T-Shirt">
                        <h3>Classic Tee</h3>
                        <p class="price">₹999</p>
                        <button class="add-to-cart-btn">Add to Cart</button>
                    </div>
                    <div class="product-card">
                        <img src="https://picsum.photos/400/300?random=2" alt="Branded Mug">
                        <h3>Coffee Mug</h3>
                        <p class="price">₹499</p>
                        <button class="add-to-cart-btn">Add to Cart</button>
                    </div>
                    <div class="product-card">
                        <img src="https://picsum.photos/400/300?random=3" alt="Branded Cap">
                        <h3>Baseball Cap</h3>
                        <p class="price">₹799</p>
                        <button class="add-to-cart-btn">Add to Cart</button>
                    </div>
                    <div class="product-card">
                        <img src="https://picsum.photos/400/300?random=4" alt="Branded Backpack">
                        <h3>Everyday Backpack</h3>
                        <p class="price">₹2,499</p>
                        <button class="add-to-cart-btn">Add to Cart</button>
                    </div>
                </div>
            </div>
        </section>
    </main>

    <footer id="contact" class="footer">
        <div class="container">
            <p>&copy; 2025 BrandStuff.in. All Rights Reserved.</p>
            <p>Made with ❤️ in Agra</p>
        </div>
    </footer>

    <script src="script.js"></script>
</body>
</html>
/* --- Basic Reset & Global Styles --- */
:root {
    --primary-color: #007BFF; /* A nice blue */
    --secondary-color: #333; /* Dark grey for text */
    --background-color: #f4f4f4; /* Light grey background */
    --card-bg-color: #ffffff; /* White for cards */
}

* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: 'Poppins', sans-serif;
    line-height: 1.6;
    color: var(--secondary-color);
    background-color: #fff;
}

.container {
    max-width: 1100px;
    margin: 0 auto;
    padding: 0 2rem;
}

/* --- Header & Navigation --- */
.header {
    background: var(--card-bg-color);
    box-shadow: 0 2px 5px rgba(0,0,0,0.1);
    position: sticky;
    top: 0;
    width: 100%;
    z-index: 100;
}

.header .container {
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 1rem 2rem;
}

.logo {
    font-size: 1.5rem;
    font-weight: 700;
    text-decoration: none;
    color: var(--primary-color);
}

.main-nav ul {
    list-style: none;
    display: flex;
}

.main-nav ul li {
    margin-left: 20px;
}

.main-nav a {
    text-decoration: none;
    color: var(--secondary-color);
    font-weight: 600;
    transition: color 0.3s ease;
}

.main-nav a:hover {
    color: var(--primary-color);
}

/* --- Hero Section --- */
.hero {
    background-color: var(--background-color);
    height: 60vh;
    display: flex;
    justify-content: center;
    align-items: center;
    text-align: center;
    padding: 0 2rem;
}

.hero h1 {
    font-size: 3rem;
    margin-bottom: 1rem;
}

.hero p {
    font-size: 1.2rem;
    margin-bottom: 2rem;
}

.cta-button {
    display: inline-block;
    background-color: var(--primary-color);
    color: #fff;
    padding: 12px 25px;
    border-radius: 5px;
    text-decoration: none;
    font-weight: 600;
    transition: background-color 0.3s ease;
}

.cta-button:hover {
    background-color: #0056b3;
}

/* --- Products Section --- */
.products-section {
    padding: 4rem 0;
    text-align: center;
}

.products-section h2 {
    font-size: 2.5rem;
    margin-bottom: 3rem;
}

.product-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
    gap: 2rem;
}

.product-card {
    background: var(--card-bg-color);
    border-radius: 10px;
    box-shadow: 0 4px 15px rgba(0,0,0,0.1);
    overflow: hidden;
    transition: transform 0.3s ease, box-shadow 0.3s ease;
    text-align: left;
}

.product-card:hover {
    transform: translateY(-10px);
    box-shadow: 0 8px 25px rgba(0,0,0,0.15);
}

.product-card img {
    width: 100%;
    height: 200px;
    object-fit: cover;
}

.product-card h3 {
    font-size: 1.2rem;
    margin: 1rem;
}

.product-card .price {
    font-size: 1.1rem;
    font-weight: 600;
    color: var(--primary-color);
    margin: 0 1rem 1rem;
}

.add-to-cart-btn {
    display: block;
    width: calc(100% - 2rem);
    margin: 0 1rem 1rem;
    padding: 10px;
    background-color: #28a745;
    color: white;
    border: none;
    border-radius: 5px;
    cursor: pointer;
    font-weight: 600;
    transition: background-color 0.3s ease;
}

.add-to-cart-btn:hover {
    background-color: #218838;
}

/* --- Footer --- */
.footer {
    background-color: var(--secondary-color);
    color: #fff;
    text-align: center;
    padding: 2rem 0;
}
document.addEventListener('DOMContentLoaded', () => {
    // Select all "Add to Cart" buttons
    const cartButtons = document.querySelectorAll('.add-to-cart-btn');

    // Add a click event listener to each button
    cartButtons.forEach(button => {
        button.addEventListener('click', () => {
            // Find the product name from the parent card
            const productCard = button.closest('.product-card');
            const productName = productCard.querySelector('h3').textContent;

            // Show a confirmation alert
            alert(`${productName} has been added to your cart!`);
        });
    });

    // Smooth scrolling for navigation links
    const navLinks = document.querySelectorAll('.main-nav a');

    navLinks.forEach(link => {
        link.addEventListener('click', function(e) {
            e.preventDefault(); // Prevent default jump
            
            const targetId = this.getAttribute('href');
            const targetSection = document.querySelector(targetId);
            
            if (targetSection) {
                window.scrollTo({
                    top: targetSection.offsetTop - 70, // Adjust for sticky header height
                    behavior: 'smooth'
                });
            }
        });
    });
});
