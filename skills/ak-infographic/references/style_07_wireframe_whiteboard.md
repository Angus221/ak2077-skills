# 风格 07: 黑白线框 / 白板示意 (Wireframe / Whiteboard)

## 1. 风格概述与特征
- **风格定义**：极致纯粹的黑白单色线框风格，完全去除色彩干扰，专注展现纯粹的**逻辑拓扑、信息流转与因果分支**。
- **视觉标签**：黑白线简、箭头关系、结构清楚、无多余修饰。
- **色彩体系**：纯白底（#FFFFFF） + 纯黑细边框与线条（#111111） + 极少量的浅灰填充（#F3F4F6）。
- **视觉组件**：单线方框容器、单双向指示箭头、虚线反馈循环（如“持续优化/迭代改进”）、结构化列表打点。

---

## 2. 版式设计与布局思路 (宽屏 vs 竖屏)

### 📱 竖屏布局 (9:16 移动端优先)
- **设计思路**：**纵向闭环流程图 / 级联线框卡片**。
- **视觉动线**：顶部线框标题 -> 中部 4 组垂直级联方框（1 收集 -> 2 分析 -> 3 决策 -> 4 输出），每框内嵌列表要点 -> 右侧虚线箭头回流至顶部闭环。

### 🖥️ 宽屏布局 (16:9 桌面/PPT演示优先)
- **设计思路**：**横向端到端全景架构流 / 多层泳道图 (Swimlane)**。
- **视觉动线**：自左向右横向 4 大阶段方框推进，纵向划分 3 条清晰泳道（业务层 / 逻辑层 / 数据层），底部带有大跨度虚线反馈回路。

---

## 3. 适用场景与内容类型
- 软件工程原型设计、系统逻辑流转推演、学术研讨白板草图、业务闭环梳理。

---

## 4. AI 绘制提示词模板 (Prompt Templates)

### 📱 9:16 竖屏提示词 (Vertical Mobile)
```text
9:16 vertical mobile-first clean black and white wireframe flowchart infographic, crisp whiteboard diagram style, vertical layout, pure white background, sharp black thin vector outlines, clean rounded rectangles, clear vertical directional arrow flows with feedback loop, structured text bullet points, minimalist monochrome system architecture, ultra-legible
```

### 🖥️ 16:9 宽屏提示词 (Widescreen Desktop)
```text
16:9 widescreen clean black and white wireframe architecture diagram, crisp whiteboard blueprint style, horizontal swimlane layout across 3 vertical tiers, sharp thin black vector outlines on pure white background, structured boxes with clear directional arrows, feedback loops, minimalist monochrome data flow, ultra-high legibility
```
