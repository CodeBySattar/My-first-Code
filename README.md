<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sattar Ahmed - Portfolio</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <!-- Navigation Bar -->
    <nav class="navbar">
        <div class="container">
            <div class="logo">Sattar Ahmed</div>
            <ul class="nav-links">
                <li><a href="#home">Home</a></li>
                <li><a href="#about">About</a></li>
                <li><a href="#skills">Skills</a></li>
                <li><a href="#projects">Projects</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </div>
    </nav>
    <!-- Home Section -->
    <section id="home" class="hero">
        <div class="container">
            <div class="hero-content">
                <img src="https://via.placeholder.com/200" alt="Sattar Ahmed" class="profile-pic">
                <h1>Sattar Ahmed</h1>
                <p class="tagline">Web Developer | Designer | Problem Solver</p>
                <button class="cta-button" onclick="document.getElementById('contact').scrollIntoView({behavior: 'smooth'})">Get In Touch</button>
            </div>
        </div>
    </section>
    <!-- About Section -->
    <section id="about" class="about">
        <div class="container">
            <h2>About Me</h2>
            <div class="about-content">
                <div class="about-text">
                    <p>Hello! I'm Sattar Ahmed, a passionate web developer with expertise in creating beautiful and functional websites. I love turning ideas into reality through code and design.</p>
                    <p>With a strong foundation in web technologies, I'm committed to delivering high-quality projects that exceed expectations. I'm always eager to learn new technologies and improve my skills.</p>
                </div>
            </div>
        </div>
    </section>
    <!-- Skills Section -->
    <section id="skills" class="skills">
        <div class="container">
            <h2>Skills</h2>
            <div class="skills-grid">
                <div class="skill-card">
                    <h3>HTML & CSS</h3>
                    <p>Expert in semantic HTML and modern CSS techniques</p>
                </div>
                <div class="skill-card">
                    <h3>JavaScript</h3>
                    <p>Proficient in vanilla JS and popular frameworks</p>
                </div>
                <div class="skill-card">
                    <h3>Responsive Design</h3>
                    <p>Creating mobile-first and accessible websites</p>
                </div>
                <div class="skill-card">
                    <h3>Web Development</h3>
                    <p>Full-stack development and optimization</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Projects Section -->
    <section id="projects" class="projects">
        <div class="container">
            <h2>Projects</h2>
            <div class="projects-grid">
                <div class="project-card">
                    <h3>Project 1</h3>
                    <p>A responsive web application built with modern technologies</p>
                    <a href="#" class="project-link">View Project →</a>
                </div>
                <div class="project-card">
                    <h3>Project 2</h3>
                    <p>An interactive dashboard with real-time data visualization</p>
                    <a href="#" class="project-link">View Project →</a>
                </div>
                <div class="project-card">
                    <h3>Project 3</h3>
                    <p>A mobile-friendly e-commerce platform</p>
                    <a href="#" class="project-link">View Project →</a>
                </div>
            </div>
        </div>
    </section>

    <!-- CV Section -->
    <section id="cv" class="cv-section">
        <div class="container">
            <h2>My CV</h2>
            <div class="cv-content">
                <div class="cv-section-item">
                    <h3>Education</h3>
                    <p><strong>Degree Name</strong> - University Name (Year)</p>
                    <p>Relevant coursework and achievements</p>
                </div>
                <div class="cv-section-item">
                    <h3>Experience</h3>
                    <p><strong>Job Title</strong> - Company Name (Years)</p>
                    <p>Description of responsibilities and achievements</p>
                </div>
                <div class="cv-section-item">
                    <h3>Certifications</h3>
                    <p>List your certifications and professional achievements</p>
                </div>
            </div>
            <a href="#" class="cv-download">Download Full CV</a>
        </div>
    </section>
    <!-- Contact Section -->
    <section id="contact" class="contact">
        <div class="container">
            <h2>Get In Touch</h2>
            <form class="contact-form" onsubmit="handleSubmit(event)">
                <input type="text" placeholder="Your Name" required>
                <input type="email" placeholder="Your Email" required>
                <textarea placeholder="Your Message" rows="5" required></textarea>
                <button type="submit" class="submit-btn">Send Message</button>
            </form>
        </div>
    </section>
    <!-- Footer -->
    <footer class="footer">
        <div class="container">
            <p>&copy; 2026 Sattar Ahmed. All rights reserved.</p>
            <div class="social-links">
                <a href="#">GitHub</a>
                <a href="#">LinkedIn</a>
                <a href="#">Twitter</a>
            </div>
        </div>
    </footer>
    <script src="script.js"></script>
</body>
</html> 
