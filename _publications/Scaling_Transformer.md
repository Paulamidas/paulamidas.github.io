---
title: "Scaling Transformer Inference Through CPU and Memory Optimization"
permalink: /publication/Scaling_Transformer
date: 2024-12-04
venue: 'SNPD 2024'
---

_**Abstract**_ -- Transformer models have revolutionized various natural language processing tasks, offering unprecedented
accuracy and flexibility. However, deploying these models for inference presents significant challenges, particularly when
relying on GPUs. A single GPU cannot efficiently accelerate inferences, the GPU can also be considered as accelerator with
powerful computing capabilities. Due to its limited memory capacity, which demands frequent transfers of the pre-trained
model parameters needed by the GPU to compute subsequent layers from the CPU memory. While GPUs provide high
computational throughput, their usage for inference comes with notable disadvantages, including high operational costs, thermal
management challenges, hardware-software compatibility issues, and spatial constraints. Additionally, frequent transfers of these
model parameters are executed over slow device interconnects such as PCIe or NVLink. In contrast, CPUs present several
advantages for inference tasks, making them a practical option for users who seek efficient and cost-effective solutions, as they are
widely available, offer a more energy-efficient alternative to GPUs, and provide significant opportunities for performance
optimization despite their current underutilization. This paper explores optimization techniques for enhancing CPU performance
in transformer inferences, focusing on underutilized resources such as CPU cores, DRAM Memory Bandwidth and Memory
capacity. By improving memory management and usability, we were able to achieve 2.05x inference performance improvement.

[paper link](https://ieeexplore.ieee.org/abstract/document/11481685)

