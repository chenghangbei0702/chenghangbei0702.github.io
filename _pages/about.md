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

## 🧍‍♂️ About Me

**Hangbei Cheng (成航北)**  
Master's Student (Class of 2023)  
[College of Computer Science and Technology](https://ccst.tyut.edu.cn/), [Taiyuan University of Technology (TYUT)](https://www.tyut.edu.cn/)  
Advisor: [Assoc. Prof. Yongfei Wu](https://tylgswyxgc.tyut.edu.cn/info/1411/5135.htm)  
Lab: [IMBR Lab @ TYUT](https://lab.rjmart.cn/10579/3146DDB7959849F4)

My research interests lie in **intelligent medical image analysis**, with a particular focus on:

- **Lesion Segmentation in Histopathology Images**
- **Weakly Supervised Segmentation with Incomplete or Imprecise Annotations**
- **Large Vision Models in Medicine**
- **Federated Learning Security & Face Anti-spoofing**
- **Embodied Intelligence for Clinical Medical Applications**

I am actively exploring the integration of intelligent imaging technologies into real-world clinical workflows.

📫 **Contact**: [chenghangbei0702@163.com](mailto:chenghangbei0702@163.com)  
🔗 **Links**: [GitHub](https://github.com/chenghangbei0702)

---

## 📝 Publications

### 📌 Representative Papers

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ESWA</div><img src='images/GLMKD.png' alt="GLMKD" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**GLMKD: Joint Global and Local Mutual Knowledge Distillation for Weakly Supervised Lesion Segmentation in Histopathology Images**  
**Expert Systems with Applications (SCI-Q1 TOP, IF=7.6)** — *Accepted*  
**Hangbei Cheng**, Xueyu Liu, Jun Zhang, Xiaorong Dong, Xuetao Ma, Yansong Zhang, Hao Meng, Xing Chen, Guanghui Yue, Yidi Li, Yongfei Wu\*

[[Paper]](https://www.sciencedirect.com/science/article/pii/S0957417425010474) | [[Code]](https://github.com/chenghangbei0702/GLMKD-WSSS)

**Highlights:**
- Proposed a novel dual-stream knowledge distillation framework for weakly supervised pathology segmentation.
- Combined global supervision and multi-scale MIL for the first time in WSSS.
- Introduced shape transfer loss for improved global-local feature alignment.

</div></div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TCSVT</div><img src='images/MAMBA.png' alt="FMaMIL" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**FMaMIL: FFT-enhanced Vision Mamba Multi-instance Learning for Weakly Supervised Lesion Segmentation**  
**Medical Image Analysis (SCI-Q1 TOP \| CCF-B, IF=10.7)** — *1st Under Review*  
**Hangbei Cheng**, Xiaorong Dong, Jia Shen, Xueyu Liu, Jianan Zhang, Xuetao Ma, Mingqiang Wei, Liansheng Wang, Junxin Chen, Yongfei Wu\*

[[Paper]]() | [[Code]](https://github.com/chenghangbei0702/MambaMIL)

**Highlights:**
- Introduced the first Mamba-based MIL segmentation model with learnable frequency encoding.
- Bidirectional scanning captures contextual pathology structures.
- CAM-guided soft label correction boosts robustness to label noise.

</div></div>

### 📚 Other Publications

3. **[First Author]** *FALMIL: Frequency-aware Linear MIL for Efficient WSSS*, PRCV 2025 (Submitted)  
4. **[Second Author]** *Dual-branch Cross-scale Network for WSIs Classification*, *Information Fusion* (IF=15.5), 2025 (*With Editor*)  
5. **[Second Author / Advisor]** *DSAGL for Weakly Supervised WSI Classification*, *BSPC* (IF=4.9), 2025 (*Under Review*)  
6. **[Third Author]** *MTSec for Secure Multimodal Federated Learning*, *Knowledge-Based Systems* (IF=7.2), 2025 (*2nd RRC*)  
7. **[Third Author]** *Online Distillation for Face Anti-Spoofing*, *ACM MM* (CCF-A), 2025 (*Rebuttal*)  
8. **[Third Author / Advisor]** *LEPG-SAM for WSSS*, *Computer Methods and Programs in Biomedicine* (IF=4.8), 2025 (*With Editor*)  
9. **[Second Author / Advisor]** *DGMCN for Polyp Segmentation*, *JVCIR* (IF=3.1), 2025 (*Under Review*)  
10. **[Co-author]** *Fourier Shape Constrained Framework for Segmentation*, *PRCV*, 2025  
11. **[Co-author]** *MSMTSeg: Multi-Stained Kidney Histology Segmentation*, *IEEE JBHI* (IF=6.7), 2024  
12. **[Co-author]** *AI-assisted DKD Diagnosis in WSIs*, *Computers in Biology and Medicine* (IF=7.0), 2023

---

## 🎖 Honors & Awards

- 🏅 *2023.06* — Outstanding Undergraduate Graduate, TYUT  
- 🏅 *2022.05* — “May Fourth” Outstanding Communist Youth League Member, TYUT  
- 🏅 *2023.07* — Outstanding Undergraduate Thesis, TYUT  

---

## 🎓 Education

- **2019.09 – 2023.07** — B.Eng. in Data Science and Big Data Technology, College of Big Data, TYUT  
- **2023.09 – Present** — M.Eng. in Computer Science and Technology, College of CCST, TYUT  

---

## 🧑‍🎓 Student Leadership & Activities

- **2021.06 – 2023.06** — Head, University Science and Technology Association, TYUT  
- **2021.09 – 2023.06** — TYUT RuinoYun Innovation Base Student Leader  
- **2022.09 – 2023.06** — Committee Member, Undergraduate Party Branch, College of Big Data  

---

## 💬 Projects

- **2024.09 – Present**  
  PI, *Multi-domain Visual Feature Fusion for Weakly Supervised Pathology Segmentation*  
  Shanxi Postgraduate Innovation Project — No. 2024KY232

- **2022.06 – 2023.06**  
  PI, *GAN-based Pathology Stain Quality Enhancement and Evaluation*  
  Shanxi Undergraduate Innovation Training Project

- **2025.06 – Present**  
  PI, *Auxiliary Diagnosis System for Kidney Pathology via Missing-Modality Generation*  
  National Innovation Training Program for College Students

- **2023.09 – Present**  
  Core Member, *WSI-based Intelligent Kidney Disease Diagnosis*  
  Shanxi Natural Science Foundation (General Project)

---
