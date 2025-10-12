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

Junjielong Xu is a Ph.D. candidate of Computer Science in the [School of Data Science](https://sds.cuhk.edu.cn/en) at [The Chinese University of Hong Kong, Shenzhen](https://www.cuhk.edu.cn/en) (CUHK-SZ). His supervisor is [Prof. Pinjia He](https://pinjiahe.github.io). Currently, he is a visiting scholar in [AST Lab](https://ast.ethz.ch/), [ETH Zurich](https://ethz.ch/en.html), mentored by [Zhendong Su](https://people.inf.ethz.ch/suz/). Before joining CUHK-SZ, he received his BEng degree from the [School of Electronic Information and Communication](https://eic.hust.edu.cn/) at [Huazhong University of Science and Technology](https://hust.edu.cn/) (HUST) in 2022.

🔎 His research focuses on LLM-based DevOps automation for enhancing reliability of code and services. He is also interested in recent LLM research topics such as scalable oversight, reinforcement learning, and test-time scaling.

🔑 His objective is to provide non-trivial insights into AI models to address impactful challenges in real-world SE scenarios. He is trying hard to work toward this and hopes to conduct interesting yet meaningful research one day. 🫨

***P.S.*** My name "Junjielong Xu" is written as "徐俊杰龙" in Chinese, and is pronounced like "Joon-jyeh-long Shoo."

# 🔥 News

- *2025.10*: &nbsp;🎉🎉 I started my research visit in AST Lab, ETH Zurich.
- *2025.09*: &nbsp;🎉🎉 One collaborative paper with ByteDance was accepted by **NeurIPS'25** (*Spotlight*).
- *2025.04*: &nbsp;🎉🎉 I started my internship in Trae Research, ByteDance.（*筋斗云人才计划* ）
- *2025.03*: &nbsp;🎉🎉 I served as Art Design Chair for **FSE'26**. 
- *2025.01*: &nbsp;🎉🎉 I served as Program Committee for **FSE'25** industry track.
- *2025.01*: &nbsp;🎉🎉 One first-authored paper was accepted by **ICLR'25**.
- *2024.10*: &nbsp;🎉🎉 One first-authored paper was accepted by **ICSE'25**.
- *2024.03*: &nbsp;🎉🎉 I served as Shadow Program Committee for **ICSE'25**.

# 📝 Publications 

- &nbsp; <span class="badge">arXiv</span> &nbsp;**AL-Bench: A Benchmark for Automatic Logging**

  <span style="font-size:13px;"> Boyin Tan, <strong><em>Junjielong Xu*</em></strong>, Zhouruixing Zhu, Pinjia He.</span>

  <span style="font-size:14px;"> *arXiv prepreint*, 2025. </span>

  [[paper](https://arxiv.org/pdf/2502.03160)]
  [[code](https://github.com/shuaijiumei/logging-benchmark)]

- &nbsp; <span class="badge">NeurIPS'25</span> &nbsp;**Repo2Run: Automated Building Executable Environment for Code Repository at Scale**

  <span style="font-size:13px;"> Ruida Hu, Chao Peng, XinchenWang, Junjielong Xu, Cuiyun Gao </span>

  <span style="font-size:14px;"> *Annual Conference on Neural Information Processing Systems*, San Diego, Dec 2025. </span>

  [[paper](https://openreview.net/pdf?id=fZsd3KLMje)]
  [[code](https://github.com/bytedance/Repo2Run)]

- &nbsp; <span class="badge">ICLR'25</span> &nbsp;**OpenRCA: Can Large Language Models Locate the Root Cause of Software Failures?**

  <span style="font-size:13px;"> <strong><em>Junjielong Xu</em></strong>, Qinan Zhang, Zhiqing Zhong, Shilin He, Chaoyun Zhang, Qingwei Lin, Dan Pei, Pinjia He, Dongmei Zhang, Qi Zhang.</span>

  <span style="font-size:14px;"> *International Conference on Learning Representations*, Singapore, April 2025. </span>

  [[paper](https://openreview.net/pdf?id=M4qNIzQYpd)]
  [[code](https://github.com/microsoft/OpenRCA)]

- &nbsp; <span class="badge">ICSE'25</span> &nbsp;**Aligning the Objective of LLM-based Program Repair**

  <span style="font-size:13px;"> <strong><em>Junjielong Xu</em></strong>, Ying Fu, Shin Hwei Tan, Pinjia He.</span>

  <span style="font-size:14px;"> *International Conference on Software Engineering*, Ottawa, April 2025. </span>

  [[paper](https://arxiv.org/pdf/2404.08877)]
  [[code](https://github.com/CUHK-Shenzhen-SE/D4C)]

- &nbsp; <span class="badge">ICSE'24</span> &nbsp;**DivLog: Log Parsing with Prompt Enhanced In-Context Learning**

  <span style="font-size:13px;"> <strong><em>Junjielong Xu</em></strong>, Ruichun Yang, Yintong Huo, Chengyu Zhang, Pinjia He.</span>

  <span style="font-size:14px;"> *International Conference on Software Engineering*, Lisbon, April 2024. </span>

  [[paper](https://dl.acm.org/doi/abs/10.1145/3597503.3639155)]
  [[code](https://github.com/logpai/logparser)]

- &nbsp; <span class="badge">ICSE'24</span> &nbsp;**UniLog: Automatic Logging via LLM and In-Context Learning**

  <span style="font-size:13px;"> <strong><em>Junjielong Xu</em></strong>, Ziang Cui, Yuan Zhao, Xu Zhang, Shilin He, Pinjia He, Liqun Li, Yu Kang, Qingwei Lin, Yingnong Dang, Saravan Rajmohan, Dongmei Zhang</span>

  <span style="font-size:14px;"> *International Conference on Software Engineering*, Lisbon, April 2024. </span>

  [[paper](https://dl.acm.org/doi/abs/10.1145/3597503.3623326)]
  [[code](https://github.com/shuaijiumei/logging-benchmark)]

- &nbsp; <span class="badge">FSE'23</span> &nbsp;**Hue: A User-Adaptive Parser for Hybrid Logs**

  <span style="font-size:13px;"> <strong><em>Junjielong Xu</em></strong>, Qiuai Fu, Zhouruixing Zhu, Yutong Cheng, Zhijing Li, Yuchi Ma, Pinjia He.</span>

  <span style="font-size:14px;"> *International Conference on the Foundations of Software Engineering*, San Francisco, December 2023. </span>

  [[paper](https://dl.acm.org/doi/abs/10.1145/3611643.3616260)]
  [[code](https://github.com/Siyuexi/Hue)]


# 🎖 Honors and Awards

- *2024.04* 💰Duan Yong Ping Travel Award, CUHK-Shenzhen (¥10,000)
- *2023.12* 🥉3rd Prize, CCF International AIOps Challenge (Ranked 🏅1st among student teams)
- *2020.10* 🏅1st Prize, China Undergraduate Mathematical Contest in Modeling (CUMCM) (🤺Leader)
- *2020.04* 🏆Finalist Prize, Mathematical Contest In Modeling (MCM) (🤺Solo)

# 💬 Service

*Journal*
- Reviewer, [TSE](https://ieeexplore.ieee.org/xpl/RecentIssue.jsp?punumber=32), [TOSEM](https://dl.acm.org/journal/tosem)

*Conference*
- Art Design Chair: FSE'26
- Program Committee: ISSRE'26 (research-track), FSE'25 (industry-track), ICSE'25 (shadow-PC)
- Artifact Evaluation Committee: ICSE'25, ISSRE'24
- Reviewer: ICLR'26

# 💻 Internships

- *2025.04 - (now)*, ByteDance Trae IDE, researcher.
- *2023.12 - 2024.09*, Microsoft DKI Team, researcher.
- *2023.05 - 2023.09*, Huawei Cloud PaaS Lab, researcher.
- *2021.06 - 2021.08*, Tencent IEG User Platform, engineer.

# 📖 Educations

- *2025.10 - (now)*, Academic guest in AST Lab, ETH Zurich.
- *2022.09 - (now)*, Ph.D. in Computer Science, The Chinese University of Hong Kong, Shenzhen. 
- *2018.09 - 2022.06*, B.Eng. in Electronic Information Engineering, Huazhong University of Science and Technology.

# 📐 Teaching

*Teaching Assistant @CUHK-SZ*

- *2025.02* - CSC4001 Software Engineering
- *2024.09* - CSC1001 Python Programming
- *2024.02* - CSC4001 Software Engineering
- *2023.02* - CSC4001 Software Engineering
- *2022.09* - CSC1003 Java Programming

# 📉 Statistics

- Highest stars for a repo: <img alt="GitHub Repo stars" src="https://img.shields.io/github/stars/microsoft/OpenRCA">
- Most rejections for a paper: <img alt="Static Badge" src="https://img.shields.io/badge/4_rejection-red">