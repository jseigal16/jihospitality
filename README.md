# jihospitality 
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>J&I Hospitality</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f9;
        }
        header {
            background-color: #007BFF;
            color: white;
            padding: 1rem;
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
            text-align: center;
        }
        nav a:hover {
            background-color: #ddd;
            color: black;
        }
        main {
            padding: 20px;
            background-color: white;
            margin: 20px auto;
            max-width: 800px;
        }
        section {
            margin-bottom: 20px;
        }
        h2 {
            color: #333;
        }
        footer {
            text-align: center;
            padding: 1rem;
            background-color: #333;
            color: white;
            position: fixed;
            bottom: 0;
            width: 100%;
        }
        .contact-form {
            display: flex;
            flex-direction: column;
        }
        .contact-form input, .contact-form textarea {
            padding: 10px;
            margin-bottom: 10px;
            border: 1px solid #ccc;
        }
        .contact-form button {
            padding: 10px;
            background-color: #007BFF;
            color: white;
            border: none;
        }
    </style>
</head>
<body>
    <header>
        <h1>Welcome to J&I Hospitality</h1>
    </header>
    <nav>
        <a href="#home">Home</a>
        <a href="#services">Services</a>
        <a href="#testimonials">Testimonials</a>
        <a href="#contact">Contact</a>
    </nav>
    <main>
        <section id="home">
            <h2>Home</h2>
            <p>we are jihospitality we help struggling airbnb owners or owner who just are sick of the hassle of airbnb bost property ratings and manage day to day task our 7 property's we have managed so far have all seen a great level of improvement in ratings and a up sale in nights per month .</p>
        </section>
        <section id="services">
            <h2>Our Services</h2>
            <ul>
                <li>Hotel Management</li>
                <li>Event Planning</li>
                <li>Catering Services</li>
                <li>Consultancy</li>
            </ul>
        </section>
        <section id="testimonials">
            <h2>Testimonials</h2>
            <p>"J&I Hospitality made our event unforgettable. Their attention to detail was impeccable." - Jane Doe</p>
            <p>"Our hotel's occupancy rates have never been higher, thanks to J&I's expertise." - John Smith</p>
        </section>
        <section id="contact">
            <h2>Contact Us</h2>
            <form class="contact-form">
                <input type="text" name="name" placeholder="Your Name" required>
                <input type="email" name="email" placeholder="Your Email" required>
                <textarea name="message" rows="4" placeholder="Your Message" required></textarea>
                <button type="submit">Send Message</button>
            </form>
        </section>
    </main>
    <footer>
        <p>&copy; 2024 J&I Hospitality</p>
    </footer>
</body>
</html>
