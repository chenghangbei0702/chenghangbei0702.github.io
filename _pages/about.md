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

**🧍‍♂️ Biography ---Cheng Hangbei (成航北)**

I am a master's student (Class of 2023) at [School of CCST](https://ccst.tyut.edu.cn/), [Taiyuan University of Technology (TYUT)](https://www.tyut.edu.cn/), under the supervision of [**Associate Professor Wu Yongfei**](https://tylgswyxgc.tyut.edu.cn/info/1411/5135.htm). I am a member of the [TYUT Intelligent Medicine and Biometric Laboratory (IMBR)](https://lab.rjmart.cn/10579/3146DDB7959849F4), and my research primarily focuses on intelligent analysis of medical images, with key interests in:

-  **Intelligent Lesion Segmentation in Pathological Images** 
-  **Segmentation of Incompletely or Imprecisely Labeled Medical Images** 
-  **Research and Applications of Large Medical Vision Models** 

Additionally, I have experience in **federated learning security defenses** and **face anti-spoofing**, particularly in their applications for medical privacy protection and biometric recognition. 
Recently, I have been interested in the application of **embodied intelligence in the medical field** and am actively exploring ways to advance the integration of intelligent medical imaging into clinical practice.

If you are interested in my research or potential collaborations, feel free to contact me via the provided details!

