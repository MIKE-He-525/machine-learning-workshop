# Machine Learning Workshop

机器学习课程实验项目，包含 10 个实验（LAB2–LAB11），覆盖从数据预处理到聚类分析的完整机器学习工作流。每个实验以 Jupyter Notebook 形式组织，配套数据集位于对应实验目录中。

## 项目结构

```
Machine-Learning-Workshop/
├── LAB2/   Data_Preprocessing.ipynb
├── LAB3/   Linear_Regression.ipynb
├── LAB4/   Logistic_Regression.ipynb
├── LAB5/   Neural_Network.ipynb
├── LAB6/   Multiclass_Classification.ipynb
├── LAB7/   Cross_Validation_and_Regularization.ipynb
├── LAB8/   Support_Vector_Machine.ipynb
├── LAB9/   KNN_and_Decision_Tree.ipynb
├── LAB10/  Ensemble_Learning.ipynb
└── LAB11/  Clustering_Analysis.ipynb
```

## 实验内容

| 实验 | Notebook | 主题 | 数据集 |
|------|----------|------|--------|
| LAB2 | `Data_Preprocessing.ipynb` | 数据探索、缺失值处理、特征缩放、Pipeline 构建 | Airbnb `listings.csv` |
| LAB3 | `Linear_Regression.ipynb` | 线性回归建模、残差分析、交叉验证 | scikit-learn Diabetes 数据集 |
| LAB4 | `Logistic_Regression.ipynb` | 逻辑回归、L1/L2 正则化、ROC/AUC、超参数调优 | `titanic.csv`、Iris 数据集 |
| LAB5 | `Neural_Network.ipynb` | 多层感知机（MLP）、手写数字分类、GridSearchCV | scikit-learn Digits 数据集 |
| LAB6 | `Multiclass_Classification.ipynb` | 多分类问题、逻辑回归与神经网络对比、超参数调优 | `winequality-white.csv` |
| LAB7 | `Cross_Validation_and_Regularization.ipynb` | K 折交叉验证、Ridge/Lasso 正则化、GridSearchCV | Breast Cancer、California Housing |
| LAB8 | `Support_Vector_Machine.ipynb` | SVM 核函数比较、PCA 可视化、嵌套交叉验证、学习曲线 | Iris、Wine 数据集 |
| LAB9 | `KNN_and_Decision_Tree.ipynb` | KNN 与决策树、客户流失预测、超参数调优 | `Telco-Customer-Churn.csv` |
| LAB10 | `Ensemble_Learning.ipynb` | Bagging、随机森林、AdaBoost、梯度提升、Voting/Stacking | Breast Cancer 数据集 |
| LAB11 | `Clustering_Analysis.ipynb` | K-Means、层次聚类、DBSCAN、轮廓系数、客户分群 | `Wholesale customers data.csv` |

## 环境要求

- Python 3.8+
- Jupyter Notebook 或 JupyterLab

### 依赖安装

```bash
pip install numpy pandas matplotlib seaborn scikit-learn scipy jupyter
```

主要依赖说明：

| 库 | 用途 |
|----|------|
| `numpy` / `pandas` | 数值计算与数据处理 |
| `matplotlib` / `seaborn` | 数据可视化 |
| `scikit-learn` | 机器学习算法与评估工具 |
| `scipy` | 层次聚类（LAB11） |

## 快速开始

1. 克隆或下载本项目到本地。
2. 安装上述依赖。
3. 启动 Jupyter：

```bash
jupyter notebook
```

4. 进入对应实验目录，打开 Notebook 并按顺序运行单元格。

> **注意**：部分实验依赖同目录下的 CSV 数据文件（如 LAB4 的 `titanic.csv`、LAB9 的 `Telco-Customer-Churn.csv`），请确保 Notebook 与数据文件位于同一文件夹内，避免路径错误。

## 实验顺序建议

实验按编号递进，建议从 LAB2 开始依次完成：

1. **数据基础** — LAB2 数据预处理
2. **监督学习入门** — LAB3 线性回归 → LAB4 逻辑回归
3. **模型进阶** — LAB5 神经网络 → LAB6 多分类
4. **模型评估与调优** — LAB7 交叉验证与正则化 → LAB8 SVM
5. **树模型与集成** — LAB9 KNN/决策树 → LAB10 集成学习
6. **无监督学习** — LAB11 聚类分析

## 技术栈

- **语言**：Python
- **核心框架**：scikit-learn
- **交互环境**：Jupyter Notebook

## 许可证

本项目采用 [MIT License](LICENSE) 开源。
