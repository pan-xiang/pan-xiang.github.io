---
permalink: /zh/
title: ""
author_profile: true
lang: zh
alternate_url: /
---

我是京都大学 [Human-Robot Interaction Lab](https://www.robot.soc.i.kyoto-u.ac.jp/en/) 的博士后研究员，与 [Takayuki Kanda 教授](https://www.robot.soc.i.kyoto-u.ac.jp/~kanda/biography.html)合作。我的研究方向位于人机交互与具身人工智能的交叉领域。此前，我主要关注如何设计具有表达性的机器人操作策略，从而提升机器人在人类共享环境中的透明性、可读性与自然性。

目前，我正在研究机器人如何借助大语言模型（LLMs）和视觉语言模型（VLMs）推断并回应人类意图，同时结合心理学见解，使机器人在人机交互中表现出更符合社会情境的行为。

我正在寻找 2026 年 10 月前后开始的博士后机会。

# 最新动态
<ul>
{% for item in site.data.news limit:4 %}
  <li>
    <strong>{{ item.date }}:</strong> {{ item.content }}
  </li>
{% endfor %}
</ul>
<details>
  <summary style="text-align:right; margin:10px; color: #6bc9e6; font-size: 0.9em; text-transform: uppercase; letter-spacing: 0.4px;">
    查看更多
  </summary>

  <ul>
  {% for item in site.data.news offset:4 %}
    <li>
      <strong>{{ item.date }}:</strong> {{ item.content }}
    </li>
  {% endfor %}
  </ul>
</details>


# 代表论文
更多论文可见我的 [Google Scholar](https://scholar.google.com/citations?user=BksSRrsAAAAJ) 页面。

<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Publications</title>
  <link rel="stylesheet" href="{{ base_path }}/assets/css/style.css">
</head>
  
<div class="publications">
  <div class="pub-item">
    <h3>Communicating Object Relations through Robot Gestures</h3>
    <p><strong>Xiang Pan *</strong>, Malcolm Doering, Takayuki Kanda</p>
    <p><em>ACM/IEEE International Conference on Human-Robot Interaction, Edinburgh, Scotland, UK, 2026</em></p>
    <p>备注：
      <a href="https://portal.core.edu.au/conf-ranks/?search=HRI&by=all&source=ICORE2026" target="_blank">CORE A*</a>，顶级 HRI 会议，录用率 23.2%（129/557）</p>
    <div class="links">
      <a href="{{ base_path }}/files/HRI2026.pdf" class="button" target="_blank">Paper</a>
      <a href="https://dl.acm.org/doi/10.1145/3757279.3785554" class="button" target="_blank">ACM</a>
    </div>
  </div>

  <div class="pub-item">
    <h3>Communicating Physical Properties through Robot Object Manipulation</h3>
    <p><strong>Xiang Pan *</strong>, Malcolm Doering, Stela H. Seo, Takayuki Kanda</p>
    <p><em>ACM/IEEE International Conference on Human-Robot Interaction, Melbourne, Australia, 2025</em></p>
    <p>备注：CORE A*，顶级 HRI 会议，录用率 25%（100/400）</p>
    <div class="links">
      <a href="{{ base_path }}/files/HRI2025.pdf" class="button" target="_blank">Paper</a>
      <a href="https://dl.acm.org/doi/10.5555/3721488.3721579" class="button" target="_blank">ACM</a>
      <a href="https://ieeexplore.ieee.org/abstract/document/10973989" class="button" target="_blank">IEEE</a>
    </div>
  </div>

  <div class="pub-item">
    <h3>What Is Your Other Hand Doing, Robot? A Model of Behavior for Shopkeeper Robot's Idle Hand</h3>
    <p><strong>Xiang Pan *</strong>, Malcolm Doering, Takayuki Kanda</p>
    <p><em>ACM/IEEE International Conference on Human-Robot Interaction, Colorado, USA, 2024</em></p>
    <p>备注：CORE A*，顶级 HRI 会议，录用率 24.7%（87/352）</p>
    <div class="links">
      <a href="{{ base_path }}/files/HRI2024.pdf" class="button" target="_blank">Paper</a>
      <a href="https://dl.acm.org/doi/10.1145/3610977.3634986" class="button" target="_blank">ACM</a>
      <a href="https://ieeexplore.ieee.org/abstract/document/10661005" class="button" target="_blank">IEEE</a>
    </div>
  </div>
</div>


# 学术服务
- ## 会议 Workshop 组织
  - [Multi-Agentic Systems in HRI (MAgicS-HRI): Bridging Design and Real-World Challenges for End Users](https://sites.google.com/view/magics-hri/home), HRI 2026

- ## 期刊审稿
  - IEEE Robotics and Automation Letters (RA-L)
  - ACM Transactions on Human-Robot Interaction (THRI)
  - Proceedings of the ACM on Interactive, Mobile, Wearable and Ubiquitous Technologies (IMWUT)

- ## 会议审稿
  - ACM/IEEE International Conference on Human-Robot Interaction (HRI), 2025, 2026
  - ACM Conference on Human Factors in Computing Systems (CHI), 2023
  - ACM Conference on Designing Interactive Systems (DIS), 2025, 2026
  - ACM Interaction Design and Children Conference (IDC), 2025, 2026
  - ACM Conference on Automotive User Interfaces and Interactive Vehicular Applications (AutomotiveUI), 2026
  - IFIP TC13 International Conference on Human-Computer Interaction (INTERACT), 2025
  - IEEE World Haptics Conference (WHC), 2025
  - IEEE International Conference on Robot and Human Interactive Communication (RO-MAN), 2024
  - International Conference on Human-Agent Interaction (HAI), 2024

- ## 学生志愿者
  - IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS), 2022


# 代表奖项
- 浙江大学优秀研究生，2020
- 浙江大学优秀研究生干部，2018
- 安徽省优秀毕业生，2017
- 安徽工业大学青年五四奖章，2017（本科最高荣誉，全校 10 人）


# 教育经历
- **京都大学**，日本京都  
  社会信息学博士（2022 年 4 月 - 2026 年 1 月）  
  导师：[Takayuki Kanda 教授](https://www.robot.soc.i.kyoto-u.ac.jp/~kanda/biography.html)

- **浙江大学**，中国杭州  
  仪器仪表工程硕士（2017 年 9 月 - 2020 年 6 月）  
  导师：[Hong Zhou 教授](https://person.zju.edu.cn/zhouhong/)

- **安徽工业大学**，中国马鞍山  
  电子信息工程学士（2013 年 9 月 - 2017 年 7 月）  
  导师：[Bing Wang 教授](https://www.aufe.edu.cn/2023/1228/c8256a209006/page.htm)
