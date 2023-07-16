| 第二届计图挑战赛热身赛

# Jittor 草图生成风景比赛 baseline
| 标题名称包含赛题、方法

![主要结果]
https://github.com/pangyd/jittor-Eternal-my_pub/result.png

｜展示方法的流程特点或者主要结果等

## 简介
| 简单介绍项目背景、项目特点

本项目包含了第二届计图挑战赛计图 - 计图挑战热身赛的代码实现。本项目的特点是：采用了Conditional GAN（Conditional generative adversarial nets）模型，通过输入一个随机向量 z 和额外的辅助信息 y (如类别标签)，生成特定数字的图像。

## 安装 
| 介绍基本的硬件需求、运行环境、依赖安装方法

本项目可在 1 张 1050ti 上运行，训练时间约为 6 小时。

#### 运行环境
- Windows11
- python = 3.9
- jittor = 1.3.6.5

#### 训练模型
｜ 介绍模型训练的方法

单卡训练可运行以下命令：
```
python CGAN.py
```

## 致谢
| 对参考的论文、开源库予以致谢，可选

此项目基于论文 *A Style-Based Generator Architecture for Generative Adversarial Networks* 实现，部分代码参考了 [jittor-gan](https://github.com/Jittor/gan-jittor)。
