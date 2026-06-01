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
  <div class="home-hero__copy">
    <p class="eyebrow">PhD Student · Oregon State University</p>
    <h1>Yaolun Zhang</h1>
    <p class="hero-lede">I work on agentic AI, reinforcement learning, multi-agent systems, and vision-language agents, with recent projects on automatic MAS construction and end-to-end video agents.</p>
    <div class="hero-profile-grid">
      <div class="hero-profile-item">
        <span>Education</span>
        <p>First-year PhD student at Oregon State University, advised by Prof. <a href="https://huazhengwang.github.io/">Huazheng Wang</a>. Previously studied at Renmin University of China and visited UW-Madison.</p>
      </div>
      <div class="hero-profile-item">
        <span>Research</span>
        <p>I am interested in self-improving agents, automatic multi-agent system design, RL-based agent training, coding agents, and video understanding.</p>
      </div>
      <div class="hero-profile-item">
        <span>Experience</span>
        <p>Research intern at SenseTime Research on video understanding, and ModelBest/OpenBMB on coding agents.</p>
      </div>
    </div>
    <div class="hero-actions">
      <a href="#publications" class="hero-button hero-button--primary">Publications</a>
      <a href="#internships" class="hero-button">Experience</a>
      <a href="mailto:zhangyaolun5@gmail.com" class="hero-button">Contact</a>
    </div>
  </div>
</section>

<section class="intro-panel">
I was fortunate to work with Prof. <a href="https://xiaocw11.github.io/">Chaowei Xiao</a> at UW-Madison, and was previously supervised by Prof. <a href="https://mitsloan.mit.edu/staff/directory/keman-huang">Keman Huang</a> at Renmin University of China. My current work focuses on building agents that can plan, coordinate, learn from feedback, and improve their own system design.
</section>

<h1 id="news">News</h1>

<div class="timeline">
  <div class="timeline-item">
    <span class="timeline-date">2026.05</span>
    <div class="timeline-content">MetaAgent-X released: end-to-end reinforcement learning for self-designing and self-executing multi-agent systems.</div>
  </div>
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

<h1 id="publications">Publications</h1>

<div class="paper-box paper-box--lead">
  <div class="paper-box-image">
    <div>
      <div class="badge">arXiv 2026</div>
      <img src="https://mercury7353.github.io/MetaAgent-X-Page/assets/pipeline.png" alt="MetaAgent-X online RL pipeline diagram">
    </div>
  </div>
  <div class="paper-box-text">
    <p class="paper-kicker">Latest Work · Multi-Agent RL</p>
    <h2><a href="https://arxiv.org/abs/2605.14212">MetaAgent-X: Breaking the Ceiling of Automatic Multi-Agent Systems via End-to-End Reinforcement Learning</a></h2>
    <p><strong>Yaolun Zhang</strong>, Yujie Zhao, Nan Wang, Yiran Wu, Jiayu Chang, Yizhao Chen, Qingyun Wu, Jishen Zhao, Huazheng Wang</p>
    <p class="paper-summary">End-to-end RL framework that jointly optimizes automatic MAS design and execution, with hierarchical rollout and stagewise co-evolution.</p>
    <div class="paper-links">
      <a href="https://arxiv.org/abs/2605.14212">Paper</a>
      <a href="https://mercury7353.github.io/MetaAgent-X-Page/">Project</a>
      <a href="https://github.com/pettingllms-ai/PettingLLMs">Code</a>
      <a href="https://huggingface.co/Mercury7353/MetaAgent-X">Model</a>
    </div>
  </div>
</div>

<div class="paper-box paper-box--lead">
  <div class="paper-box-image">
    <div>
      <div class="badge">CVPR 2026</div>
      <img src="images/paper4.png" alt="EVA video agent overview">
    </div>
  </div>
  <div class="paper-box-text">
    <p class="paper-kicker">Video Agent · Efficient RL</p>
    <h2><a href="https://arxiv.org/abs/2603.22918">EVA: Efficient Reinforcement Learning for End-to-End Video Agent</a></h2>
    <p><strong>Yaolun Zhang</strong>, Ruohui Wang, Jiahao Wang, Yepeng Tang, Xuanyu Zheng, Haonan Duan, Hao Lu, Hanming Deng, Lewei Lu</p>
    <p class="paper-summary">Planning-before-perception video agent trained with SFT, KTO, and GRPO for query-driven long-video understanding.</p>
    <div class="paper-links">
      <a href="https://arxiv.org/abs/2603.22918">Paper</a>
      <a href="https://mercury7353.github.io/EVA-Page/">Project</a>
      <a href="https://github.com/wangruohui/EfficientVideoAgent">Code</a>
      <a href="https://huggingface.co/WRHC/EfficientVideoAgent/">Model</a>
    </div>
  </div>
</div>

<div class="paper-box">
  <div class="paper-box-image">
    <div>
      <div class="badge">ICML 2025</div>
      <img src="images/paper3.png" alt="MetaAgent finite-state-machine overview">
    </div>
  </div>
  <div class="paper-box-text">
    <p class="paper-kicker">Automatic MAS</p>
    <h2><a href="https://icml.cc/virtual/2025/poster/43677">MetaAgent: Automatically Building Multi-Agent System based on Finite State Machine</a></h2>
    <p><strong>Yaolun Zhang</strong>, Xiaogeng Liu, Chaowei Xiao</p>
    <div class="paper-links"><a href="https://icml.cc/virtual/2025/poster/43677">Paper</a></div>
  </div>
</div>

<div class="paper-box">
  <div class="paper-box-image">
    <div>
      <div class="badge">arXiv</div>
      <img src="images/paper2.png" alt="PyBench overview">
    </div>
  </div>
  <div class="paper-box-text">
    <p class="paper-kicker">Coding Agent Evaluation</p>
    <h2><a href="https://arxiv.org/abs/2407.16732">PyBench: Evaluating LLM Agent on various real-world coding tasks</a></h2>
    <p><strong>Yaolun Zhang</strong>, Yinxu Pan, Yudong Wang, Jie Cai</p>
    <div class="paper-links"><a href="https://arxiv.org/abs/2407.16732">Paper</a></div>
  </div>
</div>

<div class="paper-box">
  <div class="paper-box-image">
    <div>
      <div class="badge">arXiv</div>
      <img src="images/paper1.png" alt="Cybersecurity RL agents overview">
    </div>
  </div>
  <div class="paper-box-text">
    <p class="paper-kicker">RL Agents · Cybersecurity</p>
    <h2><a href="https://arxiv.org/pdf/2403.17674">Depending on yourself when you should: Mentoring LLM with RL agents to become the master in cybersecurity games</a></h2>
    <p>Yikuan Yan*, <strong>Yaolun Zhang*</strong>, Keman Huang</p>
    <div class="paper-links"><a href="https://arxiv.org/pdf/2403.17674">Paper</a></div>
  </div>
</div>

<h1 id="internships">Internships</h1>

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

<h1 id="educations">Educations</h1>

- *2025.9 - ?*, PhD Student, Oregon State University. 
- *2024.9 - 2024.12*, Visiting Student, University of Wisconsin-Madison. 
- *2021.09 - 2025.06*, Undergraduate, Renmin University of China. 
