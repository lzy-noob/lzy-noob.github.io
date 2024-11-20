---
permalink: /
title: ""

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

$^{\dagger}$: equal contribution.

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

## Full Pub List

### Efficient Hardware Accelerators for Autonomous Driving Systems (Jan. 2022 -- Present)
- ``DAC 2024`` [DEFA: Efficient Deformable Attention Acceleration via Pruning-Assisted Grid-Sampling and Multi-Scale Parallel Processing](https://arxiv.org/pdf/2403.10913.pdf), Yansong Xu, Dongxu Lyu, **Zhenyu Li**, Yuzhou Chen, Zilong Wang, Gang Wang, Zhican Wang, Haomin Li and Guanghui He, *2024 61th ACM/IEEE Design Automation Conference (DAC)*, San Francisco, CA, USA, 2024.
- ``TCAS-II 2024`` [A Broad-Spectrum and High-Throughput Compression Engine for Neural Network Processors](https://ieeexplore.ieee.org/document/10433078), Yuzhou Chen, Jinming Zhang, Dongxu Lyu, **Zhenyu Li** and Guanghui He, in *IEEE Transactions on Circuits and Systems II: Express Briefs*.
- ``TVLSI 2024`` [FLNA: Flexibly Accelerating Feature Learning Networks for Large-Scale Point Clouds with Efficient Dataflow Decoupling](https://ieeexplore.ieee.org/document/10416684), Dongxu Lyu$^{\dagger}$, **Zhenyu Li$^{\dagger}$**, Yuzhou Chen, Gang Wang, Weifeng He, Ningyi Xu and Guanghui He, in *IEEE Transactions on Very Large Scale Integration (VLSI) Systems*.
- ``ICCAD 2023`` [SpOctA: A 3D Sparse Convolution Accelerator with Octree-Encoding-Based Map Search and Inherent Sparsity-Aware Processing](https://ieeexplore.ieee.org/document/10323728), Dongxu Lyu, **Zhenyu Li**, Yuzhou Chen, Jinming Zhang, Ningyi Xu and Guanghui He, *2023 IEEE/ACM International Conference on Computer Aided Design (ICCAD)*, San Francisco, CA, USA, 2023, pp. 1-9.
- ``DAC 2023`` [FLNA: An Energy-Efficient Point Cloud Feature Learning Accelerator with Dataflow Decoupling](https://ieeexplore.ieee.org/abstract/document/10247674), Dongxu Lyu, **Zhenyu Li**, Yuzhou Chen, Ningyi Xu and Guanghui He, *2023 60th ACM/IEEE Design Automation Conference (DAC)*, San Francisco, CA, USA, 2023, pp. 1-6.

# 💻 Projects
## A High Performance Neural Processing Unit for Efficient CNN Inference (Oct. 2023 -- Present)

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NPU Chip Design</div><img src='images/NPU_arch.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Hybrid Precision Neural Network Processor for Edge Computing (Tape-out)]()

- **High programmability and flexibility**, designed for AI algorithms with multi-operator and multi-precision requirements.
- Equipped with an operator-assembly translation framework to support fast deployment of the entire network.
- **Deployed** in company's intelligent perception terminals for real-time device status detection.
</div>
</div>

# 🎖 Honors and Awards
- *2024.11* **Tang Youshuqi Scholarship** from Shanghai Jiao Tong University. 
- *2024.09* **3rd Prize on China Postgraduate IC Innovation Competition (中国研究生创芯大赛)** from Association of Chinese Graduate Education. 
- *2023.06* **Outstanding Graduate** from Shanghai Jiao Tong University. 
- *2023.06* **Departmental Excellent Undergraduate Thesis (Department of Micro/Nano Electronics)** from Shanghai Jiao Tong Unversity.
- *2021.11* **The Outstanding Alumni Fund of the School of SEIEE** from Shanghai Jiao Tong University.
- *2021.09* **2nd Prize on Naitional Undergraduate Embedded Chip Design Competition (嵌入式芯片与系统设计竞赛)** from Chinese Institute of Electronics.

# 📖 Educations
<div class='paper-box'><div class='paper-box-image'><div><img src='images/sjtu.png' alt="sym" width="40%"></div></div>
<div class='paper-box-text' markdown="1">

- *2023.09 - 2026.03 (expected)*, MS student in Electronic Science and Technology (Department of Micro/Nano Electronics), Shanghai Jiao Tong University, Shanghai, China.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><img src='images/sjtu.png' alt="sym" width="40%"></div></div>
<div class='paper-box-text' markdown="1">
- *2019.09 - 2023.06*, B.E. in Microelectronics Science and Engineering (Department of Micro/Nano Electronics), Shanghai Jiao Tong University, Shanghai, China.
</div>
</div>

# 💻 Internships
- *2022.11 - 2024.03*, **Hardware & Toolchain Intern** in [Huixi Technology (辉羲智能)](https://www.rhino.auto/), Shanghai, China.
