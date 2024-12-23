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

# Yuanchen Bei
I am now a final-year master's student in the College of Computer Science and Technology, Zhejiang University, advised by Prof. [Sheng Zhou](https://scholar.google.com/citations?user=Ss76nMwAAAAJ) and Prof. [Jiajun Bu](https://scholar.google.com/citations?user=OgZP2okAAAAJ). I also work closely with Prof. [Hao Chen](https://scholar.google.com/citations?user=7oeLWT0AAAAJ) at Macau CityU, Prof. [Feiran Huang](https://scholar.google.com/citations?user=of1vcxsAAAAJ) at JNU, and Prof. [Xiao Huang](https://scholar.google.com/citations?user=Be21PkYAAAAJ) at PolyU. They are all very supportive and kind.

*"There should be (explicit/implicit) relations among real-world data."* My research interests currently include **graph machine learning**, **large-scale relational data mining**, **relation foundation models**, and **relational knowledge discovery for social science**. In my free time, I am also interested in finance and economics. Please kindly reach out to me if you have any questions or cooperation interests.

👨‍💻‍ <font color="#dd0000">I am actively looking for Ph.D. opportunities in Fall 2025, and I sincerely appreciate potential opportunities!</font> 


<span class='anchor' id='-news'></span>

# News
- 2024.11: &nbsp;🎉 Our paper on **GNNs for Ambiguous Classification** is accepted by KDD 2025.
- 2024.10: &nbsp;🎉 Our paper on **LLM-based User Behavior Simulator** is accepted by WSDM 2025.
- 2024.10: &nbsp;🎉 Our paper on **Correlation-based GNNs for Recommendation** is accepted by TKDE 2024.
- 2024.09: &nbsp;🎉 Our paper on **Out-of-Vocabulary Item Recommendation** is accepted by NeurIPS 2024 as a spotlight.
- 2024.09: &nbsp;📚 Invited as the reviewer for ICLR 2025.
- 2024.07: &nbsp;📚 Invited as the reviewer for KDD 2025.
- 2024.05: &nbsp;🎉 Our paper on **GNNs for User Multi-Behavior Modeling** is accepted by KDD 2024.
- 2024.01: &nbsp;🎉 Our paper on **Macro GNNs for Billion-Scale Recommendation** is accepted by WWW 2024.
- 2023.12: &nbsp;🎉 Our paper on **Dynamic GNN Pre-Training** is accepted by ICDE 2024.
- 2023.09: &nbsp;🎉 Our paper on **Neighborhood Selection for Unsupervised Graph Anomaly Detection** is accepted by ICDM 2023.


<span class='anchor' id='-publications'></span>

# Publications 

**Published Papers (\* Co-first author):**

- **Correlation-Aware Graph Convolutional Networks for Multi-Label Node Classification**. (KDD, 2025)

  **<u>Yuanchen Bei</u>**, Weizhi Chen, Hao Chen, Sheng Zhou, Carl Yang, Jiapei Fan, Longtao Huang, Jiajun Bu.

  <a href="https://arxiv.org/pdf/2411.17350"><img src="https://img.shields.io/badge/📃 Paper-green.svg"></a> <a href="https://github.com/YuanchenBei/CorGCN"><img src="https://img.shields.io/badge/🖥 Code-yellow.svg"></a> <img src="https://img.shields.io/badge/🌟 GNNs-orange.svg">

- **LLM Behavior Simulator for Online Billion-Scale Item Cold-Start Recommendation**. (WSDM, 2025)
  
  Feiran Huang, **<u>Yuanchen Bei</u>**, Zhenghang Yang, Junyi Jiang, Hao Chen, Qijie Shen, Senzhang Wang, Fakhri Karray, Philip Yu.

  <a href="https://arxiv.org/pdf/2402.09176"><img src="https://img.shields.io/badge/📃 Paper (Previous Version)-green.svg"></a> <img src="https://img.shields.io/badge/🌟 LLMs, Cold Start RecSys-orange.svg">

