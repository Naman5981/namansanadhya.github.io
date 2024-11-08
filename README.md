# namansanadhya.github.io

<!DOCTYPE html>
<html lang="en">
<head>
    <!-- Character Set -->
    <meta charset="UTF-8">
    
    <!-- Viewport for Responsive Design -->
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    
    <!-- Page Title -->
    <title>Your Portfolio</title>
    
    <!-- Favicon (optional) -->
    <link rel="icon" href="favicon.ico" type="image/x-icon">
    
    <!-- CSS Stylesheet -->
    <link rel="stylesheet" href="styles.css">
    
    <!-- External Fonts (Google Fonts example) -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap" rel="stylesheet">
    
    <!-- Meta Description (SEO) -->
    <meta name="description" content="Personal portfolio showcasing projects and skills.">
    
    <!-- Social Media Preview (Open Graph) -->
    <meta property="og:title" content="Your Portfolio">
    <meta property="og:description" content="A showcase of my projects and skills.">
    <meta property="og:image" content="image.jpg">
    <meta property="og:url" content="https://yourwebsite.com">
    <meta name="twitter:card" content="summary_large_image">
</head>
<body>
    <!-- Header Section -->
    <header>
        <nav>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#about">About</a></li>
                <li><a href="#projects">Projects</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <!-- Main Content Section -->
    <main>
        <!-- Hero Section -->
        <section id="home">
            <h1>Welcome to My Portfolio</h1>
            <p>Showcasing my projects and skills.</p>
        </section>

        <!-- About Section -->
        <section id="about">
            <h2>About Me</h2>
            <p>A brief introduction about who you are.</p>
        </section>

        <!-- Projects Section -->
        <section id="projects">
            <h2>Projects</h2>
            <div class="project-card">
                <h3>Project Title</h3>
                <p>Project description goes here.</p>
                <a href="https://github.com/your-repo" target="_blank">View on GitHub</a>
            </div>
        </section>

        <!-- Contact Section -->
        <section id="contact">
            <h2>Contact</h2>
            <form action="submit_form.php" method="post">
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

    <!-- Footer Section -->
    <footer>
        <p>&copy; 2024 Your Name. All rights reserved.</p>
        <ul>
            <li><a href="https://github.com/yourusername" target="_blank">GitHub</a></li>
            <li><a href="https://linkedin.com/in/yourprofile" target="_blank">LinkedIn</a></li>
        </ul>
    </footer>

    <!-- JavaScript File (optional) -->
    <script src="script.js"></script>
</body>
</html>
