<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>BangOnSnow</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
            color: #333;
        }

        header {
            background: linear-gradient(90deg, #0077ff, #00d4ff);
            color: white;
            padding: 20px;
            text-align: center;
        }

        header h1 {
            margin: 0;
        }

        nav {
            display: flex;
            justify-content: center;
            background: #333;
        }

        nav a {
            color: white;
            text-decoration: none;
            padding: 15px 20px;
            display: block;
        }

        nav a:hover {
            background: #575757;
        }

        .hero {
            text-align: center;
            padding: 50px 20px;
            background: url('https://via.placeholder.com/1500x400') no-repeat center center/cover;
            color: white;
        }

        .hero h2 {
            font-size: 2.5em;
            margin: 0;
        }

        .hero p {
            font-size: 1.2em;
        }

        .content {
            max-width: 1200px;
            margin: 20px auto;
            padding: 20px;
            background: white;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
            border-radius: 8px;
        }

        .content h3 {
            margin-top: 0;
        }

        footer {
            text-align: center;
            padding: 10px;
            background: #333;
            color: white;
            position: fixed;
            bottom: 0;
            width: 100%;
        }
    </style>
</head>
<body>
    <header>
        <h1>BangOnSnow</h1>
        <p>Experience the thrill of winter!</p>
    </header>

    <nav>
        <a href="#about">About</a>
        <a href="#services">Services</a>
        <a href="#contact">Contact</a>
    </nav>

    <section class="hero">
        <h2>Welcome to BangOnSnow</h2>
        <p>Your ultimate destination for winter adventures.</p>
    </section>

    <section class="content" id="about">
        <h3>About Us</h3>
        <p>BangOnSnow is dedicated to bringing you unforgettable experiences in the snow. From skiing and snowboarding to cozy mountain retreats, we have it all!</p>
    </section>

    <section class="content" id="services">
        <h3>Our Services</h3>
        <ul>
            <li>Snowboarding and Skiing Lessons</li>
            <li>Guided Mountain Tours</li>
            <li>Winter Equipment Rentals</li>
            <li>Exclusive Winter Retreat Packages</li>
        </ul>
    </section>

    <section class="content" id="contact">
        <h3>Contact Us</h3>
        <p>Email: info@bangonsnow.com</p>
        <p>Phone: +123-456-7890</p>
        <p>Follow us on social media for updates and exclusive offers!</p>
    </section>

    <footer>
        <p>&copy; 2025 BangOnSnow. All rights reserved.</p>
    </footer>
</body>
</html>
