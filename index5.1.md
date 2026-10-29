File 1: index.html (Linked to External CSS)
HTML
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Styled Personal Website</title>
    <!-- Step 2: Link the external stylesheet in HTML -->
    <link rel="stylesheet" href="style.css">
</head>
<body>

    <!-- Header & Navigation -->
    <header>
        <h1>Welcome to My Website</h1>
        <!-- Step 5: Navigation links -->
        <nav>
            <ul>
                <li><a href="#about">About Me</a></li>
                <li><a href="#projects">Projects</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <!-- Main Content Section -->
    <main>
        <!-- Step 4: Headings and Paragraphs -->
        <section id="about">
            <h2>About Me</h2>
            <p>Hello! I am a web development enthusiast learning how to design clean, modern, and responsive websites using HTML and CSS.</p>
        </section>

        <section id="projects">
            <h2>My Projects</h2>
            <p>Here are some of the things I am working on:</p>
            <ul>
                <li><strong>Project 1:</strong> HTML Portfolio Page</li>
                <li><strong>Project 2:</strong> Styled Webpage with CSS</li>
                <li><strong>Project 3:</strong> Interactive Web Application</li>
            </ul>
        </section>

        <section id="contact">
            <h2>Contact</h2>
            <p>Feel free to reach out to me via email or social media!</p>
            <p><a href="mailto:example@email.com">Send Me an Email</a></p>
        </section>
    </main>

    <!-- Footer -->
    <footer>
        <p>&copy; 2026 My Website. All rights reserved.</p>
    </footer>

</body>
</html>
File 2: style.css (Step 1, 3, 4, and 5)
CSS
/* Step 3: Set body background, text color, and font */
body {
    background-color: #f4f7f6;
    color: #333333;
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    line-height: 1.6;
    margin: 0;
    padding: 0;
}

/* Header & Container Styling */
header {
    background-color: #2c3e50;
    color: #ffffff;
    padding: 20px 0;
    text-align: center;
}

main {
    max-width: 800px;
    margin: 20px auto;
    padding: 0 20px;
}

section {
    background-color: #ffffff;
    padding: 20px;
    margin-bottom: 20px;
    border-radius: 8px;
    box-shadow: 0 2px 5px rgba(0,0,0,0.1);
}

/* Step 4: Style headings, paragraphs, and links */
h1 {
    margin: 0 0 10px 0;
    font-size: 2.2rem;
}

h2 {
    color: #2c3e50;
    border-bottom: 2px solid #3498db;
    padding-bottom: 5px;
    margin-top: 0;
}

p {
    font-size: 1rem;
    margin-bottom: 15px;
}

a {
    color: #3498db;
    text-decoration: none;
    font-weight: bold;
}

a:hover {
    text-decoration: underline;
    color: #1d6fa5;
}

/* Step 5: Make navigation links readable and attractive */
nav ul {
    list-style-type: none;
    padding: 0;
    margin: 15px 0 0 0;
    display: flex;
    justify-content: center;
    gap: 20px;
}

nav ul li a {
    color: #ffffff;
    background-color: #3498db;
    padding: 8px 16px;
    border-radius: 4px;
    text-decoration: none;
    transition: background-color 0.3s ease;
}

nav ul li a:hover {
    background-color: #1d6fa5;
    text-decoration: none;
}

/* Footer Styling */
footer {
    text-align: center;
    padding: 15px 0;
    background-color: #e2e8f0;
    color: #666666;
    font-size: 0.9rem;
}
Step 6 Instructions: Inspecting Styles Using Chrome DevTools
To complete Step 6 for your assignment or demo:

Open index.html in your Google Chrome browser.

Right-click anywhere on the webpage (e.g., on a heading or navigation button) and select Inspect (or press Ctrl + Shift + I / Cmd + Option + I).

Under the Elements panel, click on elements to see how the rules in style.css are being applied in the Styles tab on the right side.