---
title: "VAE 与 GAN 的初步探索 / Exploring VAE and GAN on Fashion-MNIST"
permalink: /projects/vae-gan-fashionmnist/
categories: ["图像生成 / Image Generation"]
layout: single
classes: wide
---

## 🧠 项目名称 | Project Title  
**VAE 与 GAN 的初步探索 / Exploring Variational Autoencoders (VAE) and Generative Adversarial Networks (GAN) on Fashion-MNIST**

---

### 👤 项目角色 | Role  
项目独立设计与开发者（个人完成）  
Sole Developer & Researcher

---

### 📆 项目周期 | Duration  
2025年4月至5月  
April – May 2025

---

### 📚 所属课程 | Course  
[EECE 7397 – Advanced Machine Learning](/courses/spring-2025/)  
东北大学《高级机器学习》课程项目

---

### 🎯 项目目标 | Objective  
本项目旨在通过实现 VAE 和 GAN 两种基础生成模型，深入理解其原理与训练机制，并在 Fashion-MNIST 数据集上进行实验，积累生成式模型的实践经验。  
This project explored foundational concepts in generative modeling through hands-on implementation of VAE and GAN architectures. The goal was to gain practical experience with model design, training mechanics, and evaluation using the Fashion-MNIST dataset.

---

### 🔧 技术工具 | Technologies  
- Python, PyTorch, NumPy, Matplotlib  
- VAE, GAN 模型构建与训练  
- Fréchet Inception Distance (FID) 用于定量评估

---

### 🧠 我的工作内容 | My Contributions  
- 使用 PyTorch 独立完成 VAE 与 GAN 的构建与训练流程  
- 在 VAE 中实现重参数化技巧，支持网络反向传播  
- 调整 GAN 损失函数以提升训练稳定性  
- 对生成图像进行可视化，并使用 FID 分数作为图像质量参考  
- 全程独立完成数据处理、模型实现、训练评估与最终展示  

- Independently built both VAE and GAN architectures using PyTorch  
- Implemented reparameterization in VAE to enable proper backpropagation  
- Tuned GAN loss functions for stable training  
- Visualized training outputs and assessed quality using FID  
- Completed all stages from data preprocessing to model evaluation and presentation

---

### 📈 项目成果 | Results  
- 成功使用 Fashion-MNIST 数据集，分别构建并训练了 VAE 与 GAN 模型以生成灰度图像  
- VAE 模型生成的图像更平滑连贯，而 GAN 模型则呈现出更多细节与锐度  
- 项目帮助深入理解了两种生成模型的表现差异，尤其在潜空间结构设计与训练策略方面提供了实践视角  

- Successfully implemented VAE and GAN models to generate grayscale images based on the Fashion-MNIST dataset  
- VAE produced smooth and continuous image outputs, while GAN generated sharper and more detailed images  
- The project provided a hands-on understanding of generative model behavior, highlighting differences in latent space design and training strategies

---

### 🔗 项目源码 | GitHub Repository  
- 🔗 [访问项目 GitHub 仓库（中文说明）](https://github.com/kermit0125/VAE-and-GAN-on-the-Fashion-MNIST-Dataset-Using-PyTorch)  
- 🔗 [View GitHub Repository (English)](https://github.com/kermit0125/VAE-and-GAN-on-the-Fashion-MNIST-Dataset-Using-PyTorch)
