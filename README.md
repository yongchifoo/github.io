<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Yongchi Foo – Portfolio</title>
  <link href="https://fonts.googleapis.com/css?family=Montserrat:700,400&display=swap" rel="stylesheet">
  <style>
    body {
      font-family: 'Montserrat', Arial, sans-serif;
      margin: 0;
      background: #f5f7fa;
      color: #222;
    }
    header {
      background: #1a1a2e;
      color: #fff;
      padding: 2rem 0 1rem 0;
      text-align: center;
    }
    header h1 {
      margin: 0;
      font-size: 2.5rem;
      letter-spacing: 2px;
    }
    header p {
      margin-top: 0.5rem;
      font-weight: 400;
      color: #aaa;
    }
    .container {
      max-width: 800px;
      margin: 2rem auto;
      background: #fff;
      border-radius: 12px;
      padding: 2rem;
      box-shadow: 0 4px 16px rgba(34,34,34,0.08);
    }
    section {
      margin-bottom: 2rem;
    }
    h2 {
      color: #16213e;
      margin-top: 0;
    }
    .projects {
      display: flex;
      flex-wrap: wrap;
      gap: 1.5rem;
    }
    .project-card {
      background: #f1f1f1;
      border-radius: 8px;
      padding: 1.2rem;
      flex: 1 1 250px;
      min-width: 220px;
      box-shadow: 0 2px 8px rgba(34,34,34,0.04);
      transition: transform 0.2s;
    }
    .project-card:hover {
      transform: translateY(-4px) scale(1.02);
    }
    .project-title {
      font-size: 1.1rem;
      font-weight: bold;
      color: #1a1a2e;
      margin-bottom: 0.4rem;
    }
    .project-desc {
      font-size: 0.96rem;
      color: #333;
    }
    .contact-list {
      list-style: none;
      padding: 0;
      margin: 0.6rem 0 0 0;
    }
    .contact-list li {
      margin-bottom: 0.5rem;
      font-size: 1rem;
    }
    .contact-list a {
      color: #0f3460;
      text-decoration: none;
      transition: color 0.2s;
    }
    .contact-list a:hover {
      color: #533483;
    }
    @media (max-width: 600px) {
      .container {
        padding: 1rem;
      }
      .projects {
        flex-direction: column;
      }
    }
  </style>
</head>
<body>
  <header>
    <h1>Yongchi Foo</h1>
    <p>Software Developer | Web Enthusiast | Open Source Contributor</p>
  </header>
  <div class="container">
    <section>
      <h2>About Me</h2>
      <p>
        Hi! I'm Yongchi Foo, a passionate developer with experience in web development, open-source projects, and building beautiful digital experiences. I love learning new technologies and collaborating with others to solve challenging problems.
      </p>
    </section>
    <section>
      <h2>Projects</h2>
      <div class="projects">
        <div class="project-card">
          <div class="project-title">Personal Portfolio</div>
          <div class="project-desc">The very site you're viewing! Built with HTML, CSS, and hosted on GitHub Pages.</div>
        </div>
        <div class="project-card">
          <div class="project-title">Open Source Contributor</div>
          <div class="project-desc">Regular contributor to various open-source projects on GitHub, focusing on web tools and automation.</div>
        </div>
        <div class="project-card">
          <div class="project-title">Custom Project Name</div>
          <div class="project-desc">Short description of your project. <br> <em>Tip: Add your favorite projects here!</em></div>
        </div>
      </div>
    </section>
    <section>
      <h2>Contact</h2>
      <ul class="contact-list">
        <li>Email: <a href="mailto:your.email@example.com">yongchi_foo@yahoo.com</a></li>
        <li>GitHub: <a href="https://github.com/yongchifoo" target="_blank">github.com/yongchifoo</a></li>
        <li>LinkedIn: <a href="https://linkedin.com/in/YOUR-LINKEDIN" target="_blank">linkedin.com/in/yong-chi-foo</a></li>
      </ul>
    </section>
  </div>
</body>
</html>
