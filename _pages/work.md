---
permalink: /work/
title: "Selected Work"
excerpt: "Selected contributions to efficient inference, GPU/NPU deployment, and robot autonomy: No Bias Stereo, 3PTv2, and Flexion Reflect v0."
author_profile: true
---

I work on the training, optimization, and deployment of deep learning models, with a focus on robotic perception and efficient execution on real hardware. The projects below describe my contributions to the teams and models linked in each section.

## No Bias Stereo

**Google (Intrinsic) · Stereo inference on edge accelerators**

[No Bias Stereo](https://intrinsic-experimental.github.io/nbs-website/) is a stereo-reconstruction model based on a Vision Transformer. My work focused on making the model run efficiently on Qualcomm NPUs.

**Result:** reached **10.76 FPS on dual Qualcomm NPUs**, corresponding to **3.75× baseline throughput** and exceeding the 10-FPS target for the evaluated robotics workload.

**My contribution:**

- Rewrote ONNX and attention graphs for accelerator execution.
- Applied operator fusion and selective post-training quantization.
- Profiled and validated execution and numerical behavior on the target hardware.

These measurements refer to my Qualcomm deployment work. The public model paper reports its own GPU benchmarks, which use a different setup.

[Public model project](https://intrinsic-experimental.github.io/nbs-website/) · [Public model paper](https://arxiv.org/abs/2608.28933)

<a id="pose-estimation"></a>

## 3PTv2

**Google (Intrinsic) · GPU acceleration and portability for multi-view 6D pose estimation**

[3PTv2: Zero-Shot 3D-Object Perception Transformer for Robotics](https://openreview.net/forum?id=WNZ4Dr57JS) estimates object poses from multiple views. My work focused on reducing execution time and exploring portability across hardware platforms.

**Result:** reduced inference latency on **NVIDIA A100 from 6.8 to 3.1 seconds per frame**, a **54% reduction**.

**My contribution:**

- Optimized CUDA reductions and reused vision-transformer computation.
- Batched rendering and reduced CPU–GPU overhead.
- Demonstrated a separate **Qualcomm CPU/NPU proof of concept without retraining**.

The A100 latency measurements and the Qualcomm portability proof of concept are separate results.

[Public model paper](https://openreview.net/forum?id=WNZ4Dr57JS) · [Public BOP entry](https://bop.felk.cvut.cz/method_info/1778/)

## Flexion Reflect v0

**Flexion Robotics · Vision-language agents and robot autonomy**

[Flexion Reflect v0](https://flexion.ai/news/flexion-reflect-v0-towards-generalizable-robot-autonomy) connects visual and language-based reasoning with executable robot skills.

**My contribution:** built agent components for autonomous robotic operation and integrated sim-to-real workflows, contributing to a successful demonstration on a physical robot.

In separate work on humanoid locomotion, I tuned a training pipeline to achieve **2× faster training and 5% higher task reward**.

[Public project and team demo](https://flexion.ai/news/flexion-reflect-v0-towards-generalizable-robot-autonomy)

## Research and earlier experience

My academic work studies optimizer dynamics, hyperparameter scaling laws, compressed and distributed learning, and differential privacy. See [publications](/publications/) and [the numerical notebooks accompanying my PhD thesis](https://github.com/eneamc/Code_PhD_Thesis).

Earlier, I worked on scalable machine learning at **Yahoo Research** and applied machine learning in finance at **UBS**. My [CV](/cv/) contains the full experience and technical background.
