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
I am a Ph.D. candidate in the School of Integrated Circuits at Peking University, affiliated with the Institute for Artificial Intelligence, and advised by Prof. Bonan Yan. 
My research focuses on cross-layer optimization for AI systems, bridging workload understanding, system-level modeling, architecture design, and hardware implementation. 
I have worked on chip-to-chip interconnect optimization for large language model systems and hardware acceleration for reinforcement learning, and I am also interested in efficient simulation and acceleration for multi-agent.

# 💻 Internships
- *2024.12 - 2025.12*, [Alibaba Damo Academy](https://damo.alibaba.com/), China.
- Mentor: Di Wu, Dimin Niu
- Topic: Architecture analysis and optimization for chip-to-chip interconnect in scale-up LLM systems. Built workload-driven communication models and a hybrid cycle-accurate/event-driven simulator for system-level analysis and design space exploration.

# 🚀 Selected Projects
- [**C2C-Explorer**](https://github.com/Selinaee/C2C-Explorer)  
  A workload-driven framework for chip-to-chip interconnect modeling and design space exploration for large language model systems.
- [**FPGA-Gym**](https://github.com/Selinaee/FPGA_Gym)  
  An FPGA-accelerated framework for reinforcement learning environment simulation.

# 📝 Publications 

[DAC’26] **Jiayi Li**, Di Wu, Qingxu Li, Hongxiao Zhao, Jiaqi Yang, Anjunyi Fan, Wenbin Zhang, Boqiang Wu, Shuting Liu, Shifeng Fang, Jianbo Dong, Dimin Niu and Bonan Yan. 2026. “C2C-Explorer: An Exploration
Framework for Chip-to-Chip Interconnect Architectures in LLM CloudComputing Systems.“ In . ACM, New York, NY, USA, 7 pages. Chip to System, 2026

[DATE’25] **Jiayi Li**, Hongxiao Zhao, Wenshuo Yue, Yihan Fu, Daijing Shi, Anjunyi Fan, Yuchao Yang, Bonan Yan. “PEARL: FPGA-Based Reinforcement Learning Acceleration with Pipelined Parallel Environments.” Design, Automation & Test in Europe Conference & Exhibition, 2025.

[NeurIPS-OWA] **Jiayi Li**, Hongxiao Zhao, Wenshuo Yue, Yihan Fu, Daijing Shi, Anjunyi Fan, Qinghao Wang, Yaodong Yang, Bonan Yan. “FPGA-Gym: An FPGA-Accelerated Reinforcement Learning Environment Simulation Framework.” NeurIPS Workshop on Open-World Agents, 2024.

# 🎖 Honors and Awards
- *2021.10* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.09* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 

# 📖 Education
- *2022.09 - 2027.06 (expected)*, Ph.D. candidate, Peking University  
- *2018.09 - 2022.06*, Bachelor's degree, Southeast University




