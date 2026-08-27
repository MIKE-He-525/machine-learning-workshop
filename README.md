# Machine Learning Workshop

机器学习课程实验 LAB2–LAB11：数据预处理、监督学习、集成学习与聚类分析。

## 这是什么

本仓库包含 10 个机器学习课程实验（LAB2 至 LAB11），每个实验提供独立的 Jupyter Notebook，部分实验配套 CSV 数据集。涵盖数据预处理、回归与分类、神经网络、SVM、集成学习和聚类分析。

## 实验内容

| 实验 | Notebook | 主题 | 数据集 |
|------|----------|------|--------|
| LAB2 | `Data_Preprocessing.ipynb` | 数据探索、缺失值处理、特征缩放、Pipeline 构建 | `listings.csv` |
| LAB3 | `Linear_Regression.ipynb` | 线性回归建模、残差分析、交叉验证 | scikit-learn 内置数据集 |
| LAB4 | `Logistic_Regression.ipynb` | 逻辑回归、L1/L2 正则化、ROC/AUC、超参数调优 | `titanic.csv` |
| LAB5 | `Neural_Network.ipynb` | 多层感知机（MLP）、手写数字分类、GridSearchCV | scikit-learn 内置数据集 |
| LAB6 | `Multiclass_Classification.ipynb` | 多分类问题、逻辑回归与神经网络对比 | `winequality-white.csv` |
| LAB7 | `Cross_Validation_and_Regularization.ipynb` | K 折交叉验证、Ridge/Lasso 正则化 | `california_housing.csv` |
| LAB8 | `Support_Vector_Machine.ipynb` | SVM 核函数比较、PCA 可视化、嵌套交叉验证 | scikit-learn 内置数据集 |
| LAB9 | `KNN_and_Decision_Tree.ipynb` | KNN 与决策树、客户流失预测、超参数调优 | `Telco-Customer-Churn.csv` |
| LAB10 | `Ensemble_Learning.ipynb` | Bagging、随机森林、AdaBoost、梯度提升、Voting/Stacking | scikit-learn 内置数据集 |
| LAB11 | `Clustering_Analysis.ipynb` | K-Means、层次聚类、DBSCAN、轮廓系数、客户分群 | `Wholesale customers data.csv` |

## 快速开始

```bash
git clone https://github.com/MIKE-He-525/machine-learning-workshop.git
cd machine-learning-workshop
pip install numpy pandas matplotlib seaborn scikit-learn scipy jupyter
jupyter notebook
```

打开对应实验目录下的 `.ipynb` 文件，按顺序运行单元格。数据集已位于各 LAB 文件夹内。

## 实验顺序

建议按编号顺序完成：

1. **数据基础** — LAB2 数据预处理
2. **监督学习入门** — LAB3 线性回归 → LAB4 逻辑回归
3. **模型进阶** — LAB5 神经网络 → LAB6 多分类
4. **模型评估与调优** — LAB7 交叉验证与正则化 → LAB8 SVM
5. **树模型与集成** — LAB9 KNN/决策树 → LAB10 集成学习
6. **无监督学习** — LAB11 聚类分析

## 项目结构

```
machine-learning-workshop/
├── LAB2/   Data_Preprocessing.ipynb + listings.csv
├── LAB3/   Linear_Regression.ipynb
├── LAB4/   Logistic_Regression.ipynb + titanic.csv
├── LAB5/   Neural_Network.ipynb
├── LAB6/   Multiclass_Classification.ipynb + winequality-white.csv
├── LAB7/   Cross_Validation_and_Regularization.ipynb + california_housing.csv
├── LAB8/   Support_Vector_Machine.ipynb
├── LAB9/   KNN_and_Decision_Tree.ipynb + Telco-Customer-Churn.csv
├── LAB10/  Ensemble_Learning.ipynb
└── LAB11/  Clustering_Analysis.ipynb + Wholesale customers data.csv
```

## 依赖

- Python 3.8+
- numpy、pandas、matplotlib、seaborn、scikit-learn、scipy、jupyter

## 许可证

MIT
