# ML_Homework# 线性回归梯度下降作业

## 作业说明：
1. 由于本地网络环境限制，无法访问 UCI 网站下载数据集。因此，我使用了 Python 内置的 `sklearn` 数据集（load_diabetes）代替 UCI 数据集进行算法验证。
2. 本作业使用 Python 和 NumPy 实现了线性回归的梯度下降。代码中包含 `MSELoss` 类（损失类）和 `GradientDescent` 类（优化器类），成功实现了梯度下降优化。
3. 运行结果见 `loss_curve.png`，Loss 随迭代次数稳定下降，证明了优化器类的有效性。
