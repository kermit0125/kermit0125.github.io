---
title: "隐私保护的垃圾邮件识别 / Privacy-Preserving Spam Email Detection"
permalink: /projects/spam-detection-privacy/
categories: ["数据分类 / Data Classification"]
layout: single
classes: wide
---

## 🧠 项目名称 | Project Title  
**隐私保护的垃圾邮件识别 / Privacy-Preserving Spam Email Detection**

---

### 👤 项目角色 | Role  
项目代码部分负责人，主导数据预处理、模型训练与评估代码实现  
Lead Developer for Data Processing & Modeling

---

### 📆 项目周期 | Duration  
2025年11月 – 12月  
November – December 2025

---

### 📚 所属课程 | Course  
[EECE 5644 – Machine Learning & Pattern Recognition](/courses/fall-2025/)  
东北大学《机器学习与模式识别》课程项目

---

### 🎯 项目目标 | Objective  
本项目旨在构建一个轻量、隐私保护的垃圾邮件分类系统。通过词频向量替代原始文本，实现本地化特征提取与降维处理，进一步比较多种分类模型（Random Forest 与 RBF-SVM）在不同预处理下的表现，最终实现高效的邮件识别。  
This project aimed to build a lightweight, privacy-preserving spam email classification system. By replacing raw text with word frequency vectors and applying dimensionality reduction techniques (e.g., PCA), the project compared the effectiveness of models like Random Forest and RBF-SVM under various preprocessing pipelines.

---

### 🔧 技术工具 | Technologies  
- Python, scikit-learn, NumPy, Pandas  
- 自然语言处理（词频向量化） / Natural Language Processing (Word Frequency Vector)  
- 随机森林 / Random Forest  
- 径向基核支持向量机 / RBF Support Vector Machine (SVM)  
- 主成分分析 / Principal Component Analysis (PCA)  
- SMOTE 欠采样平衡方法  
- Seaborn 与 Matplotlib 可视化工具

---

### 🧠 我的工作内容 | My Contributions  
- 负责完成数据加载、清洗、SMOTE 平衡、归一化与 PCA 降维流程  
- 独立实现 Random Forest 与 RBF-SVM 模型的训练与交叉验证对比  
- 评估模型在降维与非降维下的性能差异，并生成混淆矩阵与可视化图  
- 梳理整体 pipeline，从数据预处理 → 特征提取 → 模型训练 → 精度评估  

- Led the development of data preprocessing pipeline: cleaning, SMOTE, normalization, PCA  
- Implemented and compared Random Forest and RBF-SVM models in Python  
- Evaluated performance with and without dimensionality reduction  
- Generated confusion matrices, accuracy scores, and feature importance plots  
- Contributed all code for modeling and analysis phases

---

### 📈 项目成果 | Results  
- 降维后模型整体精度仍保持在 89%–91%，特征数大幅减少  
- 成功验证了词频向量在隐私场景下的可行性，无需处理原始邮件文本  
- Random Forest 模型在泛化能力与可解释性上优于 SVM  
- 图形结果展示了重要词汇、主成分投影与模型决策边界  

- Achieved over 90% accuracy with reduced input dimensions  
- Preserved privacy by avoiding direct use of email content  
- Random Forest showed more stable and interpretable results compared to SVM  
- Visualization included PCA projections, feature importance, and confusion matrix

---

### 🔗 项目源码 | GitHub Repository  
- 🔗 [访问项目 GitHub 仓库（中文说明）](https://github.com/kermit0125/Privacy-Preserving-Spam-Email-Detection)  
- 🔗 [View GitHub Repository (English)](https://github.com/kermit0125/Privacy-Preserving-Spam-Email-Detection)