- **Macro Graph Neural Networks for Online Billion-Scale Recommender Systems**. (WWW, 2024) 
  
  Hao Chen\*, **<u>Yuanchen Bei</u>\***, Qijie Shen, Yue Xu, Sheng Zhou, Wenbing Huang, Feiran Huang, Senzhang Wang, and Xiao Huang.

  <img src="https://img.shields.io/badge/🔧 Applied in Alibaba Taobao-blue.svg">
  <a href="https://www.paperdigest.org/2024/09/most-influential-www-papers-2024-09/"><img src="https://img.shields.io/badge/🔥 Top 10 Influential Paper in WWW2024-red.svg"></a> 
  <a href="https://dl.acm.org/doi/10.1145/3589334.3645517"><img src="https://img.shields.io/badge/📃 Paper-green.svg"></a>
  <a href="https://github.com/YuanchenBei/MacGNN"><img src="https://img.shields.io/badge/🖥 Code-yellow.svg"></a>
  <img src="https://img.shields.io/badge/🌟 GNNs, Large Scale RecSys-orange.svg">
  

- **Multi-Behavior Collaborative Filtering with Partial Order Graph Convolutional Networks**. (KDD, 2024) 
  
  Yijie Zhang\*, **<u>Yuanchen Bei</u>\***, Hao Chen\*, Qijie Shen, Zheng Yuan, Huan Gong, Senzhang Wang, Feiran Huang, and Xiao Huang.

  <img src="https://img.shields.io/badge/🔧 Applied in Alibaba Taobao-blue.svg">
  <a href="https://dl.acm.org/doi/abs/10.1145/3637528.3671569"><img src="https://img.shields.io/badge/📃 Paper-green.svg"></a>
  <a href="https://github.com/Wings236/POGCN"><img src="https://img.shields.io/badge/🖥 Code-yellow.svg"></a>
  <img src="https://img.shields.io/badge/🌟 GNNs, RecSys-orange.svg">

- **CPDG: A Contrastive Pre-Training Method for Dynamic Graph Neural Networks**. (ICDE, 2024) 
  
  **<u>Yuanchen Bei</u>**, Hao Xu, Sheng Zhou, Huixuan Chi, Haishuai Wang, Mengdi Zhang, Zhao Li, and Jiajun Bu.

  <a href="https://ieeexplore.ieee.org/abstract/document/10598011"><img src="https://img.shields.io/badge/📃 Paper-green.svg"></a> <a href="https://github.com/YuanchenBei/CPDG"><img src="https://img.shields.io/badge/🖥 Code-yellow.svg"></a> <img src="https://img.shields.io/badge/🌟 Dynamic Graph Pretraining-orange.svg">

- **Fine-Tuning Out-of-Vocabulary Item Recommendation with User Sequence Imagination**. (NeurIPS, 2024)
  
  Ruochen Liu, Hao Chen, **<u>Yuanchen Bei</u>**, Qijie Shen, Fangwei Zhong, Senzhang Wang, and Jianxin Wang.

  <a href="https://nips.cc/virtual/2024/poster/95688"><img src="https://img.shields.io/badge/🔥 Spotlight Paper in NeurIPS2024-red.svg"></a> <a href="https://nips.cc/virtual/2024/poster/95688"><img src="https://img.shields.io/badge/📃 Paper-green.svg"></a> <a href="https://github.com/Ruochen1003/USIM"><img src="https://img.shields.io/badge/🖥 Code-yellow.svg"></a> <img src="https://img.shields.io/badge/🌟 RL, Cold Start RecSys-orange.svg">

