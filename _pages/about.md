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

我将前往**新南威尔士大学（UNSW）**攻读**数学与统计博士学位**，导师为**莫华栋教授**与**吕子扬教授**。
---

我的研究领域包括：
- **AI + 电池**：深度学习、半监督学习、统计模型
- **电池管理系统（BMS）**：SoX 估计（SoC/SoH/SoP）
- **预测性健康管理（PHM）**：梯次利用电池健康评估与寿命预测
- **量子计算 + 电池**：量子模型/量子优化在电池中的应用

<span class='anchor' id='-xsbj'></span>

# 🎓 学术背景
- *2022.09 - 2025.07*，清华大学，机械工程 硕士，导师：夏必忠 副教授
- *2018.09 - 2022.06*，合肥工业大学，车辆工程 学士，导师：汪洪波 副教授

<span class='anchor' id='-gzjy'></span>

# 💼 工作经历
- *2023.06 - 2024.06*，华为技术有限公司（华为云 联合培养），深圳  
  - **课题1：**面向柔性作业车间调度的强化学习优化：融合 Q-learning 与启发式规则，动态优化调度参数  
  - **课题2：**基于物理信息的电池模型：结合 P2D 模型与 PINN 进行电池状态估计

- *2025.07 - 2025.09*，比亚迪（BYD），电池算法工程师，深圳  
  - 优化混动系统 **SOC 估计**（扩展卡尔曼滤波 EKF 系列算法）  
  - 参与云端电池健康监测平台研发与电池测试

<span class='anchor' id='-kyjl'></span>

# 🔬 科研经历
- *2025.10 - 至今*，科研助理，**Revolutionary AI-Enabled Modular Power Portal System for Urban Clean Energy Distribution**  
  面向锂离子电池全生命周期 PHM，研究**统计模型 + 半监督学习**在缺失数据与退役电池场景的应用（导师：吕子扬、莫华栋）

- *2021.06 - 2021.09*，变压器运输高度监测系统项目  
  设计传感器系统，实现运输过程车辆净空实时监测（国网安徽省送变电公司）

<span class='anchor' id='-lwzl'></span>

# 📝 论文与专利

## Manuscripts in Preparation
- **[M1]** **C. Liang**，Z. Lyu，H. Mo，et al. *Missing-mechanism integrated general semi-supervised classification for Lithium-ion battery degradation classification with early data.* Manuscript in preparation

## Journal Papers
---
- **[J7]** **C. Liang**，S. Tao，et al. *Stochastic state of health estimation for lithium-ion batteries with automated feature fusion using quantum convolutional neural network.* **Journal of Energy Chemistry**, 106 (2025) 205–219. [[网页]](https://doi.org/10.1016/j.jechem.2025.02.030)

- **[J6]** **C. Liang**，B. Xia，et al. *A Quantum Particle Swarm Optimization Extended Kalman Quantum Particle Filter approach on state of charge estimation for lithium-ion battery.* **Journal of Energy Storage**, 100 (2024) 113677. [[网页]](https://doi.org/10.1016/j.est.2024.113677)

- **[J5]** X. Huang，**C. Liang**，S. Tao，et al. *IC2ML: Unified battery state-of-health, degradation trajectory and remaining useful life prediction via intra- and inter-cycle enhanced machine learning.* **Journal of Power Sources**, (2026) 239148. [[网页]](https://doi.org/10.1016/j.jpowsour.2025.239148)

- **[J4]** X. Huang，S. Tao，**C. Liang**，et al. *Robust and generalizable lithium-ion battery health estimation using multi-scale field data decomposition and fusion.* **Journal of Power Sources**, (2025) 236939. [[网页]](https://doi.org/10.1016/j.jpowsour.2025.236939)

- **[S3]** H. Hu，**C. Liang**，X. Huang，H. Mo，S. Tao，et al. *ONET: Operator network for randomized and robust battery health estimation using operation condition and cycling data matching.* **Journal of Power Sources** (Accepted)

- **[J2]** S. Yue，B. Xia，**C. Liang**，et al. *Temperature-considered active balancing strategy for lithium-ion battery packs with surrogate optimization algorithm.* **Journal of Energy Storage**, 108 (2025) 115073. [[网页]](https://doi.org/10.1016/j.est.2024.115073)

- **[J1]** B. Xia，H. Fu，Z. Qin，**C. Liang**. *Optimization of battery state of charge estimation method by correcting available capacity.* **Journal of Energy Storage**, 116 (2025) 116065. [[网页]](https://doi.org/10.1016/j.est.2025.116065)

## Submitted Papers
- **[S3]** **C. Liang**，S. Tao，Z. Lyu，H. Mo，et al. *Patterns in an Electrical Whisper: History-Free Generative Transfer Learning for Second-Life Battery Revival.* Submitted to **Patterns**
- **[S2]** X. Huang，S. Tao，**C. Liang**，et al. *PIMOE: Physically interpretable mixture of experts network for battery degradation trajectory prediction amid second-life complexities.* **Nature Communications**
- **[S1]** H. Hu，S. Tao，**C. Liang**，et al. *Robust and privacy-preserving classification of retired batteries via expert-weighted federated machine learning.* Submitted to **eTransportation**


## 专利
- **[P2]** 一种大型运输车辆测距防护装置（CN202110693693.7） [[网页]](https://d.wanfangdata.com.cn/patent/Ch1QYXRlbnROZXdTb2xyOVMyMDI2MDEyNzE1NTEzORIpWkxfQ04yMDIxMTA2OTM2OTMuN19DTjExMzMzNTE4OEJfMjAyNTAzMTQaCG1naXlud2Nx)
- **[P1]** 一种减震防跌倒拐杖 (CN202310276661.6) [[网页]](https://d.wanfangdata.com.cn/patent/Ch1QYXRlbnROZXdTb2xyOVMyMDI2MDEyNzE1NTEzORIpWkxfQ04yMDIzMTAyNzY2NjEuNl9DTjExNjI3MDE1M0JfMjAyNTA5MTYaCGJodmJ6a2Jl)

<span class='anchor' id='-ryjx'></span>

# 🏅 荣誉奖项
- *2024.12* 清华大学二等奖学金
- *2020.12* 合肥工业大学三等奖学金
- *2019.12* 合肥工业大学拓普集团NVH奖学金
- *2019.12* 合肥工业大学二等奖学金

<span class='anchor' id='-sg'></span>

# 🧑‍🏫 审稿
- Nature Communications（ECR），Journal of Energy Storage，Journal of Energy Chemistry，Measurement，IEEE TTE

<span class='anchor' id='-jn'></span>

# 🧰 技能
- **统计学习 / 半监督学习 / 缺失数据建模**: AI, Python, Quantum computing
- **电池建模与状态估计**: SPM / P2D / PINN / EKF
- **电池测试与表征**: 循环测试、整车/道路测试经验
