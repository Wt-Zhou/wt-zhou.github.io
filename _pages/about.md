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

I am the Co-founder and Chief Scientist at [SimpleAI](https://cloud.simpleai.tech/simple_world_lab/), where I lead research on world models and continual learning for general embodied intelligence. We are building robots that learn continuously through interaction, understand the physical world, and generalize across tasks, environments, and embodiments, with an initial focus on next-generation home robots.

Previously, I was a Shuimu Scholar and Postdoctoral Researcher at the [School of Vehicle and Mobility, Tsinghua University](https://eng.svm.tsinghua.edu.cn/), where I also received my Ph.D. under the supervision of [Prof. Diange Yang](https://eng.svm.tsinghua.edu.cn/info/1025/1153.htm). My earlier research treated autonomous driving as a safety-critical embodied AI problem, spanning data loops, model and policy training, closed-loop evaluation, and online improvement.

Our work on continual improvement for self-driving cars, published in [Nature Machine Intelligence](https://www.nature.com/articles/s42256-023-00610-y), was applied in the [autonomous-driving demonstration for the 2022 Beijing Winter Olympics](https://openicv.svm.tsinghua.edu.cn/info/xwzx/411), which operated with zero accidents. Related systems have been deployed at scale at [Didi Autonomous Driving](https://www.didiglobal.com/science/intelligent-driving) and [Toyota](https://global.toyota/en/), with research collaborations involving [Baidu Apollo](https://www.apollo.auto/) and [XPeng](https://www.xpeng.com/).

Additional highlights include publications at ICML, IROS, and IEEE T-ITS; Didi’s [Gaia Lighthouse Outstanding Project Award and Most Popular Project Award](https://mp.weixin.qq.com/s/KxPfIOW-O7xP4kJF8P119w); and winning the [Mcity AV Challenge](https://mcity.umich.edu/av-challenge/), where our autonomous vehicle completed the competition without a collision.

<p class="intro-contact">Follow our latest work at <a href="https://cloud.simpleai.tech/simple_world_lab/">Simple World Lab</a>. <strong>We are hiring</strong>—please reach out if you are interested in joining us. <strong>Email:</strong> zhouwt801 [at] gmail [dot] com.</p>


# 🔥 News
- **2026.07:** I am co-organizing the [Safe World Models for Trustworthy Embodied AI](https://trustworthy-world-models.github.io/ECCV2026/) workshop at **ECCV 2026**, bringing together researchers working on reliable and safe world models for embodied agents.
- **2026.07:** We are excited to share two new embodied-AI studies: [Diagnosing Semantic Handoff Failures in Agent-Orchestrated Vision-Language-Action Skill Composition](https://arxiv.org/abs/2607.06256) and [SoftVTBench: A Safety-Aware Visuo-Tactile Benchmark for Physically Constrained Robotic Manipulation of Deformable Objects](https://arxiv.org/abs/2607.04234).
- **2026.06:** I am co-organizing the [Physical World Models for Scaling Embodied AI](https://physical-world-models.github.io/IROS2026/) workshop at **IROS 2026**, focusing on how physical world models can help scale embodied intelligence.
- **2026.06:** Our paper [Dynamics Are Learned, Not Told: Semi-Supervised Discovery of Latent Dynamics Geometries for Zero-Shot Policy Adaptation](https://arxiv.org/abs/2606.02280) will appear at **ICML 2026**.
- **2026.05:** Happy to share our new paper [GaussianDream: A Feed-Forward 3D Gaussian World Model for Robotic Manipulation](https://arxiv.org/abs/2605.20752), which explores efficient 3D world modeling for robot learning.
- **2026.03:** Our paper [CounterScene: Counterfactual Causal Reasoning in Generative World Models for Safety-Critical Closed-Loop Evaluation](https://arxiv.org/abs/2603.21104) is now online.
- **2025.09:** Our work on long-tail autonomous driving, developed at Tsinghua and deployed on Didi’s RoboTaxi, received Didi’s top honor—the **Gaia Lighthouse Outstanding Project Award**—as well as the employee-voted **Most Popular Project Award**. [News](https://mp.weixin.qq.com/s/KxPfIOW-O7xP4kJF8P119w)
- **2025.07:** We organized the [Next Generation of Self-Driving Vehicles](https://mp.weixin.qq.com/s?__biz=MzUyNDEzMzkzMg==&mid=2247500932&idx=1&sn=49a48ba9864810ae2b7d2af386c0bf1f&chksm=fb0c22e5a957a64cbe673a6c5188a148bbb70fd084f01fc1a4580c4582b40ca56e793319bef8&scene=27) forum at Tsinghua University, featuring invited speakers from academia and industry. [Talk videos](https://space.bilibili.com/3546965931461541)
- **2025.06:** Our paper [DRARL: Disengagement-Reason-Augmented Reinforcement Learning for Efficient Improvement of Autonomous Driving Policy](https://arxiv.org/abs/2506.16720) was accepted by **IROS 2025**.
- **2025.03:** Our paper [Dynamically Local-Enhancement Planner for Large-Scale Autonomous Driving](https://arxiv.org/abs/2502.21134) is now online.
- **2024.10:** We organized the [Multi-Agent Autonomous Systems Workshop](https://mp.weixin.qq.com/s/S15YL6gt809I3XObmFdvrA) at **ECCV 2024**.
- **2024.09:** We organized the invited session [Driving the Edge: Addressing Corner Cases in Self-Driving Vehicles](https://its.papercept.net/conferences/scripts/abstract.pl?ConfID=87&Number=1154) at **ITSC 2024**.
- **2024.09:** We won the [Mcity AV Challenge](https://mcity.umich.edu/av-challenge/), and our autonomous vehicle completed the entire competition without a collision.
- **2024.03:** We released [SPIDER](https://github.com/Thu-ADLab/SPIDER), an open-source toolkit for building reusable data-driven and rule-based self-driving planners.
- **2023.03:** Our work [Continuous Improvement of Self-Driving Cars Using Dynamic Confidence-Aware Reinforcement Learning](https://www.nature.com/articles/s42256-023-00610-y) was published in **Nature Machine Intelligence**.
{: .news-list}

# 📝 Publications

<p class="publication-intro">Selected work is organized by research theme; see my <a href="https://scholar.google.com/citations?user=1H5PwZkAAAAJ&hl=en">Google Scholar profile</a> for the complete, up-to-date list.</p>

<section class="publication-group">
<h2>Embodied AI &amp; World Models</h2>

<article class="publication-item">
<div class="publication-venue">2026 · RSS SemRob Workshop</div>
<h3><a href="https://arxiv.org/abs/2607.06256">Diagnosing Semantic Handoff Failures in Agent-Orchestrated Vision-Language-Action Skill Composition</a></h3>
<p>Ke Rui, Yushen Zuo, Jiawei Wang, Haoran Jia, Jinming Ma, <strong>Weitao Zhou</strong>, Minglei Li</p>
</article>

<article class="publication-item">
<div class="publication-venue">2026 · Preprint</div>
<h3><a href="https://arxiv.org/abs/2607.04234">SoftVTBench: A Safety-Aware Visuo-Tactile Benchmark for Physically Constrained Robotic Manipulation of Deformable Objects</a></h3>
<p>Bowen Jing, Mingxin Wang, Ruiyang Hao, Chenchen Ge, Hanwen Shen, Junjie He, Yang Cui, Yiming Hou, <strong>Weitao Zhou</strong>, et al.</p>
</article>

<article class="publication-item">
<div class="publication-venue">2026 · ICML</div>
<h3><a href="https://arxiv.org/abs/2606.02280">Dynamics Are Learned, Not Told: Semi-Supervised Discovery of Latent Dynamics Geometries for Zero-Shot Policy Adaptation</a></h3>
<p>Zhiming Xu, <strong>Weitao Zhou</strong>, Xianghui Pan, Nanshan Deng, Chengju Liu, Qijun Chen, Chenpeng Yao</p>
</article>

<article class="publication-item">
<div class="publication-venue">2026 · Preprint</div>
<h3><a href="https://arxiv.org/abs/2605.20752">GaussianDream: A Feed-Forward 3D Gaussian World Model for Robotic Manipulation</a></h3>
<p>Zijian Zhang, Yuqing Jiang, Qian Cheng, Xiaofan Li, Si Liu, Ding Zhao, Ping Luo, <strong>Weitao Zhou</strong>, Haibao Yu</p>
</article>

<article class="publication-item">
<div class="publication-venue">2026 · Preprint</div>
<h3><a href="https://arxiv.org/abs/2603.21104">CounterScene: Counterfactual Causal Reasoning in Generative World Models for Safety-Critical Closed-Loop Evaluation</a></h3>
<p>Bowen Jing, Ruiyang Hao, <strong>Weitao Zhou</strong>, Haibao Yu</p>
</article>
</section>

<section class="publication-group">
<h2>Continual Learning &amp; Reinforcement Learning</h2>

<article class="publication-item">
<div class="publication-venue">2026 · Preprint</div>
<h3><a href="https://arxiv.org/abs/2606.29820">Dual-Flow Reinforcement Learning with State-Aware Exploration</a></h3>
<p>Qijun Li, Zheng Fu, Qi Song, Yifei He, <strong>Weitao Zhou</strong>, Kun Jiang, Diange Yang</p>
</article>

<article class="publication-item">
<div class="publication-venue">2025 · IROS</div>
<h3><a href="https://arxiv.org/abs/2506.16720">DRARL: Disengagement-Reason-Augmented Reinforcement Learning for Efficient Improvement of Autonomous Driving Policy</a></h3>
<p><strong>Weitao Zhou</strong>, Bo Zhang, Zhong Cao, Xiang Li, Qian Cheng, Chunyang Liu, Yaqin Zhang, Diange Yang</p>
</article>

<article class="publication-item">
<div class="publication-venue">2023 · Nature Machine Intelligence</div>
<h3><a href="https://www.nature.com/articles/s42256-023-00610-y">Continuous Improvement of Self-Driving Cars Using Dynamic Confidence-Aware Reinforcement Learning</a></h3>
<p>Zhong Cao, Kun Jiang, <strong>Weitao Zhou</strong>, Shaobing Xu, Huei Peng, Diange Yang · <a href="https://github.com/zhcao92/DCARL">Project</a></p>
</article>

<article class="publication-item">
<div class="publication-venue">2023 · IEEE T-ITS</div>
<h3><a href="https://arxiv.org/abs/2305.07487">Identify, Estimate and Bound the Uncertainty of Reinforcement Learning for Autonomous Driving</a></h3>
<p><strong>Weitao Zhou</strong>, Zhong Cao, Nanshan Deng, Kun Jiang, Diange Yang</p>
</article>
</section>

<section class="publication-group">
<h2>Autonomous Driving</h2>

<article class="publication-item">
<div class="publication-venue">2025 · Preprint</div>
<h3><a href="https://arxiv.org/abs/2502.21134">Dynamically Local-Enhancement Planner for Large-Scale Autonomous Driving</a></h3>
<p>Nanshan Deng, <strong>Weitao Zhou</strong>, Bo Zhang, Junze Wen, Kun Jiang, Zhong Cao, Diange Yang</p>
</article>

<article class="publication-item">
<div class="publication-venue">2024 · ITSC</div>
<h3><a href="https://github.com/Thu-ADLab/SPIDER">SPIDER: Self-Driving Planners and Intelligent Decision-Making Engines with Reusability</a></h3>
<p>Zelin Qian, Kun Jiang, Zhong Cao, Kai Qian, Yunkang Xu, <strong>Weitao Zhou</strong>, Diange Yang</p>
</article>

<article class="publication-item">
<div class="publication-venue">2023 · IEEE T-ITS</div>
<h3><a href="https://arxiv.org/abs/2305.07497">Dynamically Conservative Self-Driving Planner for Long-Tail Cases</a></h3>
<p><strong>Weitao Zhou</strong>, Zhong Cao, Nanshan Deng, Xiaoyu Liu, Kun Jiang, Diange Yang</p>
</article>

<article class="publication-item">
<div class="publication-venue">2022 · ITSC</div>
<h3><a href="https://arxiv.org/abs/2207.00788">Long-Tail Prediction Uncertainty Aware Trajectory Planning for Self-Driving Vehicles</a></h3>
<p><strong>Weitao Zhou</strong>, Zhong Cao, Yunkang Xu, Nanshan Deng, Xiaoyu Liu, Kun Jiang, Diange Yang</p>
</article>

<article class="publication-item">
<div class="publication-venue">2020 · ITSC</div>
<h3><a href="https://www.researchgate.net/profile/Weitao-Zhou-4/publication/347957240_Integrating_Deep_Reinforcement_Learning_with_Optimal_Trajectory_Planner_for_Automated_Driving/links/632f0f5686b22d3db4dbdf2b/Integrating-Deep-Reinforcement-Learning-with-Optimal-Trajectory-Planner-for-Automated-Driving.pdf">Integrating Deep Reinforcement Learning with Optimal Trajectory Planner for Automated Driving</a></h3>
<p><strong>Weitao Zhou</strong>, Kun Jiang, Zhong Cao, Nanshan Deng, Diange Yang</p>
</article>
</section>
<span class='anchor' id='-Academic-Service'></span>
# 💬 Academic Service
- **Reviewer:** Nature Machine Intelligence, Nature Computational Science, IEEE T-ITS, IEEE T-IV, ICRA, ITSC, IROS, ECCV, NeurIPS, ICML, CVPR.
- **Workshop Organizer:**
    - **ECCV 2026** — [Safe World Models for Trustworthy Embodied AI](https://trustworthy-world-models.github.io/ECCV2026/)
    - **IROS 2026** — [Physical World Models for Scaling Embodied AI](https://physical-world-models.github.io/IROS2026/)
    - **ECCV 2024** — [Multi-Agent Autonomous Systems Workshop](https://mp.weixin.qq.com/s/S15YL6gt809I3XObmFdvrA)
    - **ITSC 2024 · Invited Session** — [Driving the Edge: Addressing Corner Cases in Self-Driving Vehicles](https://its.papercept.net/conferences/scripts/abstract.pl?ConfID=87&Number=1154)
- **Forum Organizer:**
    - **Tsinghua University · 2025** — [Next Generation of Self-Driving Vehicles](https://mp.weixin.qq.com/s?__biz=MzUyNDEzMzkzMg==&mid=2247500932&idx=1&sn=49a48ba9864810ae2b7d2af386c0bf1f&chksm=fb0c22e5a957a64cbe673a6c5188a148bbb70fd084f01fc1a4580c4582b40ca56e793319bef8&scene=27)
    - **SAECCE 2023** — [Autonomous-Driving Map Updates and Safety Compliance](https://www.sohu.com/a/733306124_620780)
{: .academic-service-list}


# 💼 Experience

<section class="experience-list">
<article class="experience-item">
<div class="experience-period">Present</div>
<div class="experience-content">
<h3>Co-founder &amp; Chief Scientist · SimpleAI</h3>
<p>Leading research on world models and continual learning for general embodied intelligence and next-generation home robots.</p>
</div>
</article>

<article class="experience-item">
<div class="experience-period">Jun. 2023 – Jun. 2026</div>
<div class="experience-content">
<h3>Postdoctoral Researcher · Tsinghua University</h3>
<p>Shuimu Scholar at the School of Vehicle and Mobility, developing continual-learning and trustworthy autonomous-driving systems.</p>
</div>
</article>

<article class="experience-item">
<div class="experience-period">Apr. – Oct. 2023</div>
<div class="experience-content">
<h3>Research Intern · <a href="https://www.didiglobal.com/science/intelligent-driving">Didi Autonomous Driving</a></h3>
<p>Conducted research on reinforcement learning and long-tail autonomous-driving policy improvement.</p>
</div>
</article>

<article class="experience-item">
<div class="experience-period">Sep. 2018 – Feb. 2019</div>
<div class="experience-content">
<h3>Research Intern · <a href="https://www.apollo.auto/">Baidu Apollo</a></h3>
<p>Worked on motion planning and decision-making for autonomous driving.</p>
</div>
</article>

<article class="experience-item">
<div class="experience-period">Jun. 2017 – Mar. 2018</div>
<div class="experience-content">
<h3>Research Intern · <a href="https://www.velobotics.cn/Home.html">Idriverplus</a></h3>
<p>Worked on planning and control for autonomous vehicles.</p>
</div>
</article>
</section>
