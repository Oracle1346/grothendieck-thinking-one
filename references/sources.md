# 思想来源与归属

本文件区分格罗滕迪克的自述、数学文本中的结构方法，以及本技能为现代使用而设计的流程。这里的摘要均为转述；没有使用格罗滕迪克口吻的原创“名言”。

## 核对过的来源

### 1. 《收获与播种》：概念工作与研究主题

Alexandre Grothendieck，*Récoltes et Semailles*。

- [Grothendieck Circle 所存原始打字稿的一部分](https://webusers.imj-prg.fr/~leila.schneps/grothendieckcircle/RS0orig.pdf)：扫描原件，适合追溯文本；该文件不是全书。
- [Mateo Carmona 整理的法文转录本](https://webusers.imj-prg.fr/~leila.schneps/grothendieckcircle/RetSbis.pdf)：编辑说明注明它是尽量忠于打字稿的暂定转录本。第三部分第 122 注 “La mer qui monte...” 讨论直觉与精确语言的相互推进，并给出浸泡坚果与海水淹没障碍这两种意象。

第 122 注及前言中“Points de vue et vision”等部分，支持本技能对“让直觉与精确语言相互修正”“逐步建设概念环境”和“重视孕育结果的主题”的理解。技能中的例子检查、收益评估和两轮停止规则，是现代工作流程设计。

### 2. 《主题纲要》：作者对自己工作的回顾

Alexandre Grothendieck，*Esquisse thématique*（1972）。本次使用 [Thematic Sketch 英译本](https://webusers.imj-prg.fr/~leila.schneps/grothendieckcircle/ThematicSketch.pdf)。该译本说明其编辑调整了部分顺序，不能把译本排版当作原稿编排。

可定位的部分：

- §3(a)：概形为代数几何与算术提供共同基础。
- §3(c)：从函子出发研究表示它的空间，以及存在性问题。
- §3(f)：把关于簇的命题改写为关于态射的相对命题。
- §7：拓扑斯与为几何需要而扩大局部性。
- §9–10：不同上同调理论的共同基础与母题愿景。

本技能据此整理相对化、函子化、扩大框架与统一主题等操作。1972 年文中的未决状态是历史信息，不应用来直接判断今天某一猜想的进展。

### 3. EGA：概形与态射的系统语言

Alexandre Grothendieck，与 Jean Dieudonné 合作，*Éléments de géométrie algébrique*。

- [EGA I：Le langage des schémas（1960）](https://www.numdam.org/articles/PMIHES_1960__4__5_0/)。
- [EGA II：Étude globale élémentaire de quelques classes de morphismes（1961）](https://archive.numdam.org/item/PMIHES_1961__8__5_0/)。

这些文本是“选择合适的对象、态射和结构语言”的基础参照。本技能并不要求每个任务都读 EGA，也没有把其中全部结果转化为通用方法。

### 4. SGA 1：覆盖、基本群与下降

*Revêtements étales et groupe fondamental (SGA 1)*，由 Grothendieck 主导的研讨班著作，有多位贡献者。

- [作者存档版本与书目信息](https://arxiv.org/abs/math/0206203)。

它提供在统一几何语言中研究覆盖和下降的数学背景。若实际使用某个下降定理，仍须核对其对象类别、覆盖条件和结论，不能用整本书名替代所需假设。

### 5. Stacks Project：核查现代数学表述

Stacks Project 是协作编写的现代参考文献，不是格罗滕迪克的自述或其独创性证据。

- [Tag 01JF：A representability criterion](https://stacks.math.columbia.edu/tag/01JF)。用于核对点函子、自然同构、可表性及表示对象的唯一性。特别注意：可表函子的定义不会自动提供表示对象的存在性。
- [Tag 023A：Descent data for quasi-coherent sheaves](https://stacks.math.columbia.edu/tag/023A)。用于核对交叠同构、余循环条件，以及“有效”意味着确实来自全局对象。该节还给出开覆盖下拟凝聚层的有效下降。

## 提炼对应表

| 技能中的操作 | 数学或思想背景 | 本技能增加的工作约束 |
| --- | --- | --- |
| A：从直觉与例子提炼定义 | 《收获与播种》的直觉、语言与概念工作 | 每次改写必须解释旧障碍或产生可验证结果 |
| B：相对化 | 《主题纲要》§3(f)，EGA 的态射语言 | 分开核查纤维性质、族性质、基变换性质 |
| C：函子化 | 点函子与 Yoneda；《主题纲要》§3(c) | 明确探针范围，禁止用有限测试冒充重构 |
| D：泛性质与存在性 | 可表函子与模问题 | 将需求、存在、唯一性分开交付 |
| E：局部到整体 | 层、粘合与下降理论 | 交叠兼容与下降有效性分开验证 |
| F：扩大框架 | 概形与拓扑斯的建设 | 交代新增信息、构造收益与返回原题的路径 |
| G：明确障碍 | 同调、上同调与障碍理论的广泛传统 | 必须指定理论和适用定理，或承认尚未形式化 |
| H：统一研究主题 | 研究主题与母题愿景 | 区分构造、猜想与类比，提出可以检验的下一步 |

## 历史归属的边界

格罗滕迪克的方法并不是一个人的全部发明。范畴论来自 Eilenberg、Mac Lane 等人的工作；Yoneda 引理有其自身来源；层与上同调有 Leray 等人的先行贡献。EGA 的建设涉及 Dieudonné，SGA 及后续发展包含众多合作者。导出范畴的系统发展不能省略 Verdier 等人的贡献；《主题纲要》也明确提及这些合作者。

本技能突出的是：围绕实际数学需要，系统选择、发展和组织语言，使许多具体问题进入同一个可操作的结构。关于“两个对象在全部自然关系下如何被识别”的数学定理，与“用更多测试了解一个软件模块”的工程类比，必须保持区别。

## 本技能中的现代设计

以下内容完全属于本技能的编排，不应归为格罗滕迪克的原话或定理：

- 默认只选一至两项结构操作。
- 用最小例、典型例和退化例锚定问题。
- 用信息保留、障碍消除、具体推导衡量抽象收益。
- 连续两轮无收益时回到具体工具。
- 输出“结论—结构改写—实质工作—适用边界”。
- 软件与系统问题中的所有迁移示例。

数学示例为教学构造，不声称出自格罗滕迪克本人。需要更精细的数学史归属时，应查相应原始论文与专业数学史研究，而非从本技能名称反推发明权。
