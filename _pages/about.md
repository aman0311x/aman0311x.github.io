---
permalink: /
title: "Introduction"
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

<style>
:root {
  --accent: #1a6fa8;
  --accent-soft: rgba(26, 111, 168, 0.08);
  --green: #1e9e55;
  --line: #e6e6e6;
}

body {
  font-family: Georgia, "Times New Roman", Times, serif;
  font-size: 16px;
  line-height: 1.6;
  color: #000;
}

.ab-wrap { font-size: 1.02rem; }

.ab-card {
  background: #fff;
  border: 1px solid var(--line);
  border-radius: 14px;
  padding: 20px 24px;
  margin-bottom: 22px;
  box-shadow: 0 4px 14px rgba(0,0,0,0.05);
}

.ab-heading {
  font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Helvetica, Arial, sans-serif;
  font-size: 1.12rem;
  font-weight: 700;
  color: #222;
  margin: 0 0 12px 0;
  padding-bottom: 6px;
  border-bottom: 2px solid var(--accent-soft);
}

/* ---------- Intro ---------- */
.ab-intro { text-align: justify; line-height: 1.75; }

/* ---------- Collaboration banner (animated) ---------- */
.collab {
  display: flex;
  align-items: center;
  gap: 14px;
  flex-wrap: wrap;
  padding: 14px 20px;
  margin-bottom: 22px;
  border-radius: 14px;
  border: 1px solid rgba(30,158,85,0.45);
  background: linear-gradient(120deg, rgba(30,158,85,0.10), rgba(26,111,168,0.10), rgba(30,158,85,0.10));
  background-size: 200% 200%;
  animation: collabShift 6s ease infinite, collabGlow 2.2s ease-in-out infinite;
}
.collab-dot {
  width: 12px; height: 12px;
  border-radius: 50%;
  background: var(--green);
  flex: 0 0 auto;
  animation: collabPulse 1.6s ease-out infinite;
}
.collab-text {
  font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Helvetica, Arial, sans-serif;
  font-weight: 700;
  font-size: 1.02rem;
  color: #145c34;
}
.collab-mail {
  margin-left: auto;
  font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Helvetica, Arial, sans-serif;
  font-weight: 600;
  font-size: 0.95rem;
  color: #fff !important;
  background: linear-gradient(135deg, #1e9e55, #1a6fa8);
  padding: 8px 16px;
  border-radius: 999px;
  text-decoration: none !important;
  transition: transform .2s ease, box-shadow .2s ease;
}
.collab-mail:hover { transform: scale(1.05); box-shadow: 0 6px 16px rgba(0,0,0,0.22); }

@keyframes collabShift {
  0%   { background-position: 0% 50%; }
  50%  { background-position: 100% 50%; }
  100% { background-position: 0% 50%; }
}
@keyframes collabGlow {
  0%, 100% { box-shadow: 0 0 0 rgba(30,158,85,0.0); }
  50%      { box-shadow: 0 0 18px rgba(30,158,85,0.45); }
}
@keyframes collabPulse {
  0%   { box-shadow: 0 0 0 0 rgba(30,158,85,0.7); }
  70%  { box-shadow: 0 0 0 10px rgba(30,158,85,0); }
  100% { box-shadow: 0 0 0 0 rgba(30,158,85,0); }
}

/* ---------- Keywords ---------- */
.kw-list { display: flex; flex-wrap: wrap; gap: 8px; }
.kw {
  font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Helvetica, Arial, sans-serif;
  font-size: 0.85rem;
  padding: 4px 12px;
  border-radius: 999px;
  background: var(--accent-soft);
  color: var(--accent);
  border: 1px solid rgba(26,111,168,0.25);
}

/* ---------- Two columns ---------- */
.ab-two {
  display: grid;
  grid-template-columns: 1fr 1fr;
  gap: 22px;
  margin-bottom: 22px;
}
.ab-two .ab-card { margin-bottom: 0; }

.ab-item { margin-bottom: 12px; font-size: 0.97rem; line-height: 1.5; }
.ab-item:last-child { margin-bottom: 0; }
.ab-item b { color: #000; }
.ab-org { color: var(--accent); font-weight: 600; }
.ab-year { float: right; font-style: italic; color: #555; font-size: 0.9rem; margin-left: 10px; }

/* ---------- News ---------- */
.news-list { list-style: none; margin: 0; padding: 0; }
.news-list li {
  display: flex;
  gap: 16px;
  padding: 10px 0;
  border-bottom: 1px dashed var(--line);
  font-size: 0.98rem;
  line-height: 1.55;
}
.news-list li:last-child { border-bottom: none; }
.news-date {
  flex: 0 0 120px;
  color: #e74c3c;
  font-weight: bold;
  font-size: 0.93rem;
}
.news-paper, .news-paper:link, .news-paper:visited, .news-paper:hover {
  color: var(--accent);
  text-decoration: none !important;
}
.news-paper:hover { text-decoration: underline !important; }
.news-venue { color: var(--accent); font-style: italic; }

/* ---------- Publications ---------- */
.pub-group {
  font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Helvetica, Arial, sans-serif;
  font-weight: 700;
  color: #444;
  margin: 18px 0 8px 0;
  font-size: 0.98rem;
}
.pub-group:first-of-type { margin-top: 0; }
.pub-list { margin: 0; padding-left: 20px; }
.pub-list li { margin-bottom: 14px; line-height: 1.55; text-align: justify; }
.paper-title { color: #8b0000; }
.paper-venue { color: #008000; font-style: italic; }
.paper-venue-review { color: #d35400; font-style: italic; }
.pdf-link { color: #337ab7; font-weight: bold; text-decoration: none; }
.pdf-link:hover { text-decoration: underline; }

@media (max-width: 760px) {
  .ab-two { grid-template-columns: 1fr; }
  .news-list li { flex-direction: column; gap: 2px; }
  .news-date { flex: none; }
  .collab-mail { margin-left: 0; }
}
</style>

<div class="ab-wrap">

<!-- ================= INTRO ================= -->
<div class="ab-card ab-intro">
I hold a B.Sc. in Computer Science and Engineering from <b>Ahsanullah University of Science and Technology (AUST)</b>, Bangladesh. My research focuses on <b>medical image analysis</b> and <b>trustworthy AI for healthcare</b>, including explainable, uncertainty-aware, federated, and continual learning for ultrasound and other clinical imaging. I aim to build models that are not only accurate but also transparent, calibrated, and ready for real clinical use.
</div>

<!-- ================= COLLABORATION ================= -->
<div class="collab">
  <span class="collab-dot"></span>
  <span class="collab-text">🤝 I am always open to collaboration!</span>
  <a class="collab-mail" href="mailto:amanourrahman609@gmail.com">✉ amanourrahman609@gmail.com</a>
</div>

<!-- ================= RESEARCH INTERESTS ================= -->
<div class="ab-card">
  <div class="ab-heading">Research Interests</div>
  <div class="kw-list">
    <span class="kw">Medical Image Analysis</span>
    <span class="kw">Explainable AI (XAI)</span>
    <span class="kw">Ultrasound Segmentation</span>
    <span class="kw">Uncertainty Quantification</span>
    <span class="kw">Conformal Prediction</span>
    <span class="kw">Federated Learning</span>
    <span class="kw">Continual Learning</span>
    <span class="kw">Domain Shift &amp; Generalization</span>
    <span class="kw">Green Learning</span>
    <span class="kw">Radiomics</span>
    <span class="kw">State Space Models (Mamba)</span>
    <span class="kw">Trustworthy AI</span>
  </div>
</div>

<!-- ================= SERVICES (LEFT) + AWARDS (RIGHT) ================= -->
<div class="ab-two">

  <div class="ab-card">
    <div class="ab-heading">Academic Service</div>

    <div class="ab-item">
      <b>Journal Reviewer</b><br>
      <span class="ab-org">PLOS ONE</span><br>
      <span class="ab-org">Intelligence-Based Medicine (Elsevier)</span><br>
      <span class="ab-org">NED University Journal of Research</span>
    </div>

    <div class="ab-item">
      <b>Workshop Reviewer</b><br>
      <span class="ab-org">NeurIPS MedReasoner Workshop</span><br>
      <span class="ab-org">MICCAI 2026 Workshop on Efficient Medical AI (EMA)</span>
    </div>

    <div class="ab-item">
      <b>Open-Source Contributor</b><br>
      <span class="ab-org">Project MONAI (NVIDIA)</span> — fixed PerceptualLoss docs (Issue #8592)
    </div>

    <div class="ab-item">
      <b>Author &amp; Maintainer</b><br>
      <span class="ab-org"><a href="https://pypi.org/project/medxai/" target="_blank">MedXAI</a></span> — open-source medical imaging toolkit
    </div>

    <div class="ab-item" style="margin-top:14px;">
      <a href="/services/" class="pdf-link">More details →</a>
    </div>
  </div>

  <div class="ab-card">
    <div class="ab-heading">Honors &amp; Awards</div>

    <div class="ab-item">
      <span class="ab-year">2026</span>
      <b>EMA 2026 Best Reviewer Award</b><br>
      <span class="ab-org">MICCAI 2026 Workshop on Efficient Medical AI</span>
    </div>

    <!-- Add more awards here, e.g.:
    <div class="ab-item">
      <span class="ab-year">20XX</span>
      <b>Award name</b><br>
      <span class="ab-org">Organization</span>
    </div>
    -->
  </div>

</div>

<!-- ================= NEWS ================= -->
<div class="ab-card">
  <div class="ab-heading">News</div>
  <ul class="news-list">

    <li>
      <span class="news-date">[October 2026]</span>
      <span><strong>FedXAI: Federated Medical Imaging with Intrinsic Explainability and Differentially Private Explanation Auditing</strong> was accepted at <span class="news-venue">Machine Learning (Springer)</span>, Special Issue on Advances in Federated Learning for Critical Applications!</span>
    </li>

    <li>
      <span class="news-date">[October 2026]</span>
      <span><strong>FA-SSNet: A Frequency-Aware Semi-Supervised Network for Thyroid Nodule Segmentation in Ultrasound Images</strong> was accepted at <span class="news-venue">IET Image Processing</span>!</span>
    </li>

    <li>
      <span class="news-date">[September 2026]</span>
      <span>Selected for the <strong>EMA 2026 Best Reviewer Award</strong> at the <span class="news-venue">MICCAI 2026 Workshop on Efficient Medical AI (EMA 2026)</span> for outstanding contributions to the peer-review process!</span>
    </li>

    <li>
      <span class="news-date">[August 2026]</span>
      <span><a href="https://doi.org/10.48550/arXiv.2608.01518" class="news-paper">UCBound-Net: Uncertainty-Guided Boundary-Aware Continual Learning for Domain-Incremental Ultrasound Segmentation</a> was accepted at <span class="news-venue">MICCAI 2026 CLiMeM Workshop</span>!</span>
    </li>

    <li>
      <span class="news-date">[July 2026]</span>
      <span><a href="https://doi.org/10.1049/ipr2.70445" class="news-paper">TCB-Net: Topology-Constrained Boundary-Interior Decoupled Network for Breast Ultrasound Lesion Segmentation</a> got published in <span class="news-venue">IET Image Processing</span>!</span>
    </li>

    <li>
      <span class="news-date">[July 2026]</span>
      <span><a href="https://doi.org/10.1016/j.array.2026.101058" class="news-paper">Spectral-Spatial Mamba with Uncertainty-Guided Refinement for Thyroid Nodule Diagnosis</a> got published in <span class="news-venue">Array (Elsevier)</span>!</span>
    </li>

    <li>
      <span class="news-date">[June 2026]</span>
      <span><a href="https://doi.org/10.1016/j.ibmed.2026.100413" class="news-paper">HyFormer-Net for Breast Lesion Analysis</a> got published in <span class="news-venue">Intelligence-Based Medicine (Elsevier)</span>!</span>
    </li>

    <li>
      <span class="news-date">[June 2026]</span>
      <span><a href="https://doi.org/10.48550/arXiv.2607.02209" class="news-paper">MedSaab-US: A Backpropagation-Free Multi-Scale Wavelet-Saab Framework for Thyroid Nodule Segmentation in Ultrasound Images</a> was accepted at <span class="news-venue">IEEE ICIP 2026 Satellite Workshop</span>!</span>
    </li>

    <li>
      <span class="news-date">[June 2026]</span>
      <span><a href="https://doi.org/10.48550/arXiv.2607.02185" class="news-paper">RadiomicNet: A Hybrid Radiomics-Guided Lightweight Architecture for Interpretable Medical Image Segmentation</a> was accepted at <span class="news-venue">IEEE ICIP 2026 Satellite Workshop</span>!</span>
    </li>

    <li>
      <span class="news-date">[February 2026]</span>
      <span>Abstract accepted for a book chapter in <span class="news-venue">AI for Medical Imaging and Precision Diagnostics: From Theory to Practice</span> (<span class="news-venue">Routledge, Taylor &amp; Francis Group</span>)!</span>
    </li>

  </ul>
</div>

<!-- ================= PUBLICATIONS ================= -->
<div class="ab-card">
  <div class="ab-heading">Publications</div>

  <div class="pub-group">Journal Articles</div>
  <ol class="pub-list" reversed>
    <li>
      <span class="paper-title">FedXAI: Federated Medical Imaging with Intrinsic Explainability and Differentially Private Explanation Auditing.</span>
      <b>Mohammad Amanour Rahman</b>.
      <span class="paper-venue">[Machine Learning, Springer, Special Issue on Advances in Federated Learning for Critical Applications, 2026]</span>
    </li>
    <li>
      <span class="paper-title">FA-SSNet: A Frequency-Aware Semi-Supervised Network for Thyroid Nodule Segmentation in Ultrasound Images.</span>
      Rowzatul Zannath Prerona, <b>Mohammad Amanour Rahman</b>.
      <span class="paper-venue">[IET Image Processing, 2026]</span>
    </li>
    <li>
      <span class="paper-title">TCB-Net: Topology-Constrained Boundary-Interior Decoupled Network for Breast Ultrasound Lesion Segmentation.</span>
      <b>Mohammad Amanour Rahman</b>.
      <span class="paper-venue">[IET Image Processing, 2026]</span>
      <a href="https://doi.org/10.1049/ipr2.70445" class="pdf-link">[Link]</a>
    </li>
    <li>
      <span class="paper-title">Spectral-Spatial Mamba with Uncertainty-Guided Refinement for Thyroid Nodule Diagnosis.</span>
      <b>Mohammad Amanour Rahman</b>, Rowzatul Zannath Prerona.
      <span class="paper-venue">[Array, Elsevier, 2026]</span>
      <a href="https://doi.org/10.1016/j.array.2026.101058" class="pdf-link">[Link]</a>
    </li>
    <li>
      <span class="paper-title">HyFormer-Net: A Synergistic CNN-Transformer with Interpretable Multi-Scale Fusion for Breast Lesion Segmentation and Classification in Ultrasound Images.</span>
      <b>Mohammad Amanour Rahman</b>.
      <span class="paper-venue">[Intelligence-Based Medicine, Elsevier, 2026]</span>
      <a href="https://doi.org/10.1016/j.ibmed.2026.100413" class="pdf-link">[Link]</a>
    </li>
  </ol>

  <div class="pub-group">Conference &amp; Workshop Papers</div>
  <ol class="pub-list" reversed>
    <li>
      <span class="paper-title">UCBound-Net: Uncertainty-Guided Boundary-Aware Continual Learning for Domain-Incremental Ultrasound Segmentation.</span>
      <b>Mohammad Amanour Rahman</b>.
      <span class="paper-venue">[MICCAI 2026 CLiMeM Workshop]</span>
      <a href="https://doi.org/10.48550/arXiv.2608.01518" class="pdf-link">[arXiv]</a>
    </li>
    <li>
      <span class="paper-title">MedSaab-US: A Backpropagation-Free Multi-Scale Wavelet-Saab Framework for Thyroid Nodule Segmentation in Ultrasound Images.</span>
      <b>Mohammad Amanour Rahman</b>.
      <span class="paper-venue">[IEEE ICIP 2026 LBDL II Workshop]</span>
      <a href="https://doi.org/10.48550/arXiv.2607.02209" class="pdf-link">[arXiv]</a>
    </li>
    <li>
      <span class="paper-title">RadiomicNet: A Hybrid Radiomics-Guided Lightweight Architecture for Interpretable Medical Image Segmentation.</span>
      <b>Mohammad Amanour Rahman</b>.
      <span class="paper-venue">[IEEE ICIP 2026 LBDL II Workshop]</span>
      <a href="https://doi.org/10.48550/arXiv.2607.02185" class="pdf-link">[arXiv]</a>
    </li>
  </ol>

  <div class="pub-group">Book Chapter</div>
  <ol class="pub-list">
    <li>
      <span class="paper-title">Book chapter (abstract accepted).</span>
      <b>Mohammad Amanour Rahman</b>.
      <span class="paper-venue">[AI for Medical Imaging and Precision Diagnostics: From Theory to Practice, Routledge, Taylor &amp; Francis Group, 2026]</span>
    </li>
  </ol>

</div>

</div>