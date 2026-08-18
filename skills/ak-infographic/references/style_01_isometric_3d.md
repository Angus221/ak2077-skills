# 风格 01: 2.5D 等距立体 (Isometric 3D)

## 1. 风格定位与特征
- **风格定义**：采用 30 度等轴测投影（Isometric Projection），构建具备空间纵深、微缩沙盘感与立体层级的现代化场景。
- **视觉标签**：倾角透视、微缩模型、科技商业感强、立体分层。
- **色彩体系**：现代科技蓝、青绿、柔和立体受光/背光面（Light/Shadow 面高低明度）、中性浅灰底或柔和蓝灰底。
- **视觉组件**：立体工作台、微缩机房/服务器节点、立体车辆/物流网络、悬浮 3D 指示牌、空间立体连线。

---

## 2. 版式设计与布局思路 (宽屏 vs 竖屏)

### 📱 竖屏布局 (9:16 移动端优先)
- **设计思路**：**垂直分层微缩塔 / 自上而下流转沙盘**。
- **视觉动线**：
  - **顶部（Header）**：大字号主题标题 + 核心全局概览。
  - **中部主干（Vertical Stream）**：自上而下纵向级联的立体管道与多层浮空岛屿（上游数据源 -> 中游计算中枢 -> 下游应用端）。
  - **两侧/下方**：悬浮的 2D 半透明卡片，用于承载高密度技术参数与步骤说明。
  - **底部（Footer）**：立体指标圆盘与系统运行状态汇总。

### 🖥️ 宽屏布局 (16:9 桌面/PPT演示优先)
- **设计思路**：**横向全景微缩园区 / 左右端到端协同沙盘**。
- **视觉动线**：
  - **中央主干（Central Hub）**：大幅 3D 等轴测核心系统沙盘（如立体机房、微服务中台大厦）。
  - **左侧输入区**：外部客户端、物联网设备与接入网关微缩节点。
  - **右侧输出区**：商业交付终端、分析大屏与用户端成果展示。
  - **四周环绕**：网格化 2D 数据看板与性能指标卡，形成全景式视觉冲击。

---

## 3. 适用场景与内容类型
- 复杂业务生态全景、智慧城市、云原生数据流、智能硬件与 IoT 协同、端到端商业交付沙盘。

---

## 4. AI 绘制提示词模板 (Prompt Templates)

### 📱 9:16 竖屏提示词 (Vertical Mobile)
```text
9:16 vertical mobile-first 2.5D isometric 3D infographic illustration, miniature tech commercial ecosystem, 30-degree isometric projection angle, multi-tier vertical data flow pipelines connecting floating tech platforms from top to bottom, miniature server racks, floating digital HUD screens, clean studio lighting, soft shadows, vibrant tech blue and emerald palette on clean light grey background, high information density, crisp details, vector-like 3D render, octane render style
```

### 🖥️ 16:9 宽屏提示词 (Widescreen Desktop)
```text
16:9 widescreen 2.5D isometric 3D infographic illustration, expansive panoramic digital ecosystem sandbox, 30-degree isometric projection angle, central grand tech tower surrounded by horizontal automated pipelines, left-to-right data flow from IoT nodes to analytics control centers, floating HUD metric widgets on perimeter, sleek studio lighting, crisp shadows, high information density, blueprint vector render
```
