<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sajeeb's shop</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f9;
            color: #333;
        }
        header {
            background-color: #4CAF50;
            color: white;
            padding: 20px 0;
            text-align: center;
        }
        header h1 {
            margin: 0;
            font-size: 2.5rem;
        }
        nav {
            text-align: center;
            background-color: #333;
        }
        nav a {
            color: white;
            text-decoration: none;
            padding: 15px 20px;
            display: inline-block;
        }
        nav a:hover {
            background-color: #4CAF50;
        }
        .container {
            padding: 20px;
            max-width: 1200px;
            margin: auto;
        }
        .section {
            margin: 40px 0;
        }
        .section h2 {
            text-align: center;
            margin-bottom: 20px;
        }
        .services {
            display: flex;
            justify-content: space-around;
            flex-wrap: wrap;
        }
        .service-item {
            background-color: white;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
            text-align: center;
            padding: 20px;
            margin: 10px;
            flex: 1;
            max-width: 300px;
            min-width: 200px;
        }
        .service-item img {
            width: 100%;
            border-radius: 10px;
        }
        .contact {
            text-align: center;
        }
        .contact form {
            display: inline-block;
            text-align: left;
        }
        .contact label {
            display: block;
            margin: 10px 0 5px;
        }
        .contact input, .contact textarea {
            width: 100%;
            padding: 10px;
            margin-bottom: 10px;
            border: 1px solid #ccc;
            border-radius: 5px;
        }
        .contact button {
            padding: 10px 20px;
            background-color: #4CAF50;
            color: white;
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }
        .contact button:hover {
            background-color: #45a049;
        }
        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 10px 0;
        }
    </style>
</head>
<body>
    <header>
        <h1>SAJEEB PHYSICS</h1>
        <p>A SUCCESSFUL MAN IS ONE WHO CAN LAY A SOLID FOUNDATION WITH THE BRICKS OTHERS THROW AT HIM.</p>
    </header>
    
    <nav>
        <a href="#about">ABOUT</a>
        <a href="#services">SERVICES</a>
        <a href="#contact">CONTACT</a>
    </nav>
    
    <div class="container">
        <!-- About Section -->
        <div id="about" class="section">
            <h2>About Us</h2>
            <p>Sajeeb Physics (sajeeb Shop) is an online education center based in Dhaka, Bangladesh, specializing in providing high-quality educational resources to students across the country. Established in 2024, the platform has quickly gained popularity among Bangladeshi students, with over 00,000 students actively learning and developing their skills through its diverse range of courses.</p>
        </div>
        
        <!-- Services Section -->
        <div id="services" class="section">
            <h2>Our Services</h2>
            <div class="services">
                <div class="service-item">
                    <img src="https://via.placeholder.com/300" alt="Service 1">
                    <h3>Physics Tesla Batch</h3>
                    <p>Academic to admission.</p>
                </div>
                <div class="service-item">
                    <img src="https://via.placeholder.com/300" alt="Service 2">
                    <h3>Physics 1st paper</h3>
                    <p>Academic to admission.</p>
                </div>
                <div class="service-item">
                    <img src="https://via.placeholder.com/300" alt="Service 3">
                    <h3>Physics 2nd paper</h3>
                    <p>Academic to admission.</p>
                </div>
            </div>
        </div>
        
        <!-- Contact Section -->
        <div id="contact" class="section">
            <h2>Contact Us</h2>
            <div class="contact">
                <form action="#">
                    <label for="name">Name</label>
                    <input type="text" id="name" name="name" placeholder="Your name" required>
                    
                    <label for="email">Email</label>
                    <input type="email" id="email" name="email" placeholder="Your email" required>
                    
                    <label for="message">Message</label>
                    <textarea id="message" name="message" placeholder="Your message" rows="5" required></textarea>
                    
                    <button type="submit">Send Message</button>
                </form>
            </div>
        </div>
    </div>
    
    <footer>
        <p>&copy; 2024 Sajeeb Chowdhury. All Rights Reserved.</p>
    </footer>
</body>![Picsart_25-01-09_14-19-30-653](https://github.com/user-attachments/assets/40425457-a233-4fcb-9adb-c59f0aeb4729)
![Picsart_25-01-11_20-55-50-859](https://github.com/user-attachments/assets/893f6a12-b524-4cd8-9a1f-cb0aa880d594)

</html>
