<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <title>Abdelhakim Hani | Cybersecurity Engineer</title>
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <meta name="description" content="Cybersecurity Engineer | Full Stack Developer | AI Security Enthusiast"/>
  <link rel="icon" href="https://cdn-icons-png.flaticon.com/512/3064/3064197.png"/>

  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600;700&display=swap" rel="stylesheet">

  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: "Poppins", sans-serif;
    }

    body {
      background: linear-gradient(135deg, #020617, #020617);
      color: #e5e7eb;
      line-height: 1.7;
    }

    a {
      text-decoration: none;
      color: #22c55e;
      font-weight: 500;
    }

    header {
      height: 100vh;
      display: flex;
      align-items: center;
      justify-content: center;
      text-align: center;
      background: radial-gradient(circle at top, #022c22, #020617);
      padding: 20px;
    }

    .hero {
      max-width: 900px;
    }

    .hero h1 {
      font-size: 2.8em;
      margin-bottom: 10px;
      color: #22c55e;
    }

    .hero p {
      font-size: 1.2em;
      color: #cbd5f5;
      margin-bottom: 25px;
    }

    .badges img {
      margin: 8px;
    }

    section {
      padding: 80px 10%;
    }

    h2 {
      font-size: 2.2em;
      margin-bottom: 30px;
      color: #22c55e;
      text-align: center;
    }

    .about {
      max-width: 900px;
      margin: auto;
      text-align: center;
      font-size: 1.1em;
      color: #d1d5db;
    }

    .grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
      gap: 25px;
    }

    .card {
      background: #020617;
      padding: 25px;
      border-radius: 12px;
      border: 1px solid #1e293b;
      transition: transform 0.3s;
    }

    .card:hover {
      transform: translateY(-6px);
    }

    .card h3 {
      margin-bottom: 10px;
      color: #22c55e;
    }

    table {
      width: 100%;
      border-collapse: collapse;
      margin-top: 30px;
      background: #020617;
      border-radius: 12px;
      overflow: hidden;
    }

    th, td {
      padding: 15px;
      border: 1px solid #1e293b;
      text-align: left;
    }

    th {
      background: #022c22;
      color: #22c55e;
    }

    .projects a {
      display: block;
      margin: 10px 0;
      font-size: 1.05em;
    }

    .stats {
      text-align: center;
      margin-top: 40px;
    }

    footer {
      text-align: center;
      padding: 50px 20px;
      background: #020617;
      border-top: 1px solid #1e293b;
      color: #94a3b8;
      font-size: 0.95em;
    }

    @media(max-width: 768px){
      .hero h1 {
        font-size: 2.1em;
      }
    }
  </style>
</head>

<body>

<header>
  <div class="hero">
    <h1>Abdelhakim Hani</h1>
    <p>Cybersecurity Engineer · Full Stack Developer · AI & Automation Enthusiast</p>

    <div class="badges">
      <a href="https://www.linkedin.com/in/abdelhakim-hani" target="_blank">
        <img src="https://img.shields.io/badge/LinkedIn-0072b1?style=for-the-badge&logo=linkedin&logoColor=white">
      </a>
      <a href="mailto:han.23hani@gmail.com">
        <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white">
      </a>
      <a href="https://tryhackme.com/p/hani23" target="_blank">
        <img src="https://img.shields.io/badge/TryHackMe-7B1FA2?style=for-the-badge&logo=tryhackme&logoColor=white">
      </a>
      <a href="https://www.hackthebox.com/profile/YOUR_HTB_USERNAME" target="_blank">
        <img src="https://img.shields.io/badge/HackTheBox-101010?style=for-the-badge&logo=hackthebox&logoColor=white">
      </a>
    </div>
  </div>
</header>

<section>
  <h2>About Me</h2>
  <div class="about">
    I am a Computer Science Engineer specializing in Cybersecurity, passionate about building secure, intelligent systems that integrate AI, automation, and network defense.  
    Currently completing my engineering degree at Université Internationale de Rabat (UIR).  
    I enjoy solving real-world security challenges, building detection models, and contributing to innovative cybersecurity research.
  </div>
</section>

<section>
  <h2>Career Objective</h2>
  <div class="grid">
    <div class="card">Threat Detection & Incident Response</div>
    <div class="card">Vulnerability Management & Monitoring</div>
    <div class="card">AI-Driven Security Automation</div>
  </div>
</section>

<section>
  <h2>Professional Experience</h2>
  <div class="grid">

    <div class="card">
      <h3>Full Stack Developer — Copag (Menara Holding)</h3>
      <p><strong>July 2024 – September 2024</strong></p>
      <ul>
        <li>Developed a complete commercial management platform</li>
        <li>Designed full UML architecture</li>
        <li>Delivered production-ready web and mobile solution</li>
      </ul>
      <strong>Stack:</strong> Angular · Spring Boot · MySQL
    </div>

  </div>
</section>

<section>
  <h2>Key Projects</h2>
  <div class="grid">

    <div class="card">
      <h3>Intelligent XSS Detection System</h3>
      <p>Machine-learning based detection of advanced obfuscated XSS payloads.</p>
    </div>

    <div class="card">
      <h3>Command & Control Architecture Simulation</h3>
      <p>Realistic C2 network design with traffic and attack monitoring.</p>
    </div>

    <div class="card">
      <h3>Medical Image Classification</h3>
      <p>Deep learning model for GI bleeding detection using CNN and Random Forest.</p>
    </div>

  </div>
</section>

<section>
  <h2>Technical Skills</h2>
  <table>
    <tr><th>Category</th><th>Skills</th></tr>
    <tr><td>Network Security</td><td>TCP/IP, DNS, VLAN, VPN, Firewalls</td></tr>
    <tr><td>Penetration Testing</td><td>Reconnaissance, Exploitation, Malware</td></tr>
    <tr><td>System Administration</td><td>Linux & Windows Server Hardening</td></tr>
    <tr><td>Development</td><td>Python, Java, JavaScript, TypeScript</td></tr>
    <tr><td>AI & ML</td><td>Deep Learning, CNN, Scikit-learn, TensorFlow</td></tr>
  </table>
</section>

<section>
  <h2>Projects Repository</h2>
  <div class="projects about">
    <a href="https://github.com/Abdelhakim-Hani/XSS-Detection">XSS Detection System</a>
    <a href="https://github.com/Abdelhakim-Hani/C2-Architecture">C2 Architecture Simulation</a>
    <a href="https://github.com/Abdelhakim-Hani/Detection-Lab">Detection Lab (SOC & SIEM)</a>
    <a href="https://github.com/Abdelhakim-Hani/Commercial-Management-App">Commercial Management App</a>
  </div>
</section>

<section class="stats">
  <img src="https://github-readme-stats.vercel.app/api?username=Abdelhakim-Hani&show_icons=true&theme=radical"/>
  <br><br>
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=Abdelhakim-Hani&theme=radical"/>
</section>

<footer>
  <p>"Cybersecurity is not just protection — it’s precision."</p>
  <p>Morocco · Open to internships & junior cybersecurity roles</p>
</footer>

</body>
</html>
