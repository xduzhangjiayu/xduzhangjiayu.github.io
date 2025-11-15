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

Hi there! I'm currently a Researcher at Lenovo Research. I obtained my B.E. in Electronic Information Engineering from Xidian University in 2021, followed by a Master degree (Diplôme d'Ingénieur) in Multimedia Communications from Nantes Université, France in 2022.
My research interests lie in Computer Vision, with a specific focus on Controllable Video/Image Generation and Editing. I previously have research experience in Video Compression (H265/VP9/AV1 Codec). I’m passionate about AIGC technology, feel free to contact me at <a href="mailto:xduzhangjiayu@163.com">xduzhangjiayu@163.com</a> if you’d like to collaborate with me.

<!-- My research interest includes neural machine translation and computer vision. I have published more than 100 papers at the top international AI conferences with total <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'>google scholar citations <strong><span id='total_cit'>260000+</span></strong></a> (You can also use google scholar badge <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>). -->


# 🔥 News
- *2025.11*: &nbsp;🎉🎉 One paper is accepted by TCSVT (CCF-B)!
- *2025.09*: &nbsp;🎉🎉 One paper about Controllable Video Generation is on Arxiv!

# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Arxiv 2025</div><img src='images/teaser_ditraj.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[DiTraj: Training-free Trajectory Control for Video Diffusion Transformer](https://arxiv.org/abs/2509.21839) 

**(Co-first Author + Project Leader)**

Cheng Lei†, **Jiayu Zhang†‡**, Yue Ma\*, Xinyu Wang, Long Chen, Liang Tang, Yiqiang Yan, Fei Su, Zhicheng Zhao\*

(†Equal Contribution  ‡Project Lead  *Corresponding Author)

[**Project**](https://xduzhangjiayu.github.io/DiTraj_Project_Page/) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- DiTraj is the **first** training-free trajectory control method for DiT-based video generation models!
</div>
</div>

<!-- - [Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet](https://github.com), A, B, C, **CVPR 2020** -->

<!-- # 🎖 Honors and Awards
- *2021.10* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.09* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  -->

# 📖 Experiences
<!-- - *2019.06 - 2022.04 (now)*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2015.09 - 2019.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  -->
- *2022.11 - now*, Researcher, Lenovo Research
- *2020.09 - 2022.09*, Master's degree (Diplôme d'Ingénieur) in Multimedia Communications, Nantes Université, France
- *2017.09 - 2021.06*, Bachelor of Engineering (B.E.) in Electronic Information Engineering, Xidian University, Xi'an, China

# 💻 Open-Source Contribution
- [diffusers](https://github.com/huggingface/diffusers): State-of-the-art diffusion models for image, video, and audio generation in PyTorch.
- [intel-npu-acceleration-library](https://github.com/intel/intel-npu-acceleration-library): A PyTorch acceleration library for the NPU of Intel Core Ultra processors.