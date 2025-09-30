<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Amit Kumar | Portfolio</title>
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/css/bootstrap.min.css" rel="stylesheet">
  <link href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.10.5/font/bootstrap-icons.css" rel="stylesheet">
  <style>
    body {
      font-family: "Segoe UI", sans-serif;
      line-height: 1.6;
      background: #0d1117;
      color: #c9d1d9;
    }

    header {
      background: #161b22;
      padding: 80px 20px;
      text-align: center;
    }
    header h1 {
      font-size: 2.5rem;
      margin-bottom: 10px;
      color: #fff;
    }
    header p {
      font-size: 1.2rem;
      opacity: 0.8;
    }
    header a.btn {
      margin: 8px;
      transition: transform 0.3s;
    }
    header a.btn:hover {
      transform: scale(1.05);
    }

    section {
      padding: 60px 20px;
    }

    h2 {
      margin-bottom: 30px;
      color: #58a6ff;
    }

    .skill-badge {
      background: #21262d;
      border-radius: 20px;
      padding: 6px 12px;
      margin: 4px;
      display: inline-block;
      color: #c9d1d9;
      transition: background 0.3s;
    }
    .skill-badge:hover {
      background: #58a6ff;
      color: #0d1117;
    }

    .project-card {
      background: #161b22;
      padding: 20px;
      border-radius: 10px;
      margin-bottom: 20px;
      transition: transform 0.3s, box-shadow 0.3s, background 0.3s;
      cursor: pointer;
    }
    .project-card:hover {
      transform: translateY(-5px);
      box-shadow: 0 10px 20px rgba(0,0,0,0.5);
      background: #21262d;
    }

    .project-card a.btn {
      margin-right: 10px;
      transition: background 0.3s, transform 0.3s;
    }
    .project-card a.btn:hover {
      background: #58a6ff;
      color: #0d1117;
      transform: scale(1.05);
    }

    a {
      color: #58a6ff;
      text-decoration: none;
      transition: color 0.3s;
    }
    a:hover {
      text-decoration: underline;
      color: #1f6feb;
    }

    footer {
      background: #161b22;
      color: #8b949e;
      padding: 20px;
      text-align: center;
    }

    ul li {
      margin-bottom: 6px;
    }
  </style>
</head>
<body>

<header>
  <h1>Amit Kumar</h1>
  <p>Full-Stack Java / Microservices Developer | Pune, India</p>
  <a href="#projects" class="btn btn-primary">Projects</a>
  <a href="#contact" class="btn btn-outline-light">Contact</a>
</header>

<section id="about" class="container">
  <h2>About Me</h2>
  <p>
    I am a passionate software engineer with over <strong>11 years</strong> of experience in telecom and financial services. 
    I design and build scalable microservices, resilient backend systems, and cloud-native applications. 
    I enjoy solving complex problems and mentoring teams to deliver production-ready solutions.
  </p>
</section>

<section id="skills" class="container">
  <h2>Technical Skills</h2>
  <div class="mb-3">
    <strong>Backend:</strong> 
    <span class="skill-badge">Java</span>
    <span class="skill-badge">Spring Boot</span>
    <span class="skill-badge">Spring Cloud</span>
  </div>
  <div class="mb-3">
    <strong>Frontend:</strong>
    <span class="skill-badge">Angular</span>
    <span class="skill-badge">React</span>
    <span class="skill-badge">UI5</span>
  </div>
  <div class="mb-3">
    <strong>Messaging & Data:</strong>
    <span class="skill-badge">Kafka</span>
    <span class="skill-badge">RabbitMQ</span>
    <span class="skill-badge">MySQL</span>
    <span class="skill-badge">PostgreSQL</span>
    <span class="skill-badge">Elasticsearch</span>
  </div>
  <div class="mb-3">
    <strong>DevOps & Cloud:</strong>
    <span class="skill-badge">Docker</span>
    <span class="skill-badge">Kubernetes</span>
    <span class="skill-badge">Jenkins</span>
    <span class="skill-badge">Prometheus</span>
    <span class="skill-badge">Grafana</span>
  </div>
