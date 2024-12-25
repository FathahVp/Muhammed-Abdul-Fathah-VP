<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Your Portfolio</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f9f9f9;
        }
        header {
            background-color: #333;
            color: white;
            padding: 1rem 2rem;
            text-align: center;
        }
        nav {
            display: flex;
            justify-content: center;
            background-color: #444;
            padding: 0.5rem;
        }
        nav a {
            color: white;
            text-decoration: none;
            margin: 0 1rem;
            font-size: 1rem;
        }
        nav a:hover {
            text-decoration: underline;
        }
        main {
            padding: 2rem;
            max-width: 1000px;
            margin: auto;
        }
        section {
            margin-bottom: 2rem;
        }
        section h2 {
            border-bottom: 2px solid #ccc;
            padding-bottom: 0.5rem;
            color: #333;
        }
        .work-item {
            display: flex;
            flex-wrap: wrap;
            margin: 1rem 0;
        }
        .work-item img {
            max-width: 100%;
            border: 1px solid #ccc;
            margin-right: 1rem;
            margin-bottom: 1rem;
            flex: 1 1 300px;
        }
        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 1rem;
            margin-top: 2rem;
        }
    </style>
</head>
<body>
    <header>
        <h1>Your Name's Portfolio</h1>
        <p>Showcasing your works and posters</p>
    </header>
    <nav>
        <a href="#about">About Me</a>
        <a href="#works">My Works</a>
        <a href="#contact">Contact</a>
    </nav>
    <main>
        <section id="about">
            <h2>About Me</h2>
            <p>Write a brief introduction about yourself, your skills, and your passion. Include your professional background and what inspires your work.</p>
        </section>
        <section id="works">
            <h2>My Works</h2>
            <div class="work-item">
                <img src="path-to-your-image1.jpg" alt="Work 1">
                <img src="path-to-your-image2.jpg" alt="Work 2">
                <img src="path-to-your-image3.jpg" alt="Work 3">
            </div>
            <p>Upload more of your works by replacing the above placeholders with your actual files.</p>
        </section>
        <section id="contact">
            <h2>Contact</h2>
            <p>If you would like to get in touch, you can email me at <a href="mailto:your-email@example.com">your-email@example.com</a>.</p>
        </section>
    </main>
    <footer>
        <p>&copy; 2024 Your Name. All rights reserved.</p>
    </footer>
</body>
</html>
