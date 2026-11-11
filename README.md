# 化学结构与分子可视化工具指南

文档导航：

- [化学结构与分子可视化工具指南](README.md)
- [生物分类与生命之树工具指南](docs/tree-of-life.md)
- [地球现象与地理可视化工具指南](docs/earth-geography.md)
- [氨基酸基础知识与速查](docs/amino-acids.md)
- [维生素基础知识与速查](docs/vitamins.md)

这份指南整理了 9 个用于化合物检索、分子结构查看、反应动画学习及元素性质查询的网站，适合日常探索、课堂教学和结构研究入门。

## 快速选择

| 需求 | 建议优先使用 | 选择理由 |
| --- | --- | --- |
| 搜索小分子，旋转、缩放并观察原子和化学键 | MolView | 将结构绘制、检索和 3D 查看集中在一个界面 |
| 自行绘制、编辑分子结构 | MolView | 可将 2D 结构转换为 3D 模型，新版支持实时同步 |
| 查询化合物详细信息 | PubChem / ChemSpider | 以化合物数据检索为主，可进一步查看结构及关联资料 |
| 比较小分子的 3D 构象 | PubChem 3D Viewer | 支持多结构显示及构象叠合 |
| 学习反应机理和立体化学 | ChemTube3D | 提供交互式结构及反应动画 |
| 查找蛋白质、DNA、RNA 结构 | RCSB PDB | 提供生物大分子结构检索和交互式查看 |
| 展示大型生物分子、分子表面及相关结构数据 | Mol* | 面向大型生物分子的可视化与分析工具 |
| 联动查看序列、结构及相互作用 | iCn3D | 将 3D 结构、2D 相互作用和序列注释结合起来 |
| 查看元素周期表、电子排布和元素性质 | Ptable / WebElements | 分别侧重交互探索与元素资料查询 |

## 一、分子结构与化合物检索

### 1. MolView

**适合：** 小分子结构探索、结构绘制和教学演示。

- 支持按化学名称、分子式及化学标识符检索。
- 提供 2D 结构编辑与 3D 模型查看，可观察原子连接和空间构型。
- 新版支持绘图时实时同步 3D 模型，并可并排展示多个分子。
- 提供图片导出；具体格式和功能范围以所用版本为准。

入口：[官网](https://molview.com/) · [新版应用](https://app.molview.com/) · [旧版应用与帮助](https://molview.org/)

**版本说明：** 新旧版功能不同。旧版保留 Jmol 集成及光谱查看入口；光谱是否可用取决于数据来源。新版部分功能采用订阅方案，不宜将两个版本的功能与免费范围混为一谈。

### 2. PubChem / PubChem 3D Viewer

**适合：** 查询化合物资料，查看和比较可用的 3D 构象。

- PubChem 提供化合物记录及相关性质、标识符和来源信息。
- 3D Viewer 支持交互式模型查看、多结构展示及构象叠合。
- 可结合化合物记录获取可用的结构数据。

入口：[PubChem](https://pubchem.ncbi.nlm.nih.gov/) · [3D Viewer](https://pubchem.ncbi.nlm.nih.gov/pc3d/)

使用提示：并非每条化合物记录都有可用的 3D 构象；查看时应区分计算构象和实验结构。功能参考：[官方 3D 查看说明](https://pubchem.ncbi.nlm.nih.gov/pcfe/docs/markdown/3d-structure-viewer.md)。

### 3. ChemSpider

**适合：** 检索化合物结构、性质、标识符及关联数据源。

- 由英国皇家化学会（Royal Society of Chemistry，RSC）提供。
- 汇集多个来源的化学结构及相关资料，可用于交叉查询。
- 更适合作为化合物信息检索入口；如主要目标是绘图和旋转 3D 模型，可优先使用 MolView。

入口：[ChemSpider](https://www.chemspider.com/) · [RSC 数据库介绍](https://www.rsc.org/publishing/databases)

## 二、化学反应与立体化学教学

### 4. ChemTube3D

**适合：** 通过交互动画理解化学反应、分子几何和立体化学。

- 提供交互式 3D 分子结构及反应动画。
- 可用于学习有机反应机理、轨道及立体化学等主题。
- 适合围绕课程主题浏览，动画内容以网站已收录的教学资源为准。

入口：[ChemTube3D](https://www.chemtube3d.com/) · [利物浦大学项目介绍](https://www.liverpool.ac.uk/chemistry/research/research-impact/enhancing-chemistry-education/)

## 三、生物大分子结构

### 5. RCSB Protein Data Bank（RCSB PDB）

**适合：** 查找并查看蛋白质、DNA、RNA 及其复合物结构。

- 提供 PDB 结构数据检索，并集成交互式 3D 查看工具。
- 可结合序列、结构及注释信息探索生物大分子。
- 网站既提供实验结构，也提供计算结构模型入口；使用时应查看记录的数据来源和测定或建模方法。

入口：[RCSB PDB](https://www.rcsb.org/)

### 6. Mol*（Molstar）

**适合：** 大型生物分子的展示、结构分析和可视化集成。

- 提供基于 WebGL 的分子可视化工具。
- 支持大型生物分子、不同渲染样式及相关实验数据的展示。
- RCSB PDB 集成了 Mol*，可先在数据库中找到结构，再进入查看器探索。

入口：[Mol* 官网与示例](https://molstar.org/)

### 7. iCn3D

**适合：** 将生物分子的三维结构、序列注释及相互作用结合分析。

- NCBI 提供的网页结构查看与分析工具。
- 支持旋转、缩放、平移，以及结构、序列和相互作用视图联动。
- 支持结构比对、相互作用分析，并可将自定义视图保存为链接或图片。

入口：[iCn3D](https://www.ncbi.nlm.nih.gov/Structure/icn3d/) · [官方功能说明](https://www.ncbi.nlm.nih.gov/Structure/icn3d/icn3d.html)

## 四、元素与周期表

### 8. Ptable

**适合：** 交互式探索元素周期表、电子排布、同位素和元素性质。

入口：[Ptable](https://ptable.com/)

### 9. WebElements

**适合：** 按元素查询物理化学性质及相关资料。

入口：[WebElements](https://www.webelements.com/)

## 五、建议使用路径

1. **初次观察小分子：** 从 MolView 开始，检索目标物质，查看 2D 结构，再旋转和缩放 3D 模型。
2. **需要详细资料：** 在 PubChem 或 ChemSpider 中确认化合物身份，并查看性质和数据来源。
3. **学习反应过程：** 在 ChemTube3D 中查找对应的反应或教学主题。
4. **研究生物大分子：** 从 RCSB PDB 检索结构，用 Mol* 查看整体，用 iCn3D 结合序列和相互作用分析。
5. **查询元素信息：** 用 Ptable 交互探索，用 WebElements 查阅元素资料。

以上工具覆盖不同对象和用途，没有单一网站能够完整收录并可视化所有化学物质。若目标是日常搜索、绘制和查看小分子，本指南建议优先从 MolView 入手。

## 资料整理说明

- 整理日期：2026-11-11。
- 已清理原文的临时图片链接、重复站点图标、引用残留、追踪参数及未作答的选项。
- 功能描述依据上述官网及官方说明整理；ChemSpider、ChemTube3D 首页本次抓取受限，分别参考 RSC 和利物浦大学的项目介绍。
- 本次核对范围为公开页面与功能说明，未逐项实测交互功能和导出效果。
