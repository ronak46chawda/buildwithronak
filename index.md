---
layout: default
title: Ronak Chawda | Data Analytics Portfolio
---

<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Space+Grotesk:wght@400;500;700&family=Manrope:wght@400;600;700&display=swap" rel="stylesheet">

<style>
  :root {
    --ink: #0d1b2a;
    --slate: #243b53;
    --mist: #eef4ff;
    --accent: #ff7a59;
    --accent-dark: #e65f3f;
    --teal: #2a9d8f;
    --card: #ffffff;
  }

  body {
    font-family: "Manrope", sans-serif;
    background:
      radial-gradient(circle at 10% 10%, #d5ecff 0%, transparent 45%),
      radial-gradient(circle at 80% 15%, #ffe9d8 0%, transparent 35%),
      linear-gradient(180deg, #f8fbff 0%, #edf4ff 100%);
    color: var(--ink);
  }

  .markdown-body {
    max-width: 1080px;
    margin: 0 auto;
    padding: 1.25rem;
    font-family: "Manrope", sans-serif;
    background: transparent;
    box-shadow: none;
  }

  .hero {
    background: linear-gradient(135deg, #0f2740 0%, #1e3a5f 65%, #2a567f 100%);
    border-radius: 24px;
    color: #f7fbff;
    padding: 2rem 1.5rem;
    position: relative;
    overflow: hidden;
  }

  .hero::after {
    content: "";
    position: absolute;
    width: 260px;
    height: 260px;
    border-radius: 50%;
    background: rgba(255, 122, 89, 0.2);
    top: -110px;
    right: -80px;
  }

  .hero h1, .hero h2, .hero h3 {
    font-family: "Space Grotesk", sans-serif;
    color: #ffffff;
    border: 0;
    margin: 0;
    padding: 0;
  }

  .hero h1 {
    font-size: clamp(2rem, 4.8vw, 3.4rem);
    line-height: 1.05;
  }

  .hero p {
    font-size: 1.05rem;
    max-width: 720px;
    color: #dbeafe;
  }

  .cta {
    display: inline-block;
    margin-top: 0.75rem;
    background: var(--accent);
    color: #fff;
    text-decoration: none;
    font-weight: 700;
    border-radius: 999px;
    padding: 0.65rem 1rem;
  }

  .cta:hover { background: var(--accent-dark); }

  .section-title {
    font-family: "Space Grotesk", sans-serif;
    font-size: 1.6rem;
    margin-top: 2rem;
    margin-bottom: 0.75rem;
    color: var(--slate);
    border: 0;
  }

  .grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(240px, 1fr));
    gap: 1rem;
  }

  .card {
    background: var(--card);
    border: 1px solid #d9e4f2;
    border-radius: 16px;
    padding: 1rem;
    box-shadow: 0 8px 24px rgba(15, 39, 64, 0.06);
  }

  .card h3 {
    margin-top: 0;
    margin-bottom: 0.4rem;
    font-family: "Space Grotesk", sans-serif;
    color: var(--ink);
  }

  .chip {
    display: inline-block;
    background: #e9f7f5;
    color: #1f6f66;
    padding: 0.28rem 0.55rem;
    border-radius: 999px;
    font-size: 0.82rem;
    font-weight: 700;
    margin-bottom: 0.6rem;
  }

  .project-links a {
    margin-right: 0.8rem;
    font-weight: 700;
    color: #1e4f7f;
    text-decoration: none;
  }

  .project-links a:hover { text-decoration: underline; }

  .shot {
    width: 100%;
    border-radius: 12px;
    border: 1px solid #e4edf7;
    background: #f8fbff;
  }

  .timeline {
    border-left: 3px solid #bdd4ef;
    padding-left: 0.9rem;
    margin-left: 0.2rem;
  }

  .timeline p {
    margin: 0 0 0.9rem 0;
  }

  .fade-up {
    opacity: 0;
    transform: translateY(14px);
    animation: reveal 0.7s ease forwards;
  }

  .fade-up.delay-1 { animation-delay: 0.12s; }
  .fade-up.delay-2 { animation-delay: 0.24s; }
  .fade-up.delay-3 { animation-delay: 0.36s; }

  @keyframes reveal {
    to {
      opacity: 1;
      transform: translateY(0);
    }
  }
</style>

<section class="hero fade-up">
  <h1>Ronak Chawda, CA</h1>
  <p>Turning raw data into decisions through clear dashboards and business-focused analytics.</p>
  <p>I solve finance and operations problems by combining domain knowledge with practical analytics, so teams move faster with confidence.</p>
  <a class="cta" href="https://www.linkedin.com/in/ronak-chawda-ca">Connect on LinkedIn</a>
</section>

<h2 class="section-title fade-up delay-1">Technical Skills</h2>
<section class="grid fade-up delay-1">
  <article class="card">
    <h3>Programming</h3>
    <span class="chip">Core Tools</span>
    <p>Python, SQL</p>
  </article>
  <article class="card">
    <h3>Visualization</h3>
    <span class="chip">Dashboarding</span>
    <p>Power BI, Tableau</p>
  </article>
  <article class="card">
    <h3>Business Analytics</h3>
    <span class="chip">Decision Support</span>
    <p>KPI design, reconciliation analytics, financial storytelling</p>
  </article>
</section>

<h2 class="section-title fade-up delay-2">Project Showcases</h2>
<section class="grid fade-up delay-2">
  <article class="card">
    <h3>Collections Performance Dashboard</h3>
    <p>Tracked recovery trends and risk signals to support faster action by collections teams.</p>
    <p class="project-links">
      <a href="#">Live Dashboard</a>
      <a href="#">Project Repository</a>
    </p>
    <img class="shot" src="images/project1.svg" alt="Collections Performance Dashboard screenshot">
  </article>
  <article class="card">
    <h3>Loan Portfolio Health and DPD Analysis</h3>
    <p>Monitored movement across DPD buckets to identify high-risk segments early.</p>
    <p class="project-links">
      <a href="#">Live Dashboard</a>
      <a href="#">Project Repository</a>
    </p>
    <img class="shot" src="images/project2.svg" alt="Loan Portfolio Health Dashboard screenshot">
  </article>
  <article class="card">
    <h3>Reconciliation Automation Insights</h3>
    <p>Highlighted mismatches and process bottlenecks to reduce manual checks.</p>
    <p class="project-links">
      <a href="#">Live Dashboard</a>
      <a href="#">Project Repository</a>
    </p>
    <img class="shot" src="images/project3.svg" alt="Reconciliation Dashboard screenshot">
  </article>
  <article class="card">
    <h3>Executive Business KPI Tracker</h3>
    <p>Built a single performance view for leadership reviews and weekly planning.</p>
    <p class="project-links">
      <a href="#">Live Dashboard</a>
      <a href="#">Project Repository</a>
    </p>
    <img class="shot" src="images/project4.svg" alt="Executive KPI Tracker screenshot">
  </article>
</section>

<h2 class="section-title fade-up delay-3">Experience and Education</h2>
<section class="card timeline fade-up delay-3">
  <p><strong>Experience:</strong> Chartered Accountant with hands-on delivery of analytics-led reporting and performance improvement initiatives.</p>
  <p><strong>Focus:</strong> Finance and operations analytics, reconciliation intelligence, and stakeholder-ready dashboards.</p>
  <p><strong>Education:</strong> Chartered Accountant (CA), The Institute of Chartered Accountants of India.</p>
</section>
