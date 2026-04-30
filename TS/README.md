# TS
Shumway & Stoffer 《时间序列分析及其应用》学习笔记与 Python 实现仓库

---

## 仓库说明
本仓库为 Shumway & Stoffer 经典教材《时间序列分析及其应用》的学习记录，包含各章节笔记、关键公式推导、习题解答与 Python 代码实现，依托 `statsmodels`、`arch` 等库完成从理论到实战的闭环，为后续量化分析、金融时序建模打下基础。

---

## 目录结构

```text
TS/
├── 01_TS_CHARACTERISTICS     # 第1章 时间序列的特征
├── 02_REGRESSION_EDA         # 第2章 回归与探索性数据分析
├── 03_ARIMA_MODELS           # 第3章 ARIMA模型
├── 04_SPECTRAL_ANALYSIS      # 第4章 频谱分析与滤波
├── 05_ADVANCED_TOPICS        # 第5章 其他时域主题（单位根、GARCH等）
├── 06_STATE_SPACE_MODELS     # 第6章 状态空间模型与卡尔曼滤波
├── 07_SPECTRAL_METHODS       # 第7章 频域统计方法
└── README.md                 # 本说明文件
```

---

## 章节学习目标
| 文件夹 | 核心内容 | 关联后续内容 |
| :--- | :--- | :--- |
| 01_TS_CHARACTERISTICS | 时序数据性质、平稳性、自相关/偏自相关、向量与多维时序 | 所有时序模型的基础 |
| 02_REGRESSION_EDA | 时序背景下的回归、探索性数据分析、平滑方法 | 趋势建模、数据预处理必备 |
| 03_ARIMA_MODELS | AR/MA/ARMA/ARIMA/SARIMA 模型、模型识别、估计、预测 | 经典时序预测的核心 |
| 04_SPECTRAL_ANALYSIS | 周期图、谱密度、线性滤波、傅里叶变换 | 频域分析、季节性建模 |
| 05_ADVANCED_TOPICS | 单位根检验、GARCH 模型、阈值模型、ARMAX 模型 | 金融时序、波动率建模核心 |
| 06_STATE_SPACE_MODELS | 线性高斯模型、卡尔曼滤波、极大似然估计、缺失数据处理 | 高级时序建模、状态估计 |
| 07_SPECTRAL_METHODS | 谱矩阵、回归分析、主成分分析、频域推断 | 多变量时序、降维分析 |

---

## 工具与依赖
- Python 3.x
- `numpy` / `pandas`：数据处理
- `statsmodels`：ARIMA、平稳性检验、时间序列分析
- `arch`：GARCH 等波动率模型
- `matplotlib` / `seaborn`：时序可视化
- `scipy`：频谱分析、统计计算

---

## 学习说明
1. **笔记格式**：每章文件夹下包含 `notes.md`（知识点与公式）、`exercises.md`（习题解答）、`code.ipynb`（Python 实现）。
2. **代码规范**：所有示例代码可直接运行，附详细注释，对应教材中的 R 语言案例。
3. **关联学习**：本仓库与 `PSTAT`（概率论与数理统计）仓库联动，重点内容会标注对应章节的关联知识点。

---

## 学习顺序建议
1. 优先学习 01-03 章（基础与 ARIMA 模型）
2. 再学习 05 章（单位根与 GARCH，直接关联金融量化）
3. 04、06、07 章可在基础扎实后再深入学习

---

## 参考资料
- Shumway, R. H., & Stoffer, D. S. 《时间序列分析及其应用（原书第4版）》
- `statsmodels` 官方文档
- `arch` 库官方文档
