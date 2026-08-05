---
title: "A scalable solution to AlphaZero based Redundancy Analysis for semiconductor chips"
permalink: /publication/Scalable_Alphara
date: 2023-03-23
venue: 'ICMLA 2022'
---

_**Abstract**_ -- Manufacturing flaws in memory devices give rise to defective memory cells rendering the chips unusable and consequently reducing the wafer yield. To overcome the effect of faulty memory cells, redundancies are included in the form of spare rows and columns in the memory device. Redundancy Analysis (RA) is the process of mapping these spare rows and columns to repair faulty lines in the chip. Our previous work AlphaRA, an AlphaZero based Redundancy Analysis method, has demonstrated promising yields. However, training for large values of chip sizes (n) is time-consuming. In this paper, we introduce SAZRA, a scalable solution for AlphaZero based Redundancy Analysis algorithms with the use of Graph Neural Networks (GNNs). The memory chip is designed as a graph so that it can be used in GNNs, thus making the solution independent of n. With just a single training on a dataset of n=16 chips, we are able to achieve yields outperforming existing algorithms on n up to 128 times larger and previously unseen to the neural network. SAZRA maintains a high yield while having the least spare utilization across all chip sizes. It achieves scalability with reduction in training time, execution time, and GPU memory and disk memory requirements.

[paper link](https://ieeexplore.ieee.org/document/10069266)

