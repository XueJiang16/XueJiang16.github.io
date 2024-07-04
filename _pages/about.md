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

Hi, I am Xue Jiang, a joint Ph.D. student at Trustworthy Machine Learning and Reasoning (TMLR) Group in Department of Computer Science, Hong Kong Baptist University, advised by [Dr. Bo Han](https://bhanml.github.io/) and Southern University of Science and Technology, advised by [Prof. Feng Zheng](https://faculty.sustech.edu.cn/?tagid=fengzheng&iscss=1&snapid=1&orderby=date&go=1&lang=en). In TMLR Group, I am also co-supervised by [Dr. Feng Liu](https://fengliu90.github.io/index.html) and work closely with [Dr. Zhen Fang](https://fang-zhen.github.io/).

My research interests mainly include **out-of-distribution detection, object hallucination in MLLM, and saftety in diffusion models**.

*Please feel free to [email me](mailto:csxjiang@comp.hkbu.edu.hk) for research, collaborations, or a casual chat.* 

<!-- *Please consider giving me [anonymous feedback](https://docs.google.com/forms/d/e/1FAIpQLSeE4_y14QlUtJ8MhltnGnWwco7J1sWprXnlGoFWFo002k26lw/viewform?usp=sf_link).* -->

<!-- # 📣 News
- **$\frak{2024.05}$**: One paper is accepted by [ICML 2024](https://icml.cc/virtual/2024/poster/33444). -->

# 📖 Educations
- *2022.09 - present*, Southern University of Science and Technology (SusTech) & Hong Kong Baptist University (HKBU), Ph.D. in Computer Science.
- *2019.09 – 2022.06*, Wuhan University, M.E. in Computer Science.
- *2015.09 - 2019.06*, Wuhan University, B.E. in Electronic Information Engineering.

<!-- # 📝 Featured Publications
TODO -->

# 📝 Publications
✉️ Corresponding author.

<div class='paper-box'><div class='paper-box-image'><div><img src='/_pages/data/figures/neg_label_fig1.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">


[![Static Badge](https://img.shields.io/badge/Conference-ICLR'24-blue)]() *Spotlight (Accept rate: 5%)* **Negative Label Guided OOD Detection with Pretrained Vision-Language Models**. 
[[paper]](https://arxiv.org/pdf/2403.20078)
[[code]](https://github.com/tmlr-group/NegLabel)

<!-- [[slides]](https://drive.google.com/file/d/1tsftBBdy6YfqIeap_QJ-kh1Ut7sqmdRb/view?usp=sharing) -->
<!-- [[poster]]() -->
<!-- [[CN-video]](https://www.bilibili.com/video/BV1k4421X7zK/?spm_id_from=333.1007.top_right_bar_window_dynamic.content.click&vd_source=a1aae47e2835186f922fa2e1c94933c9)   -->
  **Xue Jiang**, Feng Liu, Zhen Fang, Hong Chen, Tongliang Liu, Feng Zheng✉️, Bo Han.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><img src='/_pages/data/figures/lt_ood.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[![Static Badge](https://img.shields.io/badge/Conference-ICML'23-blue)]() **Detecting out-of-distribution data through in-distribution class prior**. 
[[paper]](https://proceedings.mlr.press/v202/jiang23e/jiang23e.pdf)
[[code]](https://github.com/tmlr-group/class_prior)

<!--[[slides]](/_pages/data/slides-neural-atoms.pdf)
[[poster]](/_pages/data/poster-neural-atoms.pdf)
[[EN-video]](https://recorder-v3.slideslive.com/?share=92308&s=8e966150-4ba4-41b7-97d3-8ed0c1a1cd0c)
[[CN-video]](https://www.bilibili.com/video/BV1qH4y1L7mb/?share_source=copy_web&vd_source=65ec14228a98f635bf0406f14c7f8660&t=5342)-->  
 **Xue Jiang**, Feng Liu, Zhen Fang, Hong Chen, Tongliang Liu, Feng Zheng✉️, Bo Han.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><img src='/_pages/data/figures/aaai.jpg' alt="sym" width="80%"></div></div>
<div class='paper-box-text' markdown="1">

[![Static Badge](https://img.shields.io/badge/Conference-AAAI'23-blue)]() **On the stability and generalization of triplet learning**.
[[paper]](https://arxiv.org/pdf/2302.09815)
<!-- [[code]](https://github.com/tmlr-group/class_prior) -->
<!--[[slides]](/_pages/data/slides-neural-atoms.pdf)
[[poster]](/_pages/data/poster-neural-atoms.pdf)
[[EN-video]](https://recorder-v3.slideslive.com/?share=92308&s=8e966150-4ba4-41b7-97d3-8ed0c1a1cd0c)
[[CN-video]](https://www.bilibili.com/video/BV1qH4y1L7mb/?share_source=copy_web&vd_source=65ec14228a98f635bf0406f14c7f8660&t=5342)-->  
 Jun Chen, Hong Chen✉️,  **Xue Jiang**, Bin Gu, Weifu Li, Tieliang Gong, Feng Zheng
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><img src='/_pages/data/figures/kd.jpg' alt="sym" width="80%"></div></div>
<div class='paper-box-text' markdown="1">

[![Static Badge](https://img.shields.io/badge/Conference-CVPR'22-blue)]() **Cross-image relational knowledge distillation for semantic segmentation**. 
[[paper]](https://openaccess.thecvf.com/content/CVPR2022/papers/Yang_Cross-Image_Relational_Knowledge_Distillation_for_Semantic_Segmentation_CVPR_2022_paper.pdf)
[[code]](https://github.com/winycg/CIRKD)
<!--[[slides]](/_pages/data/slides-neural-atoms.pdf)
[[poster]](/_pages/data/poster-neural-atoms.pdf)
[[EN-video]](https://recorder-v3.slideslive.com/?share=92308&s=8e966150-4ba4-41b7-97d3-8ed0c1a1cd0c)
[[CN-video]](https://www.bilibili.com/video/BV1qH4y1L7mb/?share_source=copy_web&vd_source=65ec14228a98f635bf0406f14c7f8660&t=5342)-->  
 Chuanguang Yang, Helong Zhou, Zhulin An✉️, **Xue Jiang**, Yongjun Xu, Qian Zhang
</div>
</div>

# 🎖 Awards
- Best Research Performance Award, HKBU 2024.05.
- Research Excellence Award, HKBU 2023.11.
- Excellent Postgraduate, Wuhan University 2020.
- 2nd Prize Excellent Academic Scholarship, Wuhan University 2020.
- Meritorious Winner (9\%), The Interdisciplinary Contest in Modeling 2018.
- Excellent Student, Wuhan University 2016 & 2017.
- 3rd Prize Scholarship, Wuhan University 2016 & 2017.


<!--💬 Talks
- *2024.06*, Youth PhD Talk on Trustworthy Machine Learning @AI Time, Online.
[[Video]](https://www.bilibili.com/video/BV1ag4y1Q7ye/?t=7945)-->

# 💻 Services
- Conference Reviewer for ICML (22-24), NeurIPS (22-24), ICLR (22-24), MM 24.
- Journal Reviewer for TMLR, TNNLS, JAIR.

# 🏫 Teaching
- *2024 Spring*, TA for CS308: Computer Vision, SusTech.
- *2023 Fall*, TA for CS205: C/C++ Program Design, SusTech.
- *2019 Fall*, TA for Fundamentals of circuit and electronics, WHU.

# 📖 Experiences
- *2021.05 - 2021.12*, Internship @Horizon Robotics, focusing on self-supervised learning related to object detection.

  
<!-- <div align=center> -->
<!-- <a href='https://clustrmaps.com/site/1byjf'  title='Visit tracker'><img src='//clustrmaps.com/map_v2.png?cl=080808&w=400&t=tt&d=EuVM39DBt0G0cQJh20EJFBL7BHU5A5hzsTXUdCbe7Ic&co=ffffff&ct=808080'/></a> -->
<!--<a href='https://clustrmaps.com/site/1byjf'  title='Visit tracker'><img src='//clustrmaps.com/map_v2.png?cl=080808&w=a&t=m&d=EuVM39DBt0G0cQJh20EJFBL7BHU5A5hzsTXUdCbe7Ic&co=ffffff&ct=808080'/></a>-->
<!-- <a href="https://clustrmaps.com/site/1bztd" title="Visit tracker"><img src="//www.clustrmaps.com/map_v2.png?d=9WmKAuGZx-jp_Cqemh_qyo-Fhw-l77tju_9bukYAC-o&cl=ffffff"></a> -->
<a href="https://clustrmaps.com/site/1c0c2"  title="Visit tracker"><img src="//www.clustrmaps.com/map_v2.png?d=7PdXNU2gYycCDZGFXoFEuLh8gRdIoqAFS1CtitbXK0g&cl=ffffff" /></a>
<!-- </div> -->
