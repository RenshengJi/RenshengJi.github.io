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

I am currently a **Senior Undergraduate** student majoring in [Computer Science and Technology at College of Intelligence and Computing, Tianjin University](https://cic.tju.edu.cn/). I am interested in Machine Learning, Computer Vision, and Robotics. I will join the [New Laboratory of Pattern Recognition, Institute of Automation, Chinese Academy of Sciences](http://www.cripac.ia.ac.cn/CN/model/index.htm) to pursue my PhD in the fall of 2025, under the guidance of Professor [Zhang Zhaoxiang](https://people.ucas.ac.cn/~zhangzhaoxiang).

<!-- I have published more than 100 papers at the top international AI conferences with total <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'>google scholar citations <strong><span id='total_cit'>260000+</span></strong></a> (You can also use google scholar badge <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>). -->

<!-- # 🔥 News

- _2024.05_: &nbsp;🎉🎉 My paper "Controllable Continual Test-Time Adaptation" has been published, and I welcome everyone to discuss it. The paper can be accessed on [arXiv](https://arxiv.org/abs/2405.14602), and the code is available on [GitHub](https://github.com/RenshengJi/C-CoTTA). -->

# 📝 Publications

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Arxiv</div><img src='images/1.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**Controllable Continual Test-Time Adaptation**

**Ziqi Shi**,Fan Lyu,Ye Liu,...,Wei Feng,Zhang Zhang,Liang Wang

[[paper]](https://arxiv.org/abs/2405.14602) [[code]](https://github.com/RenshengJi/C-CoTTA)

<strong><span class='show_paper_citations' data='XUaL4MMAAAAJ:qjMakFHDy7sC'></span></strong>

We propose $\textbf{C}$ontrollable $\textbf{Co}$ntinual $\textbf{T}$est-$\textbf{T}$ime $\textbf{A}$daptation (C-CoTTA), which explicitly prevents any single category from encroaching on others, thereby mitigating the mutual influence between categories caused by uncontrollable shifts. Moreover, our method reduces the sensitivity of model to domain transformations, thereby minimizing the magnitude of category shifts.

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Arxiv</div><img src='images/2.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**Conformal Uncertainty Indicator for Continual Test-Time Adaptation**

Fan Lyu, Hanyu Zhao, **Ziqi Shi**,..., Zhang Zhang, Liang Wang

[[paper]](https://arxiv.org/abs/2502.02998) [[code]](https://github.com/RenshengJi/TUI)

<!-- <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong> -->

we propose a Conformal Uncertainty Indicator (CUI) for CTTA, leveraging Conformal Prediction (CP) to generate prediction sets that include the true label with a specified coverage probability. Since domain shifts can lower the coverage than expected, making CP unreliable, we dynamically compensate for the coverage by measuring both domain and data differences. Reliable pseudo-labels from CP are then selectively utilized to enhance adaptation.

</div>
</div>

<!--
- [Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet](https://github.com), A, B, C, **CVPR 2020** -->

<!-- # 🎖 Honors and Awards -->
<!-- - *2021.10* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.
- *2021.09* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  -->

# 📖 Educations

- _2022.09 - Present_, [College of Intelligence and Computing, Tianjin University](https://cic.tju.edu.cn/)

<!-- # 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/) -->

# 💻 Internships

- _2024.04 - Present_, [New Laboratory of Pattern Recognition, Institute of Automation, Chinese Academy of Sciences](http://www.cripac.ia.ac.cn/CN/model/index.htm).

# 📖 Service

- _2024.08 - Present_, captain of the [Peiyang Robot Team](https://space.bilibili.com/520634089), Tianjin University.
- ICLR 2025 Reviewer.
- ICME 2025 Reviewer.
