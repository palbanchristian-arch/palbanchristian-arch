<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8"/>
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Christian M. Palban | IT Portfolio</title>
  <style>
    * { box-sizing: border-box; margin: 0; padding: 0; }
    body { font-family: 'Segoe UI', sans-serif; background: #f5f5f5; color: #333; line-height: 1.6; }
    nav { background: #2c3e50; padding: 14px 32px; display: flex; justify-content: space-between; align-items: center; }
    nav .logo { color: #fff; font-weight: 700; font-size: 1rem; }
    nav ul { list-style: none; display: flex; gap: 24px; }
    nav ul a { color: #ccc; text-decoration: none; font-size: .9rem; }
    nav ul a:hover { color: #fff; }
    .hero { background: #2c3e50; color: #fff; text-align: center; padding: 60px 20px 50px; border-bottom: 4px solid #3498db; }
    .hero img { width: 140px; height: 140px; border-radius: 50%; object-fit: cover; object-position: center top; border: 3px solid #3498db; margin-bottom: 18px; }
    .hero h1 { font-size: 1.9rem; margin-bottom: 6px; }
    .hero .role { color: #3498db; font-size: 1rem; margin-bottom: 4px; }
    .hero .tagline { color: #aaa; font-size: .88rem; }
    section { padding: 48px 20px; max-width: 760px; margin: 0 auto; }
    section + section { border-top: 1px solid #ddd; }
    h2 { font-size: 1.3rem; color: #2c3e50; margin-bottom: 16px; padding-bottom: 8px; border-bottom: 2px solid #3498db; display: inline-block; }
    .about p { color: #555; font-size: .95rem; }
    .skills-list { display: flex; flex-wrap: wrap; gap: 10px; margin-top: 4px; }
    .skill { background: #2c3e50; color: #fff; padding: 6px 16px; border-radius: 4px; font-size: .85rem; }
    .project { background: #fff; border: 1px solid #ddd; border-radius: 6px; padding: 20px 22px; margin-bottom: 14px; }
    .project h3 { font-size: 1rem; color: #2c3e50; margin-bottom: 6px; }
    .project p { font-size: .88rem; color: #666; margin-bottom: 10px; }
    .project-tags { display: flex; gap: 8px; flex-wrap: wrap; }
    .project-tags span { background: #eaf2fb; color: #2980b9; padding: 3px 10px; border-radius: 4px; font-size: .78rem; }
    .contact-list { list-style: none; }
    .contact-list li { margin-bottom: 8px; font-size: .93rem; color: #555; }
    .contact-list li strong { color: #2c3e50; }
    footer { text-align: center; padding: 24px; font-size: .82rem; color: #aaa; border-top: 1px solid #ddd; }
  </style>
</head>
<body>

<nav>
  <span class="logo">BSIT-1B</span>
  <ul>
    <li><a href="#about">About</a></li>
    <li><a href="#skills">Skills</a></li>
    <li><a href="#projects">Projects</a></li>
    <li><a href="#contact">Contact</a></li>
  </ul>
</nav>

<div class="hero">
  <img src="IMAGES/Images1.jpg" alt="Christian M. Palban"/>
  <h1>Christian M. Palban</h1>
  <p class="role">Information Technology Student</p>
  <p class="tagline">Future IT Professional &nbsp;|&nbsp; Web Developer &nbsp;|&nbsp; Java Enthusiast</p>
</div>

<section id="about" class="about">
  <h2>About Me</h2>
  <p>I am Christian M. Palban, a first-year BSIT student at Davao Del Norte State College (DNSC). I am passionate about software development and building systems that solve real-world problems. My goal is to become a reliable IT professional who creates meaningful and practical solutions.</p>
</section>

<section id="skills">
  <h2>Skills</h2>
  <div class="skills-list">
    <span class="skill">HTML</span>
    <span class="skill">CSS</span>
    <span class="skill">JavaScript</span>
    <span class="skill">Java</span>
    <span class="skill">Database Management</span>
  </div>
</section>

<section id="projects">
  <h2>Projects</h2>

  <div class="project">
    <h3>Bank Management System</h3>
    <p>A console-based banking app built in Java using JOptionPane. Handles account creation, deposits, withdrawals, and balance inquiries.</p>
    <div class="project-tags"><span>Java</span><span>JOptionPane</span><span>OOP</span></div>
  </div>

  <div class="project">
    <h3>HealthConnect</h3>
    <p>A website have many compatables to do such with portals and designed for the people hassle to search seperated websites for health.</p>
    <div class="project-tags"><span>HTML</span><span>CSS</span><span>JavaScript</span></div>
  </div>

  <div class="project">
    <h3>Attendly: Presence Program</h3>
    <p>An attendance system that helps teachers to digitally track students and also create a qr code key—to make the students automatically take the attendance.</p>
    <div class="project-tags"><span>Java</span><span>JOptionPane</span><span>JFrame</span><span>Database</span><span>SQL</span></div>
  </div>
  
    <div class="project">
    <h3>Hangman Game System</h3>
    <p>console-base code simple game.</p>
    <div class="project-tags"><span>Java</span><span>JOptionPane</span></div>
  </div>
</section>

<section id="contact">
  <h2>Contact</h2>
  <ul class="contact-list">
    <li><strong>Email:</strong> cpalban20@email.com</li>
    <li><strong>GitHub:</strong>https://github.com/palbanchristian-arch</li>
    <li><strong>Location:</strong> Davao, Philippines</li>
  </ul>
</section>

<footer>
  &copy; 2025 Christian M. Palban | IT Portfolio
</footer>

</body>
</html>
