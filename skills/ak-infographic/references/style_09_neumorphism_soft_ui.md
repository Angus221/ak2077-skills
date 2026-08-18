# 风格 09: 新拟态 / 软 UI (Neumorphism)

## 1. 风格概述与特征
- **风格定义**：通过同色系背景下的**双向柔和投影（一侧亮光白影、一侧暗色阴影）**，塑造出仿佛从物理表面挤压凸起或凹陷的“软雕塑”界面。
- **视觉标签**：柔和浮雕、简洁克制、软界面、极简触感。
- **色彩体系**：浅灰白同色系（#E2E8F0 / #EDF2F7） + 凹凸阴影光效 + 极少量状态强调色（如运行正常绿 #22C55E）。
- **视觉组件**：凸起圆角软卡片、凹陷输入槽、浮雕开关按键、柔和状态指示灯（运行正常）。

---

## 2. 版式设计与布局思路 (宽屏 vs 竖屏)

### 📱 竖屏布局 (9:16 移动端优先)
- **设计思路**：**单列软浮雕控制面板**。
- **视觉动线**：顶部极简软雕塑标题 -> 中部 4 组自上而下凸起卡片（凹陷箭头连接） -> 底部任务进度软槽与运行状态指示牌。

### 🖥️ 宽屏布局 (16:9 桌面/PPT演示优先)
- **设计思路**：**硬件中控台面板 / 多区域软浮雕矩阵**。
- **视觉动线**：横向铺开的 4 栏软质卡片，中间嵌入凹陷的曲线图表槽与立体浮雕旋钮，极具极简北欧工业触感。

---

## 3. 适用场景与内容类型
- 智能家居控制逻辑、极简硬件操作系统、医疗健康设备操作流、注重极简触感的产品设计。

---

## 4. AI 绘制提示词模板 (Prompt Templates)

### 📱 9:16 竖屏提示词 (Vertical Mobile)
```text
9:16 vertical mobile-first sleek neumorphism soft UI infographic, uniform light grey-white surface (#E6ECF5), extruded soft embossed cards and debossed input containers stacked vertically, realistic double soft shadow highlights, minimal vector icons, progress track bar (75%), green status indicator dot, ultra-clean aesthetic, high readability
```

### 🖥️ 16:9 宽屏提示词 (Widescreen Desktop)
```text
16:9 widescreen sleek neumorphism soft UI hardware console infographic, uniform soft grey surface, extruded embossed panel layout from left to right, debossed waveform chart slots, physical tactile feel with dual directional soft drop shadows, minimal status indicators, pristine modern industrial design, high information density
```
