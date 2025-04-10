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

I am currently a **Senior Undergraduate** student majoring in [Computer Science and Technology at College of Intelligence and Computing, Tianjin University](https://cic.tju.edu.cn/). I am interested in Machine Learning, Computer Vision, and Robotics. I will join the [New Laboratory of Pattern Recognition, Institute of Automation, Chinese Academy of Sciences](http://www.cripac.ia.ac.cn/CN/model/index.htm) to pursue my PhD in the fall of 2025,
supervised by Ap. [Lue Fan](https://lue.fan) Prof. [Zhaoxiang Zhang](https://people.ucas.ac.cn/~zhangzhaoxiang).

<!-- I have published more than 100 papers at the top international AI conferences with total <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'>google scholar citations <strong><span id='total_cit'>260000+</span></strong></a> (You can also use google scholar badge <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>). -->

# 🔥 News

- _2025.03_: &nbsp;🎉🎉 I joined [Li Auto](https://www.liauto.com) as an intern, and the research content was 4D feed forward reconstruction of driving scene.
- _2025.03_: &nbsp;🎉🎉 My first paper "Controllable Continual Test-Time Adaptation" has been accepted by ICME25, and I welcome everyone to discuss it. The paper can be accessed on [arXiv](https://arxiv.org/abs/2405.14602), and the code is available on [GitHub](https://github.com/RenshengJi/C-CoTTA).

# 📝 Publications

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICME 25</div><img src='images/1.png' alt="sym" width="100%"></div></div>
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

# 📝 Projects

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Github</div><img src='images/3.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**TJURM-Radar**

[[code]](https://github.com/RenshengJi/TJURM-Radar)

This project implements the radar station robot functionality in Robomaster competitions using two approaches: monocular RGB and RGB + LiDAR fusion. Both methods employ 4K images captured by industrial RGB cameras as direct inputs for target detection models to identify and locate all robots on the field. In the monocular RGB approach, the camera’s extrinsic parameters are calibrated using large-scale PnP to establish the relationship between the camera and field coordinate systems. Depth information is then obtained through 3D structure rendering of the field. For the RGB + LiDAR fusion approach, the robot’s onboard LiDAR provides more precise depth information for targets, enhancing localization accuracy. This integration leverages the complementary strengths of RGB cameras and LiDAR, where RGB images offer rich texture and color information, while LiDAR supplies accurate depth data.

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Github</div><img src='images/4.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**TJURM-AutoDrive**

[[code]](https://github.com/RenshengJi/TJURM-AD)

This project leverages a large collection of first-person videos from Robomaster competitions to extract the movement trajectories of robots within the mini-map using traditional computer vision algorithms. These trajectories and videos form the basis of an autonomous driving dataset. By extracting image features through common backbone networks and employing GRU for trajectory prediction, the autonomous driving model in the Robomaster context goes beyond navigation and obstacle avoidance. It also incorporates trajectory planning (deciding its own route, unlike in traditional cars where this is determined by road planning algorithms) and autonomous decision-making (choosing where to go, unlike in traditional cars where this is specified by the driver). These three capabilities correspond to increasingly distant prediction horizons. **(The project is currently in active development, and interested parties are welcome to get in touch.)**

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Github</div><img src='images/5.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**TJURM-ArmorDiffuse**

[[code]](https://github.com/RenshengJi/TJURM-AD)

This project addresses the challenges of limited datasets and high annotation costs in Robomaster competitions by leveraging existing data and employing diffusion models to augment the dataset. Specifically, we designed a keypoint-conditional generation model to produce datasets that inherently contain the labels required for training detection models. Unlike existing approaches such as ControlNet, which inefficiently render keypoints as images, we innovatively use vector inputs directly as conditions. Extensive experiments have validated the effectiveness of our conditional generation approach.

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Github</div><img src='images/6.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**TJURM-Detector**

[[code]](https://github.com/RenshengJi/TJURM-AD)

The customized key point detection model for Robomaster competition, modified from Yolov5, supports the key point detection of armor plate and energy mechanism, and provides the coordinates of points in the image coordinate system for the subsequent PnP positioning algorithm. Deploy to the Jetson Xavier NX edge computing device to accelerate inference using TensorRT while using knowledge distillation to achieve lossless compression of the model for faster inference.

</div>
</div>

<!--
- [Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet](https://github.com), A, B, C, **CVPR 2020** -->

<!-- # 🎖 Honors and Awards -->
<!-- - *2021.10* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.
- *2021.09* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  -->

# 📖 Educations

- _2022.09 - Present_, [College of Intelligence and Computing, Tianjin University](https://cic.tju.edu.cn/)

# 💻 Internships

- _2025_, [Li Auto](https://www.liauto.com).
- _2024_, [New Laboratory of Pattern Recognition, Institute of Automation, Chinese Academy of Sciences](http://www.cripac.ia.ac.cn/CN/model/index.htm).
- _2023_, [Natural Language Processing Group, Department of Computer Science and Technology, Nanjing University](http://nlp.nju.edu.cn/homepage/).
- _2024_, [Visual Intelligence Lab, Tianjin University](http://www.tjuvil.net/default.aspx).
- _2024_, [Lab of Machine Learning and Data Mining, Tianjin University](http://datasci.tju.edu.cn/).

# 📖 Service

- _2024.08 - 2025.02_, captain of the [Peiyang Robot Team](https://space.bilibili.com/520634089), Tianjin University.

<!-- ![image](images/7.png) -->

- Reviewer: ICLR25、ICME25.
