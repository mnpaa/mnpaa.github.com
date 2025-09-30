<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Amit Kumar | Portfolio</title>
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/css/bootstrap.min.css" rel="stylesheet">
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
    }
    a {
      color: #58a6ff;
      text-decoration: none;
    }
    a:hover {
      text-decoration: underline;
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
    I am a passionate software engineer with over <strong>11 years</strong> of experience in the telecom and financial services sectors. 
    I thrive at designing and building scalable, resilient systems using modern architectures. 
    My core strengths lie in <strong>backend development</strong>, <strong>cloud-native microservices</strong>, and <strong>DevOps practices</strong>.
  </p>
</section>

<section id="skills" class="container">
  <h2>Technical Skills</h2>
  <div>
    <span class="skill-badge">Java</span>
    <span class="skill-badge">Spring Boot</span>
    <span class="skill-badge">Spring Cloud</span>
    <span class="skill-badge">Angular</span>
    <span class="skill-badge">React</span>
    <span class="skill-badge">Kafka</span>
    <span class="skill-badge">RabbitMQ</span>
    <span class="skill-badge">MySQL</span>
    <span class="skill-badge">PostgreSQL</span>
    <span class="skill-badge">Elasticsearch</span>
    <span class="skill-badge">Docker</span>
    <span class="skill-badge">Kubernetes</span>
    <span class="skill-badge">Jenkins</span>
    <span class="skill-badge">Prometheus</span>
    <span class="skill-badge">Grafana</span>
  </div>
</section>

<section id="projects" class="container">
  <h2>Projects</h2>
  <div class="mb-4">
    <h4>E-Commerce Microservices</h4>
    <p>A modular microservices-based e-commerce platform with product, order & payment services.</p>
    <p><strong>Tech:</strong> Java, Spring Boot, Docker, Kubernetes</p>
    <a href="#">View on GitHub</a>
  </div>
  <div class="mb-4">
    <h4>UI5 Analytics Dashboard</h4>
    <p>An analytics dashboard built with SAP UI5 and REST APIs.</p>
    <p><strong>Tech:</strong> UI5, Java, PostgreSQL</p>
    <a href="#">View on GitHub</a>
  </div>
  <div class="mb-4">
    <h4>DevOps Pipeline</h4>
    <p>Jenkins CI/CD pipeline for automated builds and deployments of Dockerized microservices.</p>
    <p><strong>Tech:</strong> Jenkins, Docker, Spring Boot</p>
    <a href="#">View on GitHub</a>
  </div>
</section>

<section id="experience" class="container">
  <h2>Work Experience</h2>
  <h5>Deloitte India — Technical Architect / Senior Developer</h5>
  <p><em>June 2019 – Present</em></p>
  <ul>
    <li>Designed and implemented microservices architectures for financial clients.</li>
    <li>Integrated messaging with Kafka/RabbitMQ for event-driven systems.</li>
    <li>Configured monitoring and alerting with Prometheus & Grafana.</li>
  </ul>
  <h5>HCL — Senior Developer</h5>
  <p><em>Aug 2018 – June 2019</em></p>
  <ul>
    <li>Developed REST APIs and integrated backend services for telecom clients.</li>
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
</section>

<footer>
  <p>© 2025 Amit Kumar</p>
</footer>

</body>
</html>