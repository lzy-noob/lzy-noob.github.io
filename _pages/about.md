---
permalink: /
title: ""

author_profile: true
redirect_from: 
  - /about/
  - /about.html
---
<script charset="UTF-8" id="LA_COLLECT" src="//sdk.51.la/js-sdk-pro.min.js"></script>
<script>LA.init({id:"3KnA9M9tzXDhke2r",ck:"3KnA9M9tzXDhke2r"})</script>

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

I am currently enrolled in a Master's program for Electrical Science and Technology at the School of Electronic Information and Electrical Engineering (电子信息与电气工程学院), Shanghai Jiao Tong University (SJTU), Shanghai, China, and under the supervision of Professor [Guanghui He](https://dmne.sjtu.edu.cn/dmne/faculty/heguanghui/). 

My current research interests focus on **Efficient ASIC Architecture Design for Emerging Applications**. 

- **Efficient Hardware Accelerators for Autonomous Driving Systems**
  - Preprocessing: feature learning network (DAC2023, TVLSI2024)
  - Backbone: 3D sparse convolution (ICCAD2023)
  - Multi-modality Fusion: vision-centric 3D perception (DAC2024, TCAS-I2025)
  - Data Compression Techniques for High-bandwidth Requirement from Future Neural Networks (TCAS-II2024)
- **Efficient Hardware Accelerators for Neural Radiance Field (NeRF)**
  - Hardware/Software Co-Design for NERF based 3D reconstruction (TCAD2025)
- **Efficient Hardware Accelerators for Transformers**
  - KV Cache Compression (2 x DAC2025)
  - Bit-Serial Acceleration (DAC2025)
  - Processing-in-Memory (DAC2025)

# 🔥 News
- *2025.04*: &nbsp;🎉🎉 One co-authored paper about Acceleration for Vision-Centric 3D Perception is accepted by TCAS-I.
- *2025.02*: &nbsp;🎉🎉 Our paper about DSA’s Efficiency Optimization on KV Cache in LLMs is accepted by DAC. One co-authored paper about Near Memory Processing for Generative LLM inference is accepted by DAC. One co-authored paper about Bit-serial Neural Network Acceleration is accepted by DAC.
- *2024.11*: &nbsp;🎉🎉 Our paper about Neural Rendering Acceleration is accepted by TCAD.
- *2024.03*: &nbsp;🎉🎉 The preprint version of our DAC’24 paper DEFA: Deformable Attention Accelerator is available on ArXiv.
- *2024.02*: &nbsp;🎉🎉 One co-authored paper about *Deformable Attention Acceleration* is accepted by DAC'24.
- *2024.02*: &nbsp;🎉🎉 One co-authored paper about *NN data compression engine* is accepted by IEEE TCAS-II.
- *2024.01*: &nbsp;🎉🎉 The extended paper of our DAC'23 is accepted by IEEE TVLSI.
- *2023.07*: &nbsp;🎉🎉 One co-authored paper about *3D Sparse Convolution Accelerator* is accepted by ICCAD'23.
- *2023.02*: &nbsp;🎉🎉 One co-authored paper about *Feature Learning Network Acceleration of Point Clouds* is accepted by DAC'23.

# 📝 Publications 

$^{\dagger}$: equal contribution.

## Selected Publications

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TVLSI 2024</div><img src='images/TVLSI24.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[FLNA: Flexibly Accelerating Feature Learning Networks for Large-Scale Point Clouds with Efficient Dataflow Decoupling](https://ieeexplore.ieee.org/document/10416684)

Dongxu Lyu$^{\dagger}$, **Zhenyu Li**$^{\dagger}$, Yuzhou Chen, Gang Wang, Weifeng He, Ningyi Xu and Guanghui He

- The **first** grid-based feature learning network accelerator with algorithm-architecture co-optimization for large-scale point clouds. 
- It demonstrates substantial performance boost over the state-of-the-art point cloud accelerators while providing superior support of large-scale point clouds ($>10^6$ points in $\sim$2ms).
- **An extension of our DAC'24 paper**.
- *IEEE Transactions on Very Large Scale Integration (VLSI) Systems*
</div>
</div>

