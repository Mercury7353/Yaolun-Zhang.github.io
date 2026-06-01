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
<section class="home-hero">
  <div class="home-hero__copy" markdown="1">
    <p class="eyebrow">Agentic AI · Multi-Agent Systems · Vision-Language Agents</p>
    <h1>Yaolun Zhang</h1>
    <p class="hero-lede">I build agentic AI systems that learn, coordinate, and evolve across coding, video understanding, and multi-agent decision-making.</p>
    <div class="hero-actions">
      <a href="#featured-work" class="hero-button hero-button--primary">Featured Work</a>
      <a href="mailto:zhangyaolun5@gmail.com" class="hero-button">Contact</a>
    </div>
  </div>
  <div class="home-hero__signal">
    <div class="signal-card signal-card--main">
      <span class="signal-card__number">PhD</span>
      <span class="signal-card__label">Oregon State University</span>
    </div>
    <div class="signal-grid">
      <div class="signal-card">
        <span class="signal-card__number">CVPR</span>
        <span class="signal-card__label">Video Agents</span>
      </div>
      <div class="signal-card">
        <span class="signal-card__number">ICML</span>
        <span class="signal-card__label">Multi-Agent Systems</span>
      </div>
      <div class="signal-card">
        <span class="signal-card__number">LLM</span>
        <span class="signal-card__label">Coding Agents</span>
      </div>
      <div class="signal-card">
        <span class="signal-card__number">RL</span>
        <span class="signal-card__label">Self-Evolving Agents</span>
      </div>
    </div>
  </div>
</section>

<section class="intro-panel" markdown="1">
I am a first-year PhD student at Oregon State University, advised by Prof. [Huazheng Wang](https://huazhengwang.github.io/). I was previously an undergraduate student at Renmin University of China and a visiting student at UW-Madison, where I was fortunate to work with Prof. [Chaowei Xiao](https://xiaocw11.github.io/). I was also supervised by Prof. [Keman Huang](https://mitsloan.mit.edu/staff/directory/keman-huang) at Renmin University of China.
</section>

<span class='anchor' id='featured-work'></span>
# Featured Work

<div class="featured-grid">
  <a class="featured-card" href="https://icml.cc/virtual/2025/poster/43677">
    <img src="images/paper3.png" alt="MetaAgent project preview">
    <div>
      <span class="featured-card__venue">ICML 2025</span>
      <h2>MetaAgent</h2>
      <p>Automatically builds multi-agent systems through finite-state machine structure.</p>
    </div>
  </a>
  <div class="featured-card">
    <img src="images/paper4.png" alt="EVA project preview">
    <div>
      <span class="featured-card__venue">CVPR 2026</span>
      <h2>EVA</h2>
      <p>Efficient reinforcement learning for end-to-end video agents.</p>
    </div>
  </div>
  <a class="featured-card" href="https://arxiv.org/abs/2407.16732">
    <img src="images/paper2.png" alt="PyBench project preview">
    <div>
      <span class="featured-card__venue">arXiv</span>
      <h2>PyBench</h2>
      <p>Evaluates LLM agents on realistic coding tasks and tool-use workflows.</p>
    </div>
  </a>
</div>

<span class='anchor' id='news'></span>
# News

<div class="timeline">
  <div class="timeline-item">
    <span class="timeline-date">2026.02</span>
    <div class="timeline-content">Two papers accepted to CVPR 2026.</div>
  </div>
  <div class="timeline-item">
    <span class="timeline-date">2025.04</span>
    <div class="timeline-content">One paper accepted to ICML 2025. See you in Vancouver.</div>
  </div>
  <div class="timeline-item">
    <span class="timeline-date">2025.04</span>
    <div class="timeline-content">Admitted to Oregon State University as an AI PhD student.</div>
  </div>
  <div class="timeline-item">
    <span class="timeline-date">2024.09</span>
    <div class="timeline-content">Arrived at UW-Madison as a visiting student.</div>
  </div>
</div>

<span class='anchor' id='publications'></span>
# Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICML</div><img src='images/paper3.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[MetaAgent: Automatically Building Multi-Agent System based on Finite State Machine](https://icml.cc/virtual/2025/poster/43677)

**Yaolun Zhang**, Xiaogeng Liu, Chaowei Xiao

<div class="paper-links"><a href="https://icml.cc/virtual/2025/poster/43677">Paper</a></div>
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR</div><img src='images/paper4.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[EVA: Efficient Reinforcement Learning for End-to-End Video Agent]

**Yaolun Zhang**, Ruohui Wang, Jiahao Wang, Yepeng Tang, Haonan Duan, Xuanyu Zheng, Hao Lu, Hanming Deng, Lewei Lu
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">arXiv</div><img src='images/paper2.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[PyBench: Evaluating LLM Agent on various real-world coding tasks](https://arxiv.org/abs/2407.16732)

**Yaolun Zhang**, Yinxu Pan, Yudong Wang, Jie Cai

<div class="paper-links"><a href="https://arxiv.org/abs/2407.16732">Paper</a></div>
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">arXiv</div><img src='images/paper1.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Depending on yourself when you should: Mentoring LLM with RL agents to become the master in cybersecurity games](https://arxiv.org/pdf/2403.17674)

Yikuan Yan*, **Yaolun Zhang***, Keman Huang

<div class="paper-links"><a href="https://arxiv.org/pdf/2403.17674">Paper</a></div>
</div>
</div>

<span class='anchor' id='internships'></span>
# Internships

<div class="experience-list">
  <div class="experience-item">
    <span>2025.2 - 2025.10</span>
    <strong>SenseTime Research</strong>
    <p>Research Intern on Video Understanding</p>
  </div>
  <div class="experience-item">
    <span>2024.2 - 2024.8</span>
    <strong>ModelBest (OpenBMB)</strong>
    <p>Research Intern on Coding Agent</p>
  </div>
</div>

<span class='anchor' id='educations'></span>
# Educations
- *2025.9 - ?*, PhD Student, Oregon State University. 
- *2024.9 - 2024.12*, Visiting Student, University of Wisconsin-Madison. 
- *2021.09 - 2025.06*, Undergraduate, Renmin University of China. 



