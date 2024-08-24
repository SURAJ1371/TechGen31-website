# TechGen31-website
Designed to link YouTube video contents providing online education related to technical field

  WEBSITE code is written below:

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>TechGen31</title>
    
    <style>
        body {
    font-family: Arial, sans-serif;
    line-height: 1.6;
    margin: 0;
    padding: 0;
}

header {
    background: #ad1dd8;
    color: #fff;
    padding: 20px 0;
    text-align: center;
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
}

h2 {
    color: #b6161e;
}

.video-container {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
}

.video-container iframe {
    width: 300px;
    height: 200px;
    margin: 10px;
}

footer {
    background: #330d8c;
    color: #fff;
    text-align: center;
    padding: 1px 0;
    position: absolute;
    width: 100%;
    bottom: 1;
}

form {
    max-width: 400px;
    margin: auto;
}

form label, form input, form textarea {
    display: block;
    width: 100%;
    margin: 10px 0;
}

form button {
    background: #333;
    color: #fff;
    border: none;
    padding: 10px;
    cursor: pointer;
}

    </style>

    

    </script>
</head>
<body>
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

    <main>
        <section id="videos">
            <h2>Latest Videos</h2>
            <div class="video-container">
                <iframe width="560" height="315" src="https://www.youtube.com/embed/FIALcCgvX_0?si=_IWjeNszHwbuajdX" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
                <iframe width="654" height="368" src="https://www.youtube.com/embed/7rTBFmsahf4?list=PLAWsJKLQm8m1evpFiIJTWolI1B9jDqrqx" title="Importance of C++ language for coding career...   in 2 minutes!" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
                <iframe width="654" height="368" src="https://www.youtube.com/embed/sOsCxLb5q3Q?list=PLAWsJKLQm8m1evpFiIJTWolI1B9jDqrqx" title="AP Sum Calculator" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
                <iframe width="654" height="368" src="https://www.youtube.com/embed/klaGQeoJeug?list=PLAWsJKLQm8m1evpFiIJTWolI1B9jDqrqx" title="Let&#39;s learn how to program patterns into C++ language." frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
                <iframe width="631" height="368" src="https://www.youtube.com/embed/IdN1jEPmHJo" title="Is a^n b^n c^2n Context free Language or not?" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
                <iframe width="654" height="368" src="https://www.youtube.com/embed/H3op7ZGz8tY" title="DFS(Depth first search)" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
                <!-- Add more videos as needed -->
            </div>
        </section>

        <section id="about">
            <h2>About Me</h2>
            <p> I AM A BTECH COMPUTER SCIENCE STUDENT CREATED THIS ONLINE
                EDUCATIONAL PLATFORM FOR PROVIDING FREE AND QUALTITY CONTENT TO
                ALL NEEDY ASPIRANTS OF GREAT LEARNING AND SEEKING CAREER OPTIONS 
                IN IT SECTOR.
            </p>
        </section>

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

    <footer>
        <p>&copy; 2024 TechGen31. All rights reserved.</p>
    </footer>

    <script> //javascript code is embedded into HTML code.
        
        document.getElementById('contact-form').addEventListener('submit', function(e) {
    e.preventDefault();
    alert('Your message has been sent!');
    this.reset();
});

    
    </script>
</body>
</html>
