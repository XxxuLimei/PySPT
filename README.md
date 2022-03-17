# PySPT——执行信号处理和分析
[![Python](https://img.shields.io/badge/python-3.9-blue)](https://docs.python.org/zh-cn/3.9/)
[![Numpy](https://img.shields.io/badge/numpy-1.22.0-brightgreen)](https://numpy.org/doc/stable/)
[![Scipy](https://img.shields.io/badge/scipy-1.9.0-brightgreen)](https://docs.scipy.org/doc/)
[![Matplotlib](https://img.shields.io/badge/matplotlib-3.5.1-brightgreen)](https://matplotlib.org/3.5.1/index.html)

PySPT 提供了一些函数和 App，用来分析、预处理及提取均匀和非均匀采样信号的特征。该工具箱包含可用于滤波器设计和分析、重采样、平滑处理、去趋势和功率谱估计的工具。该工具箱还提供了提取特征（如变化点和包络）、寻找波峰和信号模式、量化信号相似性以及执行 SNR 和失真等测量的功能。您还可以对振动信号执行模态和阶次分析。

使用信号分析器，您可以：在时域、频域和时频域同时预处理和分析多个信号，而无需编写代码；探查长信号；以及提取感兴趣的区域。通过滤波器设计工具，您可以从多种算法和响应中进行选择来设计和分析数字滤波器。

> 对应的Matlab案例 : [Signal Processing Toolbox--MathWorks](https://ww2.mathworks.cn/help/signal/index.html?s_tid=CRUX_lftnav)  

---
### 目录  
- [PySPT 快速入门](./Content/PySPT快速入门.md)  
PySPT 基础知识学习

- 信号分析和可视化  
使用**Signal Analyzer**来可视化、预处理和探查信号

- [信号生成和预处理](./Content/信号生成和预处理.md)  
对信号进行创建、重采样、平滑、去噪和去趋势处理

- 测量和特征提取  
波峰、信号统计、脉冲和瞬态指标、功率、带宽、失真

- [变换、相关性和建模](./Content/变换、相关性和建模.md)  
互相关、自相关、傅里叶、DCT、Hilbert、Goertzel、参数化建模、线性预测编码

- 数字和模拟滤波器  
FIR 和 IIR、单速率和多速率滤波器设计、分析和实现

- 频谱分析  
功率谱、相干性、窗口

- 时频分析  
频谱图、同步压缩、重排、Wigner-Ville、时频边缘、数据自适应方法

- 振动分析  
阶数分析、时间同步平均、包络频谱、模态分析、雨流计数

- 信号的机器学习和深度学习延伸  
信号标注、特征工程、数据集生成

- 代码生成和 GPU 支持  
生成可移植的 C/C++/MEX 函数，并使用 GPU 来部署或加速处理
