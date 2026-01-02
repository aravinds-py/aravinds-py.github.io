<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width,initial-scale=1.0">
  <title>Aravind | Data Analyst Portfolio</title>
  <meta name="description" content="Portfolio of Aravind, Data Analyst">
  <link href="https://fonts.googleapis.com/css?family=Roboto:400,700&display=swap" rel="stylesheet">
  <style>
    body {
      font-family: 'Roboto', Arial, sans-serif;
      background: #f8f9fa;
      color: #222;
      margin: 0;
      padding: 0;
    }
    header {
      background: #373a40;
      color: #fff;
      padding: 2rem 0 1.2rem 0;
      text-align: center;
    }
    header h1 {
      margin: 0;
      font-size: 2.3rem;
      letter-spacing: 2px;
    }
    header p {
      margin-top: 0.5rem;
      font-size: 1.1rem;
      color: #fafafa;
    }
    section {
      max-width: 750px;
      margin: 1.5rem auto 2rem auto;
      background: #fff;
      border-radius: 8px;
      box-shadow: 0 2px 10px rgba(44,62,80,0.08);
      padding: 2rem;
    }
    h2 {
      color: #373a40;
      margin-top: 0;
      font-size: 1.35rem;
      border-bottom: 1px solid #eee;
      padding-bottom: 0.3rem;
      letter-spacing: 1px;
    }
    ul.skills {
      list-style-type: none;
      padding: 0;
      margin: 0 0 0.5rem 0;
      display: flex;
      flex-wrap: wrap;
      gap: 10px;
    }
    ul.skills li {
      background: #eef;
      padding: 6px 13px;
      border-radius: 6px;
      font-size: 0.98rem;
    }
    .projects {
      margin-top: 1rem;
    }
    .project-card {
      background: #f2f3f6;
      border-radius: 6px;
      padding: 1rem;
      margin-bottom: 1.1rem;
      box-shadow: 0 1px 5px rgba(44,62,80,0.04);
    }
    .project-card h3 {
      margin: 0 0 0.4rem 0;
      font-size: 1.07rem;
      color: #235a9b;
    }
    .project-tech {
      font-size: 0.92rem;
      color: #555;
      margin-bottom: 0.3rem;
    }
    .project-desc {
      margin: 0;
      font-size: 0.99rem;
    }
    .contact {
      background: #eaf5ee;
      padding: 1.3rem 1rem;
      border-radius: 7px;
      margin-top: 1.7rem;
      text-align: center;
      font-size: 1.04rem;
    }
    .contact a {
      color: #235a9b;
      text-decoration: none;
      font-weight: bold;
      margin: 0 8px;
    }
    footer {
      text-align: center;
      padding: 1.2rem 0;
      font-size: 1rem;
      background: #e0e2e7;
      border-top: 1px solid #d4d5d8;
      color: #444;
    }
    @media (max-width: 800px) {
      section {
        margin: 1rem 9px;
        padding: 1.1rem;
      }
    }
  </style>
</head>
<body>
  <header>
    <h1>Aravind</h1>
    <p>Data Analyst · Portfolio &dash; <a href="https://aravindviz.me" target="_blank" style="color:#fafafa;text-decoration:underline;">aravindviz.me</a></p>
  </header>
  <section>
    <h2>About Me</h2>
    <p>
      I am a data analyst passionate about extracting meaning from data, uncovering actionable insights, and driving informed decisions. I work with Python, R, SQL, and modern visualization tools. My expertise is in communicating complex findings in clear, impactful ways.
    </p>

    <h2>Skills</h2>
    <ul class="skills">
      <li>Python</li>
      <li>R</li>
      <li>SQL</li>
      <li>Pandas</li>
      <li>NumPy</li>
      <li>Tableau</li>
      <li>Power BI</li>
      <li>Plotly</li>
      <li>scikit-learn</li>
      <li>Data Visualization</li>
      <li>Machine Learning</li>
      <li>Statistics</li>
      <li>Business Reporting</li>
    </ul>

    <h2>Projects</h2>
    <div class="projects">
      <div class="project-card">
        <h3>Sales Trends Dashboard</h3>
        <div class="project-tech">Python · Pandas · Plotly</div>
        <p class="project-desc">
          Developed an interactive dashboard to visualize and analyze sales data, enabling stakeholders to uncover seasonality and product trends.
        </p>
      </div>
      <div class="project-card">
        <h3>Customer Segmentation</h3>
        <div class="project-tech">Python · scikit-learn · Clustering</div>
        <p class="project-desc">
          Implemented clustering algorithms to segment customers for targeted marketing strategies and improved engagement.
        </p>
      </div>
      <div class="project-card">
        <h3>Web Analytics</h3>
        <div class="project-tech">SQL · Tableau</div>
        <p class="project-desc">
          Built visualizations and analytics dashboards to interpret website traffic patterns and user behaviors.
        </p>
      </div>
      <div class="project-card">
        <h3>Forecast Modeling</h3>
        <div class="project-tech">R · Prophet</div>
        <p class="project-desc">
          Developed time series models to forecast key business metrics, improving planning and resource allocation.
        </p>
      </div>
      <!-- Add more projects as you like -->
    </div>

    <div class="contact">
      <strong>Let's connect!</strong><br>
      <a href="mailto:your.email@example.com">Email</a>
      <a href="https://linkedin.com/in/your-linkedin" target="_blank">LinkedIn</a>
      <a href="https://aravindviz.me" target="_blank">Website</a>
      <!-- Optionally add a link to download CV -->
      <!-- <a href="cv.pdf" target="_blank">Download CV</a> -->
    </div>
  </section>
  <footer>
    &copy; 2026 Aravind &middot; <a href="https://aravindviz.me" target="_blank">aravindviz.me</a>
  </footer>
</body>
</html>
