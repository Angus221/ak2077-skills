# 风格 15: 数据新闻 / Bloomberg 风 (Data Editorial)

## 1. 风格概述与特征
- **风格定义**：源自彭博社（Bloomberg）、华尔街日报（WSJ）等顶级数据新闻媒体的图表语言，以**醒目的关键统计指标、折线趋势图与多维度对比表格**为核心。
- **视觉标签**：数据驱动、图表突出、分析感强、商业说服力极高。
- **色彩体系**：清爽亮白底（#FFFFFF） + 彭博蓝（#0052FF） + 警示深红 + 墨黑文字与极简辅助浅灰网格。
- **视觉组件**：超大字号百分比与核心洞察（如 -92% 巨大数字）、价格/成本下行折线走势图、横向数据矩阵、官方数据来源脚注。

---

## 2. 版式设计与布局思路 (宽屏 vs 竖屏)

### 📱 竖屏布局 (9:16 移动端优先)
- **设计思路**：**移动端金融早报信息卡 / 单列数据流**。
- **视觉动线**：顶部大标题 -> 上中部醒目的巨大核心降幅数值（-92%）及要点解读 -> 中部单列价格下行折线图 -> 下部 4 联关键指标矩阵（覆盖模型、供应商、平均降幅等） -> 底部数据源。

### 🖥️ 宽屏布局 (16:9 桌面/PPT演示优先)
- **设计思路**：**彭博终端研报全景看板 / 多维财经图表矩阵**。
- **视觉动线**：顶部通栏大标题与宏观结论；左侧 1/3 巨大核心数值卡与市场走势要点；中间 1/3 多年份复合折线走势图；右侧 1/3 头部供应商横向对比柱状图与多维评分矩阵；底部为完整数据源与更新时戳。

---

## 3. 适用场景与内容类型
- 商业成本/营收趋势分析、市场占有率演变、AI 算力成本下行研报、投融资与市场动态盘点。

---

## 4. AI 绘制提示词模板 (Prompt Templates)

### 📱 9:16 竖屏提示词 (Vertical Mobile)
```text
9:16 vertical mobile-first Bloomberg data journalism editorial infographic, clean white background with crisp typography, prominent huge bold metric number (-92%) at top, clear cost-reduction downward line chart in the middle, structured 4-column metric summary table below (Models 12, Providers 7, Avg Drop 92%, Max Drop 97%), professional financial media chart style, high information density
```

### 🖥️ 16:9 宽屏提示词 (Widescreen Desktop)
```text
16:9 widescreen Bloomberg data journalism financial infographic, multi-panel analytics layout, clean white background with sharp grid, left panel showing huge bold metric (-92%) and key market takeaways, central panel featuring multi-year price decline curve, right panel displaying competitor market share bar charts and KPI metrics table, authoritative financial media design, high information density
```