- **Graph Cross-Correlated Network for Recommendation**. (TKDE, 2024)

  Hao Chen\*, **<u>Yuanchen Bei</u>\***, Wenbing Huang, Shengyuan Chen, Feiran Huang, and Xiao Huang.

  <a href="https://arxiv.org/pdf/2411.01182"><img src="https://img.shields.io/badge/📃 Paper-green.svg"></a> <img src="https://img.shields.io/badge/🌟 GNNs, RecSys-orange.svg">

- **Feedback Reciprocal Graph Collaborative Filtering**. (CIKM, 2024) 
  
  Weijun Chen\*, **<u>Yuanchen Bei</u>\***, Qijie Shen, Hao Chen, Xiao Huang, and Feiran Huang.

  <a href="https://dl.acm.org/doi/10.1145/3627673.3680015"><img src="https://img.shields.io/badge/📃 Paper-green.svg"></a> <img src="https://img.shields.io/badge/🌟 GNNs, RecSys-orange.svg">

- **Reinforcement Neighborhood Selection for Unsupervised Graph Anomaly Detection**. (ICDM, 2023) 
  
  **<u>Yuanchen Bei</u>**, Sheng Zhou, Qiaoyu Tan, Hao Xu, Hao Chen, Zhao Li, and Jiajun Bu.

  <a href="https://ieeexplore.ieee.org/abstract/document/10415759"><img src="https://img.shields.io/badge/📃 Paper-green.svg"></a> <a href="https://github.com/YuanchenBei/RAND"><img src="https://img.shields.io/badge/🖥 Code-yellow.svg"></a> <img src="https://img.shields.io/badge/🌟 Graph Anomaly Detection-orange.svg">
  
- **Non-Recursive Cluster-Scale Graph Interacted Model for Click-Through Rate Prediction**. (CIKM, 2023) 
  
  **<u>Yuanchen Bei</u>**, Hao Chen, Shengyuan Chen, Xiao Huang, Sheng Zhou, and Feiran Huang.

  <a href="https://dl.acm.org/doi/10.1145/3583780.3615180"><img src="https://img.shields.io/badge/📃 Paper-green.svg"></a> <a href="https://github.com/YuanchenBei/NRCGI"><img src="https://img.shields.io/badge/🖥 Code-yellow.svg"></a> <img src="https://img.shields.io/badge/🌟 GNNs, RecSys-orange.svg">


**Preprint Papers:**
- **Revisiting the Message Passing in Heterophilous Graph Neural Networks**.
  
  Zhuonan Zheng, **<u>Yuanchen Bei</u>**, Sheng Zhou, Yao Ma, Ming Gu, Hongjia Xu, Chengyu Lai, Jiawei Chen, and Jiajun Bu.

  <a href="https://arxiv.org/pdf/2405.17768"><img src="https://img.shields.io/badge/📃 Paper-green.svg"></a> <a href="https://github.com/zfx233/CMGNN"><img src="https://img.shields.io/badge/🖥 Code-yellow.svg"></a> <img src="https://img.shields.io/badge/🌟 GNNs, Heterophily-orange.svg">

- **CLR-Bench: Evaluating Large Language Models in College-level Reasoning**.
  
  Junnan Dong, Zijin Hong, **<u>Yuanchen Bei</u>**, Feiran Huang, Xinrun Wang, Xiao Huang.

  <a href="https://arxiv.org/pdf/2410.17558"><img src="https://img.shields.io/badge/📃 Paper-green.svg"></a> <img src="https://img.shields.io/badge/🌟 LLMs, Benchmark-orange.svg">

- **Better Late Than Never: Formulating and Benchmarking Recommendation Editing**.
  
  Chengyu Lai, Sheng Zhou, Zhimeng Jiang, Qiaoyu Tan, **<u>Yuanchen Bei</u>**, Jiawei Chen, Ningyu Zhang, and Jiajun Bu.

  <a href="https://arxiv.org/pdf/2406.04553"><img src="https://img.shields.io/badge/📃 Paper-green.svg"></a> <a href="https://github.com/cycl2018/Recommendation-Editing"><img src="https://img.shields.io/badge/🖥 Code-yellow.svg"></a> <img src="https://img.shields.io/badge/🌟 RecSys Editing, Benchmark-orange.svg">

