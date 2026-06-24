---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

<style>
  .research-body {
    font-family: Georgia, "Times New Roman", Times, serif;
    font-size: 18px;
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
    color: #8b0000;
  }
  .paper-venue {
    color: #008000;
    font-style: italic;
  }
  .paper-venue-review {
    color: #d35400;
    font-style: italic;
  }
  .pdf-link {
    color: #337ab7;
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
    margin-bottom: 15px;
  }
</style>
<div class="research-body">
My research interests lie in AI for healthcare, particularly Medical Image Analysis and Explainable AI (XAI). I focus on developing trustworthy, transparent, and clinically relevant deep learning models for real-world healthcare applications.

<div class="section-heading">1. Medical Image Analysis & Explainable AI (XAI)</div>
Medical Image Analysis leverages artificial intelligence to interpret complex clinical scans (such as Ultrasounds, MRIs, and CTs) to automate and enhance diagnostic tasks like lesion detection, segmentation, and disease classification. This field is crucial for accelerating early diagnosis, reducing clinical workloads, and minimizing human error in healthcare.
However, the practical adoption of these AI systems is severely bottlenecked by two major challenges. First, models often suffer from "domain shift," failing to generalize across diverse datasets captured by different hospital machines. Second, traditional deep learning models operate as "black boxes," providing predictions without transparent reasoning. Explainable AI (XAI) is essential to address this trust deficit. While some visualizers exist, the field currently lacks robust, intrinsically interpretable models that can provide quantitative, clinically aligned reasoning. Without solving these lackings of generalization and transparency, AI cannot be safely deployed in real-world clinical decision-making.
<span class="related-paper-heading">Related Paper:</span>
<ul class="paper-list">
  <li>
    <span class="paper-title">HyFormer-Net: A Synergistic CNN-Transformer with Interpretable Multi-Scale Fusion for Breast Lesion Segmentation and Classification in Ultrasound Images.</span>
    Mohammad Amanour Rahman.
    <span class="paper-venue">[Intelligence-Based Medicine, Elsevier, 2026]</span>
    <a href="https://doi.org/10.1016/j.ibmed.2026.100413" class="pdf-link">[Link]</a>
  </li>
</ul>
<div class="section-heading">2. Federated Learning & Privacy-Preserving Medical AI</div>
Federated Learning (FL) is a decentralized machine learning paradigm that enables multiple healthcare institutions to collaboratively train robust AI models without ever sharing or transferring raw patient data. In the medical domain, where diagnostic data is highly sensitive and protected by strict privacy regulations (such as HIPAA), FL is paramount. It allows the creation of generalized, unbiased algorithms by learning from a diverse, multi-institutional population while keeping patient records strictly within the hospital firewalls.
Despite its immense potential, Privacy-Preserving Medical AI faces significant limitations. The inherent heterogeneity of data across different clinics makes model convergence and cross-site consistency extremely difficult. Furthermore, maintaining the interpretability of models within a decentralized network remains a critical lacking. The field currently struggles to resolve the trilemma of ensuring strict data privacy (e.g., through differential privacy), maintaining high diagnostic performance, and providing consistent, trustworthy clinical explanations across diverse healthcare silos. Overcoming these barriers is essential for scaling collaborative medical AI.
<span class="related-paper-heading">Related Paper:</span>
<ul class="paper-list">
  <li>
    <span class="paper-title">FedXAI: Privacy-Preserving Federated Learning with Intrinsic Explainability for Medical Imaging.</span>
    Mohammad Amanour Rahman.
    <span class="paper-venue-review">[Under Review]</span>
  </li>
</ul>
</div>