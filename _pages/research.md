---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

<style>
  .research-body {
    font-family: Georgia, "Times New Roman", Times, serif;
    font-size: 16px;
    line-height: 1.6;
    text-align: justify;
    color: #000;
  }
  .section-heading {
    font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Helvetica, Arial, sans-serif;
    color: #444;
    font-size: 1.3em;
    margin-top: 40px;
    margin-bottom: 15px;
    font-weight: bold;
  }
  .related-paper-heading {
    font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Helvetica, Arial, sans-serif;
    color: #444;
    font-weight: bold;
    margin-top: 25px;
    display: block;
  }
  .paper-title {
    color: #8b0000; /* Dark Red / Maroon */
  }
  .paper-venue {
    color: #008000; /* Green */
    font-style: italic;
  }
  .pdf-link {
    color: #337ab7; /* Blue */
    text-decoration: none;
    font-weight: bold;
  }
  .pdf-link:hover {
    text-decoration: underline;
  }
  .paper-list {
    margin-top: 10px;
    padding-left: 20px;
  }
  .paper-list li {
    margin-bottom: 10px;
  }
</style>

<div class="research-body">

My research focuses on the intersection of artificial intelligence and healthcare, particularly in Medical Image Analysis and Explainable AI (XAI). I work on developing reliable and transparent deep learning models that can support real-world clinical decision-making.
I am also interested in building trustworthy and secure medical AI systems, ensuring that these technologies are robust, safe, and suitable for practical healthcare use. The key areas I have explored or am currently working on are listed below.

<div class="section-heading">1. Medical Image Analysis & Explainable AI (XAI)</div>

Medical Image Analysis involves leveraging artificial intelligence to interpret complex clinical scans such as ultrasounds, MRIs, and CTs. The core objectives in this domain include detection, segmentation, and classification. A significant hurdle in this field is dataset variability; models often suffer from "domain shift" when applied to new, unseen datasets.
Furthermore, clinical adoption of AI is strictly bottlenecked by the "black box" nature of deep learning. Explainable AI (XAI) addresses this by providing transparent reasoning behind AI predictions. XAI techniques range from post-hoc visualizers (like Grad-CAM) to intrinsic methods (like attention maps built directly into the model's architecture). My research integrates these paradigms to build highly accurate, robust, and trustworthy diagnostic systems.
In this context, we developed a hybrid framework that simultaneously handles segmentation and classification while utilizing a dual-pipeline XAI approach to quantitatively validate the model's internal reasoning against clinical ground truth.

<span class="related-paper-heading">Related Paper:</span>

<ul class="paper-list">
  <li>
    <span class="paper-title">HyFormer-Net: A Synergistic CNN-Transformer with Interpretable Multi-Scale Fusion for Breast Lesion Segmentation and Classification in Ultrasound Images.</span> 
    Mohammad Amanour Rahman. 
    <span class="paper-venue">arXiv preprint arXiv:2511.01013 (2025).</span> 
    <a href="https://arxiv.org/abs/2511.01013" class="pdf-link">[PDF]</a>
  </li>
</ul>

</div>