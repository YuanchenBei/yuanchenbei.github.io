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

My research interest lies in <span class="kw">human-centered AI</span>. My long-term goal is to build <span class="kw-underline">personalized and interactive agents capable of omni-modal reasoning</span>. Toward this goal, I currently focus on <span class="kw-underline">memory management, proactiveness, multimodal understanding, and long-horizon post-training for personalized agents</span>.


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

<div class="pub-groups">
<details class="pub-group" open>
<summary><span class="pub-group__title"><span class="pub-group__icon" aria-hidden="true">🧠</span>Agent Memory and Context Management</span><span class="pub-group__meta">4 papers · ACL'26 · EMNLP'26</span></summary>
<ul class="pub-list"><li><div class="pub-title"><a href="https://arxiv.org/abs/2601.03515">Mem-Gallery: Benchmarking Multimodal Long-Term Conversational Memory for MLLM Agents</a></div><div class="pub-authors"><strong>Yuanchen Bei</strong>, Tianxin Wei, Xuying Ning, Yanjun Zhao, Zhining Liu, Xiao Lin, Yada Zhu, Hendrik Hamann, Jingrui He, Hanghang Tong</div><div class="pub-venue"><span class="pub-venue__name">ACL 2026</span><span class="pub-tag">110+ GitHub Stars</span><span class="pub-tag">3000+ HuggingFace Monthly Downloads</span></div></li><li><div class="pub-title"><a href="https://arxiv.org/abs/2603.21520">Generalizable Self-Evolving Memory for Automatic Prompt Optimization</a></div><div class="pub-authors">Guanbao Liang<sup>*</sup>, <strong>Yuanchen Bei</strong><sup>*</sup>, Sheng Zhou, Yuheng Qin, Huan Zhou, Bingxin Jia, Bin Li, Jiajun Bu</div></li><li><div class="pub-title"><a href="https://arxiv.org/abs/2511.20857">Evo-Memory: Benchmarking LLM Agent Test-time Learning with Self-Evolving Memory</a></div><div class="pub-authors">Tianxin Wei, Noveen Sachdeva, Benjamin Coleman, Zhankui He, <strong>Yuanchen Bei</strong>, Xuying Ning, Mengting Ai, Yunzhe Li, Jingrui He, Ed H. Chi, Chi Wang, Shuo Chen, Fernando Pereira, Wang-Cheng Kang, Derek Zhiyuan Cheng</div></li><li><div class="pub-title"><a href="https://arxiv.org/abs/2608.15071">Evo-Harness: Context-to-Harness Skill Compilation for Self-Evolving Agents</a></div><div class="pub-authors">Tianxin Wei, Zhan Shi, Minhua Lin, Bing He, Zewen Liu, Yisi Sang, <strong>Yuanchen Bei</strong>, Xuying Ning, Jiaru Zou, Ting-Wei Li, Xiao Lin, Yanjun Zhao, Chi Wang, Benoit Dumoulin, Dakuo Wang, Jingrui He, Hanqing Lu</div><div class="pub-venue"><span class="pub-venue__name">EMNLP 2026</span></div></li></ul>
</details>
<details class="pub-group" open>
<summary><span class="pub-group__title"><span class="pub-group__icon" aria-hidden="true">⚙️</span>Agent Reasoning and Post-Training</span><span class="pub-group__meta">3 papers · NeurIPS'26</span></summary>
<ul class="pub-list"><li><div class="pub-title"><a href="https://arxiv.org/abs/2609.13734">PolicyMem: Geometric Policy Memory for LLM Governance</a></div><div class="pub-authors"><strong>Yuanchen Bei</strong>, Zhengzhang Chen, Yanjun Zhao, Haoyu Wang, Hanghang Tong, Haifeng Chen</div></li><li><div class="pub-title"><a href="https://arxiv.org/abs/2608.05446">EvoHarness-RL: Learning Runtime Harness Coordination for Self-Evolving Agents</a></div><div class="pub-authors">Xuying Ning, Dongqi Fu, Tianxin Wei, <strong>Yuanchen Bei</strong>, Xiyuan Yang, Wujiang Xu, Yueqi Song, Bingxuan Li, Zihao Li, Hanqing Zeng, Xiang Shen, Yajuan Wang, Yifan Wu, Qifan Wang, Jiayi Liu, Hong Li, Yinglong Xia, Xiangjun Fan, Hanghang Tong, Jingrui He</div></li><li><div class="pub-title"><a href="https://arxiv.org/abs/2608.18575">Beyond LLM-Based Reasoning: Lightweight GNNs for Agent Failure Attribution</a></div><div class="pub-authors">Ting-Wei Li, <strong>Yuanchen Bei</strong>, Xiao Lin, Hanghang Tong</div><div class="pub-venue"><span class="pub-venue__name">NeurIPS 2026</span></div></li></ul>
</details>
<details class="pub-group">
<summary><span class="pub-group__title"><span class="pub-group__icon" aria-hidden="true">🔗</span>User Modeling, Personalization, and Recommendation</span><span class="pub-group__meta">5 papers · WWW'26 · KDD'25 · WSDM'25 · WWW'24 · NeurIPS'24</span></summary>
<ul class="pub-list"><li><div class="pub-title"><a href="https://doi.org/10.1145/3774904.3792800">AliBoostV2: CTR-Growth Balanced Boosting Framework in Billion-Scale Recommendation Platform</a></div><div class="pub-authors">Qijie Shen<sup>*</sup>, <strong>Yuanchen Bei</strong><sup>*</sup>, Zihong Huang, Xixian Wang, Zhibo Xiao, Dimin Wang, Jialin Zhu, Yuning Jiang, Feiran Huang, Hao Chen</div><div class="pub-venue"><span class="pub-venue__name">WWW 2026</span><span class="pub-tag">Applied at Alibaba</span></div></li><li><div class="pub-title"><a href="https://dl.acm.org/doi/10.1145/3711896.3737188">AliBoost: Ecological Boosting Framework in Alibaba Platform</a></div><div class="pub-authors">Qijie Shen<sup>*</sup>, <strong>Yuanchen Bei</strong><sup>*</sup>, Zihong Huang, Jialin Zhu, Keqin Xu, Boya Du, Jiawei Tang, Yuning Jiang, Feiran Huang, Xiao Huang, Hao Chen</div><div class="pub-venue"><span class="pub-venue__name">KDD 2025</span><span class="pub-tag">Applied at Alibaba</span></div></li><li><div class="pub-title"><a href="https://dl.acm.org/doi/10.1145/3701551.3703546">Large Language Model Simulator for Cold-Start Recommendation</a></div><div class="pub-authors">Feiran Huang, <strong>Yuanchen Bei</strong>, Zhenghang Yang, Junyi Jiang, Hao Chen, Qijie Shen, Senzhang Wang, Fakhri Karray, Philip S. Yu</div><div class="pub-venue"><span class="pub-venue__name">WSDM 2025</span><span class="pub-tag">Top-1 Most Cited Paper</span></div></li><li><div class="pub-title"><a href="https://dl.acm.org/doi/10.1145/3589334.3645517">Macro Graph Neural Networks for Online Billion-Scale Recommender Systems</a></div><div class="pub-authors">Hao Chen<sup>*</sup>, <strong>Yuanchen Bei</strong><sup>*</sup>, Qijie Shen, Yue Xu, Sheng Zhou, Wenbing Huang, Feiran Huang, Senzhang Wang, Xiao Huang</div><div class="pub-venue"><span class="pub-venue__name">WWW 2024</span><span class="pub-tag">Top-10 Influential Paper</span><span class="pub-tag">Applied at Alibaba</span></div></li><li><div class="pub-title"><a href="https://proceedings.neurips.cc/paper_files/paper/2024/hash/10d52f5d2ef0f69ac10da7c962fb6db9-Abstract-Conference.html">Fine-Tuning Out-of-Vocabulary Item Recommendation with User Sequence Imagination</a></div><div class="pub-authors">Ruochen Liu, Hao Chen, <strong>Yuanchen Bei</strong>, Qijie Shen, Fangwei Zhong, Senzhang Wang, Jianxin Wang</div><div class="pub-venue"><span class="pub-venue__name">NeurIPS 2024</span><span class="pub-tag">Spotlight</span><span class="pub-tag">Top 2%</span></div></li></ul>
</details>
<details class="pub-group">
<summary><span class="pub-group__title"><span class="pub-group__icon" aria-hidden="true">📐</span>Graph Representation Learning</span><span class="pub-group__meta">3 papers · KDD'25 · NeurIPS'25</span></summary>
<ul class="pub-list"><li><div class="pub-title"><a href="https://arxiv.org/abs/2606.31166">TAG-DLM: Diffusion Language Models for Text-Attributed Graph Learning</a></div><div class="pub-authors">Lingjie Chen<sup>*</sup>, <strong>Yuanchen Bei</strong><sup>*</sup>, Haobo Xu<sup>*</sup>, Yanjun Zhao, Yuzhong Chen, Hanghang Tong</div></li><li><div class="pub-title"><a href="https://dl.acm.org/doi/10.1145/3690624.3709197">Correlation-Aware Graph Convolutional Networks for Multi-Label Node Classification</a></div><div class="pub-authors"><strong>Yuanchen Bei</strong>, Weizhi Chen, Hao Chen, Sheng Zhou, Carl Yang, Jiapei Fan, Longtao Huang, Jiajun Bu</div><div class="pub-venue"><span class="pub-venue__name">KDD 2025</span></div></li><li><div class="pub-title"><a href="https://openreview.net/pdf/0447b73eb0fd4156c928c524b67af251008e70a4.pdf">Understanding and Enhancing Message Passing on Heterophilic Graphs via Compatibility Matrix</a></div><div class="pub-authors">Zhuonan Zheng, <strong>Yuanchen Bei</strong>, Zhiyao Zhou, Sheng Zhou, Yao Ma, Ming Gu, Hongjia Xu, Jiawei Chen, Jiajun Bu</div><div class="pub-venue"><span class="pub-venue__name">NeurIPS 2025</span></div></li></ul>
</details>
<p class="pub-note"><sup>*</sup> Equal contribution. See <a href="https://scholar.google.com/citations?user=7XFbwrcAAAAJ">Google Scholar</a> for the full publication list.</p>
</div>

