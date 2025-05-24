---
emoji: 💻
layout: projects.njk
title: PROJECTS
subtitle: ""
metaDescription: A sample Projects page
date: 2021-01-01
permalink: /projects/index.html
eleventyNavigation:
  key: Projects
  order: 3
---
<style>
.project-landing {
  max-width: 680px;
  margin: 0 auto 32px auto;
  background: #fff;
  border-radius: 15px;
  padding: 30px 22px 24px 22px;
  font-family: 'Segoe UI', 'Roboto', Arial, sans-serif;
  font-size: 12px;
  color: #232b33;
}
.project-landing-banner {
  background: linear-gradient(90deg, #4f8cff 0%, #30cfd0 100%);
  color: #fff;
  padding: 18px 0 12px 0;
  border-radius: 15px 15px 0 0;
  text-align: center;
}
.project-landing-banner h2 {
  font-size: 1.5em;
  margin: 0 0 0.12em 0;
  font-family: 'Montserrat', 'Segoe UI', Arial, sans-serif;
  font-weight: 700;
  letter-spacing: .5px;
}
.project-landing-intro {
  font-size: 1.03em;
  color: #24527a;
  margin: 22px 0 0 0;
  text-align: center;
  font-family: 'Segoe UI', 'Roboto', Arial, sans-serif;
}
.project-table-min {
  width: 96%;
  margin: 20px auto 0 auto;
  border-collapse: collapse;
  font-size: 12px;
  background: #f9fbff;
  border-radius: 7px;
  overflow: hidden;
}
.project-table-min th, .project-table-min td {
  padding: 8px 14px;
  text-align: left;
}
.project-table-min th {
  background: #eaf5fa;
  color: #217ab8;
  font-weight: 600;
}
.project-table-min td {
  color: #324155;
  background: #f9fbff;
}
.project-quote-block {
  background: #f1f8fd;
  margin: 26px 0 16px 0;
  border-left: 4px solid #4f8cff;
  padding: 12px 16px 8px 16px;
  font-style: italic;
  color: #287bc8;
  font-size: 1.02em;
  border-radius: 7px;
  text-align: left;
  max-width: 92%;
  margin-left: auto;
  margin-right: auto;
}
@media (max-width: 600px) {
  .project-landing { padding: 8px 2vw 8px 2vw; }
  .project-landing-banner { padding: 10px 0 6px 0; }
  .project-table-min th, .project-table-min td { padding: 6px 6px; }
  .project-quote-block { padding: 8px 8px 6px 12px; font-size: 0.97em;}
}
</style>

<div class="project-landing">
  <div class="project-landing-banner">
    <h2>Project Catalog</h2>
  </div>
  <div class="project-landing-intro">
    Explore a curated showcase of our favorite projects—from bold brand launches to smart digital solutions. Each project is designed with intent and brought to life with care, creativity, and that signature Raketsuki touch.
  </div>
  <div class="project-quote-block">
    “Great projects are not just built, they’re crafted.” <span style="font-size:11px;opacity:.88;">– Raketsuki Studio</span>
  </div>
  <table class="project-table-min">
    <tr>
      <th style="width:38%;">Project Types</th>
      <th>What to Expect</th>
    </tr>
    <tr>
      <td>Branding & Visual Identity</td>
      <td>Distinctive designs that make brands memorable</td>
    </tr>
    <tr>
      <td>Digital Graphics</td>
      <td>Modern visuals for web and social media</td>
    </tr>
    <tr>
      <td>Custom Solutions</td>
      <td>Tailored freelance support to fit any need</td>
    </tr>
  </table>
</div>