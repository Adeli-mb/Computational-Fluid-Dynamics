# Computational-Fluid-Dynamics
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>[Your Name] | Portfolio</title>
    <link rel="stylesheet" href="style.css">
    <script src="https://kit.fontawesome.com/a076d05399.js" crossorigin="anonymous"></script>
</head>
<body>
    <header>
        <div class="logo">[Your Name]</div>
        <nav>
            <ul>
                <li><a href="#about">About</a></li>
                <li><a href="#projects">Projects</a></li>
                <li><a href="#skills">Skills</a></li>
                <li><a href="#contact">Contact</a></li>
                <li><button id="theme-toggle">🌙</button></li>
            </ul>
        </nav>
    </header>

    <section id="about">
        <div class="about-container">
            <img src="assets/profile.jpg" alt="Profile Picture" class="profile-img">
            <div class="about-text">
                <h2>Hi, I'm [Your Name]</h2>
                <p>Aspiring [Your Field] Engineer specializing in **CFD, Mechanical Design, and Aerospace Engineering.** Passionate about innovation and problem-solving.</p>
                <div class="socials">
                    <a href="https://linkedin.com/in/yourprofile" target="_blank"><i class="fab fa-linkedin"></i></a>
                    <a href="https://github.com/your-username" target="_blank"><i class="fab fa-github"></i></a>
                    <a href="assets/resume.pdf" download class="btn">Download Resume</a>
                </div>
            </div>
        </div>
    </section>

    <section id="projects">
        <h2>Projects</h2>
        <div class="project-grid">
            <div class="project-card">
                <h3>A320 CFD Simulation</h3>
                <p>Optimized A320 tail design to reduce drag and increase lift using CFD analysis.</p>
            </div>
            <div class="project-card">
                <h3>Two-Stroke UAV Engine</h3>
                <p>Designed a small-scale, two-stroke compression ignition engine for UAV applications.</p>
            </div>
        </div>
    </section>

    <section id="skills">
        <h2>Skills</h2>
        <ul class="skills-list">
            <li>Computational Fluid Dynamics (CFD)</li>
            <li>SolidWorks & Fusion 360</li>
            <li>Finite Element Analysis (FEA)</li>
            <li>MATLAB & Python</li>
            <li>Manufacturing Processes</li>
        </ul>
    </section>

    <section id="contact">
        <h2>Contact</h2>
        <form id="contact-form">
            <input type="text" placeholder="Your Name" required>
            <input type="email" placeholder="Your Email" required>
            <textarea placeholder="Your Message" required></textarea>
            <button type="submit">Send Message</button>
        </form>
    </section>

    <footer>
        <p>© 2024 [Your Name] | All Rights Reserved.</p>
    </footer>

    <script src="script.js"></script>
</body>
</html>
