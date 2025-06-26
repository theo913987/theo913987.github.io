---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

I am an undergraduate student (Class of 2022) at the 
<a href="https://ccst.tyut.edu.cn/" target="_blank">School of Computer Science and Technology</a>, 
<a href="https://www.tyut.edu.cn/" target="_blank">Taiyuan University of Technology (TYUT)</a>, 
supervised by Associate Professor Yongfei Wu. I am currently a member of the Intelligent Medicine and Biometric Research Laboratory (IMBR) at TYUT. 
My research primarily focuses on medical image analysis, including weakly supervised classification and segmentation of pathological and endoscopic images.


In addition to my core research in medical imaging, I am also deeply interested in emerging areas such as large language models and their interdisciplinary applications, as well as multimodal learning, foundation models in vision, and weakly supervised learning. I am always eager to explore new ideas, equipped with a strong willingness and ability to learn, and I look forward to growing together with my future advisor through collaborative research and continuous exploration.

If you are interested in my research or potential collaborations, feel free to contact me via the provided details!




# 🔥 News
- *2024.08*: &nbsp;🎉🎉The Undergraduate Innovation and Entrepreneurship Training Program project in which I played a key role was recognized as a provincial-level project.
- *2024.02*: &nbsp;I joined the <a href="https://lab.rjmart.cn/10579/3146DDB7959849F4" target="_blank">Intelligent Medicine and Biometric Research Laboratory (IMBR)</a> as an undergraduate member. 

# 📝 Publications

<!-- DSAGL Paper -->
<div class='paper-box' style="display: flex; gap: 24px; align-items: flex-start; margin-bottom: 30px;">

  <!-- Left: Image Section -->
  <div class='paper-box-image' style="flex: 0 0 300px; max-width: 300px;">
    <div>
      <div class="badge">BSPC</div>
      <img src='images/500x300.png' alt="DSAGL Figure" width="100%">
    </div>
  </div>

  <!-- Right: Text Section -->
  <div class='paper-box-text' style="flex: 1;">

    <p>
      <a href="https://arxiv.org/abs/2505.23341"><strong>DSAGL: Dual-Stream Attention-Guided Learning for Weakly Supervised Whole Slide Image Classification</strong></a><br>
      <em>Biomedical Signal Processing and Control (SCI Q2), Under Review</em>
    </p>

    <p>
      <strong>Daoxi Cao</strong>, Hangbei Cheng, Yijin Li, Ruolin Zhou, Xinyi Li, Xuehan Zhang, Binwei Li, Xuancheng Gu, Xueyu Liu, Yongfei Wu
    </p>

    <div style="display: flex; gap: 20px; margin-top: 10px;">
      <a href="https://arxiv.org/pdf/2505.23341" target="_blank"><strong>[Paper]</strong></a>
      <a href="#" target="_blank"><strong>[Code]</strong></a>
    </div>

    <hr style="border: none; height: 2px; background-color: #ddd; margin: 20px 0;">

    <p><strong>Highlights</strong></p>
    <ul>
      <li>We propose DSAGL, a novel weakly supervised classification framework that integrates a dual‑stream structure and a teacher–student mechanism to jointly enhance instance‑level and bag‑level performance.</li>
      <li>An alternating training strategy is introduced to improve semantic consistency and enable effective collaboration between the teacher and student branches.</li>
      <li>We design a lightweight encoder (VSSMamba) and a scale‑aware attention module (FASA) to balance efficient long‑range modeling and focus on diagnostically critical regions.</li>
      <li>DSAGL consistently outperforms representative MIL‑based methods on both synthetic and real‑world pathological datasets at the instance and bag levels.</li>
    </ul>

  </div>
</div>

<!-- FALMIL Paper -->
<div class='paper-box' style="display: flex; gap: 24px; align-items: flex-start; margin-bottom: 30px;">

  <!-- Left: Image Section -->
  <div class='paper-box-image' style="flex: 0 0 300px; max-width: 300px;">
    <div>
      <div class="badge">PRCV 2025</div>
      <img src='images/falmil-figure.png' alt="FALMIL Figure" width="100%">
    </div>
  </div>

  <!-- Right: Text Section -->
  <div class='paper-box-text' style="flex: 1;">

    <p>
      <a href=""><strong>FALMIL: Frequency-aware Linear MIL for Efficient Weakly Supervised Lesion Segmentation in Gigapixel Pathology Images</strong></a><br>
      <em>Chinese Conference on Pattern Recognition and Computer Vision (CCF-C), Submitted</em>
    </p>

    <p>
      <strong>Daoxi Cao</strong>, [Author List], Yongfei Wu
    </p>

    <div style="display: flex; gap: 20px; margin-top: 10px;">
      <a href="" target="_blank"><strong>[Paper]</strong></a>
      <a href="" target="_blank"><strong>[Code]</strong></a>
    </div>

    <hr style="border: none; height: 2px; background-color: #ddd; margin: 20px 0;">

    <p><strong>Highlights</strong></p>
    <ul>
      <li>We propose FALMIL, a frequency-aware linear MIL framework for efficient weakly supervised lesion segmentation in WSIs using only image-level labels.</li>
      <li>We design a dual-domain encoder combining learnable frequency features with Mamba-based long-range instance modeling under linear complexity.</li>
      <li>Without any soft-label refinement, FALMIL directly uses binarized CAMs as pseudo masks, achieving competitive performance on challenging pathology datasets.</li>
    </ul>

  </div>
</div>



# 🎖 Honors and Awards
- *2021.10* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.09* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 

# 📖 Educations
- *2019.06 - 2022.04 (now)*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2015.09 - 2019.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 

# 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/)

# 💻 Internships
- *2019.05 - 2020.02*, [Lorem](https://github.com/), China.
