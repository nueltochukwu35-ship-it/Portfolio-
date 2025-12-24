<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Emmanuel Joseph Tochukwu | 3D Designer</title>
    <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap" rel="stylesheet">
    <style>
        /* Reset and base styles */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        body {
            font-family: 'Roboto', sans-serif;
            line-height: 1.6;
            color: #333;
            background-color: #f5f5f5;
        }
        a {
            text-decoration: none;
            color: inherit;
        }
        img {
            max-width: 100%;
            display: block;
        }

        /* Header / Navigation */
        header {
            background-color: #0d47a1;
            color: white;
            padding: 20px 0;
        }
        nav {
            max-width: 1100px;
            margin: auto;
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 0 20px;
        }
        nav h1 {
            font-size: 1.8rem;
        }
        nav ul {
            list-style: none;
            display: flex;
            gap: 20px;
        }
        nav ul li a {
            color: white;
            font-weight: 500;
            transition: color 0.3s;
        }
        nav ul li a:hover {
            color: #ffc107;
        }

        /* Hero Section */
        .hero {
            background: url('https://images.unsplash.com/photo-1605902711622-cfb43c4439a1?auto=format&fit=crop&w=1400&q=80') no-repeat center center/cover;
            color: white;
            text-align: center;
            padding: 120px 20px 80px;
        }
        .hero h2 {
            font-size: 2.5rem;
            margin-bottom: 20px;
        }
        .hero p {
            font-size: 1.2rem;
            max-width: 700px;
            margin: 0 auto 30px;
        }
        .hero a.button {
            background-color: #ffc107;
            color: #0d47a1;
            padding: 12px 30px;
            font-weight: bold;
            border-radius: 5px;
            transition: background 0.3s;
        }
        .hero a.button:hover {
            background-color: #ffb300;
        }

        /* Sections */
        section {
            padding: 60px 20px;
            max-width: 1100px;
            margin: auto;
        }
        h2.section-title {
            text-align: center;
            margin-bottom: 40px;
            font-size: 2rem;
            color: #0d47a1;
        }

        /* About */
        .about p {
            max-width: 800px;
            margin: auto;
            font-size: 1.1rem;
        }

        /* Projects */
        .projects-container {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 30px;
        }
        .project-card {
            background: white;
            border-radius: 8px;
            overflow: hidden;
            box-shadow: 0 4px 12px rgba(0,0,0,0.1);
            transition: transform 0.3s;
        }
        .project-card:hover {
            transform: translateY(-5px);
        }
        .project-card img {
            height: 200px;
            object-fit: cover;
        }
        .project-card .project-content {
            padding: 20px;
        }
        .project-card .project-content h3 {
            color: #0d47a1;
            margin-bottom: 10px;
        }
        .project-card .project-content p {
            font-size: 0.95rem;
            margin-bottom: 10px;
        }

        /* Skills & Tools */
        .skills-container, .tools-container {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            gap: 15px;
        }
        .skill, .tool {
            background-color: #0d47a1;
            color: white;
            padding: 10px 20px;
            border-radius: 20px;
            font-weight: 500;
            transition: background 0.3s;
        }
        .skill:hover, .tool:hover {
            background-color: #ffc107;
            color: #0d47a1;
        }

        /* Contact Form */
        .contact-form {
            max-width: 600px;
            margin: auto;
            display: flex;
            flex-direction: column;
            gap: 15px;
        }
        .contact-form input, .contact-form textarea {
            padding: 12px;
            border-radius: 5px;
            border: 1px solid #ccc;
            font-size: 1rem;
            width: 100%;
        }
        .contact-form button {
            background-color: #0d47a1;
            color: white;
            padding: 12px;
            font-weight: bold;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            transition: background 0.3s;
        }
        .contact-form button:hover {
            background-color: #ffc107;
            color: #0d47a1;
        }

        /* Footer */
        footer {
            background-color: #0d47a1;
            color: white;
            text-align: center;
            padding: 20px 0;
        }

        /* Responsive */
        @media(max-width:768px){
            nav ul {
                flex-direction: column;
                gap: 10px;
            }
        }
    </style>
</head>
<body>

    <!-- Header / Navigation -->
    <header>
        <nav>
            <h1>Emmanuel Joseph Tochukwu</h1>
            <ul>
                <li><a href="#about">About</a></li>
                <li><a href="#projects">Projects</a></li>
                <li><a href="#skills">Skills</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <!-- Hero Section -->
    <section class="hero">
        <h2>Mechanical Engineer & 3D Designer</h2>
        <p>Transforming concepts into stunning visual realities through 3D design, technical precision, and creative innovation.</p>
        <a href="#contact" class="button">Get in Touch</a>
    </section>

    <!-- About Section -->
    <section id="about" class="about">
        <h2 class="section-title">About Me</h2>
        <p>
            As a passionate 3D Designer with over 4 years of experience, I specialize in transforming imaginary concepts into stunning visual realities. 
            My expertise spans product design, architectural visualization, and realistic rendering. I thrive on delivering detail-rich, captivating models that leave a thrilling experience.
            <br><br>
            Proficient in industry-leading tools like AutoCAD, Fusion 360, and SolidWorks, I combine technical precision with creative vision to ensure every project is executed with finesse. 
            My operation is built on collaboration, innovation, and a relentless pursuit of excellence.
        </p>
    </section>

    <!-- Projects Section -->
    <section id="projects">
        <h2 class="section-title">Projects</h2>
        <div class="projects-container">
            <!-- Example Project -->
            <div class="project-card">
                <img src="https://images.unsplash.com/photo-1581092795368-0b6e8e02c5cb?auto=format&fit=crop&w=700&q=80" alt="Garri Frying Machine">
                <div class="project-content">
                    <h3>Garri Frying Machine – Agro Industry</h3>
                    <p>Developed a conceptual model and transformed it into a realistic, market-ready 3D model for an agro-industrial client.</p>
                    <p><strong>Tools Used:</strong> Fusion 360</p>
                </div>
            </div>
            <!-- Add more project cards here -->
        </div>
    </section>

    <!-- Skills Section -->
    <section id="skills">
        <h2 class="section-title">Skills & Tools</h2>
        <h3 style="text-align:center;">Skills</h3>
        <div class="skills-container">
            <div class="skill">3D Design</div>
            <div class="skill">Realistic Rendering</div>
            <div class="skill">Technical Drawings</div>
            <div class="skill">Problem Solving</div>
        </div>
        <h3 style="text-align:center; margin-top:30px;">Tools</h3>
        <div class="tools-container">
            <div class="tool">AutoCAD</div>
            <div class="tool">Fusion 360</div>
            <div class="tool">SOLIDWORKS</div>
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contact">
        <h2 class="section-title">Contact Me</h2>
        <form class="contact-form">
            <input type="text" placeholder="Your Name" required>
            <input type="email" placeholder="Your Email" required>
            <textarea rows="5" placeholder="Your Message" required></textarea>
            <button type="submit">Send Message</button>
        </form>
        <p style="text-align:center; margin-top:20px;">Or email me directly at <a href="mailto:noeljoseph419@gmail.com">noeljoseph419@gmail.com</a></p>
        <p style="text-align:center;">Phone: +2349017493504 | LinkedIn: <a href="https://www.linkedin.com/in/joseph-emmanuel-5a0290323" target="_blank">Profile</a></p>
    </section>

    <!-- Footer -->
    <footer>
        <p>&copy; 2025 Emmanuel Joseph Tochukwu. All rights reserved.</p>
    </footer>

</body>
</html>
