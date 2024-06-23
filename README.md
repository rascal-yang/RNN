# 循环神经网络起名程序

## 项目简介
本项目是一个使用循环神经网络（Recurrent Neural Network, RNN）来生成名字的实验程序。项目中实现了基本的RNN结构，并探索了双向RNN（BiRNN）的构造和训练过程。

## 环境要求
- Python 3.9
- PyTorch
- NumPy
- 其他可能的依赖项（根据实际运行情况可能需要安装）

## 文件结构
```
RNN_Name_Generator/
│
├── Bidirectional_RNN.ipynb # 双向RNN探索
├── RNN.ipynb       # 实现了RNN起名程序的核心代码
└── A5实验报告.pdf     # 包含项目详细描述、实验结果和分析的实验报告
```

## 如何运行
1. 确保Python环境已安装，并且安装了所需的依赖包。
2. 打开`Phase_One.py`文件，并根据需要调整参数或添加额外的功能。
3. 运行`Phase_One.py`文件开始训练起名程序。

## 实验概览
- **数据集**：使用了包含8000多个英文名字的数据集。
- **模型结构**：项目中实现了基本的RNN结构，并尝试了双向RNN的构造。
- **训练过程**：详细记录了模型的训练过程，包括损失函数的选择和参数的更新策略。
- **实验结果**：提供了模型训练过程中损失值的变化情况，以及模型生成名字的示例。

## 贡献与反馈
欢迎提交Pull Request或创建Issue来改进项目。