## Full Pub List

### Efficient Hardware Accelerators for AI Computing (Jan. 2022 -- Present)
- ``TCAS-I 2025`` [An Efficient Multi-View Cross-Attention Accelerator for Vision-Centric 3D Perception in Autonomous Driving](https://ieeexplore.ieee.org/document/10950425), Dongxu Lyu, **Zhenyu Li**, Yansong Xu, Gang Wang, Wenjie Li, Yuzhou Chen, Liyan Chen, Weifeng He and Guanghui He, in *IEEE Transactions on Circuits and Systems I: Regular Papers*, vol. 72, no. 7, pp. 3272-3285, July 2025.
- ``DAC 2025`` [KVO-LLM: Boosting Long-Context Generation Throughput for Batched LLM Inference](), **Zhenyu Li**$^{\dagger}$, Dongxu Lyu$^{\dagger}$, Gang Wang, Yuzhou Chen, Liyan Chen, Wenjie Li, Jianfei Jiang, Yanan Sun and Guanghui He, *2025 62th ACM/IEEE Design Automation Conference (DAC)*, San Francisco, CA, USA, 2025.
- ``DAC 2025`` [VEDA: Efficient LLM Generation Through Voting-based KV Cache Eviction and Dataflow-flexible Accelerator](), Zhican Wang, Hongxiang Fan, Haroon Waris, Gang Wang, **Zhenyu Li**, Jianfei Jiang, Yanan Sun and Guanghui He, *2025 62th ACM/IEEE Design Automation Conference (DAC)*, San Francisco, CA, USA, 2025.
- ``DAC 2025`` [BitPattern: Enabling Efficient Bit-Serial Acceleration of Deep Neural Networks through Bit-Pattern Pruning](), Gang Wang, Siqi Cai, **Zhenyu Li**, Wenjie Li, Dongxu Lyu, Yanan Sun, Jianfei Jiang and Guanghui He, *2025 62th ACM/IEEE Design Automation Conference (DAC)*, San Francisco, CA, USA, 2025.
- ``DAC 2025`` [AttenPIM: Accelerating LLM Attention with Dual-mode GEMV in Processing-in-Memory](), Liyan Chen$^{\dagger}$, Dongxu Lyu$^{\dagger}$, **Zhenyu Li**, Jianfei Jiang, Qin Wang, Zhigang Mao and Naifeng Jing, *2025 62th ACM/IEEE Design Automation Conference (DAC)*, San Francisco, CA, USA, 2025.
- ``TCAD 2024`` [Neural Rendering Acceleration with Deferred Neural Decoding and Voxel-Centric Data Flow](https://ieeexplore.ieee.org/abstract/document/10819500), Yuzhou Chen$^{\dagger}$, **Zhenyu Li**$^{\dagger}$, Dongxu Lyu, Yansong Xu and Guanghui He, in *IEEE Transactions on Computer-Aided Design of Integrated Circuits and Systems*, vol. 44, no. 7, pp. 2725-2737, July 2025.
- ``DAC 2024`` [DEFA: Efficient Deformable Attention Acceleration via Pruning-Assisted Grid-Sampling and Multi-Scale Parallel Processing](https://arxiv.org/pdf/2403.10913.pdf), Yansong Xu, Dongxu Lyu, **Zhenyu Li**, Yuzhou Chen, Zilong Wang, Gang Wang, Zhican Wang, Haomin Li and Guanghui He, *2024 61th ACM/IEEE Design Automation Conference (DAC)*, San Francisco, CA, USA, 2024.
- ``TCAS-II 2024`` [A Broad-Spectrum and High-Throughput Compression Engine for Neural Network Processors](https://ieeexplore.ieee.org/document/10433078), Yuzhou Chen, Jinming Zhang, Dongxu Lyu, **Zhenyu Li** and Guanghui He, in *IEEE Transactions on Circuits and Systems II: Express Briefs*, vol. 71, no. 7, pp. 3528-3532, July 2024.
- ``TVLSI 2024`` [FLNA: Flexibly Accelerating Feature Learning Networks for Large-Scale Point Clouds with Efficient Dataflow Decoupling](https://ieeexplore.ieee.org/document/10416684), Dongxu Lyu$^{\dagger}$, **Zhenyu Li**$^{\dagger}$, Yuzhou Chen, Gang Wang, Weifeng He, Ningyi Xu and Guanghui He, in *IEEE Transactions on Very Large Scale Integration (VLSI) Systems*, vol. 32, no. 4, pp. 739-751, April 2024.
- ``ICCAD 2023`` [SpOctA: A 3D Sparse Convolution Accelerator with Octree-Encoding-Based Map Search and Inherent Sparsity-Aware Processing](https://ieeexplore.ieee.org/document/10323728), Dongxu Lyu, **Zhenyu Li**, Yuzhou Chen, Jinming Zhang, Ningyi Xu and Guanghui He, *2023 IEEE/ACM International Conference on Computer Aided Design (ICCAD)*, San Francisco, CA, USA, 2023.
- ``DAC 2023`` [FLNA: An Energy-Efficient Point Cloud Feature Learning Accelerator with Dataflow Decoupling](https://ieeexplore.ieee.org/abstract/document/10247674), Dongxu Lyu, **Zhenyu Li**, Yuzhou Chen, Ningyi Xu and Guanghui He, *2023 60th ACM/IEEE Design Automation Conference (DAC)*, San Francisco, CA, USA, 2023.

# 💻 Projects
## A High Performance Neural Processing Unit for Efficient CNN Inference (Oct. 2023 -- Present)

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NPU Chip Design</div><img src='images/NPU_arch.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**Hybrid Precision Neural Network Processor for Edge Computing (Tape-out)**

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

  <table style="width:100%;border:0px;border-spacing:0px;border-collapse:separate;margin-right:auto;margin-left:auto;"><tbody>
  <tr>
    <td style="padding:10px;width:15%;vertical-align:middle;">
      <img src="images/sjtu.png" alt="sjtu" width="150">
    </td>
    <!-- <td width="75%" valign="center"> -->
    <td style="padding:10px;width:85%;vertical-align:middle">
      <h2><a href="https://en.sjtu.edu.cn" target="_blank">SHANGHAI JIAO TONG UNIVERSITY</a></h2>
      Degree: Bachelor
      <br>
      Period: 2019.09 - 2023.06
      <br>
      Major: Microelectronics Science and Engineering
      <br>
      <strong>GPA: 4.03/4.3 (ranked 2nd out of 67)</strong>
    </td>
  </tr>
</tbody></table>

  <table style="width:100%;border:0px;border-spacing:0px;border-collapse:separate;margin-right:auto;margin-left:auto;"><tbody>
  <tr>
    <td style="padding:10px;width:15%;vertical-align:middle;">
      <img src="images/sjtu.png" alt="sjtu" width="150">
    </td>
    <!-- <td width="75%" valign="center"> -->
    <td style="padding:10px;width:85%;vertical-align:middle">
      <h2><a href="https://en.sjtu.edu.cn" target="_blank">SHANGHAI JIAO TONG UNIVERSITY</a></h2>
      Degree: Master
      <br>
      Period: 2023.09 - 2026.03 （expected）
      <br>
      Major: Integrated Circuit Science and Engineering
      <br>
      <strong>GPA: 3.98/4.00 (ranked 1st out of 115)</strong>
    </td>
  </tr>
</tbody></table>

# 💻 Internships

  <table style="width:100%;border:0px;border-spacing:0px;border-collapse:separate;margin-right:auto;margin-left:auto;"><tbody>
  <tr>
    <td style="padding:10px;width:25%;vertical-align:middle;">
      <img src="images/hx.jpg" alt="hx" width="200">
    </td>
    <!-- <td width="75%" valign="center"> -->
    <td style="padding:10px;width:75%;vertical-align:middle">
      <h2><a href="https://www.rhino.auto/" target="_blank">Huixi Technology (辉羲智能)</a></h2>
      2022.11 - 2024.03
      <br>
      <strong>Hardware & Toolchain Intern</strong>
      <br>
      Shanghai, China.
    </td>
  </tr>
</tbody></table>
