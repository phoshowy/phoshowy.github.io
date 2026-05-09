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


### I am currently a second-year graduate student at the Xiamen University Institute of Artificial Intelligence, focusing on research in neural network robustness, particularly adversarial purification.

### I earned my Bachelor of Engineering degree in Data Science and Big Data Technology from the School of Computer Science and Big Data at Fuzhou University. I am now pursuing my master's degree at the Intelligent Multimedia Laboratory at Xiamen University under the guidance of Associate Professor [Zhiming Luo](https://scholar.google.com/citations?user=RdRCIIYAAAAJ&hl=en).



# 🔥 News
- Nothing has happened recently.🫡

# 📝 Publications 

<!-- 标题和作者 -->
<div style="margin-bottom:1em;">
  <p>
    <a href="https://arxiv.org/pdf/2509.25082">
      <b>MANI-Pure: Magnitude-Adaptive Noise Injection for Adversarial Purification</b>
    </a>
  </p>
  <p><b>Xiaoyi Huang</b>, Junwei Wu, Kejia Zhang, Carl Yang, Zhiming Luo</p>
</div>

<!-- 图片 -->
<div style="text-align:center; margin:1em 0;">
  <img src="images/pipeline_mani.png" alt="sym" style="max-width:500px; box-shadow:3px 3px 6px #888;">
</div>

<!-- 贡献 -->
<div style="margin-top:1em;">
  <b>Contributions</b>
  <ul>
    <li>We demonstrate that hallucination risks are token-specific rather than uniformly distributed across the sequence. We reveal that contrastive decoding is only essential for specific "vulnerable" steps, providing a empirical basis for efficiency optimization.
    </li>
    <li>We propose CHASD, a training-free framework that introduces a spatio-temporal joint constraint. It dynamically couples temporal confidence gating with spatial attention guidance to calibrate only selected low-confidence decoding steps.
    </li>
    <li>Extensive evaluations across POPE, AMBER, MME, MMHal-Bench and CHAIR show that CHASD improves hallucination-related metrics over strong training-free baselines. It reduces unnecessary negative-branch forward passes while maintaining competitive generation quality.
    </li>
  </ul>
</div>

<hr>

<!--文章2-->
<div style="margin-bottom:1em;">
  <p>
    <a href="">
      <b>CHASD: Language Increment-Calibrated Contrastive
Decoding against Hallucination in LVLMs</b>
    </a>
  </p>
  <p><b>Xiaoyi Huang</b>, Kejia Zhang, Zhiming Luo</p>
</div>

<!-- 图片 -->
<div style="text-align:center; margin:1em 0;">
  <img src="images/pipeline_chasd.png" alt="sym" style="max-width:500px; box-shadow:3px 3px 6px #888;">
</div>

<!-- 贡献 -->
<div style="margin-top:1em;">
  <b>Contributions</b>
  <ul>
    <li>We further reveal distributional differences between adversarial and clean samples in the magnitude spectrum.</li>
    <li>The proposed MANI-Pure framework combines magnitude-adaptive diffusion with frequency-domain purification, achieving a principled balance between semantic fidelity and perturbation mitigation.</li>
    <li>Extensive experiments across datasets, attacks, and backbones demonstrate the superiority of our method.</li>
  </ul>
</div>



# 📖 Educations
- *2024.09 - now*, Xiamen University, Institute of Artificial Intelligence, Artificial Intelligence, Intelligent Multimedia Laboratory. 
- *2020.09 - 2024.06*, Fuzhou University, School of Computer Science and Big Data, Data Science and Big Data Technology, Bachelor of Engineering.

# 🎖 Honors and Awards
- *2023.05*  **Meritorious Winner**, Mathematical Contest in Modeling (MCM/ICM) 
- *2023.07* **Honorable Mention**, Mathematical Contest in Modeling (MCM/ICM)



