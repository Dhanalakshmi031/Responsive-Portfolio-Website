# Responsive-Portfolio-Website
portfolio-website/
├── index.html
├── style.css
└── script.js
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>My Portfolio</title>
    <link rel="stylesheet" href="style.css" />
</head>
<body>
    <header>
        <nav class="navbar">
            <h1 class="logo">MyPortfolio</h1>
            <ul class="nav-links">
                <li><a href="#hero">Home</a></li>
                <li><a href="#about">About</a></li>
                <li><a href="#projects">Projects</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <section id="hero" class="hero">
        <h2>Hello, I'm Jane Doe</h2>
        <p>Web Developer | Designer | Tech Enthusiast</p>
    </section>

    <section id="about" class="about">
        <h2>About Me</h2>
        <p>I am a passionate front-end developer with experience in HTML, CSS, and JavaScript. I love building beautiful and responsive websites.</p>
    </section>

    <section id="projects" class="projects">
        <h2>My Projects</h2>
        <div class="project-card">
            <h3>Project One</h3>
            <p>A to-do list app built with vanilla JavaScript.</p>
        </div>
        <div class="project-card">
            <h3>Project Two</h3>
            <p>Responsive landing page using Flexbox and CSS Grid.</p>
        </div>
    </section>

    <section id="contact" class="contact">
        <h2>Contact Me</h2>
        <form id="contact-form">
            <input type="text" name="name" placeholder="Your Name" required />
            <input type="email" name="email" placeholder="Your Email" required />
            <textarea name="message" placeholder="Your Message" required></textarea>
            <button type="submit">Send</button>
        </form>
    </section>

    <footer>
        <p>&copy; 2025 Jane Doe. All rights reserved.</p>
    </footer>

    <script src="script.js"></script>
</body>
</html>
