# 🌐 GitHub Pages: <https://wadesha.github.io/toymodel-poi/>

# ToyModel · 全国模拟 POI 可视化

基于 **2013-2023 全国 POI 数据湖真实分布**（省规模占比 + 17 标准分类占比）生成的轻量模拟数据，并做成交互式全国地图展示。

## 页面

- **[index.html](index.html)** — 交互式全国模拟 POI 地图（分类/省份/密度可筛选）
- **[tutorial.html](tutorial.html)** — 零基础入门教程：分析结果解读（含可交互地图展示）+ 地图三步实现拆解 + 从零复刻与 GitHub Pages 部署跟做指南

## 数据

- **poi_sim.json** — 22,001 条模拟 POI（<1MB）。字段：`[省份索引, 名称, 分类索引, 经度, 纬度]`，省/分类名在 meta 中。
- **china_mainland.json** — 全国省级边界（ECharts geo）。

## 说明

- 数据为**模拟演示**，坐标与名称为合成，用于可视化原型验证，非真实 POI。
- 生成基于数据湖实测分布，供后续真实数据接管道直接替换。