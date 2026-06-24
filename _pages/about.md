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
My research focuses on communication–computation co-optimization and hardware–software co-design for large-scale agent (LLM/RL Agent) systems.
Targeting the training and deployment bottlenecks of large-scale agent systems, my work spans workload modeling, communication–computation co-optimization, and heterogeneous computing prototyping, aiming to improve the training, inference, and interaction efficiency of LLM/RL Agent systems across heterogeneous platforms such as AI accelerators, FPGAs, and multi-XPU clusters.

# 💻 Internships
- *2026.5 - now*, [ByteDance](https://www.bytedance.com/), Beijing.
- Mentor: Shuai Wang, Yinxiao Feng
- Topic: Modeling and hardware–software co-design for low-latency MoE inference clusters, analyzing topology/architecture parameters across compute, communication, and topology dimensions.
  
- *2024.12 - 2025.12*, [Alibaba Damo Academy](https://damo.alibaba.com/), Beijing.
- Mentor: Di Wu, Dimin Niu
- Topic: Architecture analysis and optimization for chip-to-chip interconnect in scale-up LLM systems. Built workload-driven communication models and a hybrid cycle-accurate/event-driven simulator for system-level analysis and design space exploration.

# 🚀 Selected Projects
- [**C2C-Explorer**](https://github.com/Selinaee/C2C-Explorer)  
  A workload-driven framework for chip-to-chip interconnect modeling and design space exploration for large language model systems.
- [**FPGA-Gym**](https://github.com/Selinaee/FPGA_Gym)  
  An FPGA-accelerated framework for reinforcement learning environment simulation.

# 📝 Publications 
## First-author papers
- **[FCCM'26]** Jiayi Li, et al. **“FPGA-Gym-v2: FPGA-Based RL Environment Acceleration with LLM-Assisted Onboarding”** Field-Programmable Custom Computing Machines, 2026.
  
- **[DAC'26]** Jiayi Li, et al. **“C2C-Explorer: An Exploration Framework for Chip-to-Chip Interconnect Architectures in LLM Cloud Computing Systems.”** Design Automation Conference, 2026.

- **[DATE'25]** Jiayi Li, et al. **“PEARL: FPGA-Based Reinforcement Learning Acceleration with Pipelined Parallel Environments.”** Design, Automation and Test in Europe Conference, 2025.

- **[NeurIPS-OWA'24]** Jiayi Li, et al. **“FPGA-Gym: An FPGA-Accelerated Reinforcement Learning Environment Simulation Framework.”** Advances in Neural Information Processing Systems (Workshop), 2024.
  
  I have also contributed to several co-authored publications in related areas.
# 🎖 Honors and Awards
- *2023*, Academic Excellence Award, Peking University  
- *2022*, Zhishan Student Award, Southeast University  
- *2021*, Merit Student, Southeast University  
- *2018–2022*, Multiple Course Excellence Awards
# 📖 Education
- *2022.09 - 2027.06 (expected)*, Ph.D. candidate, Peking University  
- *2018.09 - 2022.06*, Bachelor's degree, Southeast University




