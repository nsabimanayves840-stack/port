<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Nsabimana Yves | Portfolio</title>
  <style>
    /* ===== BASIC STYLES ===== */
    body {
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      margin: 0;
      background-color: #2e63f7;
      color: #333;
      line-height: 1.6;
    }

    header {
      background-color: #254580;
      color: #1b1717;
      text-align: center;
      padding: 3rem 1rem;
    }

    header img {
      width: 150px;
      height: 150px;
      border-radius: 50%;
      border: 3px solid #6625ce;
      object-fit: cover;
      margin-bottom: 15px;
    }

    header h1 {
      margin: 0;
      font-size: 2rem;
      letter-spacing: 1px;
    }

    header p {
      font-style: italic;
      color: #20d3b5;
    }

    section {
      max-width: 900px;
      margin: 2rem auto;
      background: #67c014;
      border-radius: 8px;
      padding: 2rem;
      box-shadow: 0 2px 8px rgba(0, 0, 0, 0.1);
    }

    h2 {
      color: #2c3e50;
      border-left: 5px solid #2c3e50;
      padding-left: 10px;
      margin-bottom: 1rem;
    }

    .skills, .projects, .experience, .education {
      display: flex;
      flex-wrap: wrap;
      gap: 20px;
    }

    .card {
      background-color: #1e964c79;
      border-radius: 6px;
      padding: 1rem;
      flex: 1 1 260px;
      box-shadow: 0 1px 4px rgba(0, 0, 0, 0.05);
    }

    .card h3 {
      color: #2c3e50;
    }

    footer {
      background-color: #2c3e50;
      color: rgba(34, 28, 33, 0.795);
      text-align: center;
      padding: 1.5rem 0;
      margin-top: 40px;
      font-size: 0.9rem;
    }

    a {
      color: #2c3e50;
      text-decoration: none;
    }

    a:hover {
      text-decoration: underline;
    }

    .quote {
      background-color: #3b5a43;
      border-left: 4px solid #2c3e50;
      padding: 1rem;
      font-style: italic;
      margin-top: 10px;
    }

    .contact-info p {
      margin: 6px 0;
    }

    .button {
      display: inline-block;
      margin-top: 15px;
      background-color: #2c3e50;
      color: #272626;
      padding: 10px 18px;
      border-radius: 4px;
      text-decoration: none;
    }

    .button:hover {
      background-color: #3f5369;
    }
  </style>
</head>
<body>
  <header>
    <img src="./african-man-congo-traditional-clothes-toothy-smile-showing-thumbs-heart-loke-sign-indoor-isolated-gray-african-man-179995190.webp"Nsabimana Yves photo">
    <h1>Nsabimana Yves</h1>
    <p>Front-End Developer • Designer • Creative Thinker</p>
  </header>

  <section id="about">
    <h2>About Me</h2>
    <p>Hello! I’m <strong>Yves Nsabimana</strong>, a front-end web developer from Kigali, Rwanda. I enjoy turning ideas into clean, simple, and effective websites. My goal is to help individuals and organizations create strong digital identities that communicate clearly and look great on any device.</p>
    <p>When I’m not coding, I enjoy learning about design trends, improving my skills, and helping others understand technology.</p>
    <a class="button" href="#">Download CV</a>
  </section>

  <section id="skills">
    <h2>Skills</h2>
    <div class="skills">
      <div class="card"><h3>HTML & CSS</h3><p>Building clean and responsive websites using modern web standards.</p></div>
      <div class="card"><h3>JavaScript</h3><p>Adding interactivity, animations, and logic to web pages.</p></div>
      <div class="card"><h3>Figma</h3><p>Creating professional wireframes and mockups for clients.</p></div>
      <div class="card"><h3>Responsive Design</h3><p>Ensuring layouts adapt beautifully to any screen size.</p></div>
      <div class="card"><h3>Git & GitHub</h3><p>Version control and project collaboration with teams.</p></div>
    </div>
  </section>

  <section id="projects">
    <h2>Projects</h2>
    <div class="projects">
      <div class="card">
        <h3>School Website Redesign</h3>
        <p>A modern, easy-to-navigate school website built with HTML, CSS, and JavaScript.</p>
      </div>
      <div class="card">
        <h3>Coffee Shop Landing Page</h3>
        <p>Elegant landing page showcasing menu and gallery using pure CSS and Figma design.</p>
      </div>
      <div class="card">
        <h3>Personal Blog Template</h3>
        <p>Minimal blog with post categories and clean typography, optimized for mobile devices.</p>
      </div>
      <div class="card">
        <h3>Portfolio Site</h3>
        <p>The website you’re viewing now — designed with simplicity and usability in mind.</p>
      </div>
    </div>
  </section>

  <section id="experience">
    <h2>Experience</h2>
    <div class="experience">
      <div class="card">
        <h3>Freelance Web Designer</h3>
        <p><strong>2023 - Present</strong></p>
        <p>Worked with local businesses to design and launch small websites and landing pages. Focused on improving usability and branding consistency.</p>
      </div>
      <div class="card">
        <h3>Student Developer</h3>
        <p><strong>2022 - 2023</strong></p>
        <p>Built multiple school projects, improved HTML/CSS skills, and learned responsive design through practical exercises.</p>
      </div>
    </div>
  </section>

  <section id="education">
    <h2>Education</h2>
    <div class="education">
      <div class="card">
        <h3>Diploma in Information Technology</h3>
        <p><strong>Kigali Institute of Technology</strong><br>2021 - 2024</p>
        <p>Studied web design, networking, and programming fundamentals.</p>
      </div>
      <div class="card">
        <h3>Online Certifications</h3>
        <p><strong>Coursera, FreeCodeCamp</strong><br>2023 - Present</p>
        <p>Completed courses in JavaScript, Responsive Web Design, and UI/UX principles.</p>
      </div>
    </div>
  </section>

  <section id="testimonials">
    <h2>Testimonials</h2>
    <div class="quote">"Yves is a dedicated and creative developer who delivers beyond expectations. His work always shows professionalism." — Client</div>
    <div class="quote">"He helped our school modernize its website. The layout is simple, easy to use, and looks great on phones!" — School Staff</div>
  </section>

  <section id="contact">
    <h2>Contact</h2>
    <div class="contact-info">
      <p><strong>Email:</strong> <a href="mailto:nsabimanayves@gmail.com">nsabimanayves@gmail.com</a></p>
      <p><strong>Phone:</strong> 0798811200</p>
      <p><strong>Location:</strong> Kigali, Rwanda</p>
      <p><strong>LinkedIn:</strong> <a href="#">linkedin.com/in/nsabimanayves</a></p>
      <p><strong>GitHub:</strong> <a href="#">github.com/nsabimanayves</a></p>
    </div>
  </section>

  <footer>
    <p>© 2025 Nsabimana Yves | Built with passion and simplicity</p>
  </footer>
</body>
</html>
