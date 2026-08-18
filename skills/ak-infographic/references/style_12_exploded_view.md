# 风格 12: 爆炸拆解图 (Exploded View)

## 1. 风格概述与特征
- **风格定义**：将一个复杂的整体设备或软件计算模块沿法线方向**分层拉开、悬浮拆解**，展示内部所有核心层级与微观元件。
- **视觉标签**：分层拆解、模块悬浮、结构表达强、纵深剖析。
- **色彩体系**：浅蓝灰或深空灰科技底 + 真实芯片/PCB/散热鳍片材质质感（金属灰、铜绿、哑光黑、硅晶片反光）。
- **视觉组件**：垂直/斜向悬浮的各层组件（顶盖 -> 冷却风扇 -> 散热片 -> 主板 -> 内存模块 -> 处理器 -> 电源模块 -> 底壳） + 对应序号引线。

---

## 2. 版式设计与布局思路 (宽屏 vs 竖屏)

### 📱 竖屏布局 (9:16 移动端优先)
- **设计思路**：**垂直天梯式爆炸拆解**。
- **视觉动线**：从上至下垂直悬浮的 8 层精密组件贯穿画面中心，左侧整齐排列 ①~⑧ 标签与虚线引线，天然完美契合手机竖屏纵向阅读。

### 🖥️ 宽屏布局 (16:9 桌面/PPT演示优先)
- **设计思路**：**45度斜向等轴测爆炸拆解 + 左右参数展开**。
- **视觉动线**：中央为 45 度斜向悬浮展开的立体爆炸模型；左侧为模块层级概览与架构树；右侧为各层硬件规格、散热功率与制造工艺详细参数卡。

---

## 3. 适用场景与内容类型
- 算力芯片/AI 服务器硬件拆解、软硬件一体机内部解构、系统软件栈层级（OS/驱动/运行时/框架/应用）纵深剖析。

---

## 4. AI 绘制提示词模板 (Prompt Templates)

### 📱 9:16 竖屏提示词 (Vertical Mobile)
```text
9:16 vertical mobile-first 3D exploded view schematic of AI computing module, layered floating components vertically disassembled from top to bottom: top cover, cooling fan, heat sink fins, mainboard PCB, memory chips, CPU processor, power module, and bottom case. Numeric callouts 1 to 8 on the left, high precision industrial product rendering, studio clean lighting
```

### 🖥️ 16:9 宽屏提示词 (Widescreen Desktop)
```text
16:9 widescreen 3D exploded view diagram of advanced AI server hardware, components hovering diagonally in isometric perspective (top chassis, heatsinks, PCB, accelerator modules, bottom tray), left-side architectural taxonomy breakdown, right-side detailed hardware technical specifications table, studio lighting, hyper-detailed product rendering
```
