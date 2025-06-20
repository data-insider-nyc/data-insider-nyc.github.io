---
layout: default
title: Data Insider
---

<style>
body {
  font-family: 'Inter', 'Segoe UI', Arial, sans-serif;
  background: linear-gradient(120deg, #f8fafc 0%, #e0e7ef 100%);
  color: #222;
  margin: 0;
  padding: 0;
}
.main-hero {
  max-width: 700px;
  margin: 60px auto 32px auto;
  padding: 32px 24px;
  background: #fff;
  border-radius: 18px;
  box-shadow: 0 4px 32px rgba(0,0,0,0.07);
  text-align: center;
}
.main-hero h1 {
  font-size: 2.7rem;
  font-weight: 800;
  margin-bottom: 0.5em;
  background: linear-gradient(90deg, #3b82f6 30%, #06b6d4 100%);
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
}
.main-hero p {
  font-size: 1.25rem;
  margin-bottom: 1.5em;
}
.cta-btn {
  display: inline-block;
  background: linear-gradient(90deg, #3b82f6 30%, #06b6d4 100%);
  color: #fff;
  font-weight: 600;
  padding: 0.85em 2.2em;
  border-radius: 999px;
  text-decoration: none;
  font-size: 1.1rem;
  transition: box-shadow 0.2s;
  box-shadow: 0 2px 8px rgba(59,130,246,0.08);
}
.cta-btn:hover {
  box-shadow: 0 4px 16px rgba(6,182,212,0.15);
}
.projects {
  display: flex;
  flex-wrap: wrap;
  gap: 24px;
  justify-content: center;
  margin: 40px auto 0 auto;
  max-width: 900px;
}
.project-card {
  background: #f1f5f9;
  border-radius: 14px;
  padding: 24px 20px;
  min-width: 240px;
  max-width: 300px;
  flex: 1 1 240px;
  box-shadow: 0 2px 12px rgba(0,0,0,0.04);
  text-align: left;
}
.project-card h3 {
  margin-top: 0;
  font-size: 1.2rem;
  margin-bottom: 0.5em;
}
.project-card p {
  font-size: 1rem;
  margin-bottom: 0.7em;
}
.project-card a {
  color: #3b82f6;
  text-decoration: none;
  font-weight: 500;
}
@media (max-width: 700px) {
  .main-hero { margin: 24px 4px; padding: 18px 6px; }
  .projects { flex-direction: column; gap: 16px; }
}
</style>

<div class="main-hero">
  <h1>Data Insider</h1>
  <p>AI-driven open-source tools for visualizing public data.<br>
  <span style="font-size:1.1em; color:#06b6d4;">Empowering everyone to see the story in the data.</span></p>
  <a class="cta-btn" href="https://github.com/data-insider-nyc?tab=repositories" target="_blank">🚀 Explore Our Projects</a>
</div>

<div class="projects">
  <div class="project-card">
    <h3>📊 <a href="https://github.com/data-insider-nyc/layoffstracker" target="_blank">LayoffsTracker</a></h3>
    <p>Real-time dashboard visualizing tech industry layoffs by company, date, and sector. Insightful charts and timelines powered by open data.</p>
  </div>
  <div class="project-card">
    <h3>🧠 <a href="https://github.com/data-insider-nyc/di" target="_blank">DI</a></h3>
    <p>Core data-insider library for AI-driven data analysis and visualization. Modular, extensible, and open-source.</p>
  </div>
  <div class="project-card">
    <h3>🔗 <a href="https://github.com/data-insider-nyc/GoJS" target="_blank">GoJS</a></h3>
    <p>Interactive JavaScript diagramming for flowcharts, org charts, and more. Forked and extended for public data use cases.</p>
  </div>
  <div class="project-card">
    <h3>📈 <a href="https://github.com/data-insider-nyc/funnycharts" target="_blank">funnycharts</a></h3>
    <p>Creative, playful charting library for unique data stories. Make your data fun and engaging!</p>
  </div>
</div>

<div style="text-align:center; margin:48px 0 24px 0; color:#64748b; font-size:1em;">
  <a href="https://www.linkedin.com/company/datainsidernyc" target="_blank" style="color:#06b6d4; text-decoration:none;">LinkedIn</a> &nbsp;|&nbsp; <a href="https://github.com/data-insider-nyc" target="_blank" style="color:#06b6d4; text-decoration:none;">GitHub</a>
  <br>
  <span style="font-size:0.95em;">&copy; 2025 Data Insider NYC</span>
</div>
