---
layout: archive
title: "Education"
permalink: /education/
author_profile: true
redirect_from:
  - /education
---

{% include base_path %}

<h2>Education</h2>

<style>
  .edu-card {
    background: #ffffff10;
    backdrop-filter: blur(12px);
    border-radius: 16px;
    padding: 20px;
    margin-bottom: 20px;
    box-shadow: 0 8px 20px rgba(0,0,0,0.25);
    border: 1px solid rgba(255,255,255,0.15);
    transition: transform 0.25s ease, box-shadow 0.25s ease;
    font-family: "Times New Roman", Times, serif;
  }
  body {
   font-family: Georgia, "Times New Roman", Times, serif;
    font-size: 16px;
    line-height: 1.6;
    text-align: justify;
    color: #000;
}

  .edu-card:hover {
    transform: translateY(-6px) scale(1.02);
    box-shadow: 0 16px 35px rgba(0,0,0,0.35);
  }
</style>

<div class="edu-card">
  <h3>Ahsanullah University of Science and Technology</h3>
  <p>
    Bachelor of Science (B.Sc.) in Computer Science and Engineering<br>
    Duration: 2022 – 2026<br>
    CGPA: N/A / 4.00<br>
    [Certificate]
  </p>
</div>

<div class="edu-card">
  <h3>Brahmanbaria Government High School</h3>
  <p>
    Higher Secondary Certificate (HSC)<br>
    Duration: 2019 – 2021<br>
    GPA: 5.00 / 5.00<br>
    [Certificate]
  </p>
</div>

<div class="edu-card">
  <h3>Annada Government High School</h3>
  <p>
    Secondary School Certificate (SSC)<br>
    Duration: 2013 – 2018<br>
    GPA: 5.00 / 5.00
  </p>
</div>

{% for post in site.portfolio %}
  {% include archive-single.html %}
{% endfor %}