---
permalink: /
title: "About Zhihang Yuan"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Hello! I'm Zhihang Yuan. 
I obtained my bachelor's degree from Peking University in 2017, and my PhD degree from the School of Computer Science at Peking University in 2022, under the supervision of Professor Guangyu Sun.
Currently, I am conducting research related to Efficient AI at the [NICS-effalg team](https://nics-effalg.com/) at Tsinghua University and at Infinigence-AI. My research focuses on the design of efficient neural networks architecture, neural network compression, and the co-optimization of software and hardware.

袁之航于2017年获得北京大学学士学位，于2022年获得北京大学计算机学院博士学位，博士导师为孙广宇老师。
目前他在清华[NICS-effalg组](https://nics-effalg.com/)和无问芯穹从事高效人工智能（Efficient AI）相关的研究工作，研究方向为高效神经网络设计、神经网络的压缩、深度学习的软硬件协同优化。
喜欢走走，曾参加过北京大学自行车协会2014年暑期远征和北京大学山鹰社2022年英吉沙科考。

袁之航的研究方向为高效人工智能（Efficient AI）。在多个AI顶会和顶刊上发表十余篇论文（3 ICLR, 3 NeurIPS, 3 CVPR, 2 ECCV, 1 TPAMI, 1 COLM, 1 ICRA），在计算机系统架构方面发表数篇论文（1 TCAD, 1 HPCA, 1 TC, 1 DATE, 1 ASP-DAC, 1 SCIS），根据 Google Scholar，他的文章总被引用次数超过 1500 次。他在神经网络的压缩方面做了很多创新性的工作，例如ASVD是最早对LLM进行低秩分解压缩的工作、PTQ4ViT是最早对Vision Transformer量化压缩工作之一、PTQ4DM是最早对图像生成模型量化压缩的工作、S2DNAS是最早的自动化动态神经网络设计的工作（ECCV Oral）。他的研究主要在以下几个方面：

-	高效大语言模型（LLM） 
	-	模型的量化压缩、模型的低秩分解压缩、稀疏注意力
	-	端侧LLM的设计和训练、Sparse/Linear Attention混合模型
-	高效视觉生成模型（图像生成、视频生成） 
	-	动态神经网络、模型的量化压缩、稀疏注意力
 	-	视觉生成AR/Diffusion混合架构模型
-	高效计算机视觉模型
	-	视觉模型的量化与剪枝、动态神经网络、网络架构搜索、脉冲神经网络
-	软件-硬件协同优化设计
	-	AI加速器量化系统设计、大模型推理芯片软硬件协同设计


## Publications
Please visit [Google Scholar page](https://scholar.google.com/citations?user=iipYHLoAAAAJ) for more detailed information.

\* indicates equal contribution, + indicates communication author

1. **Yuan Z**\*, Xie R\*, Shang Y, et al. VGDFR: Diffusion-based Video Generation with Dynamic Latent Frame Rate, arXiv preprint arXiv:2504.12259, 2025.
1. Zhou S\*, **Yuan Z**\*, Yang D, et al. PillarHist: A Quantization-aware Pillar Feature Encoder based on Height-aware Histogram, CVPR 2025.
2. Wang K, Shi M, Zhou Y, et al. A Closer Look at Time Steps is Worthy of Triple Speed-Up for Diffusion Model Training, CVPR 2025.
3. **Yuan Z**\*, Wang S\*, Shang Y, et al. DLFR-VAE: Dynamic Latent Frame Rate VAE for Efficient Video Generation, ICML 2025 submission.
4. Hu X\*, Cheng Y\*, Yang D\*..., **Yuan Z**+. OSTQuant: Refining Large Language Model Quantization with Orthogonal and Scaling Transformations for Better Distribution Fitting, ICLR 2025.
5. Xu Z\*, Yue Y\*, Hu X, et al. MambaQuant: Quantizing the Mamba Family with Variance Aligned Rotation Methods, ICLR 2025.
6. **Yuan Z**\*, Shang Y\*, Zhang H, et al. E-CAR: Efficient Continuous Autoregressive Image Generation via Multistage Modeling. arXiv preprint arXiv:2412.14170, 2024.
7. **Yuan Z**\*, Lu P\*, Zhang H\*, et al. DiTFastAttn: Attention Compression for Diffusion Transformer Models, NeurIPS 2024.
8. Duanmu H\*, **Yuan Z**\*, Li X, et al. SKVQ: Sliding-window Key and Value Cache Quantization for Large Language Models. COLM 2024 (Oral).
9. Han Y\*, Liu Z\*, **Yuan Z**\*, et al. Latency-aware unified dynamic networks for efficient image recognition. TPAMI 2024.
10. **Yuan Z**\*, Shang Y\*, Zhou Y\*, et al. LLM Inference Unveiled: Survey and Roofline Model Insights. arXiv preprint arXiv:2402.16363, 2024.
11. Yue Y\*, **Yuan Z**\*, Duanmu H, et al. Wkvquant: Quantizing weight and key/value cache for large language models gains more. arXiv preprint arXiv:2402.12065, 2024.
12. Shang Y\*, **Yuan Z**\*, et al. PB-LLM: Partially Binarized Large Language Models. ICLR 2024.
13. Zhang C, **Yuan Z**, et al. Algorithm-hardware co-design for Energy-Efficient A/D conversion in ReRAM-based accelerators. DATE 2024.
14. Guo A, Chen X, Dong F, et al. 34.3 A 22nm 64kb Lightning-Like Hybrid Computing-in-Memory Macro with a Compressed Adder Tree and Analog-Storage Quantizers for Transformer and CNNs, IEEE International Solid-State Circuits Conference (ISSCC) 2024.
15. **Yuan Z**\*, Shang Y\*, et al. ASVD: Activation-aware Singular Value Decomposition for Compressing Large Language Models. arXiv 2023.
16. Shang Y, **Yuan Z**, et al. MIM4DD: Mutual Information Maximization for Dataset Distillation, NeurIPS 2023.
17. **Yuan Z**\*, Lin N\*, Liu J, et al. RPTQ: Reorder-based Post-training Quantization for Large Language Models. arXiv preprint arXiv:2304.01089, 2023.
18. Niu L, Liu J, **Yuan Z**\+, et al. Improving Post-Training Quantization on Object Detection with Task Loss-Guided Lp Metric. arXiv preprint arXiv:2304.09785, 2023.
19. **Yuan Z**\*, Liu J\*, Wu J, et al. Benchmarking the Reliability of Post-training Quantization: a Particular Focus on Worst-case Performance. AdvML-Frontiers 2023.
20. Shang Y\*, **Yuan Z**\*, Xie B, et al. Post-training Quantization on Diffusion Models. CVPR 2023.
21. Liu J, Niu L, **Yuan Z**\+, et al. PD-Quant: Post-Training Quantization based on Prediction Difference Metric. CVPR 2023.
22. Han Y\*, **Yuan Z**\*, Pu Y, et al. Latency-aware Spatial-wise Dynamic Networks, NeurIPS 2022.
23. Li X\*, **Yuan Z**\*, Guan Y, et al. Flatfish: a Reinforcement Learning Approach for Application-Aware Address Mapping. TCAD 2022.
24. Li X, Bing Z, Guang Y, et al. Enabling High-Quality Uncertainty Quantification in a PIM Designed for Bayesian Neural Network. HPCA 2022.
25. **Yuan Z**\*, Xue C\*, Chen Y, et al. PTQ4ViT: Post-Training Quantization Framework for Vision Transformers. ECCV 2022.
26. **Yuan Z**, Chen Y, Xue C, et al. PTQ-SL: Exploring the Sub-layerwise Post-training Quantization. arXiv preprint arXiv:2110.07809, 2021.
27. **Yuan Z**, Jingze L, Xingchen L, et al. NAS4RRAM: Neural Network Architecture Search for Inference on RRAM-based Accelerators. SCIENCE CHINA Information Sciences (SCIS), 2021.
28. Ding M, Kang Y, **Yuan Z**, et al. Detection of facial landmarks by a convolutional neural network in patients with oral and maxillofacial disease. International Journal of Oral and Maxillofacial Surgery, 2021, 50(11): 1443-1449.
29. **Yuan Z**\*, Wu B\*, Sun G, et al. S2DNAS: Transforming Static CNN Model for Dynamic Inference via Neural Architecture Search. ECCV 2020 (oral).
30. **Yuan Z**, Liu X, Wu B, et al. ENAS4D: Efficient Multi-stage CNN Architecture Search for Dynamic Inference. arXiv preprint, 2020.
31. Guan Y, Sun G, **Yuan Z**, et al. Crane: Mitigating Accelerator Under-utilization Caused by Sparsity Irregularities in CNNs. IEEE Transactions on Computers (TC), 2020.
32. Guan Y, **Yuan Z**, Sun G, et al. FPGA-based accelerator for long short-term memory recurrent neural networks. Asia and South Pacific Design Automation Conference (ASP-DAC), 2017.
33. Wu B, Liu Z, **Yuan Z**, et al. Reducing overfitting in deep convolutional neural networks using redundancy regularizer. International Conference on Artificial Neural Networks (ICANN), 2017.
