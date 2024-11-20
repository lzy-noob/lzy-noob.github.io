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

I am currently enrolled in a Master's program for Electrical Science and Technology at the School of Electronic Information and Electrical Engineering (电子信息与电气工程学院), Shanghai Jiao Tong University, Shanghai, China, and under the supervision of Professor [Guanghui He](https://dmne.sjtu.edu.cn/dmne/faculty/heguanghui/). 

My current research interests focus on **Efficient ASIC Architecture Design for Emerging Applications**  (<a href='https://scholar.google.com/citations?user=vOi3QPQAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>). 
- **Efficient Hardware Accelerators for Autonomous Driving Systems**
  - Preprocessing: *feature learning network* (DAC'23, TVLSI'24)
  - Backbone: *3D sparse convolution* (ICCAD'23)
  - Multi-modality Fusion: *vision-centric 3D perception* (DAC'24 and TCAS-I'24 (under minor revision))
  - Data Compression Techniques for High-bandwidth Requirement from Future Neural Networks (TCAS-II'24)
- **Efficient Hardware Accelerators for Neural Radiance Field (NeRF)**
  - Hardware/Software Co-Design for NERF based 3D reconstruction (TCAD'24 (under minor revision))

# 🔥 News
- *2024.02*: &nbsp;🎉🎉 One co-authored paper about *Deformable Attention Acceleration* is accepted by DAC'24 ! Congratulations to Yansong !
- *2024.02*: &nbsp;🎉🎉 One co-authored paper about *NN data compression engine* is accepted by IEEE TCAS-II. Congratulations to Yuzhou !
- *2024.01*: &nbsp;🎉🎉 The extended paper of our DAC'23 is accepted by IEEE TVLSI !
- *2023.07*: &nbsp;🎉🎉 One co-authored about *3D Sparse Convolution Accelerator* is accepted by ICCAD'23. Congratulations to Dongxu ! 
- *2023.02*: &nbsp;🎉🎉 One co-authored about *Feature Learning Network Acceleration of Point Clouds* is accepted by DAC'23. Congratulations to Dongxu !

# 📝 Publications 

$^{\star}$: project manager; $^{\dagger}$: equal contribution.

## Selected Publications

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TVLSI 2024</div><img src='images/TVLSI24.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[FLNA: Flexibly Accelerating Feature Learning Networks for Large-Scale Point Clouds with Efficient Dataflow Decoupling]()

Dongxu Lyu$^{\dagger}$, **Zhenyu Li**$^{\dagger}$, Yuzhou Chen, Gang Wang, Weifeng He, Ningyi Xu and Guanghui He

- The **first** grid-based feature learning network accelerator with algorithm-architecture co-optimization for large-scale point clouds. 
- It demonstrates substantial performance boost over the state-of-the-art point cloud accelerators while providing superior support of large-scale point clouds ($>10^6$ points in $\sim$2ms).
- **An extension of our DAC'24 paper**.
- *IEEE Transactions on Very Large Scale Integration (VLSI) Systems*
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
