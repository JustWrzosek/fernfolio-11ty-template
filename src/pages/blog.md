---
layout: blog.njk
title: ARTICLES
metaDescription: A sample Blog page listing various posts.
date: 2017-01-01
permalink: blog{% if pagination.pageNumber > 0 %}/page/{{ pagination.pageNumber
  }}{% endif %}/index.html
subtitle: A collection of technical blog posts and random thoughts
eleventyNavigation:
  key: Blog
  order: 2
pagination:
  data: collections.post
  size: 20
---
<style>
.article-landing {
  max-width: 680px;
  margin: 0 auto 32px auto;
  background: #fff;
  border-radius: 15px;
  padding: 30px 22px 24px 22px;
  font-family: 'Segoe UI', 'Roboto', Arial, sans-serif;
  font-size: 12px;
  color: #232b33;
}
.article-landing-banner {
  background: linear-gradient(90deg, #30cfd0 0%, #4f8cff 100%);
  color: #fff;
  padding: 18px 0 12px 0;
  border-radius: 15px 15px 0 0;
  text-align: center;
}
.article-landing-banner h2 {
  font-size: 1.5em;
  margin: 0 0 0.12em 0;
  font-family: 'Montserrat', 'Segoe UI', Arial, sans-serif;
  font-weight: 700;
  letter-spacing: .5px;
}
.article-landing-intro {
  font-size: 1.03em;
  color: #24527a;
  margin: 22px 0 0 0;
  text-align: center;
  font-family: 'Segoe UI', 'Roboto', Arial, sans-serif;
}
.quote-block {
  background: #f1f8fd;
  margin: 26px 0 18px 0;
  border-left: 4px solid #30cfd0;
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
.table-min {
  width: 96%;
  margin: 18px auto 0 auto;
  border-collapse: collapse;
  font-size: 12px;
  background: #f9fbff;
  border-radius: 7px;
  overflow: hidden;
}
.table-min th, .table-min td {
  padding: 8px 14px;
  text-align: left;
}
.table-min th {
  background: #eaf5fa;
  color: #217ab8;
  font-weight: 600;
}
.table-min td {
  color: #324155;
  background: #f9fbff;
}
@media (max-width: 600px) {
  .article-landing { padding: 8px 2vw 8px 2vw; }
  .article-landing-banner { padding: 10px 0 6px 0; }
  .table-min th, .table-min td { padding: 6px 6px; }
  .quote-block { padding: 8px 8px 6px 12px; font-size: 0.97em;}
}
</style>

<div class="article-landing">
  <div class="article-landing-banner">
    <h2>Articles & Insights</h2>
  </div>
  <div class="article-landing-intro">
    Welcome to our creative journal—a space for ideas, tips, and inspiration on design, branding, and freelancing. Here, less is more and every insight is made to spark something new.
  </div>
  <div class="quote-block">
    “Creativity is intelligence having fun.” <span style="font-size:11px;opacity:.88;">– Albert Einstein</span>
  </div>
  <table class="table-min">
    <tr>
      <th style="width:38%;">What You'll Find</th>
      <th>Why Read?</th>
    </tr>
    <tr>
      <td>Quick design tips</td>
      <td>Easy wins for your next project</td>
    </tr>
    <tr>
      <td>Branding advice</td>
      <td>Practical ways to stand out</td>
    </tr>
    <tr>
      <td>Freelance insights</td>
      <td>Smarter, happier workflows</td>
    </tr>
  </table>
</div>