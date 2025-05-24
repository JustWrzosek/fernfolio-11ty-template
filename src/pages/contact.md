---
section: contact
layout: contact.njk
title: GET IN TOUCH
metaDescription: This is a sample meta description. If one is not present in
  your page/post's front matter, the default metadata.desciption will be used
  instead.
date: 2018-01-01
permalink: /contact/index.html
subtitle: Contact Subtitle
eleventyNavigation:
  key: Contact
  order: 4
---
<style>
.contact-landing {
  max-width: 680px;
  margin: 0 auto 32px auto;
  background: #fff;
  border-radius: 15px;
  padding: 30px 22px 24px 22px;
  font-family: 'Segoe UI', 'Roboto', Arial, sans-serif;
  font-size: 12px;
  color: #232b33;
}
.contact-landing-banner {
  background: linear-gradient(90deg, #30cfd0 0%, #4f8cff 100%);
  color: #fff;
  padding: 18px 0 12px 0;
  border-radius: 15px 15px 0 0;
  text-align: center;
}
.contact-landing-banner h2 {
  font-size: 1.5em;
  margin: 0 0 0.12em 0;
  font-family: 'Montserrat', 'Segoe UI', Arial, sans-serif;
  font-weight: 700;
  letter-spacing: .5px;
}
.contact-landing-intro {
  font-size: 1.03em;
  color: #24527a;
  margin: 22px 0 0 0;
  text-align: center;
  font-family: 'Segoe UI', 'Roboto', Arial, sans-serif;
}
.contact-table-min {
  width: 92%;
  margin: 22px auto 0 auto;
  border-collapse: collapse;
  font-size: 12px;
  background: #f9fbff;
  border-radius: 7px;
  overflow: hidden;
}
.contact-table-min th, .contact-table-min td {
  padding: 8px 14px;
  text-align: left;
}
.contact-table-min th {
  background: #eaf5fa;
  color: #217ab8;
  font-weight: 600;
  width: 36%;
}
.contact-table-min td {
  color: #324155;
  background: #f9fbff;
}
.contact-quote-block {
  background: #f1f8fd;
  margin: 26px 0 16px 0;
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
@media (max-width: 600px) {
  .contact-landing { padding: 8px 2vw 8px 2vw; }
  .contact-landing-banner { padding: 10px 0 6px 0; }
  .contact-table-min th, .contact-table-min td { padding: 6px 6px; }
  .contact-quote-block { padding: 8px 8px 6px 12px; font-size: 0.97em;}
}
</style>

<div class="contact-landing">
  <div class="contact-landing-banner">
    <h2>Contact & Connect</h2>
  </div>
  <div class="contact-landing-intro">
    Whether you have a project in mind, a question to ask, or just want to say hello, we’d love to hear from you.<br>
    Reach out and let’s make something great together.
  </div>
  <div class="contact-quote-block">
    “The beginning of every great collaboration starts with a simple hello.”
  </div>
  <table class="contact-table-min">
    <tr>
      <th>Email</th>
      <td><a href="mailto:raketsuki@gmail.com">raketsuki@gmail.com</a></td>
    </tr>
    <tr>
      <th>Facebook</th>
      <td><a href="https://facebook.com/raketsuki" target="_blank">@raketsuki</a></td>
    </tr>
    <tr>
      <th>Phone</th>
      <td><a href="tel:+639942716090">+63 994 271 6090</a></td>
    </tr>
  </table>
</div>