[Email](chenghangbei0702@163.com) / [Github](https://github.com/chenghangbei0702) 

# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ESWA</div><img src='images/GLMKD.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

1. [**GLMKD: Joint Global and Local Mutual Knowledge Distillation for Weakly Supervised Lesion Seg‑mentation in Histopathology Images**](https://www.sciencedirect.com/science/article/pii/S0957417425010474)

Expert Systems with Applications**(SCI‑Q1 TOP, IF=7.6)**  Accept

**Hangbei Cheng**, Xueyu Liu, Jun Zhang, Xiaorong Dong, Xuetao Ma, Yansong Zhang, Hao Meng, Xing Chen, Guanghui Yue, Yidi Li, Yongfei Wu∗

[Paper] | [[**Code**]]([https://github.com/chenghangbei0702/GLMKD-WSSS]) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>

**Highlights**
- A novel weakly-supervised segmentation framework is proposed to enhance lesion delineation in digital pathology images by integrating global and local information.
- This study is the first to combine global supervisory information and multi-scale MIL via dual-stream knowledge distillation in a WSSS framework.
- A multi-scale multi-instance learning model (MMIL) is designed to capture subtle variations in lesions across different scales.
- A shape transfer loss function is introduced to facilitate effective information exchange between global and local contexts during the dual-flow mutual knowledge distillation (MKD) segmentation phase.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TCSVT</div><img src='images/MAMBA.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

2. FMaMIL: FFT-enhanced Vision Mamba Multi-instance Learning for Weakly Supervised Lesion Segmentation in Medical Images

Medical Image Analysis(**（SCI‑Q1 TOP \ CCF-B, Top Medical Journal, IF=10.7）** 1st Under Review

**Hangbei Cheng** , Xiaorong Dong, Jia Shen, Xueyu Liu, Jianan Zhang, Xuetao Ma, Mingqiang Wei, Liansheng Wang, Junxin Chen, Yongfei Wu*

[Paper] | [[**Code**]]([https://github.com/chenghangbei0702/MambaMIL]) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>

**Highlights**
- We propose FMaMIL, the first Mamba-based MIL framework enhanced with learnable frequency-domain encoding for weakly supervised lesion segmentation using only image-level labels.
- A bidirectional spatial scanning strategy is introduced to model contextual structures in pathology images more effectively.
- A CAM-guided pseudo-label refinement strategy with soft supervision and self-correction enhances segmentation under label noise.
- Our method achieves state-of-the-art segmentation performance on both public and private histopathology datasets without relying on pixel-level annotations.
</div>
</div>

3. **[First Author]** FALMIL: Frequency-aware Linear MIL for Efficient Weakly Supervised Lesion Segmentation in Gigapixel Pathology Images, Pattern Recognition and Computer Vision (PRCV) (CCF-C Conference), 2025 (Submitted)
4. [Second Author] A Dual-branch Network with Cross-scale Feature Interaction and Alignment for Weakly Supervised Whole Slide Image Classification, Information Fusion (SCI-Q1 TOP, IF=15.5), 2025 (With Editor)
5. [Second Author / Undergraduate Advisor] DSAGL: Dual-Stream Attention-Guided Learning for Weakly Supervised Whole Slide Image Classification, Biomedical Signal Processing and Control (SCI-Q2, IF=4.9), 2025 (1st Under Review)
6. [Third Author / First Author is Supervisor] MTSec: AIGC-Enhanced Security Model Training for Multimodal Federated Learning, Knowledge-Based Systems (SCI-Q1 TOP, IF=7.2), 2025 (2nd RRC)
7. [Third Author] Face Anti-Spoofing Model with Online Distillation of Local and Global Features, ACM International Conference on Multimedia (CCF-A Conference), 2025 (Rebuttal, Avg. Score: 5.8)
8. [Third Author / Undergraduate Advisor] LEPG-SAM: Local Enhancement Perception and Guidance for Weakly Supervised Medical Image Segmentation, Computer Methods and Programs in Biomedicine (SCI-Q2, IF=4.8), 2025(With Editor)
9. [Second Author / Undergraduate Advisor] DGMCN: Depth-Guided Multi-modal Collaboration Network for Robust Polyp Segmentation in Endoscopic Images, JVCIR (CCF-C Journal, IF=3.1), 2025 (1st Under Review)
10. [Co-author] Fourier Transform-Based Shape Constrained Framework for Generalizable Medical Image Segmentation, PRCV (CCF-C Conference), 2025 (Submitted)
11. [Co-author] MSMTSeg: Multi-Stained Multi-Tissue Segmentation of Kidney Histology Images via Generative Self-Supervised Meta Learning Framework, IEEE JBHI (SCI-Q2 TOP, IF=6.7), 2024 (Published)
12. [Co-author] Diagnosis of Diabetic Kidney Disease in Whole Slide Images via AI-driven Quantification of Pathological Indicators, Computers in Biology and Medicine (SCI-Q2 TOP, IF=7.0), 2023 (Published)

# 🎖 Honors and Awards
- *2023.06* Outstanding undergraduate graduates of Taiyuan University of Technology
- *2022.05* Taiyuan University of Technology May Fourth Commendation "Outstanding Communist Youth League Member"
- *2023.07* Outstanding Undergraduate Thesis of Taiyuan University of Technology

# 📖 Educations
- **2019.09 - 2023.07**: B.ENG. Major in Data Science and Big Data Technology, College of Big Data, Taiyuan University of Technology, China
- **2023.09 - present**: M.ENG. Major in Computer Science and Technology, College of Computer Science and Technology (College of Big Data) , Taiyuan University of Technology, China

# 📖 Student work
- **2021.06 - 2023.06**: 大学生科学技术协会负责人，大数据学院，太原理工大学（2022、2023届优秀大学生科学技术协会）
- **2021.09 - 2023.06**: TYUT睿诺云双创项目孵化基地本科生负责人，太原理工大学双创项目实践孵化基地
- **2022.09 - 2023.06**: 大数据本科党支部支部委员会

  
# 💬 Project
- *2024.09- present*, 基于多级特征融合与多域视觉状态空间的数字病理切片弱监督分割模型研究，山西研究生教育创新项目（主持，在研） No.2024KY232
- *2022.06-2023.06*, 基于生成对抗网络的病理图像染色质量优化与评价技术与系统, 山西省大学生创新训练计划项目（负责/引领）
- *2025.06-present*, 基于缺失染色模态生成的肾脏病理图像分割辅诊系统, 全国大学生创新训练计划项目（负责/引领）
- *2023.09-present*, 基于超高分辨病理 WSIs 的肾病智能辅助诊断技术研究, 山西省自然科学研究项目-面上项目（核心成员）
  
# 💻 
