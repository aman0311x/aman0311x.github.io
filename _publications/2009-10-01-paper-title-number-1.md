---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---



<style>
  .publication-content {
    font-family: Georgia, "Times New Roman", Times, serif;
    font-size: 16px;
    line-height: 1.6;
    text-align: justify;
    color: #000;
  }
  .pub-year-heading {
    font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Helvetica, Arial, sans-serif;
    font-weight: bold;
    font-size: 1.4em;
    margin-top: 30px;
    margin-bottom: 5px;
  }
  .pub-entry {
    margin-bottom: 15px;
    padding-bottom: 10px;
    border-bottom: none;
  }
  .pub-title,
  .pub-title:link,
  .pub-title:visited,
  .pub-title:hover,
  .pub-title:active,
  .pub-title:focus {
    color: blue;
    font-weight: bold;
    font-size: 1.05em;
    text-decoration: none !important;
    border-bottom: none !important;
    box-shadow: none !important;
    outline: none !important;
  }
  .pub-badge {
    font-weight: bold;
    font-size: 0.9em;
  }
  .badge-q1 { color: green; }
  .badge-q2 { color: green; }
  .badge-corea { color: green; }
  .pub-authors {
    margin-top: 2px;
    margin-bottom: 2px;
  }
  .pub-me {
    color: green;
    font-weight: bold;
  }
  .pub-journal {
    font-style: italic;
  }
  .pub-venue-link {
    color: #3178b3;
    text-decoration: none;
  }
  .pub-venue-link:hover {
    text-decoration: underline;
  }
  .pub-links {
    margin-top: 6px;
    font-size: 0.95em;
  }
  .pub-links a {
    color: #c0392b;
    text-decoration: none;
    margin-right: 4px;
  }
  .pub-links a:hover {
    text-decoration: none;
  }
  .abs-toggle {
    color: #d35400;
    border: 1px solid #d35400;
    padding: 1px 5px;
    cursor: pointer;
    font-size: 0.93em;
  }
  .abs-box {
    display: none;
    margin-top: 12px;
    font-size: 0.95em;
    background: #fafafa;
    border-left: 3px solid #d35400;
    padding: 10px 14px;
    color: #333;
    text-align: left;
  }
  .cite-box {
    display: none;
    margin-top: 10px;
    background-color: #f9f9f9;
    border-left: 3px solid #d35400;
    padding: 10px;
    font-family: monospace;
    font-size: 0.9em;
    color: #333;
    text-align: left;
  }
</style>
<div class="publication-content">
  <p style="margin-bottom: 25px;">
    Most recent publication updates can be found on my
    [<a href="https://scholar.google.com/citations?user=r-opZlMAAAAJ&hl=en" style="color: purple; font-style: italic; text-decoration: none;">Google Scholar</a>]
    profile.
  </p>
  <div class="pub-year-heading">2026</div>
  <hr style="border-top: 1px solid #ddd; margin-bottom: 20px;">
  <div class="pub-entry">
    <p style="margin-bottom: 3px;">
      📌
      <a href="https://doi.org/10.1016/j.ibmed.2026.100413" class="pub-title">
        HyFormer-Net: A Synergistic CNN-Transformer with Interpretable Multi-Scale Fusion for Breast Lesion Segmentation and Classification in Ultrasound Images
      </a>
      <span class="pub-badge badge-q2">(Q2)</span>
    </p>
    <p class="pub-authors" style="margin-bottom: 2px;">
      <b>Authors:</b> <span class="pub-me">Mohammad Amanour Rahman</span>
    </p>
    <p style="margin-bottom: 5px;">
      <b>Journal:</b>
      <span class="pub-journal">Intelligence-Based Medicine</span>
      (<a href="https://doi.org/10.1016/j.ibmed.2026.100413" class="pub-venue-link">Elsevier, 2026</a>)
    </p>
    <div class="pub-links">
      [<a onclick="var x=document.getElementById('abs-hyformer');x.style.display=x.style.display==='none'?'block':'none';" class="abs-toggle">Abstract</a>]
      [<a href="https://doi.org/10.1016/j.ibmed.2026.100413">Link</a>]
      [<a onclick="var y=document.getElementById('cite-hyformer');y.style.display=y.style.display==='none'?'block':'none';" style="cursor:pointer;">Citation bib</a>]
    </div>
    <div id="abs-hyformer" class="abs-box">
      Breast cancer early detection heavily relies on ultrasound imaging, but accurate diagnosis is often hindered by speckle noise, operator dependency, and indistinct lesion boundaries. Existing deep learning methods lack hierarchical multi-scale integration, quantitative interpretability validation, and cross-dataset generalization analysis, hindering clinical adoption. In this work, we propose HyFormer-Net, a hybrid CNN-Transformer framework integrating EfficientNet-B3 and Swin Transformer via multi-scale hierarchical fusion blocks at four encoder stages. The attention-gated decoder enables dual-pipeline interpretability: intrinsic attention validation (quantitative IoU verification) and Grad-CAM classification reasoning. We evaluated performance on BUSI dataset and conducted systematic cross-dataset validation on BUS-UCLM with progressive fine-tuning. HyFormer-Net achieved 76.1% Dice score and 93.2% classification accuracy on BUSI, with clinically critical 92.1% Malignant Recall. Cross-dataset evaluation showed zero-shot failure, but 10% target-domain fine-tuning recovered 92.5% performance.
    </div>
    <div id="cite-hyformer" class="cite-box">
      <b>Cite as:</b><br>
      @article{rahman2026hyformernet,<br>
      &nbsp;&nbsp;title={HyFormer-Net: A Synergistic CNN-Transformer with Interpretable Multi-Scale Fusion for Breast Lesion Segmentation and Classification in Ultrasound Images},<br>
      &nbsp;&nbsp;author={Rahman, Mohammad Amanour},<br>
      &nbsp;&nbsp;journal={Intelligence-Based Medicine},<br>
      &nbsp;&nbsp;year={2026},<br>
      &nbsp;&nbsp;publisher={Elsevier},<br>
      &nbsp;&nbsp;doi={10.1016/j.ibmed.2026.100413}<br>
      }
    </div>
  </div>
</div>