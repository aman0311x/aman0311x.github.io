---
permalink: /
title: "Introduction"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<style>

/* ---------------- GLOBAL 3D + GLASS STYLE ---------------- */
:root {
  --card-bg: rgba(255, 255, 255, 0.12);
  --card-border: rgba(255, 255, 255, 0.18);
  --glass-blur: blur(14px);
  --radius: 18px;
}
body {
    font-family: Georgia, "Times New Roman", Times, serif;
    font-size: 16px;
    line-height: 1.6;
    text-align: justify;
    color: #000;
}

/* Paragraph styling for elegance */
body p {
  line-height: 1.7;
  font-size: 1.05rem;
}


/* ---------------- CARD CONTAINER ---------------- */
.cards {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(260px, 1fr));
  gap: 25px;
  margin-top: 25px;
}


/* ---------------- GLASS 3D NEWS CARDS ---------------- */
.card {
  background: var(--card-bg);
  border: 1px solid var(--card-border);
  padding: 22px;
  border-radius: var(--radius);
  backdrop-filter: var(--glass-blur);
  box-shadow: 0 10px 25px rgba(0,0,0,0.22);
  transition: transform .25s ease, box-shadow .25s ease;
}

.card:hover {
  transform: translateY(-10px) scale(1.03);
  box-shadow: 0 18px 40px rgba(0,0,0,0.35);
}


/* ---------------- BUTTON STYLE ---------------- */
.button {
  display: inline-block;
  margin-top: 12px;
  padding: 10px 16px;
  background: linear-gradient(135deg, #333436ff, #6e54ff);
  color: white !important;
  border-radius: 10px;
  font-weight: 600;
  text-decoration: none;
  transition: 0.25s ease;
}

.button:hover {
  transform: scale(1.05);
  box-shadow: 0 6px 18px rgba(0,0,0,0.25);
}


/* ---------------- HEADER TITLE ---------------- */
h2, h3 {
  font-weight: 700;
}

</style>





<div style="border-left: 4px solid #545458ff;text-align: justify ; padding: 18px 22px; margin-top: 15px; line-height: 1.7; font-size: 1.05rem; background: rgba(255,255,255,0.08); border-radius: 10px;">
I began my journey with a deep passion for computer science, which led me to pursue a Bachelor's degree in Computer Science and Engineering at AUST in 2022. From the very beginning of my academic career, I immersed myself in <a href="https://www.stopstalk.com/user/profile/aman0311" target="_blank">competitive programming</a>, sharpening my problem-solving skills and building a solid foundation in algorithms and data structures.<br><br>
Alongside my academic studies, I actively worked on various <a href="https://github.com/aman0311x" target="_blank">projects</a>, experimenting with different programming languages and frameworks. This hands-on experience allowed me to gain practical knowledge in web development and software engineering.<br><br>
However, as I delved deeper into the world of technology, I became increasingly fascinated by the field of Computer Vision, Image Processing, and Explainable AI. Driven by this passion, I decided to shift my focus towards AI research and development.<br><br>
Currently, I am in my final year, specializing in Image Processing for my thesis. I am exploring advanced techniques and working on innovative solutions to push the boundaries of AI in visual recognition and analysis.
</div>

<div style="height: 2cm;"></div>


<style>
  .news-body {
    /*font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Helvetica, Arial, sans-serif;*/
    font-family: Georgia, "Times New Roman", Times, serif;
    font-size: 18px;
    line-height: 1.75;
    color: #000;
  }
  .news-body ul {
    list-style: disc;
    padding-left: 25px;
    margin-top: 10px;
  }
  .news-body ul li {
    margin-bottom: 10px;
  }
  .news-date {
    color: #e74c3c;
    font-weight: bold;
  }

.news-paper,
.news-paper:link,
.news-paper:visited,
.news-paper:hover,
.news-paper:active,
.news-paper:focus {
    color: #1a6fa8;
    text-decoration: none !important;
}

.news-venue {
    color: #1a6fa8;
    font-style: italic;
}


</style>

<div class="news-body">
  <ul>
    <li>
      <span class="news-date">[June 2026]</span>
      <a href="https://doi.org/10.1016/j.ibmed.2026.100413" class="news-paper">HyFormer-Net for Breast Lesion Analysis</a>
      got published in <span class="news-venue">Intelligence-Based Medicine (Elsevier)</span>!
    </li>
    <li>
      <span class="news-date">[February 2026]</span>
      Abstract accepted for a book chapter in
      <span class="news-venue">AI for Medical Imaging and Precision Diagnostics: From Theory to Practice</span>
      (<span class="news-venue">Routledge, Taylor &amp; Francis Group</span>)!
    </li>
    <li>
      <span class="news-date">[February 2026]</span>
      Successfully contributed to the open-source medical imaging framework
      <span class="news-venue">MONAI (Medical Open Network for AI)</span>!
    </li>
  </ul>
</div>