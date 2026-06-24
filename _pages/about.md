---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% comment %}
Google Scholar citation badge data. Keep this block commented until citations are
displayed on the page again.
{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}
{% endcomment %}

<span class='anchor' id='about-me'></span>

## Yuanchen Bei
I am a Ph.D. Student at the University of Illinois Urbana-Champaign, advised by Prof. Hanghang Tong.

My research interests mainly include <span class="kw">knowledge management for generative agents</span>, especially long-term agent memory and continual learning, <span class="kw">user-centric ML and relational data mining</span>, and <span class="kw">graph learning</span>.


<!--
👨‍💻‍ <font color="#dd0000">I am actively looking for Ph.D. opportunities in Fall 2025, and I sincerely appreciate potential opportunities!</font> 
-->

---

{% comment %}
<span class='anchor' id='-news'></span>


## News

<ul class="news-list">
  <li>
    <span class="news-date">2026.01</span>
    <span class="news-content">Our new benchmark on <em>Multimodal Long-Term Memory for MLLM Agents</em> is available <a href="https://arxiv.org/pdf/2601.03515">here</a>.</span>
  </li>
</ul>


---
{% endcomment %}
<span class='anchor' id='-publications'></span>
<span class='anchor' id='-research-highlight'></span>


## Research Highlight

<span class="research-collab">🤝 <strong>Open to collaboration</strong> — feel free to reach out if you share interests in any of the directions below!</span>

<div class="research-group research-group--memory">
  <div class="research-group__label">
    <span class="research-group__icon">🧠</span>
    <span class="research-group__title">Knowledge Management for Generative Agents</span>
  </div>
  <ul>
    <li><span class="research-subtopic">Long-Term Agent Memory:</span> <a href="https://arxiv.org/pdf/2601.03515">Mem-Gallery</a> <span class="venue venue-top">ACL 2026</span>, <a href="https://arxiv.org/pdf/2511.20857">Evo-Memory</a> <span class="venue venue-top">Preprint</span></li>
    <li><span class="research-subtopic">Agentic Continual Learning</span></li>
  </ul>
</div>

<div class="research-group research-group--relational">
  <div class="research-group__label">
    <span class="research-group__icon">🔗</span>
    <span class="research-group__title">User Modeling and Relational Data Mining</span>
  </div>
  <ul>
    <li><span class="research-subtopic">Large-Scale Recommendation:</span> <a href="https://dl.acm.org/doi/pdf/10.1145/3589334.3645517">MacGNN</a> <span class="venue venue-top">🔥 Top-10 | WWW 2024</span>, <a href="https://dl.acm.org/doi/pdf/10.1145/3637528.3671569">POGCN</a> <span class="venue venue-top">KDD 2024</span></li>
    <li><span class="research-subtopic">Cold-Start and Debiased User Modeling:</span> <a href="https://dl.acm.org/doi/pdf/10.1145/3701551.3703546">ColdLLM</a> <span class="venue venue-top">WSDM 2025</span>, <a href="https://proceedings.neurips.cc/paper_files/paper/2024/file/10d52f5d2ef0f69ac10da7c962fb6db9-Paper-Conference.pdf">USIM</a> <span class="venue venue-top">Spotlight | NeurIPS 2024</span>, <a href="https://dl.acm.org/doi/pdf/10.1145/3711896.3737188">AliBoost</a> <span class="venue venue-top">KDD 2025</span></li>
    <li><span class="research-subtopic">Graph Anomaly Detection:</span> <a href="https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=10415759">RAND</a> <span class="venue venue-top">ICDM 2023</span>, <a href="https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=11017687">G3AD</a> <span class="venue venue-top">TNNLS 2025</span></li>
  </ul>
</div>

<div class="research-group research-group--graph">
  <div class="research-group__label">
    <span class="research-group__icon">📐</span>
    <span class="research-group__title">Graph Learning</span>
  </div>
  <ul>
    <li><span class="research-subtopic">General-Purpose GNNs:</span> <a href="https://dl.acm.org/doi/pdf/10.1145/3690624.3709197">CorGCN</a> <span class="venue venue-top">KDD 2025</span>, <a href="https://openreview.net/pdf/0447b73eb0fd4156c928c524b67af251008e70a4.pdf">CMGNN</a> <span class="venue venue-top">NeurIPS 2025</span></li>
    <li><span class="research-subtopic">GNN Pre-Training:</span> <a href="https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=10598011">CPDG</a> <span class="venue venue-top">ICDE 2024</span></li>
  </ul>
</div>

---

## Selected Open-Source Projects

