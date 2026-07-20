# porfolio
Ex01 Portfolio


Date:20.07.2026


AIM
To create a Portfolio using HTML and CSS.

ALGORITHM

STEP 1
Create an HTML file (index.html)

STEP 2
Create a CSS file (style.css)

STEP 3
Include a navigation bar with links to different sections.

STEP 4
Add structured sections for introduction, about, projects, and contact details.

STEP 5
Define global styles for fonts, colors, and layout.

STEP 6
Style the header, navigation bar, and sections.

STEP 7
Use Flexbox or CSS Grid for layout design.

STEP 8
Add hover effects and transitions for interactivity.

STEP 9
Add Images and Media.

STEP 10
Use optimized images for a professional look.

STEP 11
Open the HTML file in a browser to check layout and functionality.

STEP 12
Fix styling issues and refine content placement.

STEP 13
Deploy the Portfolio.

STEP 14
Upload to GitHub Pages for free hosting.

PROGRAM
```
index.html
<!DOCTYPE html>
<html lang='en'>
<head>
    <meta charset='UTF-8'>
    <meta name='viewport' content='width=device-width, initial-scale=1.0'>
    <title>My Portfolio</title>
    <link rel='stylesheet' href='style.css'>
</head>
<body>

    <!-- Header -->
    <header>
        <nav class='navbar'>
            <h1 class='logo'>CHEZHIAN</h1>
            <ul class='nav-links'>
                <li><a href='#home'>Home</a></li>
                <li><a href='#about'>About</a></li>
                <li><a href='#projects'>Projects</a></li>
                <li><a href='#contact'>Contact</a></li>
            </ul>
        </nav>
    </header>

    <!-- Home Section -->
    <section id='home' class='hero'>
        <div class='hero-content'>
            <h2>Hello, I'm Chezhian</h2>
            <p>Aspiring Web Developer | Learning HTML, CSS, JavaScript & MERN Stack</p>
            <a href='#projects' class='btn'>View My Work</a>
        </div>
        <div class='hero-image'>
            <img src='IMG_20260712_222100_572.jpg.jpeg' alt='Chezhian'>
        </div>
    </section>

    <!-- About Section -->
    <section id='about' class='section'>
        <h2>About Me</h2>
        <p>
            I am a passionate web development student building projects with HTML, CSS,
            JavaScript, React, Node.js, and MongoDB. I enjoy creating responsive and user-friendly websites.
        </p>
    </section>

    <!-- Projects Section -->
    <section id='projects' class='section'>
        <h2>My Projects</h2>
        <div class='project-container'>
            <div class='project-card'>
                <h3>E-Commerce Website</h3>
                <p>MERN stack e-commerce application with authentication and payments.</p>
            </div>
            <div class='project-card'>
                <h3>AI Photo Booth</h3>
                <p>Web application with webcam capture, filters, and photo download features.</p>
            </div>
            <div class='project-card'>
                <h3>Portfolio Website</h3>
                <p>Personal portfolio built using HTML and CSS.</p>
            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <section id='contact' class='section'>
        <h2>Contact Me</h2>
        <p>Email: chezhian@example.com</p>
        <p>LinkedIn: linkedin.com/in/yourprofile</p>
        <p>GitHub: github.com/yourusername</p>
    </section>

    

</body>
</html>

style.css
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: Arial, sans-serif;
    line-height: 1.6;
    background: #f5f7fa;
    color: #333;
}

/* Navbar */
.navbar {
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 20px 10%;
    background: #0f172a;
    color: white;
    position: sticky;
    top: 0;
}

.logo {
    font-size: 28px;
    color: #38bdf8;
}

.nav-links {
    display: flex;
    list-style: none;
}

.nav-links li {
    margin-left: 20px;
}

.nav-links a {
    text-decoration: none;
    color: white;
    transition: color 0.3s ease;
}

.nav-links a:hover {
    color: #38bdf8;
}

/* Hero Section */
.hero {
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 80px 10%;
    min-height: 90vh;
    gap: 40px;
}

.hero-content h2 {
    font-size: 48px;
    margin-bottom: 20px;
}

.hero-content p {
    font-size: 18px;
    margin-bottom: 25px;
}

.btn {
    display: inline-block;
    padding: 12px 25px;
    background: #38bdf8;
    color: white;
    text-decoration: none;
    border-radius: 5px;
    transition: transform 0.3s ease, background 0.3s ease;
}

.btn:hover {
    background: #0284c7;
    transform: translateY(-3px);
}

.hero-image img {
    width: 300px;
    border-radius: 50%;
    border: 5px solid #38bdf8;
}

/* Sections */
.section {
    padding: 80px 10%;
    text-align: center;
}

.section h2 {
    font-size: 36px;
    margin-bottom: 20px;
    color: #0f172a;
}

/* Projects */
.project-container {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
    gap: 25px;
    margin-top: 40px;
}

.project-card {
    background: white;
    padding: 25px;
    border-radius: 10px;
    box-shadow: 0 4px 15px rgba(0,0,0,0.1);
    transition: transform 0.3s ease;
}

.project-card:hover {
    transform: translateY(-8px);
}

/* Footer */
footer {
    text-align: center;
    padding: 20px;
    background: #0f172a;
    color: white;
}

/* Responsive Design */
@media (max-width: 768px) {
    .navbar {
        flex-direction: column;
        gap: 15px;
    }

    .nav-links {
        flex-wrap: wrap;
        justify-content: center;
    }

    .hero {
        flex-direction: column;
        text-align: center;
    }

    .hero-content h2 {
        font-size: 36px;
    }

    .hero-image img {
        width: 220px;
    }
}
```
OUTPUT
![alt text](<Screenshot 2026-07-20 112631.png>)
RESULT
The program for creating Portfolio using HTML and CSS is executed successfully.

