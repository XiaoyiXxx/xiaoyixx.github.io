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

I am now a PhD student (2024-) in Computer Science and Technology at Shanxi University, supervised by Prof. [Zhiqiang Wang](https://cs.sxu.edu.cn/faculty/associate_professor/4760/index.htm). Before that, I received my B.S. degree from Taiyuan University of Science and Technology in 2022, majoring in Information and Computing Sciences.

My research interests focus on dynamic graph representation learning, including graph neural ODE, etc. I am also interested in AI for Science, such as infectious disease prediction based on spatiotemporal graph neural networks. If you are interested in discussing or collaborating with me, please feel free to contact me via [email](wwwxxyi@163.com).


# 🔥 News
- *2025.05*: &nbsp;🎉🎉 One paper on ControlSynth Graph NeuralODE is accepted in [ICML2025](https://icml.cc/) <font color=red> (CCF A, poster,26.9%/ 机器学习三大顶会之一) </font>
- *2025.01*: &nbsp;🎉🎉 One paper on infectious disease prediction based on spatiotemporal graph neural networks is accepted in [Plos Computational Biology](https://journals.plos.org/ploscompbiol/) <font color=red> (CCF B, SCI 2区) </font>

# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICML 2025</div><img src='images/ICML2025.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[CSG-ODE: ControlSynth Graph ODE For Modeling Complex Evolution of Dynamic Graphs](https://openaccess.thecvf.com/content_cvpr_2016/papers/He_Deep_Residual_Learning_CVPR_2016_paper.pdf)

Zhiqiang Wang, Xiaoyi Wang, Jianqing Liang

- (1) We propose the CSG-ODE model, which enables the model to better capture the complex evolution of node states through an information propagation-based inter-node importance weighting method and multiple sub-networks with nonlinear activation functions. (2) Based on CSG-ODE, we theoretically give its stabilized version SCSG-ODE. (3) The experimental results show that the proposed CSG-ODE outperforms the existing GODE model on five dynamic system datasets. And SCSG-ODE not only outperforms the existing GODE in terms of performance, but also exhibits optimal stability.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Plos CB</div><img src='images/PCB.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Multi-region infectious disease prediction modeling based on spatio-temporal graph neural network and the dynamic model](https://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1012738)

Xiaoyi Wang, Zhen Jin

- We incorporate the Graphormer and graph learning mechanisms into the metapopulation SIR model to build a hybrid framework, Metapopulation Graph Transformer Neural Network (M-Graphormer), for high-dimensional parameter estimation and multi-regional epidemic prediction.
</div>
</div>


# 🎖 Honors and Awards
- *2024.06* The Third Class Award Scholarship of the Graduate School, Shanxi University, in 2024.
- *2023.06* The Second Class Award Scholarship of the Graduate School, Shanxi University, in 2023. 

# 📖 Educations
- *2024.09 - 2028.6(now)*, School of Computer and Information Technology, Shanxi University. Ph.D. Student. 
- *2022.09 - 2024.06*, School of Mathematics and Statistics, Shanxi University. MS. Student.
- *2018.09 - 2022.06*, School of Applied Sciences, Taiyuan University of Science and Technology. Undergrad. Student.

# 💬 Invited Talks
- None


# 💻 Internships
- *2021.05 - 2021.07*, [Beijing](https://github.com/), China.