- **Guarding Graph Neural Networks for Unsupervised Graph Anomaly Detection**.

  **<u>Yuanchen Bei</u>**, Sheng Zhou, Jinke Shi, Yao Ma, Haishuai Wang, and Jiajun Bu.

  <a href="https://arxiv.org/pdf/2404.16366"><img src="https://img.shields.io/badge/📃 Paper-green.svg"></a> <img src="https://img.shields.io/badge/🌟 Graph Anomaly Detection-orange.svg">


**Workshop Papers:**
- **Alleviating Behavior Data Imbalance for Multi-Behavior Graph Collaborative Filtering**. (IWLKG@ICDM, 2023)

  Yijie Zhang, **<u>Yuanchen Bei</u>**, Shiqi Yang, Hao Chen, Zhiqing Li, Lijia Chen, and Feiran Huang.

  <a href="https://ieeexplore.ieee.org/abstract/document/10411514"><img src="https://img.shields.io/badge/📃 Paper-green.svg"></a> <img src="https://img.shields.io/badge/🌟 GNNs, RecSys-orange.svg">

- **Modeling Spatiotemporal Periodicity and Collaborative Signal for Local-Life Service Recommendation**. (KDAH@CIKM, 2023)

  Huixuan Chi, Hao Xu, Mengya Liu, **<u>Yuanchen Bei</u>**, Sheng Zhou, Danyang Liu, and Mengdi Zhang.

  <a href="https://arxiv.org/pdf/2309.12565.pdf"><img src="https://img.shields.io/badge/📃 Paper-green.svg"></a> <img src="https://img.shields.io/badge/🌟 GNNs, RecSys-orange.svg">

- **Flattened Graph Convolutional Networks For Recommendation**. (DLP@KDD, 2022)
  
  Yue Xu, Hao Chen, Zengde Deng, **<u>Yuanchen Bei</u>**, and Feiran Huang.

  <a href="https://arxiv.org/pdf/2210.07769.pdf"><img src="https://img.shields.io/badge/📃 Paper-green.svg"></a> <img src="https://img.shields.io/badge/🌟 GNNs, RecSys-orange.svg">

**Patents:**

- **Text Sentiment Analysis Method Based on Multi-Level Graph Pooling**. (US Patent, No. 11,687,728, 2023)

  Feiran Huang, Zhiquan Liu, and **<u>Yuanchen Bei</u>**.

- **Social Recommendation Method Based on Multi-Feature Heterogeneous Graph Neural Networks**. (US Patent, No. 11,631,147, 2023)

  Feiran Huang, Guan Liu, and **<u>Yuanchen Bei</u>**.

