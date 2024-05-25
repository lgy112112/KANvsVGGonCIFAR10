
# KAN vs VGG16 on CIFAR-10

## 项目简介

本项目旨在比较 KAN（Kolmogorov-Arnold Network）和 VGG16 模型在 CIFAR-10 数据集上的性能。我使用了 ResNet 的思想对 KAN 模型进行了改造，增加了残差连接和源代码的正则化损失。最终结果表明，尽管进行了改进，KAN 模型在性能上仍然不如 VGG16 模型。

## 依赖项

请确保您的环境中安装了以下依赖项：

- Python 3.7+
- PyTorch
- torchvision
- tqdm
- matplotlib
- scikit-learn

您可以通过运行以下命令来安装这些依赖项：

```bash
pip install torch torchvision tqdm matplotlib scikit-learn
```

## 结果

![image](https://github.com/lgy112112/KANvsVGGonCIFAR10/assets/144128974/ac984542-867a-40e2-b4cd-c08a1fa2522f)
![image](https://github.com/lgy112112/KANvsVGGonCIFAR10/assets/144128974/35d445da-f961-4bac-9ecf-1fbca05cff95)

# KAN vs VGG16 on CIFAR-10

## Project Overview

This project aims to compare the performance of the KAN (Kolmogorov-Arnold Network) and VGG16 models on the CIFAR-10 dataset. I have incorporated the ideas from ResNet into the KAN model by adding residual connections and regularization loss from the source code. The final results show that, despite these improvements, the KAN model still performs worse than the VGG16 model.

## Dependencies

Please ensure that you have the following dependencies installed in your environment:

- Python 3.7+
- PyTorch
- torchvision
- tqdm
- matplotlib
- scikit-learn

You can install these dependencies by running the following command:

```bash
pip install torch torchvision tqdm matplotlib scikit-learn
```

## Results

![image](https://github.com/lgy112112/KANvsVGGonCIFAR10/assets/144128974/ac984542-867a-40e2-b4cd-c08a1fa2522f)
![image](https://github.com/lgy112112/KANvsVGGonCIFAR10/assets/144128974/35d445da-f961-4bac-9ecf-1fbca05cff95)
