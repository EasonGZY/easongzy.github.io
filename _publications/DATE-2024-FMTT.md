---
title: "DATE 2024: FMTT: Fused Multi-head Transformer with Tensor-compression for 3D Point Clouds Detection on Edge Devices"
collection: publications
date: 2024-3-25
venue: '61st IEEE/ACM Design Automation Conference. (DAC), San Francisco, CA'
slidesurl: '../files/DATE_2024_FMTT_Slide.pdf'
paperurl: '../files/DATE_2024__FMTT_Paper.pdf'
citation: 'Zikun Wei, Tingting Wang, Chenchen Ding, Bohan Wang, Ziyi Guan, Hantao Huang, and Hao Yu “FMTT: Fused Multi-head Transformer with Tensor-compression for 3D Point Clouds Detection on Edge Devices”, Design, Automation & Test in Europe Conference & Exhibition (DATE), March 25, Valencia, 2024.'
---

The real-time detection of 3D objects represents a grand challenge on edge devices. Existing 3D point clouds models are over-parameterized with heavy computation load. This paper proposes a highly compact model for 3D point clouds detection using tensor-compression. Compared to conventional methods, we propose a fused multi-head transformer tensor-compression (FMTT) to achieve both compact size yet with high accuracy. The FMTT leverages different ranks to extract both high and low-level features and then fuses them together to improve the accuracy. Experiments on the KITTI dataset show that the proposed FMTT can achieve 6.04× smaller than the uncompressed model from 55.09MB to 9.12MB such that the compressed model can be implemented on edge devices. It also achieves 2.62% improved accuracy in easy mode and 0.28%improved accuracy in hard mode.