# Selected Open-Source Project
- **Graph Pre-Training Literature Library**.
   
  <a href="https://github.com/YuanchenBei/Awesome-Pretraining-for-Graph-Neural-Networks"><img src="https://img.shields.io/badge/📚 Library-yellow.svg"></a> <img src="https://img.shields.io/badge/🌟 GNNs, Pretraining-orange.svg"> ![GitHub stars](https://img.shields.io/github/stars/YuanchenBei/Awesome-Pretraining-for-Graph-Neural-Networks) 

- **Cold-Start Recommendation Literature Library**.
  
  <a href="https://github.com/YuanchenBei/Awesome-Cold-Start-Recommendation"><img src="https://img.shields.io/badge/📚 Library-yellow.svg"></a> <img src="https://img.shields.io/badge/🌟 Cold Start RecSys-orange.svg"> ![GitHub stars](https://img.shields.io/github/stars/YuanchenBei/Awesome-Cold-Start-Recommendation)

- **ColdRec: A Comprehensive Benchmark for Cold-Start Recommendation**. *Including 20+ cold-start recommendation models with comprehensive evaluations.*
  
  <a href="https://github.com/YuanchenBei/ColdRec"><img src="https://img.shields.io/badge/🖥 Code-yellow.svg"></a> <img src="https://img.shields.io/badge/🌟 Cold Start RecSys, Benchmark-orange.svg"> ![GitHub stars](https://img.shields.io/github/stars/YuanchenBei/ColdRec)
  
- **DreamerGPT: Instruction-Tuning for Large Language Model with Chinese Corpus**.
  
  <a href="https://github.com/DreamerGPT/DreamerGPT"><img src="https://img.shields.io/badge/🖥 Code-yellow.svg"></a> <img src="https://img.shields.io/badge/🌟 LLMs, Instruction Tuning-orange.svg"> ![GitHub stars](https://img.shields.io/github/stars/DreamerGPT/DreamerGPT)

- **DGraph-Fin: A Large-Scale Dynamic Graph Anomaly Detection Leaderboard**.
  
  <a href="https://dgraph.xinye.com/leaderboards/dgraphfin"><img src="https://img.shields.io/badge/🥈 Top 2 Solution-red.svg"></a> <a href="https://github.com/YuanchenBei/GraphTransformer-DGraphFin"><img src="https://img.shields.io/badge/🖥 Code-yellow.svg"></a> <img src="https://img.shields.io/badge/🌟 Graph Anomaly Detection-orange.svg">


<span class='anchor' id='-honors-and-awards'></span>

# Honors and Awards
- 2024.12, **Outstanding Reviewer**, KDD 2025. 
- 2024.11, **National Scholarship** (Top 1%, Master).
- 2023.11, **First Class Scholarship**, Zhejiang University.
- 2022.06, **Outstanding Undergraduate Student & Thesis**.
- 2021.12, **National Scholarship** (Top 1%, Bachelor).
- 2020.05, **First Class Scholarship**, Jinan University.


<span class='anchor' id='-educations'></span>

<!--# 📖 Educations-->
<!-- - *2022.09 - 2025.03 (expected)*, Master, [Zhejiang University](https://www.zju.edu.cn/english/), Hangzhou, China.-->
<!-- - *2018.09 - 2022.06*, Undergraduate, [Jinan University](https://english.jnu.edu.cn/), Guangzhou, China.-->


<span class='anchor' id='-academic-services'></span>

# Academic Services
- **Conference Reviewer:** KDD (2024, 2025), ICLR 2025, ECAI 2024.
- **Journal Reviewer:** ACM TKDD (Since 2023), IEEE TKDE (Since 2024), IEEE TNNLS (Since 2024), IEEE TII (Since 2024).


<span class='anchor' id='-experiences'></span>

# Experiences
- 2022.09 - 2025.03, Research Assistant, Eagle Lab@[Zhejiang University](https://www.zju.edu.cn/english/), Hangzhou, China.
- 2024.06 - 2024.10, Research Assistant, DEEP Lab@[The Hong Kong Polytechnic University](https://www.polyu.edu.hk/), Hong Kong SAR, China.
- 2023.05 - 2023.11, Research Intern, CRO Security Technology Team@[Alibaba Group](https://www.alibabagroup.com/en-US), Hangzhou, China.
- 2022.02 - 2022.08, Research Intern, NLP Center@[Meituan](https://www.meituan.com/en-US/about-us), Beijing, China.
- 2019.10 - 2022.01, Research Assistant, RecSys Group@[Jinan University](https://english.jnu.edu.cn/), Guangzhou, China.


<!--<div class="view_map">
  <script type='text/javascript' id='clustrmaps' src='//cdn.clustrmaps.com/map_v2.js?cl=ffffff&w=a&t=tt&d=E60zzjtnPC8oHVWucMY0taRLS2AF5THX_Xmr-TES7RU&co=227fc1'></script>
</div>-->