<ul class="project-list">
  <li>
    <div class="project-list__header">
      <a class="project-list__name" href="https://github.com/YuanchenBei/Mem-Gallery">Mem-Gallery</a>
      <span class="project-list__tag">Benchmark</span>
      <img class="project-list__stars" src="https://img.shields.io/github/stars/YuanchenBei/Mem-Gallery" alt="stars">
    </div>
    <p class="project-list__desc">Benchmarking multimodal long-term memory for MLLM agents. Includes 10+ memory models with a new evaluation dataset.</p>
  </li>
  <li>
    <div class="project-list__header">
      <a class="project-list__name" href="https://github.com/YuanchenBei/ColdRec">ColdRec</a>
      <span class="project-list__tag">Toolkit</span>
      <img class="project-list__stars" src="https://img.shields.io/github/stars/YuanchenBei/ColdRec" alt="stars">
    </div>
    <p class="project-list__desc">A unified toolkit for cold-start recommendation. Includes 20+ models with comprehensive evaluations across multiple datasets.</p>
  </li>
  <li>
    <div class="project-list__header">
      <a class="project-list__name" href="https://github.com/DEEP-PolyU/Awesome-GraphRAG">Awesome-GraphRAG</a>
      <span class="project-list__tag">Reading List</span>
      <img class="project-list__stars" src="https://img.shields.io/github/stars/DEEP-PolyU/Awesome-GraphRAG" alt="stars">
    </div>
    <p class="project-list__desc">A curated reading list of papers on graph-based retrieval-augmented generation.</p>
  </li>
  <li>
    <div class="project-list__header">
      <a class="project-list__name" href="https://github.com/YuanchenBei/Awesome-Cold-Start-Recommendation">Awesome-Cold-Start-Recommendation</a>
      <span class="project-list__tag">Reading List</span>
      <img class="project-list__stars" src="https://img.shields.io/github/stars/YuanchenBei/Awesome-Cold-Start-Recommendation" alt="stars">
    </div>
    <p class="project-list__desc">A curated reading list of papers on cold-start recommendation.</p>
  </li>
  <li>
    <div class="project-list__header">
      <a class="project-list__name" href="https://github.com/YuanchenBei/GraphTransformer-DGraphFin">GraphTransformer-DGraphFin</a>
      <span class="project-list__tag">Leaderboard Solution</span>
      <img class="project-list__stars" src="https://img.shields.io/github/stars/YuanchenBei/GraphTransformer-DGraphFin" alt="stars">
    </div>
    <p class="project-list__desc">Top-2 solution for the DGraph-Fin leaderboard on large-scale dynamic graph anomaly detection.</p>
  </li>
</ul>


---

<span class='anchor' id='-honors-and-awards'></span>

## Honors and Awards

<ul class="info-list">
  <li>Outstanding Reviewer <span class="info-list__note">KDD 2025, TNNLS</span></li>
  <li>National Scholarship <span class="info-list__count">x2</span> <span class="info-list__note">Bachelor, Master</span></li>
  <li>First Class Scholarship <span class="info-list__count">x2</span> <span class="info-list__note">Bachelor, Master</span></li>
  <li>Outstanding Graduate <span class="info-list__note">Master</span></li>
  <li>Outstanding Undergraduate <span class="info-list__note">Bachelor</span></li>
</ul>


---
<span class='anchor' id='-academic-services'></span>


## Academic Services

<ul class="info-list">
  <li><span class="info-list__label">Conference Program Committee Member:</span> ICLR (2025–2026), KDD (2024–2026), ICML 2026, WWW 2026, WSDM 2026, MM (2025–2026), CIKM (2025–2026), SIGIR 2025, SIGIR-AP 2025, ECAI 2024.</li>
  <li><span class="info-list__label">Journal Reviewer:</span> ACM TKDD, ACM CSUR, IEEE TKDE, IEEE TNNLS, IEEE TII, IEEE TIP.</li>
</ul>


---
<span class='anchor' id='-experiences'></span>

## Experiences

<div class="exp-group">
<h3 class="exp-group__title">Internship</h3>
<ul class="exp-list">
  <li>
    <span class="exp-heading"><span class="exp-logo exp-logo--alibaba"><img src="images/alibaba-logo.svg" alt="Alibaba Group logo" width="42" height="16"></span><strong class="exp-company">Alibaba Group</strong><span class="exp-detail">Research Intern · 2023.05 – 2023.11, 2025.03 – 2025.06 · Hangzhou, China</span></span>
  </li>
  <li>
    <span class="exp-heading"><span class="exp-logo exp-logo--polyu"><img src="images/polyu-logo.svg" alt="The Hong Kong Polytechnic University logo" width="18" height="18"></span><strong class="exp-company">The Hong Kong Polytechnic University</strong><span class="exp-detail">Research Assistant · 2024.06 – 2024.10 · Hong Kong SAR, China</span></span>
  </li>
  <li>
    <span class="exp-heading"><span class="exp-logo exp-logo--meituan"><img src="images/meituan-icon.png" alt="Meituan logo" width="18" height="18"></span><strong class="exp-company">Meituan</strong><span class="exp-detail">Research Intern · 2022.02 – 2022.08 · Beijing, China</span></span>
  </li>
</ul>
</div>

<div class="exp-group">
<h3 class="exp-group__title">Education</h3>
<ul class="exp-list">
  <li>
    <span class="exp-heading"><span class="exp-logo exp-logo--uiuc"><img src="images/uiuc-logo.svg" alt="University of Illinois Urbana-Champaign logo" width="42" height="16"></span><strong class="exp-company">University of Illinois Urbana-Champaign</strong><span class="exp-detail">Ph.D. Student</span></span>
  </li>
  <li>
    <span class="exp-heading"><span class="exp-logo exp-logo--zju"><img src="images/zju-logo.svg" alt="Zhejiang University logo" width="18" height="18"></span><strong class="exp-company">Zhejiang University</strong><span class="exp-detail">M.Eng.</span></span>
  </li>
  <li>
    <span class="exp-heading"><span class="exp-logo exp-logo--jnu"><img src="images/jnu-logo.svg" alt="Jinan University logo" width="18" height="18"></span><strong class="exp-company">Jinan University</strong><span class="exp-detail">B.S.</span></span>
  </li>
</ul>
</div>

<br>
