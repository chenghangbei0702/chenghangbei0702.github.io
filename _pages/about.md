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
p, ul, ol {
  margin-bottom: 1.2em;
}
h2, h3 {
  margin-top: 2em;
  margin-bottom: 1em;
}
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

Ph.D. Student (Class of 2026)

[School of Computer Science and Technology](https://cs.bit.edu.cn/), [Beijing Institute of Technology (BIT)](https://www.bit.edu.cn/)

Advisor: [Prof. Ying Fu](https://ying-fu.github.io/)

*Previously, I obtained my Master's degree (Class of 2023) and Bachelor's degree (Class of 2019)  from [Taiyuan University of Technology (TYUT)](https://www.tyut.edu.cn/), where I was fortunate to be advised by [Assoc. Prof. Yongfei Wu](https://tylgswyxgc.tyut.edu.cn/info/1411/5135.htm) and [Assoc. Prof. Xueyu Liu](https://xueyuliu.github.io) at [IMBR Lab](https://lab.rjmart.cn/10579/3146DDB7959849F4).*

📫 **Contact**: [chenghangbei0702@163.com](mailto:chenghangbei0702@163.com) 

🔗 **Links**: [GitHub](https://github.com/chenghangbei0702)

---

<span class='anchor' id='research-interests'></span>
## 🔍 Research Interests

My research focuses on **Data-Efficient Learning, Generative AI, and Decision-Making Systems** in medical scenarios, aiming to build robust and intelligent medical AI. Specifically:

- **Medical Image Analysis & Generation (Low-Resource)**  
  → Weakly/semi-supervised segmentation, shape prior modeling, and high-fidelity image synthesis using latent diffusion models.

- **Multi-modal Foundation Models & Disease Diagnosis**  
  → Leveraging large vision-language models (e.g., CLIP, Med-SAM) for domain adaptation, semantic alignment, and automated clinical diagnosis.

- **Embodied Intelligence & Multi-agent Systems (Exploratory)**  
  → Exploring advanced decision-making, clinical reasoning, and collaborative robustness in multi-agent medical environments.
  
---
<span class='anchor' id='news'></span>

## 📢 News

<div style="height: 220px; overflow-y: auto; border: 1px solid #e1e4e6; border-radius: 6px; padding: 12px; background-color: #fafbfc; line-height: 1.8;">
  <ul style="padding-left: 20px; margin: 0; list-style-type: disc;">
    <li><strong>[2026.09]</strong> 🎓 I officially started my Ph.D. journey at <strong>Beijing Institute of Technology (BIT)</strong>!</li>
    <li><strong>[2026.06]</strong> 🎉 One paper was published by <strong>BSPC</strong>!</li>
    <li><strong>[2026.06]</strong> 🎓 I successfully graduated from Taiyuan University of Technology (TYUT) and obtained my Master's degree!</li>
    <li><strong>[2026.06]</strong> 🎉 One paper was accepted by <strong>MICCAI 2026</strong>!</li>
    <li><strong>[2026.06]</strong> 🎉 One paper was published by <strong>IEEE JBHI</strong>!</li>
    <li><strong>[2026.05]</strong> 🎉 One paper was published by <strong>EAAI</strong>!</li>
    <li><strong>[2026.03]</strong> 🎉 Our paper was published in <strong>Pattern Recognition</strong>.</li>
    <li><strong>[2026.03]</strong> 🎉 Our paper was accepted in <strong>WWW 2026</strong>.</li>
    <li><strong>[2025.11]</strong> 🎉 Our paper was published in <strong>KBS</strong>.</li>
    <li><strong>[2025.09]</strong> 🏆 I was deeply honored to receive the <strong>National Scholarship</strong> (Top 1%).</li>
    <li><strong>[2026.03]</strong> 🎉 Our paper was accepted in <strong>PRCV 2025</strong>.</li>
    <li><strong>[2025.03]</strong> 🎉 Our paper was published in <strong>Expert Systems with Applications</strong>.</li>
    <li><strong>[2024.08]</strong> 📝 Our project was funded by the <strong>Shanxi Graduate Innovation Project</strong>.</li>
    <li><strong>[2023.06]</strong> 🎓 I successfully graduated from Taiyuan University of Technology (TYUT) and obtained my Bachelor's degree!</li>
  </ul>
</div>

---
<span class='anchor' id='publications'></span>
## 📝 Publications

### 📅 2026
*   📢 Yansong Zhang, <u>Hangbei Cheng</u>, Jianan Zhang, Guangze Shi, Xueyu Liu, Lijie Shi, Junxin Chen, Yongfei Wu. Automatic Prompt Generation via Reinforcement Learning Guided Contrastive Purification for Label-Free SAM Segmentation[J]. Biomedical Signal Processing and Control<span style="color:#2a6496;">(**BSPC**)</span>, 2026.<span style="color:#d9534f;">(SCI-Q2 TOP)</span> <span style="color:#5cb85c; font-size:0.9em;">[Second Author]</span>  [[Paper]()] [[Code](https://github.com/yufei050201/CSGE)]

*   📢 Yufei Wan†, <u>Hangbei Cheng†</u>, Danchen Cui, Junran Li, Jiahui Jiang, Junxin Chen, Mingqiang Wei, Xueyu Liu, Yongfei Wu. CSGE:Break the SSL Bottleneck in Medical Image Segmentation via Collaborative Semantic-Geometric Experts[C]. 29th INTERNATIONAL CONFERENCE ON MEDICAL IMAGE COMPUTING
AND COMPUTER ASSISTED INTERVENTION <span style="color:#2a6496;">(**MICCAI 2026**)</span>, 2026.<span style="color:#d9534f;">(CCF-B)</span> <span style="color:#5cb85c; font-size:0.9em;">[Co-First Author]</span>  [[Paper]()] [[Code](https://github.com/yufei050201/CSGE)]

*   📢 Daoxi Cao†, <u>Hangbei Cheng†</u>, Yijin Li, Ruolin Zhou, Xuehan Zhang, Xinyi Li, Binwei Li, Xuancheng Gu, Jianan Zhang, Xueyu Liu, Yongfei Wu. Dual-stream attention-guided learning for weakly supervised whole slide image classification[J].Engineering Applications of Artificial Intelligence <span style="color:#2a6496;">(**EAAI**)</span>, 2026, 181: 115272.<span style="color:#d9534f;">(SCI-Q1 TOP)</span> <span style="color:#5cb85c; font-size:0.9em;">[Co-First Author]</span>  [[Paper](https://www.sciencedirect.com/science/article/abs/pii/S0952197626015563)] [[Code]()]

*   📢 Jianan Zhang, <u>Hangbei Cheng</u>, Xueyu Liu, Feixue Shao, Junxin Chen, Guanghui Yue, Yongfei Wu, Weihua Yang. A Dual-branch Network with Cross-scale Feature Interaction and Alignment for Weakly Supervised Whole Slide Image Analysis[J]. IEEE Journal of Biomedical and Health Informatics<span style="color:#2a6496;">(**IEEE JBHI**)</span>, 2026.<span style="color:#d9534f;">(新锐Q1-Top, SCI-Q2 TOP)</span> <span style="color:#5cb85c; font-size:0.9em;">[Second Author]</span>  [[Paper](https://ieeexplore.ieee.org/abstract/document/11557133)] [[Code]()]

*   📢 <u>Hangbei Cheng</u>, Xiaorong Dong, Jia Shen, Guangze Shi, Xueyu Liu, Jianan Zhang, Xuetao Ma, Mingqiang Wei, Liansheng Wang, Junxin Chen, Yongfei Wu. FMaMIL: Synergistic spatial-frequency Mamba multi-instance learning for weakly supervised pathology lesion segmentation[J]. Pattern Recognition<span style="color:#2a6496;">(**PR**)</span>, 2026: 113442.<span style="color:#d9534f;">(SCI-Q1 TOP, CCF-B)</span> <span style="color:#5cb85c; font-size:0.9em;">[First Author]</span>  [[Paper](https://www.sciencedirect.com/science/article/abs/pii/S0031320326004085)] [[Code]()]

*   📢 Zhihui Zhao, Xiaorong Dong, Yaowen Zheng, Xiaohui Chen, Yimo Ren, <u>Hangbei Cheng</u>, Yongle Chen, Limin Sun. Breaking Cross-modal Alignment in Embodied Intelligence: A Multimodal Adversarial Attack Framework for Vision-Language-Action Models[C]. Proceedings of the ACM Web Conference 2026<span style="color:#2a6496;">(**WWW 2026**)</span>, 2026: 2824-2834.<span style="color:#d9534f;">(CCF-A)</span> <span style="color:#5cb85c; font-size:0.9em;">[Co-author]</span>  [[Paper](https://dl.acm.org/doi/abs/10.1145/3774904.3792315)] [[Code]()]

### 📅 2025
*   📢 Xiaorong Dong, Zhihui Zhao, <u>Hangbei Cheng</u>, Yimo Ren, Dan Yu, Yongle Chen. MTSec: AIGC-Enhanced Security Model Training for Multimodal Federated Learning[J]. Knowledge-Based Systems<span style="color:#2a6496;">(**KBS**)</span>, 2025: 114748.<span style="color:#d9534f;">(SCI-Q1 TOP)</span> <span style="color:#5cb85c; font-size:0.9em;">[Third Author]</span>  [[Paper](https://www.sciencedirect.com/science/article/abs/pii/S0950705125017861)] [[Code]()]

*   📢 Jia Shen, Jun Zhang, Xueyu Liu, Yunfei Zhang, Guangze Shi, Feixue Shao, <u>Hangbei Cheng</u>, Yongfei Wu. Fourier Transform-Based Shape Constrained Framework for Generalizable Medical Image Segmentation[C]. Chinese Conference on Pattern Recognition and Computer Vision<span style="color:#2a6496;">(**PRCV 2025**)</span>, Singapore: Springer Nature Singapore, 2025: 295-309. <span style="color:#d9534f;">(CCF-C)</span> <span style="color:#5cb85c; font-size:0.9em;">[Co-author]</span>  [[Paper](https://link.springer.com/chapter/10.1007/978-981-95-5634-2_21)] [[Code]()]

*   📢 <u>Hangbei Cheng</u>, Xueyu Liu, Jun Zhang, Xiaorong Dong, Xuetao Ma, Yansong Zhang, Hao Meng, Xing Chen, Guanghui Yue, Yidi Li, Yongfei Wu. GLMKD: Joint global and local mutual knowledge distillation for weakly supervised lesion segmentation in histopathology images[J]. Expert Systems with Applications<span style="color:#2a6496;">(**ESWA**)</span>, 2025, 279: 127425. <span style="color:#d9534f;">(SCI-Q1 TOP)</span> <span style="color:#5cb85c; font-size:0.9em;">[First Author]</span>  [[Paper](https://www.sciencedirect.com/science/article/abs/pii/S0957417425010474)] [[Code]()]

### 📅 2024
*   📢  Xueyu Liu, Rui Wang, Yexin Lai, Yongfei Wu, <u>Hangbei Cheng</u>, Yuanyue Lu, Jianan Zhang, Ning Hao, Chenglong Ban, Yanru Wang, Shuqin Tang, Yuxuan Yang, Ming Li, Xiaoshuang Zhou, Wen Zheng. MSMTSeg: Multi-Stained Multi-Tissue Segmentation of Kidney Histology Images via Generative Self Supervised Meta Learning Framework. IEEE Journal of Biomedical and Health Informatics<span style="color:#2a6496;">(**IEEE JBHI**)</span>, 2024. <span style="color:#d9534f;">**(新锐Q1-Top | SCI-Q2 TOP)**</span> <span style="color:#5cb85c; font-size:0.9em;">[Co-author]</span>  [[Paper](https://ieeexplore.ieee.org/abstract/document/10478171)] [[Code]()]

### 📅 2023
*   📢 Xueyu Liu, Yongfei Wu, Yilin Chen, Dongna Hui, Jianan Zhang, Fang Hao, Yuanyue Lu, <u>Hangbei Cheng</u>, Yue Zeng, Weixia Han, Chen Wang, Ming Li, Xiaoshuang Zhou, Wen Zheng. Diagnosis of diabetic kidney disease in whole slide images via AI-driven quantification of pathological indicators. Computers in Biology and Medicine<span style="color:#2a6496;">(**CIBM**)</span>, 2023, 166: 107470. <span style="color:#d9534f;">**(SCI-Q2)**</span> <span style="color:#5cb85c; font-size:0.9em;">[Co-author]</span>  [[Paper](https://www.sciencedirect.com/science/article/abs/pii/S0010482523009356)] [[Code]()]

---

<span class='anchor' id='projects'></span>

## 💬 Research Projects

*   **[Core Member]** *"Knowledge-Driven Collaborative Analysis of Multi-Stained Pathology Images and Intelligent Diagnosis of Chronic Kidney Disease."*  
    National Natural Science Foundation of China (NSFC, General Program, No. 62572339) | *01/2026 – 12/2029*  
    → Focus on integrating clinical knowledge priors with multi-modal learning architectures to enhance joint representation and multi-stained diagnostic robustness.

*   **[Team Lead]** *"Auxiliary Diagnosis System for Kidney Pathology via Missing-Modality Generation."*  
    National Innovation Training Program for College Students | *06/2025 – Present*  
    → Developed a generative pipeline utilizing conditional diffusion models to synthesize missing imaging modalities, enhancing multi-modal diagnostic accuracy.

*   **[Principal Investigator (PI)]** *"Multi-domain Visual Feature Fusion for Weakly Supervised Pathology Segmentation."*  
    Shanxi Graduate Innovation Project (No. 2024KY232) | *09/2024 – 06/2026*  
    → Designed a dual-stream framework based on Vision Mamba to enhance spatial-frequency modeling for multi-scale lesion detection.

*   **[Core Member]** *"Intelligent Auxiliary Diagnosis of Kidney Diseases Based on Ultra-High Resolution WSIs."*  
    Shanxi Natural Science Foundation (General Program) | *01/2024 – 12/2026*  
    → Led the development of interpretable Multi-Instance Learning (MIL) models for whole-slide lesion segmentation and classification.

*   **[Team Lead]** *"GAN-based Pathology Stain Quality Enhancement and Evaluation."*  
    Shanxi Undergraduate Innovation Project | *06/2022 – 06/2023*  
    → Developed a stain transfer pipeline with meta-learning for style consistency and domain generalization across multi-center datasets.

---
<span class='anchor' id='education'></span>
## 🎓 Education

- **2026.09 – Present** — Ph.D. in Computer Science and Technology, School of Computer Science and Technology, [BIT](https://www.bit.edu.cn/).
- **2023.09 – 2026.06** — M.Eng. in Computer Science and Technology, College of Computer Science and Technology, [TYUT](https://www.tyut.edu.cn/).
- **2019.09 – 2023.07** — B.Eng. in Data Science and Big Data Technology, College of Big Data, [TYUT](https://www.tyut.edu.cn/).


---

<span class='anchor' id='honors-awards'></span>
## 🏆 Honors & Awards

### 📑 Academic & Merit Scholarships
*   🏅 **National Scholarship for Graduate Students**, Ministry of Education, China, 2025
*   🏅 **Outstanding Graduate Student**, TYUT, 2025
*   🏅 **First-Class Academic Scholarship for Graduate Students** (×3), TYUT, 2024, 2025, 2026
*   🏅 **Outstanding Undergraduate Thesis**, TYUT, 2023
*   🏅 **Outstanding Undergraduate Graduate**, TYUT, 2023
*   🏅 **National Encouragement Scholarship** (×3), Ministry of Education, China, 2019 – 2023
*   🏅 **First-Class Academic Scholarship for Undergraduate Students** (×6), TYUT, 2019 – 2023

### 🚀 Research & Innovation Competitions
*   🏅 **"Internet+" & "Challenge Cup" Innovation Contests**, *5× Provincial Gold Awards, 2× Provincial Silver Awards*, 2021 – 2024
*   🏅 **The 12th National "ZhengDa Cup" Market Research Competition**, *National 3rd Prize*, 2022

### 🤝 Leadership & Student Honors
*   🏅 **"May Fourth" Outstanding Youth Leadership Award**, TYUT, 2022
*   🏅 **Excellent Social Practice Award**, TYUT, 2021

---

<span class='anchor' id='student-leadership'></span>
## 🧑‍🎓 Student Leadership & Activities

- **2021.06 – 2023.06** — Head, University Science and Technology Association, TYUT  
- **2021.09 – 2023.06** — TYUT RuinoYun Innovation Base Student Leader  
- **2022.09 – 2023.06** — Committee Member, Undergraduate Party Branch, College of Big Data  

---

<span class='anchor' id='collaborations-exchange'></span>
## 💬 Looking for Collaborations & Exchanges
I am always open to academic discussions, potential research collaborations, or just a friendly chat about AI and medical imaging! If you are interested in my research directions, feel free to drop me an email or open an issue on my GitHub. Let's work together to build models that truly understand the world! 🌟

---
