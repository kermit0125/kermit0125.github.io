---
title: "基于手势识别的贪吃蛇游戏 / Gesture-Controlled Snake Game"
permalink: /projects/gesture-snake-game/
categories: ["计算机视觉 / Computer Vision", "交互设计 / Interactive Design"]
layout: single
classes: wide
---

## 🧠 项目名称 | Project Title  
**基于手势识别的贪吃蛇游戏 / Gesture-Controlled Snake Game**

---

### 👤 项目角色 | Role  
项目独立开发者，完成全部功能设计与测试  
Sole Developer: Implemented and tested all features

---

### 📆 项目周期 | Duration  
2023年11月 – 12月  
November – December 2023

---

### 📚 所属课程 | Course  
[CPS3410 – Advanced Data Structures](/courses/fall-2023/)  
东北大学《高级数据结构》课程项目

---

### 🎯 项目目标 | Objective  
本项目旨在开发一个可通过摄像头捕捉手势信息并控制游戏角色的交互式贪吃蛇游戏。项目使用 MediaPipe 进行手部关键点检测，结合 OpenCV 处理实时图像数据，重点优化环境光照适应、帧率控制（FPS > 30）及食指关键点定位稳定性，保证游戏控制的响应性与准确性。

This project aims to develop an interactive snake game controlled via hand gestures captured by a webcam. MediaPipe was used for real-time hand landmark detection and OpenCV for video processing. The project focuses on adapting to lighting conditions, ensuring a frame rate above 30 FPS, and reliably tracking the index fingertip to serve as the game control input.

---

### 🔧 技术工具 | Technologies  
- Python, OpenCV, MediaPipe, TQDM, Time
- 实时视频处理与亮度自适应调整 / Real-time video brightness normalization
- 手势检测与关键点定位 / Gesture tracking and landmark detection
- 交互式游戏控制（贪吃蛇）/ Interactive Snake Game

---

### 🧠 我的工作内容 | My Contributions  
- 构建摄像头输入与实时图像处理模块，确保帧率稳定在 30 以上  
- 利用 MediaPipe 实现手部 21 点检测，并准确获取食指指尖位置  
- 实现亮度检测与分级处理，对不同环境光进行适应性增强  
- 计划将手势控制集成至自定义贪吃蛇游戏控制系统（后续迭代）

- Built video input & processing module with consistent frame rate (>30 FPS)  
- Used MediaPipe to detect 21 hand landmarks and track the index fingertip  
- Implemented brightness detection and adaptive enhancement under different light conditions  
- Designed the gesture input module for integration with a Snake game interface (to be continued)

---

### 📈 项目成果 | Results  
- 系统成功实现了对手势的稳定检测与关键点渲染  
- 图像亮度调节显著提升了弱光/强光下手势识别效果  
- 游戏控制响应流畅，系统稳定运行于笔记本摄像头环境下

- Stable gesture tracking and fingertip detection achieved  
- Adaptive brightness correction improved usability under varied lighting  
- Real-time interaction verified with smooth response on laptop webcam

---

### 🎥 项目演示 | Demo Video  
- 📺 [点击观看演示视频 / View Demo Video](https://youtu.be/ovJpZBq11Pc)

---

### 🔗 项目链接 | Project Links  
- GitHub 暂无 / GitHub not available
