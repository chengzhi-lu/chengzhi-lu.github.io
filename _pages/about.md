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

Greetings! I am a Research Assistant in the Computer Science at Cloud and Distributed Systems (CDS) Lab at University of Macau (2021-Present), supervised by <span style="text-decoration: underline;">[Prof. Chengzhong Xu (须成忠)](https://www.fst.um.edu.mo/people/czxu/)</span>,  <span style="text-decoration: underline;">[Prof. Huanle Xu (徐欢乐)](https://www.fst.um.edu.mo/people/huanlexu)</span> and <span style="text-decoration: underline;">[Prof. Kejiang Ye (叶可江)](https://people.ucas.edu.cn/~kejiang?language=en)</span>. My research interests focus on cloud computing, serverless, systems for ML. <a href='https://scholar.google.com/citations?user=XRi4i9kAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>

<!-- My research interest includes neural machine translation and computer vision. I have published more than 100 papers at the top international AI conferences with total <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'>google scholar citations <strong><span id='total_cit'>260000+</span></strong></a> (You can also use google scholar badge <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>). -->


# 🔥 News
- *2024.07*: &nbsp;🎉🎉 Mudi is accepted by EuroSys 2025. 
- *2024.06*: &nbsp;🎉🎉 SMIless is accepted by SC 2024. 

# 📝 Publications 

<!-- <div class='paper-box'><div class='paper-box-image'><div><div class="badge">EuroSys 2025</div><img src='images/mudi.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Multiplexing Dynamic Deep Learning Workloads with SLO-awareness in GPU Clusters](https://openaccess.thecvf.com/content_cvpr_2016/papers/He_Deep_Residual_Learning_CVPR_2016_paper.pdf)

**Wenyan Chen**, Chengzhi Lu, Huanle Xu, Kejiang Ye, Chengzhong Xu.

[**Project**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=DhtAFkwAAAAJ&citation_for_view=DhtAFkwAAAAJ:ALROH1vI_8AC) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
</div>
</div> -->

- <span class="conf_title_badge">EuroSys 2025</span> <a href="pdfs/mudi.pdf">Multiplexing Dynamic Deep Learning Workloads with SLO-awareness in GPU Clusters</a>, Wenyan Chen, **Chengzhi Lu**, Huanle Xu, Kejiang Ye, Chengzhong Xu. 

- <span class="conf_title_badge">SC 2024</span> [SMIless: Serving DAG-based Inference with Dynamic Invocations under Serverless Computing](https://dl.acm.org/doi/pdf/10.1109/SC41406.2024.00044), **Chengzhi Lu**, Huanle Xu, Yudan Li, Wenyan Chen, Kejiang Ye, Chengzhong Xu. <span class='show_paper_citations' data='WKFOF1cAAAAJ:ufrVoPGSRksC'></span>

- <span class="conf_title_badge">ICWS 2024</span> [Planck: Optimizing LLM Inference Performance in Pipeline Parallelism with Fine-Grained SLO Constraint](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10707384), Yanying Lin, Shijie Peng, Shuaipeng Wu, Yanbo Li, **Chengzhi Lu**, Chengzhong Xu, Kejiang Ye. <span class='show_paper_citations' data='XRi4i9kAAAAJ:HDshCWvjkbEC'></span>

- <span class="conf_title_badge">EuroSys 2023</span> [Understanding and Optimizing Workloads for Unified Resource Management in Large Cloud Platforms](https://dl.acm.org/doi/pdf/10.1145/3552326.3587437), **Chengzhi Lu**, Huanle Xu, Kejiang Ye, Guoyao Xu, Liping Zhang, Guodong Yang, Chengzhong Xu. <span class='show_paper_citations' data='XRi4i9kAAAAJ:Se3iqnhoufwC'></span>

- <span class="conf_title_badge">TPDS 2022</span> [An in-depth study of microservice call graph and runtime performance](https://ieeexplore.ieee.org/abstract/document/9774016), Shutian Luo, Huanle Xu, **Chengzhi Lu**, Kejiang Ye, Guoyao Xu, Liping Zhang, Jian He, Chengzhong Xu. <span class='show_paper_citations' data='XRi4i9kAAAAJ:W7OEmFMy1HYC'></span>

- <span class="conf_title_badge">SoCC 2021</span> [Characterizing Microservice Dependency and Performance: Alibaba Trace Analysis](https://ieeexplore.ieee.org/abstract/document/9774016), Shutian Luo, Huanle Xu, **Chengzhi Lu**, Kejiang Ye, Guoyao Xu, Liping Zhang, Yu Ding, Jian He, Chengzhong Xu. <span class="best_paper_badge">Best Paper Award</span> <span class='show_paper_citations' data='XRi4i9kAAAAJ:LkGwnXOMwfcC'></span>

- <span class="conf_title_badge">CLUSTER 2021</span> [RPTCN: Resource prediction for high-dynamic workloads in clouds based on deep learning](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9556034), Wenyan Chen, **Chengzhi Lu**, Kejiang Ye, Yang Wang, Chengzhong Xu. <span class='show_paper_citations' data='WKFOF1cAAAAJ:Tyk-4Ss8FVUC'></span> 

- <span class="conf_title_badge">HPBD&IS 2020</span> [Understanding the workload characteristics in alibaba: A view from directed acyclic graph analysis](https://ieeexplore.ieee.org/abstract/document/9130578/), **Chengzhi Lu**, Wenyan Chen, Kejiang Ye, Cheng-Zhong Xu. <span class='show_paper_citations' data='XRi4i9kAAAAJ:Y0pCki6q_DkC'></span> 

- <span class="conf_title_badge">HPCC 2020</span> [Interference analysis of co-located container workloads: a perspective from hardware performance counters](https://ieeexplore.ieee.org/abstract/document/9130578/), Wenyan Chen, Kejiang Ye, **Chengzhi Lu**, Dongdai Zhou, Chengzhong Xu. <span class='show_paper_citations' data='XRi4i9kAAAAJ:YsMSGLbcyi4C'></span> 

- <span class="conf_title_badge">ICPADS 2020</span> [ADGS: anomaly detection and localization based on graph similarity in container-based clouds](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8975844), **Chengzhi Lu**, Kejiang Ye, Wenyan Chen, Chengzhong Xu. <span class='show_paper_citations' data='WKFOF1cAAAAJ:d1gkVwhDpl0C'></span> 

- <span class="conf_title_badge">ICPADS 2018</span> [Modeling application performance in docker containers using machine learning techniques](https://ieeexplore.ieee.org/abstract/document/8644581/), Kejiang Ye, Yanmin Kou, **Chengzhi Lu**, Yang Wang, Chengzhong Xu. <span class='show_paper_citations' data='XRi4i9kAAAAJ:_FxGoFyzp5QC'></span> 

- <span class="conf_title_badge">BigData 2017</span> [Imbalance in the cloud: An analysis on alibaba cluster trace](https://ieeexplore.ieee.org/abstract/document/8258257/), **Chengzhi Lu**, Kejiang Ye, Guoyao Xu, Cheng-Zhong Xu, Tongxin Bai. <span class='show_paper_citations' data='XRi4i9kAAAAJ:WF5omc3nYNoC'></span> 

# 🎖 Honors and Awards
- *2021-2024*, Dean’s award for academic performance, SIAT, CAS
- *2022.01*, Outstanding student, UCAS
- *2019.02*, Outstanding student, SIAT, CAS
- *2018.07*, Outstanding graduates, ZJU

# 📖 Educations
- *2019.09 - now*, PhD, Computer Science, University of Chinese Academy of Sciences.
- *2016.09 - 2018.09*, Master. Software Engineering, Zhejiang University.
- *2012.09 - 2016.06*, BS, Computer Science, Wuhan University. 

# 💬 Talks
- *2024.12*, ChinaSys 2024 Fall，SMIless: Serving DAG-based Inference with Dynamic Invocations under Serverless Computing. *Tianjin, China*  
- *2024.11*, ShanCheng Conference 2024，SMIless: Serving DAG-based Inference with Dynamic Invocations under Serverless Computing. *Chongqing, China*
- *2024.11*, SC 2024，SMIless: Serving DAG-based Inference with Dynamic Invocations under Serverless Computing. *Atlanta, USA*

# 🧑‍🎨 Teaching
- *2021 Winter*, Teaching Assistant. Computer Network, SIAT.

# 💻 Internships
- *2022.02-now*, University of Macau, Reseach Assistant.
- *2020.01-2021.02*, Alibaba Group, Reseach Intern.