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

I am doing my bachelor of science in telecommunication at ChongXin College(崇新学堂), Shandong University and expected to graduate in June 2023. I also work as a research assistant at [IR Lab](https://ir.sdu.edu.cn/index.htm) in school of computer science（山东大学计算机科学与技术学院）for over a year, advised by Prof. Pengjie Ren(任鹏杰) and Prof. Xinxin(辛鑫).

<!-- I won first prize scholarships in Research Innovation and Aesthetic Education Accomplishment(Top 3%) and was selected Chongxin College.  -->
<!-- , supervised by Prof. [Honchao Zhou](https://faculty.sdu.edu.cn/zhouhongchao/zh_CN/index.htm). -->

My research interest includes recommender system and graph mining. I have submitted a paper as second author to TOIS (accept with minor revision), which investigates the problem of user behavior leakage in recommender system. I still have two papers on going: one is about mitigating popularity bias in graph-based recommendations and the other one is concerning denoising implicit feedback for recommendations. 

For curriculum reasons, I also have knowledge about computer vision, front-end development and electrical engineering. I hold three patents in telecommunication. 

I have a good command of English(IELTS: 7.5) and a good knowledge of recommender system. I'm familiar with popular recommendation algorithms, common datasets, training losses and evaluation metrics. I'm also good at programming, such as data processing or writing codes to implement ideas. 

Interest: Piano(Gr. 10), Electronic Organ(Gr. 10), Badminton(No.5 men's team in SDUQD). 

<!-- I am willing to learning new things and have good self-disipline and strong mental resiliency when facing adversities. Hopefully, we can speak about research in the future.  -->

<!-- Ascend project, Aizoo project, real time stytle transfer app, robot
communication courses,  -->


<!-- My research interest includes Data mining and recommendation system. I have submitted a paper as second author at the top international AI journals with total <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'>google scholar </a><a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>, and still have two papers in progress. I also own three patents in telecommunication.  -->


<!-- # 🔥 News
- *2022.02*: &nbsp;🎉🎉 Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2022.02*: &nbsp;🎉🎉 Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  -->

# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TOIS 2023</div><img src='images/publications/tois23.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**On the User Behavior Leakage from Recommender System Exposure**

XIN XIN, JIYUAN YANG, **HANBING WANG**, JUN MA, PENGJIE REN, HENGLIANG LUO, XINLEI SHI, ZHUMIN CHEN, ZHAOCHUN REN

**Project**
- Accept with minor revision. 
- Investigate the problem of user behavior leakage in the field of recommender systems, and propose a
privacy-protection mechanism to solve the problem. 

</div>
</div>
<!-- <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong> -->
<!-- - [Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet](https://github.com), A, B, C, **CVPR 2020** -->

<!--                          -->
# 🛠️ Project experience

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Aizoo</div><img src='images/projects/aizoo.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Aizoo - A visual deep learning model building and cloud computing platform]

Pengjie Ren, **Hanbing Wang**, Hongtao Tian, Guojun Yan, Chaoyu Shi, Min Wei, Jiyuan Yang, et al.

[**Project information**]
- Develop and test some operators, collect information about those operators(including formulas, backgrounds, source papers, etc) and implementing a pedestrian detection task based on Aizoo. 
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Driverless Assistant Aystem</div><img src='images/projects/Ascend.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Electronic perpetual calendar</div><img src='images/projects/calendar.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Electronic perpetual calendar]

**Hanbing Wang**

[**Project information**]
- Invented a electronic perpetual calendar from scratch. 
- Circuit design and printing, MCU programming, application of various chips such as HC-05, DHT11, DS1302, LCD1602, MQ-2, etc. 
- Functions include time display, solar terms display, conversion of lunar calendar and Gregorian calendar, alarm clock with customized music, smoke alarm, measurements of temperature and humidity, remote Bluetooth control. 
</div>
</div>

[A full stack driverless assistant system based on Huawei Ascend]

Haiqiao Hong, **Hanbing Wang**, Qitao Zhao

[**Project information**]
- Invented a road information detection system which can transmit the detection results to the terminal(eg. screen. a website in our project) in real time. 
- Hardware includes the use of Raspberry Pi, Zynq, Atlas 200DK, 3D-printing, Wireless video signal transmission.
- Software includes improving the effciency of real time object detection algorithm, design a webpage to display all the information. 
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Style Transfer</div><img src='images/projects/transfer.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1"></div>

[A real time image style transfer system]

Haiqiao Hong, **Hanbing Wang**, Qitao Zhao

[**Project information**]
- Invented a real time style transfer framework which can transfer the image/video style captured by a camera and display it on a webpage. 
- Developed a computer application which can achieve style transfer as long as you download our app. 
- Software includes real time style transfer algorithm, webpage design, video streaming and application development. 
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Equipment Management System</div><img src='images/projects/deviceManagement.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Laboratory instrument and equipment management system]

**Hanbing Wang**

[**Project information**]
- Developed a online equipment Management System including React based front-end, Springboot based back-end and MySQL Database. 
- Functions includes data addition, deletion, modification query, system login, fuzzy search, paging display, data statistics(taccording to price or quantity) statistics display(line chart).
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Interdisciplinary Project</div><img src='images/projects/law.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Research on copyright protection obligations and technical regulation of cloud storage service providers based on deep learning ——Take Baidu online disk as an example]

**Hanbing Wang**, Cheng Zhang, Zihao Xiao, Chengzhuo Li, Hankang Sun, Xinyu Shen

[**Project information**]
- This is an interdisciplinary project between computer science and law. 
- Knowledge includes fast video/image/text detection and comparison algorithm in various situations. 
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Interdisciplinary Project</div><img src='images/projects/biology.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[An online website for querying the signal pathways of hematopoietic cells in human body]

**Hanbing Wang**, Xiaoyu Ji, Bingyang Cui, Baoxun Du, Zihan Liu

[**Project information**]
- This is an interdisciplinary project between computer science and biology.
- Mapped the complete signal pathway of hematopoietic cells in human body, and made a web page for display. The webpage supports addition, deletion, modification, search of genes, fisheye magnification and freely adjusting gene arrangement. 
</div>
</div>

<!-- - **Aizoo - A visual deep learning model building and cloud computing platform** I'm in charge of writing some operators and collect information about common operators.  -->
<!-- - **Laboratory instrument and equipment management system** includes: React based front-end framework, Springboot based back-end and MySQL Database.  -->
<!--                -->

# 🎖 Honors and Awards
- *2021.10* Third Prize in Mathematical Contest in Modeling. 
- *2021.10* First prize scholarships in Research Innovation and Aesthetic Education Accomplishment.
- *2021.08* Second prize in Mathematical Contest in modeling of Shandong University.
- *2021.05* Third Prize in 2021 National English Competition for college students. 
- *2020.10* Third Prize in National Undergraduate Electronic Design Contest. 
- *2020.10* First prize scholarships in Research Innovation and Aesthetic Education Accomplishment.
- *2020.11* Fifth place in badminton competition of Shandong University.
- *2020.06* Outstanding Youth Volunteer. 

# 📖 Educations
- *2019.06 - 2022.07 (now)*, Bachelor, Shandong University, Qingdao. 
<!-- - *2015.09 - 2019.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  -->

# 💬 Invited Talks
- None yet.

# 💻 Internships
- *2021.05 - 2022.07*, Research Assistant, [IR lab](https://ir.sdu.edu.cn/index.htm), Qingdao.