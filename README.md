<!DOCTYPE html>
<html>
<head>
  <style>
    body { 
      background: linear-gradient(45deg, #000000, #242424);
      color: white;
      font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
    }
    .container {
      max-width: 1200px;
      margin: 0 auto;
      padding: 20px;
    }
    .hero {
      text-align: center;
      margin-bottom: 40px;
    }
    .stats-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
      gap: 20px;
      margin: 40px 0;
    }
    .tech-stack {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(100px, 1fr));
      gap: 20px;
      margin: 40px 0;
      text-align: center;
    }
    .projects {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
      gap: 20px;
      margin: 40px 0;
    }
    .connect {
      text-align: center;
      margin: 40px 0;
    }
    .badge {
      padding: 8px 16px;
      border-radius: 20px;
      background: linear-gradient(45deg, #A177FE, #7530FF);
      display: inline-block;
      margin: 5px;
      transition: transform 0.3s ease;
    }
    .badge:hover {
      transform: translateY(-2px);
    }
  </style>
</head>
<body>
  <div class="container">
    <div class="hero">
      <h1>👋 Hi, I'm Sourav P</h1>
      <p>MERN Stack Developer | Tech Enthusiast</p>
      <div>
        <img src="/api/placeholder/800/200" alt="Coding Stats" />
      </div>
    </div>

    <div class="tech-stack">
      <h2>🛠️ Tech Stack</h2>
      <div class="badge">React</div>
      <div class="badge">Node.js</div>
      <div class="badge">Express</div>
      <div class="badge">MongoDB</div>
      <div class="badge">TypeScript</div>
      <div class="badge">Next.js</div>
      <div class="badge">Tailwind</div>
      <div class="badge">Redux</div>
      <div class="badge">AWS</div>
      <div class="badge">Docker</div>
    </div>

    <div class="projects">
      <h2>🚀 Featured Projects</h2>
      <div>
        <h3>Ecobazar</h3>
        <img src="/api/placeholder/400/200" alt="Ecobazar Project" />
      </div>
      <div>
        <h3>Portfolio</h3>
        <img src="/api/placeholder/400/200" alt="Portfolio Project" />
      </div>
      <div>
        <h3>Starbucks Clone</h3>
        <img src="/api/placeholder/400/200" alt="Starbucks Project" />
      </div>
      <div>
        <h3>Netflix Clone</h3>
        <img src="/api/placeholder/400/200" alt="Netflix Project" />
      </div>
    </div>

    <div class="connect">
      <h2>🤝 Let's Connect</h2>
      <a href="https://www.linkedin.com/in/sourav-p-949b622b3/" class="badge">LinkedIn</a>
      <a href="https://leetcode.com/u/Sour__av/" class="badge">LeetCode</a>
      <a href="mailto:souravappu57@gmail.com" class="badge">Email</a>
    </div>
  </div>
</body>
</html>
