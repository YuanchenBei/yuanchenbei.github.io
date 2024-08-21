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
I am now a final-year master's student in the College of Computer Science and Technology, Zhejiang University, advised by Prof. [Sheng Zhou](https://scholar.google.com/citations?user=Ss76nMwAAAAJ) and Prof. [Jiajun Bu](https://scholar.google.com/citations?user=OgZP2okAAAAJ). I also work closely with Dr. [Hao Chen](https://scholar.google.com/citations?user=7oeLWT0AAAAJ), Prof. [Xiao Huang](https://scholar.google.com/citations?user=Be21PkYAAAAJ) at PloyU and Prof. [Feiran Huang](https://scholar.google.com/citations?user=of1vcxsAAAAJ) at JNU.

*"There should be (explicit/implicit) relations among real-world data."* My research interests currently include **graph learning**, **relation foundation models**, **recommender systems**, and **multi-modal relation learning**. In my free time, I am also interested in finance and economics. Please kindly reach out to me if you have any questions or cooperation interests.

👨‍💻‍ <font color="#dd0000">I am actively looking for Ph.D. opportunities in Summer/Fall 2025, and I sincerely appreciate any opportunity!</font> It is my [curriculum vitae](https://github.com/YuanchenBei/yuanchenbei.github.io/blob/main/cv/resume_yuanchen.pdf).


<span class='anchor' id='-news'></span>

# News
- *2024.07*: &nbsp;📚📚 Invited as the reviewer for **KDD 2025**.
- *2024.05*: &nbsp;🎉🎉 Our paper "**Multi-Behavior Collaborative Filtering with Partial Order Graph Convolutional Networks**" is accepted by KDD 2024.
- *2024.05*: &nbsp;📚📚 Invited as the reviewer for **IEEE TII** and **IEEE TKDE**.
- *2024.01*: &nbsp;🎉🎉 Our paper "**Macro Graph Neural Networks for Online Billion-Scale Recommender Systems**" is accepted by TheWebConf 2024.
- *2023.12*: &nbsp;🎉🎉 Our paper "**CPDG: A Contrastive Pre-Training Method for Dynamic Graph Neural Networks**" is accepted by ICDE 2024.
- *2023.09*: &nbsp;🎉🎉 Our paper "**Reinforcement Neighborhood Selection for Unsupervised Graph Anomaly Detection**" is accepted by ICDM 2023.


<span class='anchor' id='-publications'></span>

# Publications 

***Conference Papers (\* equal-contributed):***

- [6] [Multi-Behavior Collaborative Filtering with Partial Order Graph Convolutional Networks](https://arxiv.org/pdf/2402.07659.pdf). (KDD, 2024) **[Applied in Alibaba Taobao]**

  Yijie Zhang\*, **<u>Yuanchen Bei</u>\***, Hao Chen\*, Qijie Shen, Zheng Yuan, Huan Gong, Senzhang Wang, Feiran Huang, and Xiao Huang.

- [5] [Macro Graph Neural Networks for Online Billion-Scale Recommender Systems](https://dl.acm.org/doi/10.1145/3589334.3645517). (TheWebConf, 2024) **[Applied in Alibaba Taobao]**

  Hao Chen\*, **<u>Yuanchen Bei</u>\***, Qijie Shen, Yue Xu, Sheng Zhou, Wenbing Huang, Feiran Huang, Senzhang Wang, and Xiao Huang.

- [4] [CPDG: A Contrastive Pre-Training Method for Dynamic Graph Neural Networks](https://ieeexplore.ieee.org/abstract/document/10598011). (ICDE, 2024)
  
  **<u>Yuanchen Bei</u>**, Hao Xu, Sheng Zhou, Huixuan Chi, Haishuai Wang, Mengdi Zhang, Zhao Li, and Jiajun Bu.

- [3] [Feedback Reciprocal Graph Collaborative Filtering](https://arxiv.org/pdf/2408.02404). (CIKM, 2024)

  Weijun Chen\*, **<u>Yuanchen Bei</u>\***, Qijie Shen, Hao Chen, Xiao Huang, and Feiran Huang.

- [2] [Reinforcement Neighborhood Selection for Unsupervised Graph Anomaly Detection](https://ieeexplore.ieee.org/abstract/document/10415759). (ICDM, 2023)

  **<u>Yuanchen Bei</u>**, Sheng Zhou, Qiaoyu Tan, Hao Xu, Hao Chen, Zhao Li, and Jiajun Bu.
  
- [1] [Non-Recursive Cluster-Scale Graph Interacted Model for Click-Through Rate Prediction](https://dl.acm.org/doi/10.1145/3583780.3615180). (CIKM, 2023)
  
  **<u>Yuanchen Bei</u>**, Hao Chen, Shengyuan Chen, Xiao Huang, Sheng Zhou, and Feiran Huang.


***Preprint Papers (\* equal-contributed):***
- [4] [Revisiting the Message Passing in Heterophilous Graph Neural Networks](https://arxiv.org/pdf/2405.17768).

  Zhuonan Zheng, **<u>Yuanchen Bei</u>**, Sheng Zhou, Yao Ma, Ming Gu, Hongjia Xu, Chengyu Lai, Jiawei Chen, and Jiajun Bu.

- [3] [Better Late Than Never: Formulating and Benchmarking Recommendation Editing](https://arxiv.org/pdf/2406.04553).
  
  Chengyu Lai, Sheng Zhou, Zhimeng Jiang, Qiaoyu Tan, **<u>Yuanchen Bei</u>**, Jiawei Chen, Ningyu Zhang, and Jiajun Bu.

- [2] [Guarding Graph Neural Networks for Unsupervised Graph Anomaly Detection](https://arxiv.org/pdf/2404.16366).

  **<u>Yuanchen Bei</u>**, Sheng Zhou, Jinke Shi, Yao Ma, Haishuai Wang, and Jiajun Bu.

- [1] [Large Language Model Interaction Simulator for Cold-Start Item Recommendation](https://arxiv.org/pdf/2402.09176.pdf).

  Feiran Huang, Zhenghang Yang\*, Junyi Jiang\*, **<u>Yuanchen Bei</u>\***, Yijie Zhang, and Hao Chen.

***Workshop Papers:***
- [3] [Alleviating Behavior Data Imbalance for Multi-Behavior Graph Collaborative Filtering](https://ieeexplore.ieee.org/abstract/document/10411514). (IWLKG@ICDM, 2023)

  Yijie Zhang, **<u>Yuanchen Bei</u>**, Shiqi Yang, Hao Chen, Zhiqing Li, Lijia Chen, and Feiran Huang.

- [2] [Modeling Spatiotemporal Periodicity and Collaborative Signal for Local-Life Service Recommendation](https://arxiv.org/pdf/2309.12565.pdf). (KDAH@CIKM, 2023)

  Huixuan Chi, Hao Xu, Mengya Liu, **<u>Yuanchen Bei</u>**, Sheng Zhou, Danyang Liu, and Mengdi Zhang.

- [1] [Flattened Graph Convolutional Networks For Recommendation](https://arxiv.org/pdf/2210.07769.pdf). (DLP@KDD, 2022)

  Yue Xu, Hao Chen, Zengde Deng, **<u>Yuanchen Bei</u>**, and Feiran Huang.

***Patents:***

- [2] Text Sentiment Analysis Method Based on Multi-Level Graph Pooling. (US Patent, No. 11,687,728, 2023)

  Feiran Huang, Zhiquan Liu, and **<u>Yuanchen Bei</u>**.

- [1] Social Recommendation Method Based on Multi-Feature Heterogeneous Graph Neural Networks. (US Patent, No. 11,631,147, 2023)

  Feiran Huang, Guan Liu, and **<u>Yuanchen Bei</u>**.

# Selected Open-Source Project
- [ColdRec: A Comprehensive Benchmark for Cold-Start Recommendation](https://github.com/YuanchenBei/ColdRec). (A Comprehensive Open-Source Toolkit for Cold-Start Recommendations) ![GitHub stars](https://img.shields.io/github/stars/YuanchenBei/ColdRec)

  *Include 20+ cold-start recommendation models with comprehensive evaluations.*
  
- [DreamerGPT: Chinese Instruction-tuning for Large Language Model](https://github.com/DreamerGPT/DreamerGPT). (Instruction Tuning for Open-Source LLMs with Chinese Corpus) ![GitHub stars](https://img.shields.io/github/stars/DreamerGPT/DreamerGPT)

- [Graph Pre-Training Library](https://github.com/YuanchenBei/Awesome-Pretraining-for-Graph-Neural-Networks). (A Comprehensive Library of Graph Pre-Training Literature) ![GitHub stars](https://img.shields.io/github/stars/YuanchenBei/Awesome-Pretraining-for-Graph-Neural-Networks) 

- [Cold-Start Recommendation Library](https://github.com/YuanchenBei/Awesome-Cold-Start-Recommendation). (A Comprehensive Library of Cold-Start Recommendation Literature) ![GitHub stars](https://img.shields.io/github/stars/YuanchenBei/Awesome-Cold-Start-Recommendation)

- [DGraph-Fin Leaderboard](https://dgraph.xinye.com/leaderboards/dgraphfin). (A Large-Scale Dynamic Graph Anomaly Detection Leaderboard) 🥈 **Top-2 Solution**


<span class='anchor' id='-honors-and-awards'></span>

# Honors and Awards
- *2023.11*, First Class Scholarship, Zhejiang University.
- *2022.06*, Outstanding Undergraduate Student & Thesis.
- *2021.12*, National Scholarship.
- *2020.05*, First Class Scholarship, Jinan University.


<span class='anchor' id='-educations'></span>

<!--# 📖 Educations-->
<!-- - *2022.09 - 2025.03 (expected)*, Master, [Zhejiang University](https://www.zju.edu.cn/english/), Hangzhou, China.-->
<!-- - *2018.09 - 2022.06*, Undergraduate, [Jinan University](https://english.jnu.edu.cn/), Guangzhou, China.-->


<span class='anchor' id='-academic-services'></span>

# Academic Services
- **Conference Reviewer:** KDD (2024, 2025), ECAI 2024.
- **Journal Reviewer:** ACM TKDD (Since 2023), IEEE TII (Since 2024), IEEE TKDE (Since 2024).


<span class='anchor' id='-experiences'></span>

# Experiences
- *2024.07 - 2024.09*, Research Assistant, DEEP Lab@[The Hong Kong Polytechnic University](https://www.polyu.edu.hk/), Hong Kong SAR, China.
- *2022.09 - 2025.03*, Research Assistant, Eagle Lab@[Zhejiang University](https://www.zju.edu.cn/english/), Hangzhou, China.
- *2023.06 - 2023.11*, Research Intern, CRO Security Technology Team@[Alibaba Group](https://www.alibabagroup.com/en-US), Hangzhou, China.
- *2022.02 - 2022.08*, Research Intern, NLP Center@[Meituan](https://www.meituan.com/en-US/about-us), Beijing, China.
- *2019.10 - 2022.01*, Research Assistant, RecSys Group@[Jinan University](https://english.jnu.edu.cn/), Guangzhou, China.
