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

Hi, everyone! I am an undergraduate student in Communication Engineering at **Beijing Jiaotong University** and **Lancaster University** (expected graduation: **Jun 2027**).  
I am currently a research intern at the **Institute for AI Industry Research (AIR), Tsinghua University**, supervised by Prof. **Yan Wang**.

My research interests focus on **Computer Vision (CV)** and **embodied intelligence**, especially **generative models (diffusion / Flow Matching)**, **inverse problems**, and **diffusion-based world models** for robust long-horizon prediction and planning under distribution shift (OOD).

---

# 🔥 News
- *2025.10*: Started working on **Test-Time Training for Robot Navigation World Models**, focusing on reducing OOD drift and stabilizing long-horizon rollouts.
- *2025.08*: Completed a summer internship at **Wuxi Research Institute of Applied Technologies (Tsinghua University)** on **VLA and World Models for Robot Manipulation and Navigation**.
- *2025.05*: Received **S Award** in the **Mathematical Contest in Modeling (MCM)**.
- *2025.01*: Joined **AIR, Tsinghua University** as a research intern and worked on **Diffusion Models for Inverse Problems**.

---

# 📝 Manuscripts in Preparation / Projects

<div class='paper-box'>
  <div class='paper-box-image'>
    <div>
      <div class="badge">Project</div>
      <img src='images/500x300.png' alt="sym" width="100%">
    </div>
  </div>
  <div class='paper-box-text' markdown="1">

**A Low- and High-Frequency Fusion Framework for Anti-UAV Detection and Tracking**  
- Proposed a **low-/high-frequency fusion** framework for robust anti-UAV detection and tracking under **low-light** and **dynamic-background** scenarios.  
- Designed a **Decoupling Light and Reconstructing (DLR)** module to disentangle illumination cues and extract **light-source-aware low-frequency** features.  
- Developed a **Null Space Super-Resolution Model (NSRM)** to recover **high-frequency motion details** via null-space decomposition and super-resolution.

  </div>
</div>

<div class='paper-box'>
  <div class='paper-box-image'>
    <div>
      <div class="badge">Project</div>
      <img src='images/500x300.png' alt="sym" width="100%">
    </div>
  </div>
  <div class='paper-box-text' markdown="1">

**Diffusion Models for Inverse Problems**  
- Studied **diffusion** and **Flow Matching** theory and used it to guide model design for **fast image generation**.  
- Reproduced a **Shortcut single-step diffusion** model on canonical inverse problems, implementing forward operators and noise models, and benchmarking speed–quality trade-offs.

  </div>
</div>

<div class='paper-box'>
  <div class='paper-box-image'>
    <div>
      <div class="badge">Ongoing</div>
      <img src='images/500x300.png' alt="sym" width="100%">
    </div>
  </div>
  <div class='paper-box-text' markdown="1">

**Test-Time Training for Robot Navigation World Models (Working on)**  
- Proposed a **distribution-consistency** strategy to reduce **OOD drift** in diffusion-based world model planning.  
- Used an **offline expert reference set** and a **similarity-based guidance** signal during sampling to stabilize **long-horizon rollouts**.

  </div>
</div>

---

# 🎖 Honors and Awards
- *2025.05* **S Award**, Mathematical Contest in Modeling (MCM)
- *2024.05* **Beijing Municipal Undergraduate Innovation Project**

---

# 📖 Educations
- *2023.09 - present*, **Beijing Jiaotong University**, China  
  Bachelor of Engineering in **Communication Engineering** (expected in **Jun 2027**)
- *2023.09 - present*, **Lancaster University**, UK

---

# 💻 Internships
- *2025.07 - 2025.08*, **Algorithm Intern**, Wuxi Research Institute of Applied Technologies, Tsinghua University  
  **VLA and World Models for Robot Manipulation and Navigation**  
  - Integrated a robotic arm and multi-sensor stack (camera, force & torque) in **ROS2**, and debugged end-to-end communication for stable runtime operation.  
  - Implemented model-to-control interfaces for **VLA models (Pi0-series and world-model inference)**, enabling direct execution of predicted actions on the robot.  
  - Validated grasping, placement, and container-operation demos with **sim-to-real consistency** by unifying observation/action formats and task scripts.

---

# 🧰 Skills
- **Programming**: Python, PyTorch; multi-GPU distributed training and debugging  
- **Foundations**: Computer Vision and VLA; familiar with diffusion models and recent VLA methods  
- **Research**: end-to-end research execution (modeling, experiments, paper writing)  
- **Hardware**: schematic and multi-layer PCB design  
- **English**: CET-4 535; CET-6 455; preparing for TOEFL

---

# 📫 Contact
- **Email**: 23721030@bjtu.edu.cn  
- **Tel**: (+86) 13326268486
