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
</style>

<div class="publication-content">

  <p style="margin-bottom: 25px;">
    Most recent publication updates can be found on my [<a href="https://scholar.google.com/citations?user=r-opZlMAAAAJ&hl=en" style="color: purple; font-style: italic; text-decoration: none;">Google Scholar</a>] profile.
  </p>

  <h2 style="font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Helvetica, Arial, sans-serif; font-weight: bold; margin-bottom: 10px;">2025</h2>
  <hr style="border-top: 1px solid #ddd; margin-bottom: 20px;">

  <p style="margin-bottom: 5px;">
    📌 <a href="https://arxiv.org/abs/2511.01013" style="color: blue; font-weight: bold; text-decoration: none; font-size: 1.1em;">HyFormer-Net: A Synergistic CNN-Transformer with Interpretable Multi-Scale Fusion for Breast Lesion Segmentation and Classification in Ultrasound Images</a> <span style="color: red; font-weight: bold;">[under review]</span>
  </p>
  
  <p style="margin-bottom: 5px;">
    <b>Authors:</b> <span style="color: green; font-weight: bold;">Mohammad Amanour Rahman</span>
  </p>
  
  <p style="margin-bottom: 5px;">
    <b>Journal:</b> <i>arXiv preprint</i> (<a href="https://arxiv.org/abs/2511.01013" style="color: #3178b3; text-decoration: none;">arXiv 2025</a>)
  </p>
  
  <p style="margin-bottom: 15px; font-size: 0.95em;">
    [<a onclick="var x = document.getElementById('abs-1'); if (x.style.display === 'none') { x.style.display = 'block'; } else { x.style.display = 'none'; }" style="color: #d35400; border: 1px solid #d35400; padding: 1px 4px; cursor: pointer; text-decoration: none;">Abstract</a>] 
    [<a href="https://arxiv.org/abs/2511.01013" style="color: red; text-decoration: none;">PDF</a>] 
    [<a href="#" style="color: red; text-decoration: none;">Code & Dataset</a>] 
    [<a onclick="var y = document.getElementById('cite-1'); if (y.style.display === 'none') { y.style.display = 'block'; } else { y.style.display = 'none'; }" style="color: red; cursor: pointer; text-decoration: none;">Citation</a>]
  </p>
  
  <div id="abs-1" style="display: none; margin-top: 15px; margin-bottom: 10px; font-size: 0.95em;">
    Breast cancer early detection heavily relies on ultrasound imaging, but accurate diagnosis is often hindered by speckle noise, operator dependency, and indistinct lesion boundaries. Existing deep learning methods lack hierarchical multi-scale integration, quantitative interpretability validation, and cross-dataset generalization analysis, hindering clinical adoption. In this work, we propose HyFormer-Net, a hybrid CNN-Transformer framework integrating EfficientNet-B3 and Swin Transformer via multi-scale hierarchical fusion blocks at four encoder stages. The attention-gated decoder enables dual-pipeline interpretability: intrinsic attention validation (quantitative IoU verification) and Grad-CAM classification reasoning. We evaluated performance on BUSI dataset and conducted systematic cross-dataset validation on BUS-UCLM with progressive fine-tuning. HyFormer-Net achieved 76.1% Dice score and 93.2% classification accuracy on BUSI, with clinically critical 92.1% Malignant Recall. Cross-dataset evaluation showed zero-shot failure, but 10% target-domain fine-tuning recovered 92.5% performance.
  </div>

  <div id="cite-1" style="display: none; background-color: #f9f9f9; border-left: 3px solid #d35400; padding: 10px; margin-top: 10px; font-family: monospace; font-size: 0.9em; color: #333; text-align: left;">
    <b>Cite as:</b> arXiv:2511.01013  <br>
    
  </div>

</div>