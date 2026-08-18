# 风格 05: 科技蓝图 / HUD 界面 (Tech HUD / Blueprint)

## 1. 风格概述与特征
- **风格定义**：借鉴科幻人机交互界面（FUI/HUD）与现代工程蓝图（Blueprint），具备深邃暗黑背景与发光线框。
- **视觉标签**：深色发光、技术线框、未来感、精密控制台。
- **色彩体系**：深蓝黑底（#050B14） + 科技电光青蓝发光色（#00E5FF / #0088FF） + 纯白高亮文字。
- **视觉组件**：圆形雷达仪表、发光网络拓扑节点、实时波形折线（Data Stream）、网格十字准星刻度、百分比状态进度环。

---

## 2. 版式设计与布局思路 (宽屏 vs 竖屏)

### 📱 竖屏布局 (9:16 移动端优先)
- **设计思路**：**单兵手持终端 / 纵向级联控制台**。
- **视觉动线**：
  - **顶部**：AI WORKFLOW SYSTEM 霓虹发光标题 + 核心指标概览。
  - **中部**：垂直级联的 4~8 组发光节点与卡片（数据输入 -> 协议路由 -> 决策处理 -> 结果输出），节点间带流动光束脉冲。
  - **下部**：双折线波形图谱与系统指标（CPU/MEM/QPS、SLA 99.95%）。

### 🖥️ 宽屏布局 (16:9 桌面/PPT演示优先)
- **设计思路**：**指挥中心全局监控大屏 / 横向三段式数据拓扑控制台**。
- **视觉动线**：
  - **左侧控制区**：客户端接入拓扑、身份鉴权状态与实时请求流量计。
  - **中间主控区**：核心系统架构与服务网格拓扑，带多维发光数据流分支。
  - **右侧遥测区**：全链路延迟分布柱状图、健康度雷达与告警仪表盘。
  - **底部状态横栏**：全局运行状态、SLA 达成率与安全防御日志流。

---

## 3. 适用场景与内容类型
- AI 算法模型运行链路、微服务集群治理、网络安全态势感知、DevOps 流水线监控。

---

## 4. AI 绘制提示词模板 (Prompt Templates)

### 📱 9:16 竖屏提示词 (Vertical Mobile)
```text
9:16 vertical mobile-first sci-fi futuristic tech HUD blueprint infographic, deep navy dark background (#050B14), glowing electric cyan (#00E5FF) and neon blue wireframe vector graphics, vertical cascading system nodes with glowing connecting paths, circular radar gauges, real-time data stream waveform charts, precise grid overlays, futuristic console UI, high information density
```

### 🖥️ 16:9 宽屏提示词 (Widescreen Desktop)
```text
16:9 widescreen futuristic tech HUD blueprint infographic, command center monitoring console aesthetic, deep navy background, luminous cyan and blue circuit wireframes, horizontal 3-section layout (input telemetry on left, central system architecture topology in middle, real-time analytics gauges on right), glowing data stream waves, high information density, sharp vector graphics
```
