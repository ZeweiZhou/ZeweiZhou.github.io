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

I am currently a master's student in the Institute of Intelligent Vehicles at Tongji University, co-advised by [Prof Yanjun Huang](https://scholar.google.com/citations?user=r_XUM78AAAAJ&hl=zh-CN) and Prof Zhuoping Yu. 

My research interests are in the intersection between autonomous driving and machine learning, whose goal is to enhance the safety of autonomous driving by developing algorithms and techniques that help the machine make intelligent decisions and plan trajectory. **I am searching for Ph.D. positions in related field. Please feel free to connect with me.**

# 📖 Educations
- *2020.09 - 2023.03*, Master of Science, Automotive Engineering, Tongji University (Tongji), Shanghai, China 
  - GPA: 5.00/5.00 (92.36/100)
  - Core Courses: System Identification (5.0/5.0), Modern Control Theory (5.0/5.0), Numerical Analysis (5.0/5.0)
- *2016.09 - 2020.06*, Bachelor of Engineering, Automotive Engineering, Chongqing University (CQU), Chongqing, China
  - GPA: 3.71/4.00 (94.89/100) | Comprehensive Ranking:  1^{st}/154 (Top 0.6%)
  - Core Courses: Mathematical Model (4.0/4.0), C Program Design (4.0/4.0), Fundamentals of Computer Technology (3.9/4.0), Calculus A (4.0/4.0), Linear Algebra (4.0/4.0), Probability and Statistics (4.0/4.0), Automobile Structure (4.0/4.0), Key Technologies of New Energy Vehicles (4.0/4.0), Fundamentals of Vehicle Dynamic and Control (4.0/4.0)

# 🔥 News
- *2022.08*: &nbsp;🎉🎉 Our paper on evolutionary decision-making and planning for autonomous driving has been submitted to _Engineering_, the official journal of the Chinese Academy of Engineering, and it is under reviewed now.
- *2022.07*: &nbsp;🎉🎉 Our paper on cooperative vehicle infrastructure system has been submitted to _IEEE Transactions on Intelligent Transportation System_, and it is under reviewed now.
- *2022.04*: &nbsp;🎉🎉 Our paper on trajectory-prediction methods for autonomous driving has been accepted by _IEEE Transactions on Intelligent Vehicles_! 
- *2022.03*: &nbsp;🎉🎉 Our paper on speed prediction in transportation system has been accepted by iScience from **Cell Press**！

# 📝 Publications 
<!--
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2016</div><img src='images/500x300.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Deep Residual Learning for Image Recognition](https://openaccess.thecvf.com/content_cvpr_2016/papers/He_Deep_Residual_Learning_CVPR_2016_paper.pdf)

**Kaiming He**, Xiangyu Zhang, Shaoqing Ren, Jian Sun

[**Project**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=DhtAFkwAAAAJ&citation_for_view=DhtAFkwAAAAJ:ALROH1vI_8AC) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
</div>
</div>

- [Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet](https://github.com), A, B, C, **CVPR 2020**
-->


<div class='paper-box'><div class='paper-box-image'><img src='images/Comprehensive_Study_of_Speed_Prediction.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

A Comprehensive Study of Speed Prediction in Transportation System: From Vehicle to Traffic

**Zewei Zhou**, Ziru Yang, Yuanjian Zhang, Yanjun Huang, Hong Chen, Zhuoping Yu

_**iScience (Cell Press)**_, 2022 

- We comprehensively analyze existing researches of speed prediction in transportation system at three levels, i.e. macro traffic, micro vehicles, and meso lane.
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><img src='images/Survey_on_Trajectory_Prediction_Methods.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

A Survey on Trajectory-Prediction Methods for Autonomous Driving

Kang Yuan, Yanjun Huang, Shuo Yang, **Zewei Zhou**, Yulei Wang, Dongpu Cao, Hong Chen

_**IEEE Transactions on Intelligent Vehicles**_, 2022

- We provide a comparative review of trajectory-prediction methods for autonomous driving and elaborate the popular methods based on physics, classic machine learning, deep learning, and reinforcement learning. 
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><img src='images/Evolutionary_Decision-Making_Planning.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

Evolutionary Decision-Making and Planning for Autonomous Driving based on Safe and Rational Exploration and Exploitation

Kang Yuan, Yanjun Huang, Shuo Yang, **Zewei Zhou**, Yulei Wang, Dongpu Cao, Hong Chen

_**Engineering**_, 2022 (under review)

- We propose a online-evolution framework of decision-making and planning for autonomous driving in the operating stage is proposed by developing a hybrid data and model-driven method based on DRL and MPC. 
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><img src='images/Cooperative_Vehicle_Infrastructure_System.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

Cooperative Vehicle Infrastructure System: Architecture, Functions and Future Challenges

Yangjie Ji, **Zewei Zhou**, Ziru Yang, Yanjun Huang, Hong Chen, Zhuoping Yu

_**IEEE Transactions on Intelligent Transportation System**_, 2022 (under review)

- We provide a comparative review of trajectory-prediction methods for autonomous driving and elaborate the popular methods based on physics, classic machine learning, deep learning, and reinforcement learning. 
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><img src='images/Reliable_Path_Planning_Method.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

A Reliable Path Planning Method for Lane Change Based on Hybrid PSO-IACO Algorithm

**Zewei Zhou**, Zhuoping Yu, Lu Xiong, Dequan Zeng, Zhiqiang Fu, Zhuoren Li, Bo leng

_**2021 6th International Conference on Transportation Information and Safety (ICTIS)**_, 2021

- We propose a path planning method based on B-spline and hybrid PSO-IACO algorithm to reliably obtain a quality path with control flexibility and continuous curvature.
</div>
</div>


# 🎖 Honors and Awards
- *2021.09* Tongji Outstanding Master’s Scholarship
- *2020.06* CQU Outstanding Graduate (Top 1%)
- *2019.09* Thanksgiving for Scientists Scholarship, China (Highest scholarship in CQU, 0.2%)
- *2018.09* National Scholarship, China (Top 0.2%)
---
- *2020.12* Second Prize of National Post-Graduate Mathematical Contest in Modeling, China
- *2019.09* Third Prize of Challenge Cup National Academic Science and Technology Works Competition, China
- *2018.11* Second Prize of National College Youth Entrepreneurship Competition, China
- *2018.04* Meritorious Winner of 2018 Mathematical Contest in Modeling, U.S.


<!--
# 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/)
-->

<!--
# 💻 Internships
- *2019.05 - 2020.02*, [Lorem](https://github.com/), China.
-->
