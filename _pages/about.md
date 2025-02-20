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

袁之航的研究方向为高效人工智能（Efficient AI）。在多个AI顶会和顶刊上发表十余篇论文（3 ICLR, 3 NeurIPS, 2 CVPR, 2 ECCV, 1 TPAMI），在计算机系统架构方面发表数篇论文（1 TCAD, 1 HPCA, 1 TC, 1 DATE, 1 ASP-DAC, 1 SCIS），根据 Google Scholar 2025年1月的数据，他的文章总引用次数超过 1100 次。根据Github的数据，他的开源项目Star 1500+，Fork 200+。他在神经网络的压缩方面做了很多创新性的工作，例如ASVD是最早对LLM进行低秩分解压缩的工作、PTQ4ViT是最早对Vision Transformer量化压缩工作之一、PTQ4DM是最早对图像生成模型量化压缩的工作、S2DNAS是最早的自动化动态神经网络设计的工作（ECCV Oral）。他的研究主要在以下几个方面：

-	高效大语言模型（LLM） 
	-	模型的量化压缩、模型的低秩分解压缩、稀疏注意力
	-	多模态模型的压缩、端侧LLM的设计和训练、具身智能VLA模型的压缩
-	高效视觉生成模型（图像生成、视频生成） 
	-	模型的量化压缩、稀疏注意力、高效生成模型架构设计和训练
-	高效计算机视觉模型
	-	视觉模型的量化与剪枝、动态神经网络、网络架构搜索、脉冲神经网络
-	软件-硬件协同优化设计
	-	AI加速器量化系统设计、大模型推理芯片软硬件协同设计


## Publications
Please visit [Google Scholar page](https://scholar.google.com/citations?user=iipYHLoAAAAJ) for more detailed information.

- Yuan Z, Shang Y, Zhang H, et al. E-CAR: Efficient Continuous Autoregressive Image Generation via Multistage Modeling. arXiv preprint arXiv:2412.14170, 2024 (co-first).
- Yuan Z, Lu P, Zhang H, et al. DiTFastAttn: Attention Compression for Diffusion Transformer Models. NeurIPS 2024 (co-first).
- Zhou S, Yuan Z, Yang D, et al. PillarHist: A Quantization-aware Pillar Feature Encoder based on Height-aware Histogram. arXiv preprint arXiv:2405.18734, 2024 (co-first).
- Hu X, Chen Y, Yang D, et al. I-LLM: Efficient Integer-Only Inference for Fully-Quantized Low-Bit Large Language Models. arXiv preprint arXiv:2405.17849, 2024.
- Duanmu H, Yuan Z, Li X, et al. SKVQ: Sliding-window Key and Value Cache Quantization for Large Language Models. COLM 2024 (Oral) (co-first).
- Han Y, Liu Z, Yuan Z, et al. Latency-aware unified dynamic networks for efficient image recognition. IEEE Transactions on Pattern Analysis and Machine Intelligence (TPAMI), 2024 (co-first).
- Yuan Z, Shang Y, Zhou Y, et al. LLM Inference Unveiled: Survey and Roofline Model Insights. arXiv preprint arXiv:2402.16363, 2024 (co-first).
- Yue Y, Yuan Z, Duanmu H, et al. Wkvquant: Quantizing weight and key/value cache for large language models gains more. arXiv preprint arXiv:2402.12065, 2024. (co-first)
- Wang H, Shang Y, Yuan Z, et al. QuEST: Low-bit Diffusion Model Quantization via Efficient Selective Finetuning. arXiv preprint arXiv:2402.03666, 2024.
- Yang D, He N, Hu X, et al. Post-training quantization for re-parameterization via coarse & fine weight splitting. Journal of Systems Architecture, 2024, 147: 103065.
- Yuan Z*, Shang Y*, et al. ASVD: Activation-aware Singular Value Decomposition for Compressing Large Language Models. arXiv 2023. (co-first)
- Yuan Z, et al. PB-LLM: Partially Binarized Large Language Models. ICLR 2024.
- Shang Y, Yuan Z, et al. MIM4DD: Mutual Information Maximization for Dataset Distillation, NeurIPS, 2023.
- Yuan Z, Lin N, Liu J, et al. RPTQ: Reorder-based Post-training Quantization for Large Language Models. arXiv preprint arXiv:2304.01089, 2023.
- Niu L, Liu J, Yuan Z, et al. Improving Post-Training Quantization on Object Detection with Task Loss-Guided Lp Metric. arXiv preprint arXiv:2304.09785, 2023.
- Yuan Z, Liu J, Wu J, et al. Benchmarking the Reliability of Post-training Quantization: a Particular Focus on Worst-case Performance. AdvML-Frontiers 2023.
- Shang Y, Yuan Z, Xie B, et al. Post-training Quantization on Diffusion Models. CVPR 2023. (co-first)
- Liu J, Niu L, Yuan Z, et al. PD-Quant: Post-Training Quantization based on Prediction Difference Metric. CVPR 2023. (communication)
- Han Y, Yuan Z, Pu Y, et al. Latency-aware Spatial-wise Dynamic Networks, NeurIPS 2022. (co-first)
- Li X, Yuan Z, Guan Y, et al. Flatfish: a Reinforcement Learning Approach for Application-Aware Address Mapping. IEEE Transactions on Computer-Aided Design of Integrated Circuits and Systems (TCAD), 2022. (co-first)
- Li X, Bing Z, Guang Y, et al. Enabling High-Quality Uncertainty Quantification in a PIM Designed for Bayesian Neural Network. HPCA, 2022.
- Yuan Z, Xue C, Chen Y, et al. PTQ4ViT: Post-Training Quantization Framework for Vision Transformers. European Conference on Computer Vision (ECCV), 2022. (co-first)
- Yuan Z, Chen Y, Xue C, et al. PTQ-SL: Exploring the Sub-layerwise Post-training Quantization. arXiv preprint arXiv:2110.07809, 2021.
- Yuan Z, Jingze L, Xingchen L, et al. NAS4RRAM: Neural Network Architecture Search for Inference on RRAM-based Accelerators. SCIENCE CHINA Information Sciences, 2021. 
- Yuan Z, Wu B, Sun G, et al. S2DNAS: Transforming Static CNN Model for Dynamic Inference via Neural Architecture Search. European Conference on Computer Vision (ECCV oral), 2020.
- Yuan Z, Liu X, Wu B, et al. ENAS4D: Efficient Multi-stage CNN Architecture Search for Dynamic Inference. arXiv preprint, 2020.
- Guan Y, Sun G, Yuan Z, et al. Crane: Mitigating Accelerator Under-utilization Caused by Sparsity Irregularities in CNNs. IEEE Transactions on Computers (TC), 2020.
- Guan Y, Yuan Z, Sun G, et al. FPGA-based accelerator for long short-term memory recurrent neural networks. Asia and South Pacific Design Automation Conference (ASP-DAC), 2017.
- Wu B, Liu Z, Yuan Z, et al. Reducing overfitting in deep convolutional neural networks using redundancy regularizer. International Conference on Artificial Neural Networks (ICANN), 2017.