</section>

<section id="projects" class="container">
  <h2>Projects</h2>

  <div class="project-card">
    <h4>E-Commerce Microservices</h4>
    <p>A modular microservices-based e-commerce platform handling product catalog, orders, and payments.</p>
    <p><strong>Tech:</strong> Java, Spring Boot, Docker, Kubernetes</p>
    <ul>
      <li>Implemented event-driven architecture using Kafka for inter-service communication.</li>
      <li>Reduced system downtime by 30% through resilient service design.</li>
    </ul>
    <a href="#" class="btn btn-outline-light btn-sm"><i class="bi bi-github"></i> GitHub</a>
    <a href="#" class="btn btn-outline-light btn-sm"><i class="bi bi-box-arrow-up-right"></i> Demo</a>
  </div>

  <div class="project-card">
    <h4>UI5 Analytics Dashboard</h4>
    <p>Interactive analytics dashboard built with SAP UI5 and REST APIs for enterprise metrics.</p>
    <p><strong>Tech:</strong> UI5, Java, PostgreSQL</p>
    <ul>
      <li>Optimized backend endpoints for faster data retrieval.</li>
      <li>Visualized real-time metrics with charts and filters.</li>
    </ul>
    <a href="#" class="btn btn-outline-light btn-sm"><i class="bi bi-github"></i> GitHub</a>
    <a href="#" class="btn btn-outline-light btn-sm"><i class="bi bi-box-arrow-up-right"></i> Demo</a>
  </div>

  <div class="project-card">
    <h4>DevOps Pipeline</h4>
    <p>CI/CD pipeline automating builds and deployments of Dockerized microservices.</p>
    <p><strong>Tech:</strong> Jenkins, Docker, Spring Boot</p>
    <ul>
      <li>Implemented automated testing and deployment with GitHub Actions.</li>
      <li>Reduced deployment errors by 40% and accelerated release cycles.</li>
    </ul>
    <a href="#" class="btn btn-outline-light btn-sm"><i class="bi bi-github"></i> GitHub</a>
  </div>
</section>

<section id="experience" class="container">
  <h2>Work Experience</h2>

  <h5>Deloitte India — Technical Architect / Senior Developer</h5>
  <p><em>June 2019 – Present</em></p>
  <ul>
    <li>Designed and implemented scalable microservices architectures for financial clients.</li>
    <li>Integrated messaging with Kafka/RabbitMQ for event-driven systems.</li>
    <li>Configured monitoring & alerting with Prometheus & Grafana, improving MTTR by 40%.</li>
    <li>Led cross-team code reviews and mentoring for junior developers.</li>
  </ul>

  <h5>HCL — Senior Developer</h5>
  <p><em>Aug 2018 – June 2019</em></p>
  <ul>
    <li>Developed REST APIs and integrated backend services for telecom clients.</li>
    <li>Optimized database queries reducing latency by 25%.</li>
  </ul>

  <h5>Infosys — Software Engineer</h5>
  <p><em>Sep 2017 – Aug 2018</em></p>
  <ul>
    <li>Implemented authentication, data validation, and business logic in backend modules.</li>
  </ul>

  <h5>IBM — Developer</h5>
  <p><em>Dec 2014 – Aug 2017</em></p>
  <ul>
    <li>Developed and maintained backend systems for enterprise clients.</li>
  </ul>
</section>

<section id="contact" class="container">
  <h2>Contact</h2>
  <p>📧 <a href="mailto:mnpaa1991@gmail.com">mnpaa1991@gmail.com</a></p>
  <p>💼 <a href="https://linkedin.com/in/your-link" target="_blank">LinkedIn</a></p>
  <p>🐙 <a href="https://github.com/mnpaa" target="_blank">GitHub</a></p>
  <a href="resume.pdf" class="btn btn-primary mt-2" download><i class="bi bi-download"></i> Download Resume</a>
</section>

<footer>
  <p>© 2025 Amit Kumar — Built with GitHub Pages</p>
</footer>

</body>
</html>