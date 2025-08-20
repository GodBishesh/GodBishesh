<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Bishesh | Portfolio</title>
  <style>
    /* Basic Reset */
    * { margin: 0; padding: 0; box-sizing: border-box; }
    body {
      font-family: "Segoe UI", sans-serif;
      background: #f8f9fa;
      color: #333;
      line-height: 1.6;
    }
    header {
      background: linear-gradient(135deg, #007bff, #6610f2);
      color: white;
      text-align: center;
      padding: 3rem 1rem;
    }
    header h1 { font-size: 2.8rem; margin-bottom: 0.5rem; }
    header p { font-size: 1.2rem; }

    nav {
      background: #fff;
      padding: 1rem;
      display: flex;
      justify-content: center;
      gap: 2rem;
      border-bottom: 1px solid #ddd;
      position: sticky;
      top: 0;
      z-index: 100;
    }
    nav a {
      text-decoration: none;
      font-weight: bold;
      color: #333;
      transition: color 0.3s;
    }
    nav a:hover { color: #007bff; }

    section {
      padding: 4rem 1rem;
      max-width: 900px;
      margin: auto;
    }
    h2 {
      font-size: 2rem;
      color: #007bff;
      margin-bottom: 1.5rem;
      text-align: center;
    }
    .skills, .projects {
      display: grid;
      gap: 1rem;
    }
    .card {
      background: white;
      padding: 1.5rem;
      border-radius: 12px;
      box-shadow: 0 4px 10px rgba(0,0,0,0.1);
      transition: transform 0.3s;
    }
    .card:hover { transform: translateY(-5px); }
    .card h3 { margin-bottom: 0.5rem; color: #333; }

    footer {
      text-align: center;
      padding: 2rem;
      background: #333;
      color: #f8f9fa;
    }
    footer a {
      color: #007bff;
      margin: 0 0.5rem;
      text-decoration: none;
    }
    .btn {
      display: inline-block;
      margin-top: 1rem;
      padding: 0.6rem 1.2rem;
      border-radius: 6px;
      text-decoration: none;
      background: #007bff;
      color: white;
      transition: background 0.3s;
    }
    .btn:hover { background: #0056b3; }
  </style>
</head>
<body>

  <header>
    <h1>👋 Hi, I’m Bishesh</h1>
    <p>Biology Student • Self-taught Programmer • Automation Enthusiast</p>
    <a href="#projects" class="btn">View My Work</a>
    <a href="CV.pdf" class="btn">Download CV</a>
  </header>

  <nav>
    <a href="#about">About</a>
    <a href="#skills">Skills</a>
    <a href="#projects">Projects</a>
    <a href="#contact">Contact</a>
  </nav>

  <section id="about">
    <h2>About Me</h2>
    <p>I am a Biology student with a strong interest in programming and technology. I aim to combine my knowledge of life sciences with software development to build tools that solve real-world problems.</p>
    <p>Currently, I’m exploring the intersection of <b>biology, data science, and automation</b>, contributing to projects that improve research, education, and everyday life.</p>
  </section>

  <section id="skills">
    <h2>Skills & Tools</h2>
    <div class="skills">
      <div class="card"><h3>Languages</h3><p>🐍 Python, ⚡ JavaScript, 💻 C++</p></div>
      <div class="card"><h3>Core Areas</h3><p>Automation, Data Analysis, Web Development, Bioinformatics</p></div>
      <div class="card"><h3>Tools</h3><p>Git, GitHub, Linux/Termux, VS Code</p></div>
    </div>
  </section>

  <section id="projects">
    <h2>Projects</h2>
    <div class="projects">
      <div class="card"><h3>TikTok Video Downloader</h3><p>A tool to download TikTok videos efficiently.</p></div>
      <div class="card"><h3>Maicha API</h3><p>An API that randomly sends short videos from a curated list.</p></div>
      <div class="card"><h3>Facebook Chatbot (C3C)</h3><p>An AI-powered chatbot for Facebook accounts.</p></div>
      <div class="card"><h3>Automation Bots</h3><p>Bots for Facebook Pages, emoji-based names, and reaction boosting.</p></div>
    </div>
  </section>

  <section id="contact">
    <h2>Contact</h2>
    <p>Feel free to reach out for collaboration or opportunities.</p>
    <p>Email: <a href="mailto:bish.hesh@gmail.com">bish.hesh@gmail.com</a></p>
    <p>
      <a href="https://github.com/GodBishesh" target="_blank">GitHub</a> |
      <a href="https://linkedin.com" target="_blank">LinkedIn</a>
    </p>
  </section>

  <footer>
    <p>© <script>document.write(new Date().getFullYear())</script> Bishesh. All rights reserved.</p>
  </footer>

</body>
</html>
