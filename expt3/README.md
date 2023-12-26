# 分类算法原理及应用：以垃圾短信数据集为例
Created by Vulcan626 on 2023/12/26

## 概览
本实验使用短信垃圾数据集进行文本分类。目标是区分'ham'（合法信息）和'spam'（垃圾信息）。

## 数据集
数据集位于`sms-spam-collection`目录中，包含以下文件：
- `SMSSpamCollection`：带标签信息的主数据集文件。
- `readme`：描述数据集及其结构。

## 分类笔记本
`classification.ipynb` Jupyter笔记本包含数据预处理、特征提取、训练分类模型、评估性能和结果可视化的代码。

## 评估模型
- 朴素贝叶斯
- 决策树
- K最近邻（KNN）

## 结果
模型的性能详细信息记录在笔记本中，并在`classification_reports.xlsx`文件中进行了总结。

## 使用说明
要运行实验，请在Jupyter环境中打开`classification.ipynb`笔记本，并依次执行单元格。

## 许可
短信垃圾数据集根据[创作共用署名 4.0 国际许可证](https://creativecommons.org/licenses/by/4.0/)使用。
dataset url：https://archive.ics.uci.edu/dataset/228/sms+spam+collection
## 联系方式
如有其他问题或反馈，请联系[Vulcan626/08212759@cumt.edu.cn]。
