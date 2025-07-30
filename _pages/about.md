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

<style>
.badge {
  display: inline-block;
  padding: 2px 8px;
  font-size: 0.75em;
  border-radius: 5px;
  margin-right: 5px;
  color: white;
}
.badge-red { background-color: #d9534f; }
.badge-green { background-color: #5cb85c; }
.badge-warning { background-color: #f0ad4e; }
.badge-info { background-color: #5bc0de; }
.badge-purple { background-color: #613d7c; }
.badge-secondary { background-color: #777; }
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

## 🎓 Education

- **2019.09 – 2023.07** — B.Eng. in Data Science and Big Data Technology, College of Big Data, TYUT  
- **2023.09 – Present** — M.Eng. in Computer Science and Technology, College of CCST, TYUT  

---


## 📝 Publications

> ✍️ *Representative Papers categorized by research direction and status*

---

### 🧠 Medical Image Segmentation & Weak Supervision


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ESWA</div><img src='images/GLMKD.png' alt="GLMKD" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

<p>
<strong>GLMKD:</strong> Joint Global and Local Mutual Knowledge Distillation for Weakly Supervised Lesion Segmentation in Histopathology Images  
<br>
<span style="color:#d9534f;"><strong>Expert Systems with Applications</strong></span>
<span style="color:gray;">(SCI-Q1 TOP, IF=7.5)</span>
<span style="background-color:#5cb85c; color:white; padding:2px 6px; border-radius:4px; font-size:0.75em; vertical-align:middle;">Published</span>  
</p>

<p>Authors: <strong>Hangbei Cheng</strong>, Xueyu Liu, Jun Zhang, Xiaorong Dong, Xuetao Ma, Yansong Zhang, Hao Meng, Xing Chen, Guanghui Yue, Yidi Li, Yongfei Wu*</p>

[Paper](https://www.sciencedirect.com/science/article/pii/S0957417425010474) | [Code](https://github.com/chenghangbei0702/GLMKD-WSSS)

**Highlights:**
- Proposed a novel dual-stream knowledge distillation framework for weakly supervised pathology segmentation.
- Combined global supervision and multi-scale MIL for the first time in WSSS.
- Introduced shape transfer loss for improved global-local feature alignment.

</div></div>

<div class='paper-box'>
  <div class='paper-box-image'>
    <div>
      <div class="badge">MedIA</div>
      <img src='images/MAMBA.png' alt="FMaMIL" width="100%">
    </div>
  </div>
  <div class='paper-box-text' markdown="1">

<p>
<strong>FMaMIL:</strong> FFT-enhanced Vision Mamba Multi-instance Learning for Weakly Supervised Lesion Segmentation in Medical Images  
<br>
<span style="color:#d43f3a;"><strong>Medical Image Analysis</strong></span>
<span style="color:gray;">(SCI-Q1 TOP | CCF-B, IF=10.7)</span>
<span style="background-color:#f0ad4e; color:white; padding:2px 6px; border-radius:4px; font-size:0.75em; vertical-align:middle;">1st RRC</span>
</p>

<p>Authors: <strong>Hangbei Cheng</strong>, Xiaorong Dong, Jia Shen, Xueyu Liu, Jianan Zhang, Xuetao Ma, Mingqiang Wei, Liansheng Wang, Junxin Chen, Yongfei Wu*</p>

[arXiv Paper](https://arxiv.org/abs/2506.07652) | [Code](https://github.com/chenghangbei0702/MambaMIL)

**Highlights:**
- Introduced the first Mamba-based MIL segmentation model with learnable frequency encoding.
- Bidirectional scanning captures contextual pathology structures.
- CAM-guided soft label correction boosts robustness to label noise.

</div>
</div>

---


### 📚 Other Publications

- <strong>First Author</strong>. *SegMind: Dual-Brain Collaboration with Multi-Modal Prompts and Multi-Teacher Knowledge Integration for Semi-Supervised Medical Segmentation*  <span style="color:#2a6496;">AAAI 2026</span> <span style="color:#777;">(CCF-A)</span> <span style="background-color:#f0ad4e; color:white; padding:2px 6px; border-radius:4px; font-size:0.75em;">Submitted</span>

- <strong>First Author</strong>. *FALMIL: Frequency-aware Linear MIL for Efficient Weakly Supervised Lesion Segmentation in Gigapixel Pathology Images*   <span style="color:#2a6496;">PRCV 2025</span> <span style="color:#777;">(CCF-C)</span> <span style="background-color:#f0ad4e; color:white; padding:2px 6px; border-radius:4px; font-size:0.75em;">Submitted</span>

- <strong>Co-First Author</strong>, *DSAGL: Dual-Stream Attention-Guided Learning for Weakly Supervised Whole Slide Image Classification*   <span style="color:#2a6496;">Biomedical Signal Processing and Control (BSPC)</span> <span style="color:#777;">(SCI-Q2)</span> <span style="background-color:#f0ad4e; color:white; padding:2px 6px; border-radius:4px; font-size:0.75em;">1st RRC</span>

- <strong>Second Author:</strong>  *A Dual-branch Network with Cross-scale Feature Interaction and Alignment for WSIs Classification*   <span style="color:#2a6496;">Information Fusion</span> <span style="color:#777;">(SCI-Q1 TOP, IF=15.5)</span> <span style="background-color:#f0ad4e; color:white; padding:2px 6px; border-radius:4px; font-size:0.75em;">With Editor</span>

- <strong>Second Author:</strong>  *Multi-stained Renal Histopathology Image Segmentation via Meta-learning with Guided Collaborative Distillation*   <span style="color:#2a6496;">AAAI 2026</span> <span style="color:#777;">(CCF-A)</span> <span style="background-color:#f0ad4e; color:white; padding:2px 6px; border-radius:4px; font-size:0.75em;">Submitted</span>

- <strong>Second Author:</strong>  *DGMCN: Depth-Guided Multi-modal Collaboration Network for Robust Polyp Segmentation in Endoscopic Images*   <span style="color:#2a6496;">JVCIR</span> <span style="color:#777;">(SCI-Q4)</span> <span style="background-color:#f0ad4e; color:white; padding:2px 6px; border-radius:4px; font-size:0.75em;">1st UR</span>

- <strong>Third Author:</strong> *LEPG-SAM: Local Enhancement Perception and Guidance for Weakly Supervised Medical Image Segmentation*   <span style="color:#2a6496;">To be submitted CMPB</span> <span style="color:#777;">(SCI-Q2)</span>  <span style="background-color:#777; color:white; padding:2px 6px; border-radius:4px; font-size:0.75em;">Manuscript in Preparation</span>

- <strong>Co-author:</strong>  *Fourier Transform-Based Shape Constrained Framework for Generalizable Medical Image Segmentation*   <span style="color:#2a6496;">PRCV 2025</span> <span style="color:#777;">(CCF-C)</span> <span style="background-color:#f0ad4e; color:white; padding:2px 6px; border-radius:4px; font-size:0.75em;">Submitted</span>

- <strong>Co-author:</strong>  *MSMTSeg: Multi-Stained Multi-Tissue Segmentation of Kidney Histology Images via Generative Self Supervised Meta Learning Framework*   <span style="color:#2a6496;">IEEE JBHI</span> <span style="color:#777;">(SCI-Q2 TOP)</span> <span style="background-color:#5cb85c; color:white; padding:2px 6px; border-radius:4px; font-size:0.75em;">Published</span>

- <strong>Co-author:</strong>  *Diagnosis of diabetic kidney disease in whole slide images via AI-driven quantification of pathological indicators*   <span style="color:#2a6496;">CIBM</span> <span style="color:#777;">(SCI-Q2)</span> <span style="background-color:#5cb85c; color:white; padding:2px 6px; border-radius:4px; font-size:0.75em;">Published</span>

---

### 🤖 Multimodal Learning, Federated Security & Embodied AI

- <strong>Co-First Author:</strong> Hangbei Cheng. *AlignBreaker: Multimodal Feature Perturbation Attacks on Embodied AI via Alignment Disruption*    <span style="color:#2a6496;">TBD</span>  <span style="background-color:#777; color:white; padding:2px 6px; border-radius:4px; font-size:0.75em;">In Preparation</span>

- <strong>Third Author:</strong> Hangbei Cheng. *MTSec: AIGC-Enhanced Security Model Training for Multimodal Federated Learning*    <span style="color:#2a6496;">Knowledge-Based Systems</span> <span style="color:#777;">(SCI-Q1 TOP, IF=7.2)</span>    <span style="background-color:#f0ad4e; color:white; padding:2px 6px; border-radius:4px; font-size:0.75em;">2nd RRC</span>

- <strong>Third Author:</strong> Hangbei Cheng. *Face Anti-Spoofing Model with Online Distillation of Local and Global Features*    <span style="color:#2a6496;">ACM MM 2025</span> <span style="color:#777;">(CCF-A)</span>    <span style="background-color:#f0ad4e; color:white; padding:2px 6px; border-radius:4px; font-size:0.75em;">Planned Resubmission</span>

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

## 🎖 Honors & Awards

- 🏅 *2023.06* — Outstanding Undergraduate Graduate, TYUT  
- 🏅 *2023.07* — Outstanding Undergraduate Thesis, TYUT
- 🏅 *2022.05* — “May Fourth” Outstanding Communist Youth League Member, TYUT
- 🏅 *2021.09* —  Excellent Practical Team Member, TYUT
- 🏅 *2021-2024* —  “Internet+” / “Challenge Cup” Innovation Contests — *5× Shanxi Gold, 2× Shanxi Silver
- 🏅 *2022.06* —  12th National “ZhengDa Cup” Market Research Competition — *3rd Prize
- 🏅 *2023.06-present* —  National Scholarship ×1 (Postgrad), 1st-Class Postgrad Scholarship ×2  
- 🏅 *2019.06-2023.06* —  1st-Class Undergrad Scholarship ×6, National Encouragement Scholarship ×3  



## 🧑‍🎓 Student Leadership & Activities

- **2021.06 – 2023.06** — Head, University Science and Technology Association, TYUT  
- **2021.09 – 2023.06** — TYUT RuinoYun Innovation Base Student Leader  
- **2022.09 – 2023.06** — Committee Member, Undergraduate Party Branch, College of Big Data  

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