---

<span class='anchor' id='-open-source-projects'></span>

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
  <li><span class="info-list__label">Conference Program Committee Member:</span> KDD (2024–2027), ICLR (2025–2027), WWW (2026–2027), WSDM (2026–2027), AAAI 2027, ICML 2026, NeurIPS 2026, ARR 2026, MM (2025–2026), CIKM (2025–2026), SIGIR 2025, SIGIR-AP 2025, ECAI 2024.</li>
  <li><span class="info-list__label">Journal Reviewer:</span> TMLR, IEEE TKDE, IEEE TNNLS, IEEE TII, IEEE TIP, ACM CSUR, ACM TKDD.</li>
</ul>


{% comment %}
Experiences is hidden for now. To show it again, remove this comment block
and restore the Experiences entry in _data/navigation.yml.

---
<span class='anchor' id='-experiences'></span>

## Experiences

<div class="exp-group">
<!--
<h3 class="exp-group__title">Internship</h3>
-->
<ul class="exp-list info-list">
  <li>
    <span class="exp-heading"><strong class="exp-company">NEC Laboratories America</strong><span class="exp-detail">Research Intern · 2026.05 – 2026.08 · Princeton, NJ, USA</span></span>
  </li>
  <li>
    <span class="exp-heading"><strong class="exp-company">Alibaba Group</strong><span class="exp-detail">Research Intern · 2023.05 – 2023.11, 2025.03 – 2025.06 · Hangzhou, China</span></span>
  </li>
  <li>
    <span class="exp-heading"><strong class="exp-company">The Hong Kong Polytechnic University</strong><span class="exp-detail">Research Assistant · 2024.06 – 2024.10 · Hong Kong SAR, China</span></span>
  </li>
  <li>
    <span class="exp-heading"><strong class="exp-company">Meituan</strong><span class="exp-detail">Research Intern · 2022.02 – 2022.08 · Beijing, China</span></span>
  </li>
</ul>
</div>

<!--
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
-->
{% endcomment %}

---
<span class='anchor' id='-misc'></span>

## Misc

In my free time, I enjoy learning about finance and the global economy, and I highly recommend <a href="https://www.youtube.com/@xiao_lin_shuo">小Lin说</a> for its engaging and accessible explainer videos. I’m also a movie lover (especially mysteries), a fan of <span class="kw kw--bare">Jisoo</span>, and a dog lover.

{% comment %}
<span class="research-collab">If you share any of these interests, feel free to reach out. I’d be happy to make new friends!</span>
{% endcomment %}

**Languages:** Chinese (native), English (fluent), and Cantonese (proficient listening).

<br>
