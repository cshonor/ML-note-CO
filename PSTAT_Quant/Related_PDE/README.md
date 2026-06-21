# Related_PDE — 随机金融中的偏微分方程（关联模块）

**定位**：不是系统学 PDE 课，而是**随机过程 / 随机金融里出现什么 PDE，就补什么推导与应用**。

**挂靠关系**：本模块从属于 [`Shiryaev_Random_Finance`](../Shiryaev_Random_Finance/README.md) 下的随机分析主线；需要全课程 PDE 时再另开独立轨道。

---

## 收录范围（按需扩展）

| 主题 | 典型用途 | 前置 |
| :--- | :--- | :--- |
| 热方程与布朗运动 | 转移密度、扩散过程 | 布朗运动、Itô 公式 |
| Black–Scholes PDE 推导 | 欧式期权定价 PDE 形式 | 风险中性测度、Itô |
| Feynman–Kac 公式 | PDE ⟺ 期望表示（定价桥梁） | 随机积分、鞅 |
| 边界/终值条件 | 期权类型、障碍期权直觉 | BS 框架 |
| 数值要点（有限差分等） | 与 `ODE`/数值方法衔接 | 离散化直觉即可 |

**暂不收录**：广义函数论、完整 Sobolev 空间、椭圆/双曲 PDE 系统课内容。

---

## 笔记目录（待建）

```text
Related_PDE/
├── 01_Heat_Equation_and_Brownian/     # 热方程 ↔ 布朗转移密度
├── 02_Black_Scholes_Derivation/         # BS PDE 从复制组合或风险中性推出
├── 03_Feynman_Kac/                      # 概率表示与 PDE 解
└── 04_Boundary_Conditions_Options/      # 边界/终值与期权类型
```

---

## 学习策略

1. **先概率后 PDE**：鞅与 Itô 公式搞清，再读 BS 推导。  
2. **推导 + 场景**：每个文件至少包含「从随机过程到 PDE」的一条完整链路。  
3. **不阻塞主线**：某一节缺 PDE 细节时，先记结论与用法，回头再补证明。
