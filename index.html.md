<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Moriarty the Patriot T-Shirts</title>
    <style>
        /* Basic reset */
        * { margin: 0; padding: 0; box-sizing: border-box; }

        /* Body styling */
        body {
            font-family: Arial, sans-serif;
            background-color: #1e1e2e;
            color: #fff;
            line-height: 1.6;
        }

        /* Container styling */
        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 1em;
        }

        /* Header styling */
        header {
            text-align: center;
            padding: 2em 0;
        }
        header h1 {
            font-size: 2.5em;
            color: #ff4d6d;
        }
        header p {
            font-size: 1.2em;
            color: #ccc;
        }

        /* Product Section */
        .products {
            display: flex;
            flex-wrap: wrap;
            gap: 2em;
            justify-content: center;
            padding: 2em 0;
        }
        .product {
            background-color: #2d2d3b;
            border-radius: 8px;
            padding: 1em;
            text-align: center;
            max-width: 250px;
        }
        .product img {
            width: 100%;
            border-radius: 8px;
        }
        .product h3 {
            margin-top: 1em;
            font-size: 1.2em;
            color: #ff4d6d;
        }
        .product p {
            margin: 0.5em 0;
            color: #bbb;
        }
        .product .price {
            font-size: 1.1em;
            color: #ff4d6d;
        }

        /* About Section */
        .about {
            background-color: #2a2a3b;
            padding: 2em;
            border-radius: 8px;
            margin: 2em 0;
            text-align: center;
        }
        .about h2 {
            font-size: 1.8em;
            color: #ff4d6d;
        }
        .about p {
            color: #ccc;
            max-width: 600px;
            margin: 1em auto;
        }

        /* Contact Form */
        .contact {
            background-color: #2a2a3b;
            padding: 2em;
            border-radius: 8px;
            text-align: center;
        }
        .contact h2 {
            font-size: 1.8em;
            color: #ff4d6d;
        }
        .contact form {
            display: flex;
            flex-direction: column;
            align-items: center;
            gap: 1em;
        }
        .contact input, .contact textarea, .contact button {
            width: 100%;
            max-width: 400px;
            padding: 0.8em;
            border: none;
            border-radius: 4px;
        }
        .contact input, .contact textarea {
            background-color: #3a3a4d;
            color: #fff;
        }
        .contact button {
            background-color: #ff4d6d;
            color: #fff;
            font-size: 1em;
            cursor: pointer;
        }
        .contact button:hover {
            background-color: #ff6583;
        }

        /* Footer */
        footer {
            text-align: center;
            padding: 1em 0;
            color: #777;
            font-size: 0.9em;
        }
    </style>
</head>
<body>
    <div class="container">
        <!-- Header Section -->
        <header>
            <h1>Moriarty the Patriot T-Shirts</h1>
            <p>Express your love for anime with our exclusive Moriarty the Patriot collection!</p>
        </header>

        <!-- Products Section -->
        <section class="products">
            <div class="product">
                <img src="tshirt1.jpg" alt="Moriarty T-Shirt 1">
                <h3>Moriarty Classic Tee</h3>
                <p>Show your love for the mastermind of crime!</p>
                <p class="price">$25.00</p>
            </div>
            <div class="product">
                <img src="tshirt2.jpg" alt="Moriarty T-Shirt 2">
                <h3>Anime Style Silhouette</h3>
                <p>A bold, anime-style look inspired by Moriarty!</p>
                <p class="price">$28.00</p>
            </div>
            <div class="product">
                <img src="tshirt3.jpg" alt="Moriarty T-Shirt 3">
                <h3>Elegant Moriarty</h3>
                <p>Sleek, dark, and inspired by classic Moriarty style.</p>
                <p class="price">$30.00</p>
            </div>
        </section>

        <!-- About Section -->
        <section class="about">
            <h2>About Us</h2>
            <p>We are passionate anime fans dedicated to bringing iconic characters to life on high-quality T-shirts. Our designs are inspired by Moriarty the Patriot, capturing the essence of its characters with every shirt. Wear your fandom proudly!</p>
        </section>

        <!-- Contact Form -->
        <section class="contact">
            <h2>Contact Us</h2>
            <form action="#" method="post">
                <input type="text" name="name" placeholder="Your Name" required>
                <input type="email" name="email" placeholder="Your Email" required>
                <textarea name="message" rows="4" placeholder="Your Message"></textarea>
                <button type="submit">Send Message</button>
            </form>
        </section>

        <!-- Footer -->
        <footer>
            <p>&copy; 2024 Moriarty T-Shirts. All rights reserved.</p>
        </footer>
    </div>
</body>
</html>