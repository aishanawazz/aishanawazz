<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sample Portfolio</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>John Doe</h1>
        <nav>
            <ul>
                <li><a href="#about">About</a></li>
                <li><a href="#projects">Projects</a></li>
                <li><a href="#resume">Resume</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>
    <main>
        <section id="about">
            <h2>About Me</h2>
            <p>I'm a recent graduate in Information Technology with a passion for plants, research, and academic writing. Currently learning Islamic studies.</p>
        </section>
        <section id="projects">
            <h2>Projects</h2>
            <div class="project">
                <h3>Plant Care Database</h3>
                <p>A web-based application to help users manage their plant collections.</p>
                <a href="https://github.com/yourusername/plant-care-database" target="_blank">View Project</a>
            </div>
            <div class="project">
                <h3>Academic Paper Review System</h3>
                <p>A platform for reviewing and managing academic papers.</p>
                <a href="https://github.com/yourusername/paper-review-system" target="_blank">View Project</a>
            </div>
        </section>
        <section id="resume">
            <h2>Resume</h2>
            <a href="resume.pdf" target="_blank">Download Resume</a>
        </section>
        <section id="contact">
            <h2>Contact</h2>
            <form id="contact-form">
                <label for="name">Name:</label>
                <input type="text" id="name" name="name" required>
                <label for="email">Email:</label>
                <input type="email" id="email" name="email" required>
                <label for="message">Message:</label>
                <textarea id="message" name="message" required></textarea>
                <button type="submit">Send</button>
            </form>
        </section>
    </main>
    <footer>
        <p>&copy; 2024 John Doe. All rights reserved.</p>
    </footer>
    <script src="scripts.js"></script>
</body>
</html>
