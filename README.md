<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Delicious Bites</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: #ff6347;
            color: white;
            padding: 20px;
            text-align: center;
        }
        nav {
            display: flex;
            justify-content: center;
            background-color: #333;
        }
        nav a {
            color: white;
            padding: 14px 20px;
            text-decoration: none;
        }
        nav a:hover {
            background-color: #ff6347;
        }
        section {
            padding: 20px;
            text-align: center;
        }
        .food-item {
            display: inline-block;
            margin: 20px;
            border: 1px solid #ddd;
            border-radius: 8px;
            overflow: hidden;
            width: 200px;
        }
        .food-item img {
            width: 100%;
            height: 150px;
        }
        .food-item h3 {
            margin: 10px 0;
        }
        .food-item p {
            margin: 0 10px 10px;
        }
        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 10px;
            margin-top: 20px;
        }
    </style>
</head>
<body>
    <header>
        <h1>Welcome to Delicious Bites!</h1>
        <p>Explore the world of flavors with our curated menu.</p>
    </header>
    <nav>
        <a href="#menu">Menu</a>
        <a href="#about">About Us</a>
        <a href="#contact">Contact</a>
    </nav>
    <section id="menu">
        <h2>Our Menu</h2>
        <div class="food-item">
            <img src="https://via.placeholder.com/200x150" alt="Pizza">
            <h3>Margherita Pizza</h3>
            <p>$12.99</p>
        </div>
        <div class="food-item">
            <img src="https://via.placeholder.com/200x150" alt="Burger">
            <h3>Cheeseburger</h3>
            <p>$9.99</p>
        </div>
        <div class="food-item">
            <img src="https://via.placeholder.com/200x150" alt="Pasta">
            <h3>Spaghetti Bolognese</h3>
            <p>$10.99</p>
        </div>
    </section>
    <section id="about">
        <h2>About Us</h2>
        <p>Delicious Bites brings you the best in comfort food with a touch of gourmet elegance.</p>
    </section>
    <section id="contact">
        <h2>Contact Us</h2>
        <p>Email: <a href="mailto:contact@deliciousbites.com">contact@deliciousbites.com</a></p>
        <p>Phone: +123 456 7890</p>
    </section>
    <footer>
        <p>&copy; 2024 Delicious Bites. All rights reserved.</p>
    </footer>
</body>
</html>
