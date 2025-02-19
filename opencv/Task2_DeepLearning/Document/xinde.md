# TASK2_DeepLearing 
## 感知机
在理论学习阶段，理解多层感知机的基本结构以及它如何处理输入输出关系是关键。每个神经元的激活方式、权重的初始化与更新等概念都需要深入掌握。在学习过程中认识到了激活函数的重要性，在代码实现方面，运用 Python 结合 PyTorch 库进行搭建的过程，让我更加熟悉了 PyTorch 的基本操作流程，例如定义张量、构建网络层、设置前向传播机制等。调试过程也很有挑战性，需要仔细观察每层的输出结果，排查是否出现梯度消失、梯度爆炸等问题，不断调整网络的超参数，如学习率、隐藏层神经元数量等，最终看到模型能够准确输出 XOR 运算结果时

https://github.com/user-attachments/assets/cd544f88-7a70-4ffa-af15-decb56d0019c

。  
## 构建神经网络  
首先，准备自己书写的汉字数据集就是一项庞大的工程。要确保每个汉字有足够多样的书写样本，涵盖不同的字体风格、笔画粗细、书写角度等，这让我意识到数据的质量和多样性对于模型训练效果有着至关重要的影响.构建卷积神经网络模型时，我需要根据汉字图像的特点来确定合适的网络结构。比如卷积核的大小、卷积层的数量、池化方式以及全连接层的设置等，每一个参

https://github.com/user-attachments/assets/c7c2ea9f-7d2d-4c65-aded-49ce846c7c88

数的选择都会影响模型最终的识别准确率。认识了卷积的计算和池化等图像处理方法。并认识到了过拟合和防止过拟合合的方法。  
## YOLOV11的使用
在学习 yolov11 的过程中，了解其独特的网络架构和工作原理是第一步。它将目标检测任务拆分成多个子任务，通过不同尺度的特征图来检测不同大小的目标，这种多尺度融合的思想非常巧妙，也让我对目标检测领域有了新的认识。在准备垃圾数据集时，要准确地将可回收、有害垃圾、厨余垃圾等至少各三种进行分类标注，这要求我对各类垃圾的定义和特征有清晰的认知，并且标注过程需十分细致，任何错误的标注都可能影响模型的训练效果。

https://github.com/user-attachments/assets/7637267f-2a70-4e77-87a1-984a08d3b407

