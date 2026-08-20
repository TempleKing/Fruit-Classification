# 水果图像分类对比研究

## 📋 项目介绍

本项目对比了三种经典机器学习算法在水果图像分类任务上的性能表现，包括**SVM**、**KNN** 和**Decision Tree**。

通过使用 PCA 进行特征降维，我们探究了这些算法在图像分类问题上的优缺点，为实际应用中算法的选择提供参考。

## 🎯 项目目标

- 对比分析 SVM、KNN、Decision Tree 三种算法的分类性能
- 评估不同算法的准确率、训练时间等关键指标
- 探索特征提取和降维对分类效果的影响
- 为图像分类任务的算法选择提供实验依据

## 📊 项目结构

```
Fruit-Classification/
├── README.md                                          # 项目说明
├── fruit-classification-pca-svm-knn-decision-tree.ipynb  # 主实验笔记本
├── python代码/                                        # Python源代码文件
├── 演示文件/                                          # 演示和结果文件
├── 会议总结/                                          # 项目会议记录
└── 前期调查.docx                                      # 前期调查报告
```

## 🔧 主要技术栈

- **Python 3.x**
- **机器学习库**
  - scikit-learn (SVM、KNN、Decision Tree 实现)
  - numpy & pandas (数据处理)
  - matplotlib & seaborn (数据可视化)
- **特征处理**
  - PCA (主成分分析)
  - OpenCV (图像处理)

## 📈 实验内容

1. **数据集准备** - 水果图像数据收集和预处理
2. **特征提取** - 从图像中提取有效特征
3. **特征降维** - 使用 PCA 进行维度约简
4. **模型训练** - 使用三种算法分别训练分类器
5. **性能评估** - 对比分析准确率、精度、召回率等指标
6. **结果可视化** - 绘制对比图表和分析结果

## 🚀 如何使用

### 环境要求
```bash
pip install numpy pandas scikit-learn opencv-python matplotlib seaborn jupyter
```

### 运行实验
1. 打开 Jupyter Notebook：
```bash
jupyter notebook fruit-classification-pca-svm-knn-decision-tree.ipynb
```
2. 按照笔记本中的说明逐步执行代码单元
3. 查看实验结果和分析

## 📌 主要发现

- 三种算法各有特点，SVM 和 KNN 通常效果较好
- PCA 特征降维有效降低计算复杂度，对分类效果影响较小
- 不同算法的训练时间和空间复杂度存在明显差异
- 实际应用中需根据数据特性和资源限制综合选择

## 📝 参考资源

- [scikit-learn 官方文档](https://scikit-learn.org/)
- [PCA 主成分分析](https://en.wikipedia.org/wiki/Principal_component_analysis)
- [图像分类基础](https://opencv.org/)

---
