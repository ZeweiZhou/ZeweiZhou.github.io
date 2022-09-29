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

I am currently a final year M.S. student in the Institute of Intelligent Vehicles at Tongji University, co-advised by [Prof. Yanjun Huang](https://scholar.google.com/citations?user=r_XUM78AAAAJ) and [Prof. Zhuoping Yu](https://ieeexplore.ieee.org/author/37402463600). I also work closely with [Dr. Yuanjian Zhang](https://www.lboro.ac.uk/departments/aae/staff/yuanjian-zhang/).

Intelligent reasoning is the key to safe and trustworthy autonomy. My primary research interests are the reasoning process (i.e. interactive prediction, decision-making, and planning) of autonomous systems, which can endow connected autonomous vehicles with the ability to intelligently interact and cooperate with others. 

🎓[**I am searching for Ph.D. positions in the related field.**]()

# 📖 Educations
- *2020.09 - 2023.03*, Master of Science, Automotive Engineering, Tongji University (Tongji), Shanghai, China
  - GPA: 5.00/5.00 (92.36/100), Test Waiver Admission (Ranking: 1<sup>st</sup>/250), Tongji Outstanding Student (*Top 4%*)
- *2016.09 - 2020.06*, Bachelor of Engineering, Automotive Engineering, Chongqing University (CQU), Chongqing, China
  - GPA: 3.71/4.00 (94.89/100), Comprehensive Ranking: 1<sup>st</sup>/154 (*Top 0.6%*), CQU Outstanding Graduate

<!--
- Core Courses: System Identification (5.0/5.0), Modern Control Theory (5.0/5.0), Numerical Analysis (5.0/5.0)
- Core Courses: Mathematical Model (4.0/4.0), C Program Design (4.0/4.0), Fundamentals of Computer Technology (3.9/4.0), Calculus A (4.0/4.0), Linear Algebra (4.0/4.0), Probability and Statistics (4.0/4.0), Automobile Structure (4.0/4.0), Key Technologies of New Energy Vehicles (4.0/4.0), Fundamentals of Vehicle Dynamic and Control (4.0/4.0) Outstanding Graduate (*Top 1%*)
-->



# 🔥 News
<!--
- *2022.08*: &nbsp;🎉🎉 Our paper on evolutionary decision-making and planning for autonomous driving has been submitted to _Engineering_, the official journal of the Chinese Academy of Engineering, and it is under reviewed now.
- *2022.07*: &nbsp;🎉🎉 Our paper on cooperative vehicle infrastructure system has been submitted to _IEEE Transactions on Intelligent Transportation System_, and it is under reviewed now.
-->
- *2022.04*: &nbsp;🎉🎉 Our paper on trajectory-prediction methods for autonomous driving has been accepted by _IEEE Transactions on Intelligent Vehicles_! 
- *2022.03*: &nbsp;🎉🎉 Our paper on speed prediction in transportation system has been accepted by _iScience_ ([_**Cell Press**_](https://www.cell.com/))！
- *2021.12*: &nbsp;🎉🎉 Our multiple automated guided vehicles (AGVs) passed through field testing and could coordinate movements with each other, providing a valet experience.
- *2020.06*: &nbsp;🎉🎉 I graduated from Chongqing University as an Outstanding Graduate.

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
https://www.lboro.ac.uk/departments/aae/staff/yuanjian-zhang/
- [Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet](https://github.com), A, B, C, **CVPR 2020**
-->


<div class='paper-box'><div class='paper-box-image'><img src='images/Comprehensive_Study_of_Speed_Prediction.png' alt="sym" width="100%"></div>
<div class='paper-box-text' markdown="1">

[A Comprehensive Study of Speed Prediction in Transportation System: From Vehicle to Traffic](http://dx.doi.org/10.1016/j.isci.2022.103909)

**Zewei Zhou**, Ziru Yang, Yuanjian Zhang, Yanjun Huang, Hong Chen, Zhuoping Yu

_**iScience (JCR Q1, Cell Press)**_, 2022 

- We aim to draw a complete picture of speed prediction, and comprehensively analyze existing research on speed prediction in transportation system at three levels, i.e. macro traffic, micro vehicles, and meso lane.
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><img src='images/Survey_on_Trajectory_Prediction_Methods.png' alt="sym" width="100%"></div>
<div class='paper-box-text' markdown="1">

[A Survey on Trajectory-Prediction Methods for Autonomous Driving](http://dx.doi.org/10.1109/TIV.2022.3167103)

Yanjun Huang, Jiatong Du, Ziru Yang, **Zewei Zhou**, Lin Zhang, Hong Chen

_**IEEE Transactions on Intelligent Vehicles**_, 2022

- We provide a comparative review of trajectory-prediction methods for autonomous driving and elaborate the popular methods based on physics, classic machine learning, deep learning, and reinforcement learning. 
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><img src='images/Evolutionary_Decision-Making_Planning.png' alt="sym" width="100%"></div>
<div class='paper-box-text' markdown="1">

[Evolutionary Decision-Making and Planning for Autonomous Driving based on Safe and Rational Exploration and Exploitation]()

Kang Yuan, Yanjun Huang, Shuo Yang, **Zewei Zhou**, Yulei Wang, Dongpu Cao, Hong Chen

_**Engineering**_, 2022 (_JCR Q1_, under review)

- We propose an online-evolution framework of decision-making and planning for autonomous driving in the operating stage by developing a hybrid data- and model-driven method based on DRL and MPC. 
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><img src='images/Cooperative_Vehicle_Infrastructure_System.png' alt="sym" width="100%"></div>
<div class='paper-box-text' markdown="1">

[Cooperative Vehicle Infrastructure System: Architecture, Applications and Challenges]()

Yangjie Ji, **Zewei Zhou**, Ziru Yang, Yanjun Huang, Hong Chen, Lu Xiong, Zhuoping Yu

_**IEEE Transactions on Intelligent Transportation System**_, 2022 (under review)

- We review the current research on the architecture and applications of the cooperative vehicle infrastructure system and identify potential methods to enhance safety and efficiency through intelligent vehicles, intelligent roads, and even smart cities.
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><img src='images/Reliable_Path_Planning_Method.png' alt="sym" width="100%"></div>
<div class='paper-box-text' markdown="1">

[A Reliable Path Planning Method for Lane Change Based on Hybrid PSO-IACO Algorithm]()

**Zewei Zhou**, Zhuoping Yu, Lu Xiong, Dequan Zeng, Zhiqiang Fu, Zhuoren Li, Bo leng

_**2021 6th International Conference on Transportation Information and Safety (ICTIS)**_, 2021

- We propose a path planning method based on B-spline and hybrid PSO-IACO algorithm to reliably obtain a quality path with control flexibility and continuous curvature.
</div>
</div>

# 🔬 Other Research Project

<div class='paper-box'><div class='paper-box-image'><img src='images/gif_parking.gif' alt="sym" width="100%"></div>
<div class='paper-box-text' markdown="1">

[Automated Parking System for Electric Bus Based on Automated Guided Vehicles (AGV)](), Institute of Intelligent Vehicles,*2020.10 - 2021.12*

_**Student Researcher**_. Advised: [Prof. Yanjun Huang](https://scholar.google.com/citations?user=r_XUM78AAAAJ) and [Prof. Wei Tian](https://scholar.google.com/citations?user=aYKQn88AAAAJ)

- We design a global motion planner based on A* algorithm to provide global reference trajectory for a given park.
- We propose a cooperative planning and control method for an AGVs group to coordinate their movement with each other based on the reference trajectory and guide them to move a bus to its destination.
- The method is validated and tested in a real bus and AGVs.

</div>
</div>


<div class='paper-box'><div class='paper-box-image'><img src='images/DPQPplanning.gif' alt="sym" width="100%"></div>
<div class='paper-box-text' markdown="1">

[Undergraduate Thesis: Local Planning and Obstacle Avoidance for Autonomous Vehicles](), *2019.09 - 2020.06*

_**Excellent Undergraduate Graduation Thesis**_. Advised: [Prof. Ling Zheng](http://mve.cqu.edu.cn/info/1309/4297.htm)

- Spline interpolation method is adopted to smooth the rough reference path.
- Path and speed planning are divided into two steps: lattice sampling and interpolation optimization. Then, they are solved by dynamic programming and quadratic programming respectively.
- The method is validated with Prescan and Simulink in some typical scenarios: obstacle avoidance, car following, overtaking, and merging.

</div>
</div>


# 🏅 Honors and Awards
- *2022.09* National scholarship for Postgraduates, China (_Highest scholarship for graduates awarded by the Chinese government, 0.2%_)
- *2021.09* Tongji Outstanding Master’s Scholarship
- *2019.09* Thanksgiving for Scientists Scholarship, China (*Highest scholarship in CQU, Top 0.2%*)
- *2018.09* National Scholarship, China (*Highest scholarship for undergraduates awarded by the Chinese government, Top 0.2%*)
- *2018 - 2019* CQU First-class Scholarship (Four times, 2%)

---

- *2020.12* Second Prize of National Post-Graduate Mathematical Contest in Modeling, China
- *2019.09* Third Prize of Challenge Cup National Academic Science and Technology Works Competition, China (*Top 2.7% of 45,000*)
- *2018.11* Second Prize of National College Youth Entrepreneurship Competition, China (*Top 0.09% of 150,000*)
- *2018.04* Meritorious Winner of 2018 Mathematical Contest in Modeling, U.S.



# 🏓 Miscellaneous
- When I was a child, I am impressed by the consummate skills of [Takumi Fujiwara](https://en.wikipedia.org/wiki/Initial_D) and pure freedom when he get to explore the speeds with his car [AE86](https://en.wikipedia.org/wiki/Toyota_AE86) in [*Initial D*](https://en.wikipedia.org/wiki/Initial_D). Therefore, I am really interested in how to endow every machine on roads with the ability to drive like a skillful human driver, even like [Takumi Fujiwara](https://en.wikipedia.org/wiki/Initial_D). 
- Besides, I like playing ping pong, and I am good at [penhold grip](https://en.wikipedia.org/wiki/Table_tennis_styles). Now, I am learning to use the [shakehand grip](https://en.wikipedia.org/wiki/Table_tennis_styles) for offense and defense. 
- I am also a big fan of guitar, especially [Fingerstyle](https://en.wikipedia.org/wiki/Fingerstyle_guitar). My favorite acoustic guitarist is [Tommy Emmanuel](https://en.wikipedia.org/wiki/Tommy_Emmanuel). 

<!--
# 📚 Academic Services
- Reviewer of Proc. IMechE, Part D: Journal of Automobile Engineering



# 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/)
-->

<!--
# 💻 Internships
- *2019.05 - 2020.02*, [Lorem](https://github.com/), China.
-->
