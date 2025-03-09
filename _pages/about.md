![image](https://github.com/user-attachments/assets/eefc6604-98de-4fa5-a368-b3cbdf6ee1d2)---
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

I am currently a Postdoctoral Researcher at the School of Vehicle and Mobility, Tsinghua University, where I am dedicated to developing trustworthy AI systems for real-world autonomous driving. My research focuses on data-driven planners(including end-to-end approaches), reinforcement learning, and continual learning.

I earned my Ph.D. from the School of Vehicle and Mobility, Tsinghua University, advised by Professor Yang Diange. My doctoral research introduced an online continual learning planner for autonomous vehicles, addressing the challenge of ensuring system performance in long-tail cases. This technology was successfully demonstrated during the autonomous driving operations at the Shougang Park venue for the 2022 Beijing Winter Olympics.

Currently, I am collaborating with leading companies such as DiDi Autonomous Driving, Toyota, and Dongfeng to apply my research outcomes to mass-produced autonomous driving systems. In 2024, I led my team to win the Mcity AV Challenge in the United States. My contributions have also been recognized with the Outstanding Doctoral Paper Presentation Award at the China Society of Automotive Engineers Doctoral Forum and the prestigious Tsinghua University "Shuimu Scholar" Postdoctoral Fellowship.

If you are seeking any form of academic cooperation, please feel free to email me at zhouwt@mail.tsinghua.edu.cn. 


# 🔥 News
- *2025.03*: Our preprint paper for low-cost large scale autonomous driving is now online.
- *2024.09*: &nbsp;🎉🎉 We won the Mcity AV Challenge. The autonomous vehicle equipped with our algorithm did not collide during the entire competition.
- *2023.03*: Our paper on continual learning of autonomous vehicle was published in Nature Machine Intelligence. 

# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IEEE Trans-ITS</div><img src='images/dcp.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Dynamically conservative self-driving planner for long-tail cases](https://arxiv.org/pdf/2305.07497)

**Weitao Zhou**, Zhong Cao, Nanshan Deng, Xiaoyu Liu, Kun Jiang, Diange Yang


- This work proposes a method to automatically adjust the conservative level of self-driving vehicles according to each case’s “long-tail” rate, which provides a technique to guarantee 
 performance in unexpected driving cases without resorting to a global conservative setting. 
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IEEE Trans-ITS</div><img src='images/ubrl.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Identify, estimate and bound the uncertainty of reinforcement learning for autonomous driving](https://arxiv.org/pdf/2305.07487)

**Weitao Zhou**, Zhong Cao, Nanshan Deng, Kun Jiang, Diange Yang

<!--
[**Project**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=DhtAFkwAAAAJ&citation_for_view=DhtAFkwAAAAJ:ALROH1vI_8AC) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
-->

-  The proposed planner can estimate and constrain performance uncertainty by itself, which quantifies potential performance drop due to insufficient training data or
network fitting errors. 
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Nature Machine Intelligence</div><img src='images/nmi.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Continuous improvement of self-driving cars using dynamic confidence-aware reinforcement learning](https://www.nature.com/articles/s42256-023-00610-y)

 Zhong Cao, Kun Jiang, **Weitao Zhou**, Shaobing Xu, Huei Peng, Diange Yang

[**Project**](https://github.com/zhcao92/DCARL) 
- We present a dynamic confidence-aware reinforcement learning (DCARL) technology for guaranteed continuous improvement. Continuously improving means that more training always improves or maintains its current performance. Our technique enables performance improvement using the data collected during driving, and does not need a lengthy pre-training phase. 
</div>
</div>

- [Dynamically Local-Enhancement Planner for Large-Scale Autonomous Driving](https://arxiv.org/pdf/2502.21134), Nanshan Deng, **Weitao Zhou**, , Bo Zhang, Junze Wen, Kun Jiang, Zhong Cao, Diange Yang, **Preprint**

- [Long-Tail Prediction Uncertainty Aware Trajectory Planning for Self-driving Vehicles](https://arxiv.org/pdf/2207.00788), **Weitao Zhou**, Zhong Cao, Yunkang Xu, Nanshan Deng, Xiaoyu Liu, Kun Jiang, Diange Yang, **ITSC 2024**

- [An End-to-End Autonomous Driving Pre-trained Transformer Model for Multi-Behavior-Optimal Trajectory Generation], Zelin Qian, Kun Jiang,  **Weitao Zhou**, Junze Wen, Cheng Jing, Zhong Cao, Diange Yang, **ITSC 2023**

- [Integrating Deep Reinforcement Learning with Optimal Trajectory Planner for Automated Driving](https://www.researchgate.net/profile/Weitao-Zhou-4/publication/347957240_Integrating_Deep_Reinforcement_Learning_with_Optimal_Trajectory_Planner_for_Automated_Driving/links/632f0f5686b22d3db4dbdf2b/Integrating-Deep-Reinforcement-Learning-with-Optimal-Trajectory-Planner-for-Automated-Driving.pdf), **Weitao Zhou**,  Kun Jiang, Zhong Cao, Nanshan Deng, Diange Yang, **ITSC 2020**

- [Autonomous driving policy continual learning with one-shot disengagement case], Zhong Cao, Xiang Li, Kun Jiang, **Weitao Zhou**, Xiaoyu Liu, Nanshan Deng, Diange Yang, **IEEE Trans-IV**

- [LiDAR-based Object Detection Failure Tolerated Autonomous Driving Planning System], Zhong Cao, Jiaxin Liu, **Weitao Zhou**, Xinyu Jiao, Diange Yang, **IV 2021**

- [Decision-Oriented Driving Scenario Recognition Based on Unsupervised Learning], Nanshan Deng, Kun Jiang, Zhong Cao, **Weitao Zhou**, Diange Yang, **CICTP 2021**

- [Lane Change Intention Recognition for Intelligent Connected Vehicle Using Trajectory Prediction], Shengjie Kou, Kun Jiang, Weiguang Yu, Ruidong Yan, **Weitao Zhou**, Mengmeng Yang, Diange Yang, **CICTP 2020**

- [Adapt the Driving Policy to Local Traffic before Entering the New Area], Nanshan Deng,  Zhong Cao,  **Weitao Zhou**, Kunjiang, Diange Yang, **ITSC 2021**




<!--
# 🎖 Honors and Awards
- *2021.10* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.09* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 

# 📖 Educations
- *2019.09 - 2023.06*,  PhD, Tsinghua University, Beijing.
- *2016.09 - 2019.06*,  Master, Beihang University, Beijing. 

# 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/)
-->

# 💬 Academic Service
- **Reviewer**, IEEE T-ITS, IEEE T-IV, ICRA, ITSC, IROS, ECCV.
- **Program Committee**, ITSC 2024 Corner Cases in Self-driving Vehicles Invited Session, ECCV 2024 Multi-Agent Autonomous Systems Workshop, SAECCE Annual Conference High Precision Map Forum.


# 💻 Internships
- *2023.04 - 2023.10*, [Didi Autonomous Driving](https://www.didiglobal.com/science/intelligent-driving), China.
- *2018.09 - 2019.02*, Baidu Apollo, China.
- *2017.06 - 2018.03*, Idriverplus, China.


