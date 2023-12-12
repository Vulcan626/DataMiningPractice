# 聚类算法原理及应用：以Iris数据集为例
created by Vulcan626 on 2023/12/12

## 简介
本项目包含了一系列文件，用于在鸢尾花（Iris）数据集上进行聚类分析实验。主要涵盖了不同的聚类算法，包括 K-means、K-modes、K-means++、PAM (K中心点) 以及层次聚类和密度聚类方法。

## 文件列表
- `iris.zip`：原始的爱丽丝鸢尾花数据集。
- `pre.ipynb`：数据预处理 Jupyter 笔记本，包含数据加载、清洗和标准化步骤。
- `clustering.ipynb`：聚类算法实现的 Jupyter 笔记本，包含各种聚类方法的实现和评估。

## 使用说明

### 数据预处理
1. 首先，解压 `iris.zip` 文件，获取原始数据集。
2. 使用 `pre.ipynb` 笔记本对数据进行预处理，包括数据清洗、特征选择和数据标准化等。
3. 处理后的数据将被保存，以便在聚类实验中使用。

### 聚类实验
1. 打开 `clustering.ipynb` 笔记本。
2. 笔记本中包含了以下聚类方法的实现：
    - 划分式聚类（K-means、K-modes、K-means++、PAM）
    - 层次式聚类（AGNES）
    - 密度式聚类（DBSCAN）
3. 每种算法都配有相应的实现代码和参数说明。
4. 使用预处理后的数据集进行聚类实验，并通过轮廓系数等指标评估聚类效果。

### 可视化
- 聚类结果的可视化通过降维（如 PCA）实现，以便直观地评估聚类效果。

## 注意事项
- 确保在运行笔记本前已安装必要的 Python 库，如 `scikit-learn`, `scikit-learn-extra`, `kmodes` 等。
- 对于 K-modes 和 PAM 算法，请根据实际需要安装相应的 Python 库或按照给定的代码示例进行实现。
- 根据您的具体需求，您可能需要对聚类算法的参数进行调整。

---

数据集来源：[UCI Machine Learning Repository](https://archive.ics.uci.edu/dataset/53/iris)