# 支持向量机（SVM）分类项目

## 简介

本项目使用支持向量机（SVM）算法对Iris和Sonar数据集进行分类。通过不同的核函数配置，比较模型在不同数据集上的性能表现。

## 数据集

1. **Iris 数据集**：经典的鸢尾花数据集，用于多类别分类问题。
2. **Sonar 数据集**：用于区分金属物体和岩石物体的声纳信号数据集。

## 项目结构

- `SVM_Iris.ipynb`：使用SVM对Iris数据集进行分类的Notebook。
- `SVM_Sonar.ipynb`：使用SVM对Sonar数据集进行分类的Notebook。

## 环境配置

确保已安装以下Python库：

- numpy
- pandas
- scikit-learn
- matplotlib
- seaborn

可以使用以下命令安装依赖：

```bash
pip install -r requirements.txt
```

## 使用说明

1. 打开对应的Jupyter Notebook文件（如`SVM_Iris.ipynb`）。
2. 按顺序运行各个代码单元，训练并评估SVM模型。
3. 查看模型的分类报告、混淆矩阵和ROC曲线。

## 模型配置

项目中尝试了多种SVM核函数配置，包括：

- 线性核
- 多项式核（度数为2和3）
- 高斯核（RBF）
- Sigmoid核
- 拉普拉斯核

每种模型的性能指标将在Notebook中展示。

## 结果

在运行Notebook后，您将获得每个模型的分类报告、混淆矩阵和ROC曲线图像，便于对比不同核函数的效果。

## 贡献

欢迎参与本项目的开发和改进，请提交Pull Request或联系维护者。

## 许可证

本项目采用MIT许可证，详情请参阅`LICENSE`文件。
