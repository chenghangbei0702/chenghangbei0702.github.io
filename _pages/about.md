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

# 🔥 News
- *2022.02*: &nbsp;🎉🎉 Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 

# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ESWA</div><img src='images/GLMKD.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[GLMKD: Joint Global and Local Mutual Knowledge Distillation for Weakly Supervised Lesion Seg‑mentation in Histopathology Images] 

Expert Systems with Applications**（SCI‑1区 TOP）** 1st revision

**Hangbei Cheng**, Xueyu Liu, Jun Zhang, Xiaorong Dong, Xuetao Ma, Yansong Zhang, Hao Meng, Xing Chen, Guanghui Yue, Yidi Li, Yongfei Wu,∗

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

[FMaMIL: FFT enchanced vision Mamba Multi-instance learning for Weakly Supervised Lesion Segmentation in Medical Images] 

IEEE Transactions on Circuits and Systems for Video Technology**（SCI‑1区 TOP \ CCF-B类期刊）** With editor

**Hangbei Cheng** , Xiaorong Dong , Daoxi Cao , Xuehan Zhang , Xinyi Li , Ruolin Zhou , Xueyu Liu ,Yongfei Wu* 

[Paper] | [[**Code**]]([https://github.com/chenghangbei0702/MambaMIL]) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>

**Highlights**
- We propose a novel MIL framework with linear computational complexity, effectively integrating spatial and frequency-domain features to comprehensively capture inter-instance correlations. To our knowledge, this is the first work to incorporate both Mamba and frequencydomain information into MIL.
- We design a learnable frequency-domain feature encoding approach based on Fourier transform and inverse transform. By employing parameterized frequency-domain weights for feature transformation, this method replaces traditional handcrafted filtering approaches, significantly enhancing the model’s expressive capacity.
- We extend the application of bidirectional scanning methods to two-dimensional space, improving Mamba’s ability to understand contextual information in pathological images. Additionally, we integrate a multi-head attentionbased instance-to-bag classifier, further boosting segmentation performance in lesion identification tasks.
</div>
</div>
- 

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

- 
# 💬 Project
- *2024.09- present*, 基于多级特征融合与多域视觉状态空间的数字病理切片弱监督分割模型研究，山西研究生教育创新项目（主持，在研） No.RC2400005593
- *2022.06-2023.06*, 基于生成对抗网络的病理图像染色质量优化与评价技术与系统, 山西省大学生创新训练计划项目（负责）

# 💻 Resume
