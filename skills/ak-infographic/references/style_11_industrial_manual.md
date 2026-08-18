# 风格 11: 工业技术说明书 (Industrial Technical Manual)

## 1. 风格概述与特征
- **风格定义**：源自专业工程机械制造、航空航天装配与精密仪器技术白皮书的工程制图排版。
- **视觉标签**：工程手册风、编号标注、专业理性、严谨装配感。
- **色彩体系**：工程白纸底（#FFFFFF） + 机械线条墨黑/深灰（#333333） + 章节线框灰色（#E5E7EB） + 章节编号指示。
- **视觉组件**：精密零件透视线稿、气泡圈号引线（①, ②, ③...）、标准工程 BOM 物料清单表格（序号/名称/数量）、底部工作流程方框图。

---

## 2. 版式设计与布局思路 (宽屏 vs 竖屏)

### 📱 竖屏布局 (9:16 移动端优先)
- **设计思路**：**纵向工程手册单页 / 上图下表排版**。
- **视觉动线**：顶部 SECTION 3.2 规范标头 -> 上中部精密机械分解图（引出 ①~⑧ 气泡线） -> 下中部 BOM 详细参数表格 -> 底部工程框图。

### 🖥️ 宽屏布局 (16:9 桌面/PPT演示优先)
- **设计思路**：**横向工程图纸展开版式 (CAD Blueprint Layout)**。
- **视觉动线**：左侧 1/2 为大幅精密机械透视装配线稿与气泡标注；右侧 1/2 为 2 组结构化 BOM 规格表、公差参数表及底部工程时序图。

---

## 3. 适用场景与内容类型
- 硬件设备技术手册、工业级硬件架构解密、复杂机械工作原理、企业级标准操作规程（SOP）。

---

## 4. AI 绘制提示词模板 (Prompt Templates)

### 📱 9:16 竖屏提示词 (Vertical Mobile)
```text
9:16 vertical mobile-first industrial technical manual illustration, precision mechanical engineering blueprint schematic, clean white paper background, crisp black lineart assembly diagram with circular callout numbers (1 to 8), BOM components parts list table stacked below, engineering block diagram at bottom, SECTION 3.2 header, CAD schematic aesthetic
```

### 🖥️ 16:9 宽屏提示词 (Widescreen Desktop)
```text
16:9 widescreen industrial technical manual blueprint, left side displaying large precision mechanical assembly lineart with circular index callouts, right side showing structured BOM parts specifications table and engineering process flowchart, clean white grid paper background, ultra-sharp CAD lines, professional engineering documentation
```
