---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<style>
body {
  line-height: 1.8;
}

p {
  margin-bottom: 1.2em;
}

ul, ol {
  margin-bottom: 1.2em;
}

h2, h3 {
  margin-top: 2em;
  margin-bottom: 1em;
}
</style>


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

Advisor: [Assoc. Prof. Yongfei Wu](https://tylgswyxgc.tyut.edu.cn/info/1411/5135.htm) and [Assoc. Prof. Xueyu Liu](https://xueyuliu.github.io)  

Lab: [IMBR Lab @ TYUT](https://lab.rjmart.cn/10579/3146DDB7959849F4)

📫 **Contact**: [chenghangbei0702@163.com](mailto:chenghangbei0702@163.com)  

🔗 **Links**: [GitHub](https://github.com/chenghangbei0702)

---

## 🔍 Research Interests

My current research focuses on **vision modeling and learning with limited annotations** in medical image scenarios. Specifically:

- **Weakly Supervised & Semi-supervised Medical Image Segmentation**  
  → Multi-scale lesion feature learning, label noise robustness, shape prior modeling.

- **Multi-modal Prompt Engineering & Visual Foundation Models**  
  → Leveraging large-scale models (e.g., CLIP, SAM) for domain adaptation, semantic alignment, and efficient transfer to medical domains.

- **Embodied Intelligence & Multi-agent Collaboration in Medical AI (Exploratory)**  
  → Modeling decision-making and robustness in multi-agent, multi-modal diagnostic systems.

> *My long-term vision is to design intelligent, trustworthy, and interpretable visual systems that can truly “see and understand” the world, not just recognize pixels.*

---

## 📝 Publications

> ✍️ *Selected works categorized by research direction and status*

---

### 🧠 Medical Image Segmentation & Weak Supervision

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ESWA</div><img src='images/GLMKD.png' alt="GLMKD" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**GLMKD: Joint Global and Local Mutual Knowledge Distillation for Weakly Supervised Lesion Segmentation in Histopathology Images**  
<span style="color:#d9534f"><strong>Expert Systems with Applications</strong></span> <span class="badge badge-red">SCI-Q1 TOP</span> <span class="badge badge-green">IF=7.6</span> <span class="badge badge-success">Published</span>  

**Hangbei Cheng**, Xueyu Liu, Jun Zhang, Xiaorong Dong, Xuetao Ma, Yansong Zhang, Hao Meng, Xing Chen, Guanghui Yue, Yidi Li, Yongfei Wu\*

[[Paper]](https://www.sciencedirect.com/science/article/pii/S0957417425010474) | [[Code]](https://github.com/chenghangbei0702/GLMKD-WSSS)

</div></div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">MedIA</div><img src='images/MAMBA.png' alt="FMaMIL" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**FMaMIL: FFT-enhanced Vision Mamba Multi-instance Learning for Weakly Supervised Lesion Segmentation**  
<span style="color:#d43f3a"><strong>Medical Image Analysis</strong></span> <span class="badge badge-red">SCI-Q1 TOP</span> <span class="badge badge-warning">CCF-B</span> <span class="badge badge-green">IF=10.7</span> <span class="badge badge-warning">1st RRC</span>  

**Hangbei Cheng**, Xiaorong Dong, Jia Shen, Xueyu Liu, Jianan Zhang, Xuetao Ma, Mingqiang Wei, Liansheng Wang, Junxin Chen, Yongfei Wu\*

[[Code]](https://github.com/chenghangbei0702/MambaMIL)

</div></div>

- **SegMind**, AAAI 2026 — <span class="badge badge-purple">CCF-A</span> <span class="badge badge-warning">Submitted</span>  
- **FALMIL**, PRCV 2025 — <span class="badge badge-info">CCF-C</span> <span class="badge badge-warning">Submitted</span>  
- **DSAGL**, BSPC — <span class="badge badge-secondary">SCI-Q2</span> <span class="badge badge-warning">1st RRC</span>  
- **LEPG-SAM**, *In preparation* — <span class="badge badge-secondary">Medical Imaging</span>  

---

### 🤖 Multimodal Learning, Federated Security & Embodied AI

- **A Dual-branch Network**, *Information Fusion*, 2025  
  <span class="badge badge-red">SCI-Q1 TOP</span> <span class="badge badge-green">IF=15.5</span> <span class="badge badge-warning">With Editor</span>  
  <em>Second Author</em>

- **Multi-stained Renal Segmentation**, AAAI 2026  
  <span class="badge badge-purple">CCF-A</span> <span class="badge badge-warning">Submitted</span>  
  <em>Second Author</em>

- **DGMCN for Polyp Segmentation**, JVCIR  
  <span class="badge badge-info">SCI-Q4</span> <span class="badge badge-warning">1st UR</span>

- **MTSec: AIGC-enhanced Federated Learning**, *KBS*, 2025  
  <span class="badge badge-red">SCI-Q1</span> <span class="badge badge-green">IF=7.2</span> <span class="badge badge-warning">2nd RRC</span>

- **Face Anti-Spoofing**, ACMMM 2025  
  <span class="badge badge-purple">CCF-A</span> <span class="badge badge-warning">Resubmission (Avg Score: 5.25)</span>

- **AlignBreaker: Multimodal Attack**, *In preparation*  
  <span class="badge badge-secondary">Embodied AI</span>  

- **Fourier Shape-Constrained Segmentation**, PRCV 2025  
  <span class="badge badge-info">CCF-C</span> <span class="badge badge-warning">Submitted</span>

- **MSMTSeg**, IEEE JBHI, 2024  
  <span class="badge badge-secondary">SCI-Q2</span> <span class="badge badge-green">Published</span>

- **AI for Diabetic Kidney**, *CIBM*, 2023  
  <span class="badge badge-secondary">SCI-Q2</span> <span class="badge badge-green">Published</span>

## 📝 Publications

### 📌 Representative Papers

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ESWA</div><img src='images/GLMKD.png' alt="GLMKD" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**GLMKD: Joint Global and Local Mutual Knowledge Distillation for Weakly Supervised Lesion Segmentation in Histopathology Images**  

**Expert Systems with Applications (SCI-Q1 TOP, IF=7.6)** — *Published*  

**Hangbei Cheng**, Xueyu Liu, Jun Zhang, Xiaorong Dong, Xuetao Ma, Yansong Zhang, Hao Meng, Xing Chen, Guanghui Yue, Yidi Li, Yongfei Wu\*

[[Paper]](https://www.sciencedirect.com/science/article/pii/S0957417425010474) | [[Code]](https://github.com/chenghangbei0702/GLMKD-WSSS)

**Highlights:**
- Proposed a novel dual-stream knowledge distillation framework for weakly supervised pathology segmentation.
- Combined global supervision and multi-scale MIL for the first time in WSSS.
- Introduced shape transfer loss for improved global-local feature alignment.

</div></div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">MedIA</div><img src='images/MAMBA.png' alt="FMaMIL" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**FMaMIL: FFT enchanced vision Mamba Multi-instance learning for Weakly Supervised Lesion Segmentation in Medical Images**  

**Medical Image Analysis (SCI-Q1 TOP \| CCF-B, IF=10.7)** — *1st RRC*  

**Hangbei Cheng**, Xiaorong Dong, Jia Shen, Xueyu Liu, Jianan Zhang, Xuetao Ma, Mingqiang Wei, Liansheng Wang, Junxin Chen, Yongfei Wu\*

[[Paper]]() | [[Code]](https://github.com/chenghangbei0702/MambaMIL)

**Highlights:**
- Introduced the first Mamba-based MIL segmentation model with learnable frequency encoding.
- Bidirectional scanning captures contextual pathology structures.
- CAM-guided soft label correction boosts robustness to label noise.

</div></div>

### 📚 Other Publications

3. **[First Author]** *SegMind: Dual-Brain Collaboration with Multi-Modal Prompts and Multi-Teacher Knowledge Integration for Semi-Supervised Medical Segmentation*, AAAI2026 (Submitted)  
4. **[First Author]** *FALMIL: Frequency-aware Linear MIL for Efficient Weakly Supervised Lesion Segmentation in Gigapixel Pathology Images*, PRCV 2025 (Submitted)
5. **[Co-First Author]** *DSAGL: Dual-Stream Attention-Guided Learning for Weakly Supervised Whole Slide Image Classification*，BSPC(1st RRC)
6. **[Second Author]** * A Dual-branch Network with Cross-scale Feature Interaction and Alignment for Weakly Supervised Whole Slide Image Classification*, *Information Fusion*, 2025 (*With Editor*)  
7. **[Second Author]** *Multi-stained Renal Histopathology Image Segmentation via Meta-learning with Guided Collaborative Distillation*, *AAAI 2026*, (*Submitted*)
8. **[Second Author]** *DGMCN: Depth-Guided Multi-modal Collaboration Network for Robust Polyp Segmentation in Endoscopic Images*, *JVCIR*, (*1st UR*)  
9. **[Third Author]** *LEPG-SAM: Local Enhancement Perception and Guidance for Weakly Supervised Medical Image Segmentation.*, (*Manuscript in Preparation*)
10. **[Co-author]** *Fourier Transform-Based Shape Constrained Framework for Generalizable Medical Image Segmentation*, *PRCV*, 2025  (Submitted)
11. **[Co-author]** *MSMTSeg: Multi Stained Multi Tissue Segmentation of Kidney Histology Images via Generative Self Supervised Meta Learning Framework*, *IEEE JBHI*, 2024.(Published)
12. **[Co-author]** *Diagnosis of diabetic kidney disease in whole slide images via AI-driven quantification of pathological indicators*, *CIBM*, 2023.(Published)
13. **[Co-First Author]** *AlignBreaker: Multimodal Feature Perturbation Attacks on Embodied AI via Alignment Disruption*，(*Manuscript in Preparation*)
14. **[Third Author]** *MTSec: AIGC-Enhanced Security Model Training for Multimodal Federated Learning,*, *Knowledge-Based Systems* , 2025 (*2nd RRC*)  、
15. **[Third Author]** *Face Anti-Spoofing model with online distillation of local and global features*, Planned resubmission with major extension (initial version submitted to ACMM2025 .

---

## 🎖 Honors & Awards

- 🏅 *2023.06* — Outstanding Undergraduate Graduate, TYUT  
- 🏅 *2023.07* — Outstanding Undergraduate Thesis, TYUT
- 🏅 *2022.05* — “May Fourth” Outstanding Communist Youth League Member, TYUT
- 🏅 *2021.09* —  Excellent Practical Team Member, TYUT
- 🏅 *2021-2024* —  “Internet+” / “Challenge Cup” Innovation Contests — *5× Shanxi Gold, 2× Shanxi Silver
- 🏅 *2022.06* —  12th National “ZhengDa Cup” Market Research Competition — *3rd Prize
- 🏅 *2023.06-present* —  National Scholarship ×1 (Postgrad), 1st-Class Postgrad Scholarship ×2  
- 🏅 *2019.06-2023.06* —  1st-Class Undergrad Scholarship ×6, National Encouragement Scholarship ×3  

## 🎓 Education

- **2019.09 – 2023.07** — B.Eng. in Data Science and Big Data Technology, College of Big Data, TYUT  
- **2023.09 – Present** — M.Eng. in Computer Science and Technology, College of CCST, TYUT  

---

## 🧑‍🎓 Student Leadership & Activities

- **2021.06 – 2023.06** — Head, University Science and Technology Association, TYUT  
- **2021.09 – 2023.06** — TYUT RuinoYun Innovation Base Student Leader  
- **2022.09 – 2023.06** — Committee Member, Undergraduate Party Branch, College of Big Data  

---

## 💬 Research Projects

- **[PI] Multi-domain Visual Feature Fusion for Weakly Supervised Pathology Segmentation**  
  Shanxi Graduate Innovation Project (2024KY232), 09/2024–Present  
  → Designed a dual-stream framework based on Mamba encoder to enhance spatial-frequency modeling for multi-scale lesion detection.

- **[Core Member] High-resolution Kidney Pathology AI Diagnosis System**  
  Shanxi Natural Science Project(General Project), 09/2023–Present  
  → Led MIL model development for lesion segmentation and KW-node recognition with interpretability constraints.

- **[Team Lead] Auxiliary Diagnosis System for Kidney Pathology via Missing-Modality Generation**  
   National Innovation Training Program for College Students, 06/2025–Present 
  → Developed stain transfer pipeline with meta-learning for style consistency and domain generalization.

- **[Team Lead] GAN-based Pathology Stain Quality Enhancement and Evaluation**  
  Shanxi Undergraduate Innovation Project, 06/2022–06/2023  
  → Developed stain transfer pipeline with meta-learning for style consistency and domain generalization.

---

## 🧭 PhD Motivation & Direction

> “愿专注视觉理解，做真正看得懂世界的模型，也做值得被记住的成果。”

During my master's, I’ve built a strong foundation in medical image modeling, weakly-supervised learning, and large vision model tuning. I aim to further explore **explainable, robust and adaptive vision systems** for complex real-world environments.  
In the PhD phase, I hope to:

- Delve into **multimodal and embodied perception**
- Address trustworthiness and generalization in medical AI
- Bridge model-level innovation and real-world application

If you're a professor or lab PI working in related areas, I'm very open to potential collaborations!

---
