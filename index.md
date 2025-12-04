<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Amit Kumar — Full‑Stack Java & Microservices</title>
  <meta name="description" content="Amit Kumar — Full‑Stack Java & Microservices Developer. Cloud native, microservices, Kafka, Kubernetes, CI/CD." />
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600;700&display=swap" rel="stylesheet">
  <style>
    :root{
      --bg:#ffffff;
      --text:#0b1220;
      --muted:#556170;
      --accent:#0b84ff;
      --card:#f6f8fa;
      --glass: rgba(11,18,32,0.04);
      --max-width:900px;
      font-size:16px;
    }
    *{box-sizing:border-box}
    html,body{height:100%;margin:0}
    body{
      font-family:Inter,system-ui,-apple-system,"Segoe UI",Roboto,"Helvetica Neue",Arial;
      background:var(--bg);
      color:var(--text);
      -webkit-font-smoothing:antialiased;
      -moz-osx-font-smoothing:grayscale;
      line-height:1.55;
      padding:40px 20px;
      display:flex;
      justify-content:center;
    }
    .wrap{max-width:var(--max-width);width:100%}

    header{display:flex;align-items:center;justify-content:space-between;margin-bottom:36px}
    .hero{padding:28px 28px 24px;border-radius:12px;background:linear-gradient(180deg,rgba(11,132,255,0.06),transparent);}
    .name{margin:0;font-weight:700;font-size:1.6rem;letter-spacing:-0.02em}
    .role{margin:6px 0 0;color:var(--muted);font-weight:500}

    .actions{display:flex;gap:10px;align-items:center}
    .btn{border:1px solid transparent;padding:8px 12px;border-radius:8px;font-weight:600;font-size:0.95rem;text-decoration:none;display:inline-flex;gap:8px;align-items:center}
    .btn-primary{background:var(--accent);color:white}
    .btn-ghost{background:transparent;color:var(--accent);border:1px solid rgba(11,132,255,0.12)}

    main{display:grid;grid-template-columns:1fr 340px;gap:28px;align-items:start}

    section.card{background:var(--card);padding:20px;border-radius:10px}
    .muted{color:var(--muted);font-size:0.95rem}

    /* About */
    #about p{margin:0 0 12px}

    /* Skills */
    .skills{display:flex;flex-wrap:wrap;gap:8px;margin-top:8px}
    .chip{background:var(--glass);padding:6px 10px;border-radius:999px;font-weight:600;color:var(--text);font-size:0.88rem}

    /* Projects */
    .projects{display:flex;flex-direction:column;gap:12px}
    .proj{padding:14px;border-radius:8px;background:white;border:1px solid rgba(11,18,32,0.04)}
    .proj h4{margin:0 0 6px;font-size:1.03rem}
    .proj p{margin:0 0 8px;color:var(--muted);font-size:0.95rem}
    .proj .meta{display:flex;gap:8px;flex-wrap:wrap}
    .tag{font-size:0.82rem;padding:6px 8px;border-radius:6px;background:var(--glass);color:var(--text);}
    .proj .links{margin-top:10px;display:flex;gap:8px}
    .small{font-size:0.92rem;color:var(--muted)}

    /* Experience */
    .role-item{margin-bottom:14px}
    .role-item h5{margin:0;font-size:1rem}
    .role-item .period{color:var(--muted);font-size:0.9rem;margin-bottom:6px}
    .role-item ul{margin:6px 0 0;padding-left:18px;color:var(--muted)}

    /* Right column */
    aside{position:sticky;top:24px}
    .card-slim{padding:14px;border-radius:10px;background:#ffffff;border:1px solid rgba(11,18,32,0.04)}
    .contact a{display:block;color:var(--text);text-decoration:none;margin-bottom:8px}

    footer{margin-top:28px;text-align:center;color:var(--muted);font-size:0.92rem}

    /* Responsive */
    @media (max-width:980px){main{grid-template-columns:1fr;}
      aside{position:relative;top:auto}
    }
  </style>
</head>
<body>
  <div class="wrap">
    <header>
      <div class="hero" style="flex:1">
        <h1 class="name">Amit Kumar</h1>
        <div class="role">Full‑Stack Java & Microservices Developer — Pune, India</div>
      </div>
      <div class="actions" style="margin-left:18px">
        <a class="btn btn-primary" href="#contact">Contact</a>
        <a class="btn btn-ghost" href="resume.pdf" download>Download Resume</a>
      </div>
    </header>

    <main>
      <div>
        <section id="about" class="card">
          <h2 style="margin-top:0">About</h2>
          <p class="small">I am a <strong>Full‑Stack Java & Microservices Developer with 11+ years</strong> of experience building cloud‑native, resilient systems for Financial Services and Telecom. I design distributed architectures, implement scalable backend services, and optimise delivery pipelines to meet strict reliability and performance SLAs.</p>
          <p class="small">I enjoy solving complex systems problems, mentoring teams, and shipping production‑grade software with observability, security, and automation built in.</p>
        </section>

        <section id="projects" class="card" style="margin-top:16px">
          <h2 style="margin-top:0">Selected Projects</h2>
          <div class="projects">
            <article class="proj" id="ecommerce">
              <h4>E‑Commerce Microservices Platform</h4>
              <p>Cloud‑ready microservices ecosystem for catalog, orders, payments, and inventory. Focused on reliability, performance, and operational excellence.</p>
              <div class="meta">
                <span class="tag">Java</span>
                <span class="tag">Spring Boot</span>
                <span class="tag">Kafka</span>
                <span class="tag">Kubernetes</span>
                <span class="tag">PostgreSQL</span>
              </div>
              <div class="links">
                <a class="small" href="#">View Repo</a>
                <a class="small" href="#">Live Demo</a>
              </div>
              <ul style="margin-top:10px;color:var(--muted)">
                <li>Designed event‑driven communication using Kafka to decouple services and improve throughput.</li>
                <li>Implemented resilience patterns (circuit breakers, retries, fallbacks) and reduced downtime by <strong>30%</strong>.</li>
                <li>Deployed on Kubernetes with autoscaling and centralized observability (Prometheus, Grafana, ELK).</li>
              </ul>
            </article>

            <article class="proj" id="ui5">
              <h4>SAP UI5 Analytics Dashboard</h4>
              <p>Interactive enterprise dashboard showing KPIs and live operational metrics with filtering and role‑based views.</p>
              <div class="meta">
                <span class="tag">SAP UI5</span>
                <span class="tag">Java</span>
                <span class="tag">OData</span>
                <span class="tag">PostgreSQL</span>
              </div>
              <div class="links">
                <a class="small" href="#">View Repo</a>
                <a class="small" href="#">Screenshot</a>
              </div>
              <ul style="margin-top:10px;color:var(--muted)">
                <li>Optimized APIs and DB queries to improve response times by <strong>40%</strong>.</li>
                <li>Delivered dynamic charts and filters for faster operational insights.</li>
              </ul>
            </article>

            <article class="proj" id="devops">
              <h4>CI/CD Pipeline & DevOps Automation</h4>
              <p>Automated multi‑stage CI/CD pipelines for microservices including build, test, quality scans and secure deployments.</p>
              <div class="meta">
                <span class="tag">Jenkins</span>
                <span class="tag">GitHub Actions</span>
                <span class="tag">Docker</span>
                <span class="tag">Kubernetes</span>
              </div>
              <div class="links">
                <a class="small" href="#">Pipeline Scripts</a>
              </div>
              <ul style="margin-top:10px;color:var(--muted)">
                <li>Automated build/test/deploy, improved release velocity and reduced human errors by <strong>40%</strong>.</li>
                <li>Integrated SonarQube and vulnerability scanning to maintain code quality and security.</li>
              </ul>
            </article>

          </div>
        </section>

        <section id="experience" class="card" style="margin-top:16px">
          <h2 style="margin-top:0">Experience</h2>

          <div class="role-item">
            <h5>Deloitte India — Technical Architect / Senior Developer</h5>
            <div class="period">June 2019 – Present</div>
            <ul>
              <li>Designed and delivered scalable microservices for financial clients; led migration from monoliths to Spring Cloud & Kubernetes.</li>
              <li>Implemented observability (Prometheus, Grafana, ELK) and reduced MTTR by <strong>40%</strong>.</li>
              <li>Led architecture reviews and mentored engineering teams.</li>
            </ul>
          </div>

          <div class="role-item">
            <h5>HCL — Senior Developer</h5>
            <div class="period">Aug 2018 – June 2019</div>
            <ul>
              <li>Built REST APIs and middleware for telecom clients; optimized DB queries and improved latency by <strong>25%</strong>.</li>
            </ul>
          </div>

          <div class="role-item">
            <h5>Infosys — Software Engineer</h5>
            <div class="period">Sep 2017 – Aug 2018</div>
            <ul>
              <li>Developed backend logic and supported production releases with zero downtime.</li>
            </ul>
          </div>

          <div class="role-item">
            <h5>IBM — Developer</h5>
            <div class="period">Dec 2014 – Aug 2017</div>
            <ul>
              <li>Maintained enterprise backend systems and delivered integration components for large clients.</li>
            </ul>
          </div>

        </section>

      </div>

      <aside>
        <section class="card-slim contact" style="margin-bottom:12px">
          <h3 style="margin:0 0 8px">Contact</h3>
          <a href="mailto:mnpaa1991@gmail.com">mnpaa1991@gmail.com</a>
          <a href="https://linkedin.com/in/your-link" target="_blank">linkedin.com/in/your-link</a>
          <a href="https://github.com/mnpaa" target="_blank">github.com/mnpaa</a>
          <div style="margin-top:8px" class="small">Open to: Backend / Microservices / Cloud native roles • Contract & Full‑time</div>
        </section>

        <section class="card-slim" style="margin-bottom:12px">
          <h4 style="margin:0 0 8px">Skills</h4>
          <div class="skills">
            <span class="chip">Java</span>
            <span class="chip">Spring Boot</span>
            <span class="chip">Microservices</span>
            <span class="chip">Kafka</span>
            <span class="chip">Kubernetes</span>
            <span class="chip">Docker</span>
            <span class="chip">Jenkins</span>
            <span class="chip">React</span>
          </div>
        </section>

        <section class="card-slim">
          <h4 style="margin:0 0 8px">Quick Links</h4>
          <a href="#projects">Selected Projects</a>
          <a href="resume.pdf" download>Download Resume</a>
          <a href="#contact">Contact</a>
        </section>
      </aside>
    </main>

    <footer>
      © 2025 Amit Kumar — Designed for clarity & impact
    </footer>
  </div>
</body>
</html>
