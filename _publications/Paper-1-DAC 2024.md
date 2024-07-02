---
title: "DAC 2024: APTQ: Attention-aware Post-Training Mixed-Precision Quantization for Large Language Models"
collection: publications
date: 2024-6-23
venue: '61st IEEE/ACM Design Automation Conference. (DAC), San Francisco, CA'
slidesurl: '../files/DAC_2024_Slide.pdf'
paperurl: '../files/DAC_2024_Paper.pdf'
citation: 'Ziyi Guan, Hantao Huang, Yupeng Su, Hong Huang, Ngai Wong, and Hao Yu. 2024. APTQ: Attention-aware Post-Training Mixed-Precision Quantization for Large Language Models. Ziyi Guan, Hantao Huang, Yupeng Su, Hong Huang, Ngai Wong and Hao Yu, “APTQ: Attention-aware Post-Training Mixed-Precision Quantization for Large Language Models”, In Proceedings of DAC 2024: 61st IEEE/ACM Design Automation Conference, San Francisco, CA, June 23-27, 2024'
title: "DATE 2024: An Isotropic Shift-Pointwise Network for Crossbar-Efficient Neural Network Design"
collection: publications
date: 2024-3-25
venue: '61st IEEE/ACM Design Automation Conference. (DAC), San Francisco, CA'
slidesurl: '../files/DATE_2024_Slide.pdf'
paperurl: '../files/DATE_2024_Paper.pdf'
citation: 'Ziyi Guan, Boyu Li, Yuan Ren, Muqun Niu, Hantao Huang, Graziano Chesi, Hao Yu and Ngai Wong, “An Isotropic Shift-Pointwise Network for Crossbar-Efficient Neural Network Design”, Design, Automation & Test in Europe Conference & Exhibition (DATE), March 25, Valencia, 2024.'

---

Large Language Models (LLMs) have greatly advanced the natural language processing paradigm. However, the high computational load and huge model sizes pose a grand challenge for deployment on edge devices. To this end, we propose APTQ (Attention-aware Post-Training Mixed-Precision Quantization) for LLMs, which considers not only the second-order information of each layer's weights, but also, for the first time, the nonlinear effect of attention outputs on the entire model. We leverage the Hessian trace as a sensitivity metric for mixed-precision quantization, ensuring an informed precision reduction that retains model performance. Experiments show APTQ surpasses previous quantization methods, achieving an average of 4 bit width a 5.22 perplexity nearly equivalent to full precision in the C4 dataset. In addition, APTQ attains state-of-the-art zero-shot accuracy of 68.24% and 70.48% at an average bitwidth of 3.8 in LLaMa-7B and LLaMa-13B, respectively, demonstrating its effectiveness to produce high-quality quantized LLMs.

---

---

Resistive random-access memory (RRAM), with its programmable and nonvolatile conductance, permits compute-in-memory (CIM) at a much higher energy efficiency than the traditional von Neumann architecture, making it a promising candidate for edge AI. Nonetheless, the fixed-size crossbar tiles on RRAM are inherently unfit for conventional pyramid-shape convolutional neural networks (CNNs) that incur low crossbar utilization. To this end, we recognize the mixed-signal (digital-analog) nature in RRAM circuits and customize an isotropic shift-pointwise network that exploits digital shift operations for efficient spatial mixing and analog pointwise operations for channel mixing. To fast ablate various shift-pointwise topologies, a new reconfigurable energy-efficient shift module is designed and packaged into a seamless mixed-domain simulator. The optimized design achieves a near-100% crossbar utilization, providing a state-of-the-art INT8 accuracy of 94.88% (76.55%) on the CIFAR-10 (CIFAR-100) dataset with 1.6M parameters, which sets a new standard for RRAM-based AI accelerators.
