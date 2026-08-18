# 风格 08: 玻璃拟态 / 透明科技 (Glassmorphism)

## 1. 风格概述与特征
- **风格定义**：采用半透明毛玻璃质感（Backdrop Blur）、柔和环境光影与多层微光浮动卡片，极具现代 SaaS 产品的精致高级感。
- **视觉标签**：半透明卡片、科技感、适合 SaaS、层级通透。
- **色彩体系**：深邃蓝紫微光渐变底（#1E293B -> #0F172A） + 半透明磨砂玻璃卡片（`rgba(255,255,255,0.08)`） + 1px 亮白微光边框 + 亮蓝科技高光。
- **视觉组件**：半透明毛玻璃工作台、发光晶体图标、进度概览条（78%）、平滑性能走势波形图。

---

## 2. 版式设计与布局思路 (宽屏 vs 竖屏)

### 📱 竖屏布局 (9:16 移动端优先)
- **设计思路**：**移动端工作台浮层 / 纵向层叠毛玻璃流**。
- **视觉动线**：顶部半透明标题与状态栏 -> 中部 4 组垂直层叠毛玻璃卡片（数据流转节点） -> 底部进度概览与平滑波形图。

### 🖥️ 宽屏布局 (16:9 桌面/PPT演示优先)
- **设计思路**：**现代 SaaS Web 控制台全景工作台**。
- **视觉动线**：左侧 1/4 导航与系统状态树；中间 2/4 核心工作流毛玻璃卡片矩阵；右侧 1/4 实时性能监控、动态图表与进度环。

---

## 3. 适用场景与内容类型
- 现代 SaaS 平台功能架构、云计算控制台产品解说、AI Agent 工作台展示、高端数字化方案。

---

## 4. AI 绘制提示词模板 (Prompt Templates)

### 📱 9:16 竖屏提示词 (Vertical Mobile)
```text
9:16 vertical mobile-first modern glassmorphism tech UI infographic, deep slate blue gradient backdrop, frosted translucent glass cards stacked vertically with subtle blur and 1px luminous edge borders, glowing minimal vector icons, progress metrics bar (78%), smooth performance trend line graph, refined Apple SaaS software design aesthetic, high information density
```

### 🖥️ 16:9 宽屏提示词 (Widescreen Desktop)
```text
16:9 widescreen modern glassmorphism tech dashboard infographic, deep slate blue background with vibrant gradient underglow, multi-panel layout with frosted glass containers, left navigation sidebar, central workflow cards, right analytics dashboard with smooth charts and metric rings, 1px bright glass rim lights, ultra-clean SaaS UI aesthetic
```
