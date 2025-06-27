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
supervised by <a href="https://tylgswyxgc.tyut.edu.cn/info/1411/5135.htm" target="_blank">Associate Professor Yongfei Wu</a>. I am currently a member of the <a href="https://lab.rjmart.cn/10579/3146DDB7959849F4" target="_blank">Intelligent Medicine and Biometric Research Laboratory (IMBR)</a> at TYUT. 
My research primarily focuses on medical image analysis, including weakly supervised classification and segmentation of pathological and endoscopic images.


In addition to my core research in medical imaging, I am also deeply interested in emerging areas such as large language models and their interdisciplinary applications, as well as multimodal learning, foundation models in vision, and weakly supervised learning. I am always eager to explore new ideas, equipped with a strong willingness and ability to learn, and I look forward to growing together with my future advisor through collaborative research and continuous exploration.

If you are interested in my research or potential collaborations, feel free to contact me via the provided details!

<a href="theo913987@163.com" target="_blank"><strong>[Email]</strong></a>/<a href="https://github.com/theo913987" target="_blank"><strong>[Github]</strong></a>


# 🔥 News
- *2024.08*: &nbsp;🎉🎉<a href="https://jyt.shanxi.gov.cn/sjytxxgk/xxgkml/jytwj/202408/P020240806312476481683.pdf" target="_blank">The Undergraduate Innovation and Entrepreneurship Training Program project</a> in which I played a key role was recognized as a provincial-level project.
- *2024.02*: &nbsp;I joined the <a href="https://lab.rjmart.cn/10579/3146DDB7959849F4" target="_blank">Intelligent Medicine and Biometric Research Laboratory (IMBR)</a> as an undergraduate member. 
- *2023.12*: &nbsp;Competitively selected for the <a href="https://jwc.tyut.edu.cn/info/1359/7845.htm" target="_blank">Excellent Engineer Education and Training Program</a>, joining the dedicated Excellent Engineer Class designed for top-performing students.
- *2023.06*: &nbsp;🎉🎉 I was honored with the <a href="https://student.tyut.edu.cn/info/1445/12953.htm" target="_blank">Taiyuan University of Technology “Qing'ou Award” — <em>Outstanding Talent Award</em></a> (Top 2%)


# 📝 Publications

<!-- DSAGL Paper -->
<div class='paper-box' style="display: flex; gap: 24px; align-items: flex-start; margin-bottom: 30px;">

  <!-- Left: Image Section -->
  <div class='paper-box-image' style="flex: 0 0 300px; max-width: 300px;">
    <div>
      <div class="badge">BSPC</div>
      <img src='images/DSAGL.png' alt="DSAGL Figure" width="100%">
    </div>
  </div>

  <!-- Right: Text Section -->
  <div class='paper-box-text' style="flex: 1;">

    <p>
      <a href="https://arxiv.org/abs/2505.23341"><strong>DSAGL: Dual-Stream Attention-Guided Learning for Weakly Supervised Whole Slide Image Classification</strong></a><br>
      <em>Biomedical Signal Processing and Control (SCI Q2), Under Review</em>
    </p>

    <p>
      <strong>Daoxi Cao</strong>, Hangbei Cheng, Yijin Li, Ruolin Zhou, Xuehan Zhang, Xinyi Li, Binwei Li, Xuancheng Gu, Jianan Zhang, Xueyu Liu, Yongfei Wu
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

