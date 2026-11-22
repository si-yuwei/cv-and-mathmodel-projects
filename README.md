# cv-and-mathmodel-projects

CV 方向与数学建模代码仓库。

## 目录结构

- `scripts/` 可复现的 Python 脚本
- `docs/` 建模思路、实验记录、说明文档
- `data/` 数据集（本地保留，不入库）
- `figures/` 图表（本地保留，不入库）
- `results/` 结果输出（本地保留，不入库）

## 环境

- 解释器：Python 3.12（Anaconda）
- 建模栈：numpy / pandas / scipy / scikit-learn / pulp / cvxopt
- CV 栈：opencv / pillow（训练任务提交至学校 HPC 集群）

## 约定

- 脚本按"数据读取 → 预处理 → 建模/求解 → 结果输出"分段。
- 模型权重、数据集、密钥文件不入库。
- 关键实验记录写入 `docs/`，保留可复现脚本与中间数据。
