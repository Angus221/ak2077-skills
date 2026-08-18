# 风格 14: 论文 / 科研图表风 (Scientific Paper Style)

## 1. 风格概述与特征
- **风格定义**：遵循顶级学术顶会（NeurIPS, ICML, CVPR, Nature）论文插图规范，具备极度严谨的白底方框流程图、损失函数收敛曲线与学术图例。
- **视觉标签**：白底结构图、克制、学术展示感、严密逻辑。
- **色彩体系**：纯白底（#FFFFFF） + 论文标准细灰黑框线 + 经典学术配图蓝（#1F77B4 / 准确率曲线）与深蓝（#0F4C81 / 损失曲线）。
- **视觉组件**：Figure 2. Overview of the Pipeline 标准学术题头、方块流程模块（Input Data -> Preprocessing -> Feature Extraction -> Training -> Evaluation）、收敛折线图（Accuracy vs Epoch, Loss vs Epoch）、标注文字（注：实验在 5 个公开数据集上进行...）。

---

## 2. 版式设计与布局思路 (宽屏 vs 竖屏)

### 📱 竖屏布局 (9:16 移动端优先)
- **设计思路**：**单栏学术短文配图 / 上下双区结构**。
- **视觉动线**：顶部 Figure 题头 -> 上半部纵向流水线框图（带 Optimization 反馈） -> 下半部上下堆叠的双学术折线图（准确率曲线与 Loss 曲线） -> 底部数据集与超参数脚注。

### 🖥️ 宽屏布局 (16:9 桌面/PPT演示优先)
- **设计思路**：**双栏学术顶会论文海报 (Conference Poster Layout)**。
- **视觉动线**：左侧 1/2 为水平 Pipeline 架构框图与数据流转换图；右侧 1/2 为 2×2 并列学术收敛图、消融实验（Ablation Study）对比柱状图与基准指标表格。

---

## 3. 适用场景与内容类型
- 前沿 AI 算法模型机制解析、学术实验复现报告、技术评测基准（Benchmark）深度对比。

---

## 4. AI 绘制提示词模板 (Prompt Templates)

### 📱 9:16 竖屏提示词 (Vertical Mobile)
```text
9:16 vertical mobile-first academic research scientific paper style figure, NeurIPS conference illustration aesthetic, pure white background, top section showing vertical pipeline block diagram (Input -> Preprocessing -> Feature Extraction -> Model Training -> Evaluation), bottom section featuring dual scientific line plots for accuracy and logarithmic loss curves, LaTeX style typography, Figure 2 caption
```

### 🖥️ 16:9 宽屏提示词 (Widescreen Desktop)
```text
16:9 widescreen academic research scientific paper style figure, NeurIPS conference poster aesthetic, pure white background, left half showing horizontal AI model architecture pipeline diagram, right half displaying 4-grid scientific benchmark plots (accuracy curves, loss curves, ablation study bar chart), LaTeX vector typography, crisp black lines, clean academic diagram
```