<!-- DGMCN Paper -->
<div class='paper-box' style="display: flex; gap: 24px; align-items: flex-start; margin-bottom: 30px;">

  <!-- Left: Image Section -->
  <div class='paper-box-image' style="flex: 0 0 300px; max-width: 300px;">
    <div>
      <div class="badge">JVCI</div>
      <img src='images/DGMCN.png' alt="FALMIL Figure" width="100%">
    </div>
  </div>

  <!-- Right: Text Section -->
  <div class='paper-box-text' style="flex: 1;">

    <p>
      <a href=""><strong>DGMCN: Depth-Guided Multi-modal Collaboration Network for Robust Polyp Segmentation in Endoscopic Images</strong></a><br>
      <em>Journal of Visual Communication and Image Representation (CCF-C), With Editor</em>
    </p>

    <p>
      Xuehan Zhang, Hangbei Cheng, Tengfei Xu, Xinyi Li, <strong> Daoxi Cao</strong> , Xiaorong Dong, Xueyu Liu, Yongfei Wu
    </p>

    <div style="display: flex; gap: 20px; margin-top: 10px;">
      <a href="" target="_blank"><strong>[Paper]</strong></a>
      <a href="" target="_blank"><strong>[Code]</strong></a>
    </div>

    <hr style="border: none; height: 2px; background-color: #ddd; margin: 20px 0;">

    <p><strong>Highlights</strong></p>
    <ul>
      <li>A Depth-Guided Multi-modal Collaborative segmentation Network (DGMCN) is proposed for complex endo scopic scenarios. This approach pioneers the integration of monocular depth estimation with an encoder-decoder architecture, introducing structural modality to compensate for the inadequacies of RGB images in boundary identification while explicitly modeling three-dimensional deformation characteristics of mucosal surfaces.</li>
      <li>A cross-modal feature fusion module incorporating global-local collaborative pathways and a multi-scale pyramid module are designed, enabling joint modeling of spatial structures and textural appearance features.</li>
      <li>State-of-the-art performance has been achieved on three public polyp segmentation datasets, significantly enhancing the segmentation stability and generalization capability in scenarios involving complex deformations, blurred boundaries, and low-contrast conditions.</li>
    </ul>

  </div>
</div>



# 🎖 Honors and Awards
- *2025.02* The 16th Lanqiao Cup National Software and Information Technology Talent Competition – Special Project Track — *National Level – First Prize*
- *2023.06* The 25th National College English Contest — *National Level – Third Prize*
- *2023.03* The 32nd National College Mathematical Modeling Competition — *Provincial Level – Second Prize*
- *2025.06* The 16th Lanqiao Cup National Software and Information Technology Talent Competition – Design Track — *Provincial Level – Second Prize*
- *2023.12* The 15th National College Mathematical Competition — *Provincial Level – Third Prize*
- *2024.04* The 15th Lanqiao Cup National Software and Information Technology Talent Competition – Programming Track — *Provincial Level – Third Prize*
- *2024.06* Shanxi Construction Investment Education Award — *Outstanding Student Award*
- *2023.06* <a href="https://student.tyut.edu.cn/info/1445/12953.htm" target="_blank">Taiyuan University of Technology “Qing'ou Award” — *Outstanding Talent Award*</a> (Top 2%)
- School-level “Outstanding Academic Research Individual” Certificate — *Once*
- School-level “Outstanding Academic Performance Individual” Certificate — *Three times*
- School-level “Second-Class Scholarship” — *Once*
- School-level “Third-Class Scholarship” — *Three times*
 
# 💻 Patents and Software Works
- **Design Patent**: Intelligent Diagnostic Robot (Based on Multidimensional OCT Images)  
  *Inventor*: First Author  
  *Granted on*: June 24, 2025  
  *Patent No.*: [ZL 2024 3 0682609.6](https://epub.cnipa.gov.cn/)  

- **Utility Patent (Pending)**: A Multizone Adaptive Focus OCT Device  
  *Co-inventor*: Third Author  
  *Filed on*: October 2024

- **Utility Patent (Pending)**: A Disease Variant Recognition Device  
  *Co-inventor*: Third Author  
  *Filed on*: March 2025

- **Software Copyright (Pending)**: Lesion Recognition and Prediction System for AMD Based on Multidimensional OCT  
  *Co-author*: Third Author  
  *Filed on*: June 2025

# 📖 Educations
- *2019.06 - present*,B.ENG. Major in Computer Science and Technology, College of Computer Science and Technology (College of Big Data) , Taiyuan University of Technology, China
  
# 🧠 Skills  
- Proficient in **Python**, familiar with the **PyTorch** framework  
- Experienced in **Linux** server operation  
- Skilled in using programming tools such as **PyCharm** and **VSCode**  
- Familiar with AI tools including **ChatGPT**, **Deepseek**, **Cursor**, and **V0**  
- Proficient in **Word**, **PowerPoint**, **Visio**, **Excel**, and basic **video editing software**  
- Strong **learning ability**, good **teamwork** and **communication skills**
  
# 🧩 Personal Interests
- Exploring and experimenting with **AI Agents**  
- **Video creation and editing**  
- Interested in **algorithm design and research**  
- Playing the **guitar**  
- **Singing**  
- **Table tennis**  
- Enjoying **board games**

