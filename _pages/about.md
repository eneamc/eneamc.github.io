---
permalink: /
title: "Deep Learning Researcher & Engineer"
excerpt: "Stochastic optimization, training dynamics, and efficient ML systems. Research Intern at Google (Intrinsic); PhD in Computer Science, summa cum laude, University of Basel."
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

<div class="profile-kicker">Stochastic optimization · Training dynamics · Efficient inference</div>

I study how optimization shapes deep learning and engineer models to run efficiently on real hardware.

I am a **Research Intern at Google (Intrinsic)** in Zürich, working on **model compression, inference optimization, and deployment for robotic perception**. My work spans PTQ/QAT, distillation, ONNX graph transformations, GPU profiling, accelerator compilation, and on-device validation across GPU and NPU platforms, including Qualcomm and SiMa.ai.

I completed my **PhD in Computer Science at the University of Basel in November 2026, graduating summa cum laude**, under the supervision of Prof. Dr. [Aurelien Lucchi](https://omls.dmi.unibas.ch/en/persons/aurelien-lucchi/). My research uses stochastic differential equations to understand optimizer dynamics, hyperparameter scaling laws, compressed and distributed learning, and differential privacy.

<div class="profile-actions">
  <a class="profile-action profile-action--primary" href="/cv/">View CV</a>
  <a class="profile-action" href="/publications/">Publications</a>
  <a class="profile-action" href="/work/">Selected work</a>
  <a class="profile-action" href="/talks/">Talks</a>
</div>

## Selected work

- **[No Bias Stereo](/work/#no-bias-stereo):** optimized stereo inference on dual Qualcomm NPUs, reaching **10.76 FPS (3.75× baseline throughput)** through graph rewrites, operator fusion, and selective quantization.
- **[3PTv2](/work/#pose-estimation):** reduced multi-view 6D pose-estimation latency on NVIDIA A100 from **6.8 to 3.1 seconds per frame (54%)**, with a separate Qualcomm CPU/NPU portability proof of concept.
- **[Flexion Reflect v0](/work/#flexion-reflect-v0):** built agent components and integrated sim-to-real workflows, contributing to an autonomous-operation demonstration on a physical robot.

[Read about my contributions, methods, and results →](/work/)

## Research

My work connects mathematical models of optimization with experiments on language and vision models. I have **seven first-author conference papers** across ICML, ICLR, AISTATS, and IJCNN, including an **AISTATS 2025 Oral**.

- **Optimizer dynamics and scaling laws:** understanding how noise and adaptivity shape training, and how hyperparameters should change with batch size.
- **Distributed and compressed learning:** studying the interaction between communication compression, gradient noise, and stability.
- **Private and robust optimization:** understanding how privacy noise affects optimization and hyperparameter transfer.

My PhD thesis, *Modern Optimizers as Noise-Shaping Mechanisms: A Stochastic Differential Equation Perspective*, brings these themes together. [Numerical notebooks accompanying the thesis](https://github.com/eneamc/Code_PhD_Thesis) are publicly available.

[Publications and research details →](/publications/)

## Selected research talks

- **Google DeepMind**, 11 August 2026 — *Understanding Optimizer Dynamics and Scaling Laws via SDEs*.
- **Caltech, Anima Anandkumar’s Lab**, 5 March 2025 — *Unbiased and Sign Compression in Distributed Learning: Comparing Noise Resilience via SDEs*.
- **Nokia Bell Labs**, 29 January 2025 — *Unbiased and Sign Compression in Distributed Learning: Comparing Noise Resilience via SDEs*.

[All talks and conference presentations →](/talks/)

## Background and contact

Before Google (Intrinsic), I worked on robot autonomy at **Flexion Robotics**, scalable machine learning at **Yahoo Research**, and applied machine learning in finance during three years as an **AI Quantitative Analyst at UBS**. My background spans mathematics and quantitative finance; I have also [taught deep learning and optimization](/teaching/) and mentored master’s research students.

You can reach me at **[eneamonziocompagnoni@gmail.com](mailto:eneamonziocompagnoni@gmail.com)**.
