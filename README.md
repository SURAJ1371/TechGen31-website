<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>TechGen31</title>
    
    <style>
        /* General Styles */
        body {
            
            font-family: 'Roboto', sans-serif;
            line-height: 1.6;
            margin: 0;
            padding: 0;
            color: #333;
            background-color: #f4f4f4;
        }

        /* Header Styles */
        header {
            background: linear-gradient(135deg, #5e72eb, #ad1dd8);
            color: #fff;
            padding: 20px 0;
            text-align: center;
            position: sticky;
            top: 0;
            z-index: 1000;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
        }

        header h1 {
            margin: 0;
            font-size: 2.5rem;
            text-transform: uppercase;
        }

        header nav ul {
            list-style: none;
            padding: 0;
        }

        header nav ul li {
            display: inline;
            margin: 0 15px;
        }

        header nav ul li a {
            color: #fff;
            text-decoration: none;
            font-weight: bold;
        }

        header nav ul li a:hover {
            text-decoration: underline;
        }

        /* Hero Section */
        .hero {
            background-image: url('heroimg.jpg');
            height: 400px;
            display: flex;
            justify-content: center;
            align-items: center;
            color: white;
            text-align: center;

           
        }

        .hero h2 {
            font-size: 3rem;
            text-shadow: 2px 2px 5px rgba(0, 0, 0, 0.3);
        }

        /* Video Section */
        #videos {
            padding: 40px 0;
            background-color: #fff;
        }

        #videos h2 {
            color: #333;
            text-align: center;
            margin-bottom: 40px;
        }

        .video-container {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            gap: 20px;
        }

        .video-container iframe {
            flex: 1;
            min-width: 300px;
            max-width: 480px;
            border-radius: 8px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
        }

        /* About Section */
        #about {
            padding: 60px 20px;
            background-color: #f9f9f9;
            text-align: center;
        }

        #about h2 {
            margin-bottom: 20px;
            font-size: 2rem;
        }

        #about p {
            max-width: 800px;
            margin: auto;
            font-size: 1.2rem;
            line-height: 1.8;
        }

        /* Contact Section */
        #contact {
            padding: 60px 20px;
            background-color: #fff;
            text-align: center;
        }

        #contact h2 {
            margin-bottom: 40px;
            font-size: 2rem;
        }

        form {
            max-width: 500px;
            margin: auto;
            background: #f1f1f1;
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
        }

        form label, form input, form textarea {
            display: block;
            width: 100%;
            margin-bottom: 15px;
            font-size: 1rem;
        }

        form input, form textarea {
            padding: 10px;
            border: 1px solid #ccc;
            border-radius: 4px;
            font-size: 1rem;
        }

        form button {
            background: #5e72eb;
            color: #fff;
            border: none;
            padding: 10px 20px;
            border-radius: 4px;
            cursor: pointer;
            font-size: 1rem;
            font-weight: bold;
        }

        form button:hover {
            background: #4b60d1;
        }

        /* Footer Styles */
        footer {
            background: #333;
            color: #fff;
            text-align: center;
            padding: 20px 0;
            margin-top: 40px;
            position: relative;
            bottom: 0;
            width: 100%;
        }

        footer p {
            margin: 0;
            font-size: 1rem;
        }

        footer a {
            color: #fff;
            text-decoration: none;
        }

        footer a:hover {
            text-decoration: underline;
        }
    </style>
</head>
<body>

    <!-- Header -->
    <header>
        <h1>Welcome to TechGen31</h1>
        <nav>
            <ul>
                <li><a href="#videos">Videos</a></li>
                <li><a href="#about">About</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <!-- Hero Section -->
    <div class="hero">
        <h2>Inspiring the Next Generation of Tech Leaders</h2>
    </div>

    <!-- Main Content -->
    <main>
        <!-- Videos Section -->
        <section id="videos">
            <h2>Latest Videos</h2>
            <div class="video-container">
                <!-- Example YouTube videos -->
                <iframe src="https://www.youtube.com/embed/FIALcCgvX_0" title="YouTube video player"></iframe>
                <iframe src="https://www.youtube.com/embed/7rTBFmsahf4" title="YouTube video player"></iframe>
                <iframe src="https://www.youtube.com/embed/H3op7ZGz8tY" title="YouTube video player"></iframe> 
                <iframe src="https://www.youtube.com/embed/klaGQeoJeug" title="YouTube video player"></iframe>
            </div>
        </section>

        <!-- About Section -->
        <section id="about">
            <h2>About Me</h2>
            <p>I am a B.Tech Computer Science student and the creator of TechGen31, an educational platform dedicated to providing free and quality content to aspiring learners seeking career opportunities in the IT sector.</p>
        </section>

        <!-- Contact Section -->
        <section id="contact">
            <h2>Contact Me</h2>
            <form id="contact-form">
                <label for="name">Name:</label>
                <input type="text" id="name" name="name" required>

                <label for="email">Email:</label>
                <input type="email" id="email" name="email" required>

                <label for="message">Message:</label>
                <textarea id="message" name="message" required></textarea>

                <button type="submit">Send Message</button>
            </form>
        </section>
    </main>

    <!-- Footer -->
    <footer>
        <p>&copy; 2024 TechGen31. All rights reserved. | <a href="#privacy">Privacy Policy</a></p>
    </footer>

    <!-- JavaScript -->
    <script>
        document.getElementById('contact-form').addEventListener('submit', function(e) {
            e.preventDefault();
            alert('Your message has been sent!');
            this.reset();
        });
    </script>
</body>
</html>
