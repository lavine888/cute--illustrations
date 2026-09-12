---
name: cute-gouache-illustrations
description: 把中文文章、观点、流程和方法论转成可爱但不幼稚的蜡笔×水粉绘本风插画。适用于公众号、小红书、博客、Notion、AI/Agent/产品/创业/学习/职场内容、正文配图、轮播、shot list、封面、系列图和改图；默认使用暖奶油纸张、粉彩青绿/蜜桃/奶黄/珊瑚橙色板、Tiny Maker 小芽创客、低科技小世界、少量手写标注和清晰物理隐喻。核心原则是“可爱让人愿意看，场景把观点讲明白”，避免 PPT 信息图、商业扁平插画、塑料 3D、动漫厚涂、儿童贴纸感，以及只卖萌不解释内容的吉祥物。
---

# Cute Gouache Illustrations

## 核心定位

把偏硬、偏抽象的内容，变成一个**温暖、可爱、正在发生事情的小世界**。

这里的“可爱”不是装饰层。角色、机器、纸箱、轨道、植物、书本、标签和工具都应该参与解释观点。

一张合格的图应该做到：

1. 第一眼亲切，愿意停留；
2. 第二眼看懂角色正在做什么；
3. 1–3 秒内理解这个动作为什么能解释观点；
4. 去掉大部分文字后，画面仍有基本因果；
5. 角色不是贴纸，而是变化的执行者。

## 先读这些参考

按任务需要读取，不要一次把全部文件塞进上下文：

- `references/style-dna.md`：纸张、材质、色板、文字、可爱程度和视觉禁忌。
- `references/tiny-maker-ip.md`：Tiny Maker / 小芽创客的外形语言、性格、动作库和禁忌。
- `references/scene-language.md`：如何把抽象观点翻译成可爱小世界与具体物理动作。
- `references/composition-patterns.md`：构图类型、镜头变化、原创隐喻和反复刻规则。
- `references/prompt-template.md`：单张、系列、轮播和编辑提示词模板。
- `references/qa-checklist.md`：生成后的 QA、失败信号和 20 分 benchmark。
- `assets/examples/`：只做低频视觉校准，不进入默认生成路径。不要把示例当构图模板。

## 工作流

### 1. 消化内容，不平均切段

读用户给的正文、链接、Markdown、截图或主题，优先找真正值得画的“认知锚点”：

- 反常识判断；
- 一个关键机制；
- 一个前后变化；
- 一个因果关系；
- 一个流程断点；
- 一个边界条件；
- 一个值得记住的行动原则。

不要为了凑数量给普通事实配图。

### 2. 先把观点写成物理关系

先回答：**这句话如果真的发生在一个小房间里，会发生什么？**

把抽象关系换成动作：

- 筛选 → 分箱 / 过滤 / 挑选；
- 放大 → 扩音 / 增压 / 培育；
- 断点 → 漏水 / 断桥 / 掉件；
- 协作 → 接力 / 交接 / 分工修理；
- 稳定 → 校准 / 固定模具 / 标准托盘；
- 反馈 → 回流 / 回信 / 循环小车；
- 优先级 → 排队 / 标签 / 不同货架。

不要一上来就画灯泡、机器人、大脑、火箭、上升箭头或标准流程图。

### 3. 选择一个小世界，不要默认“创意机器”

可选世界：

- 创意工坊；
- 小邮局 / 分拣站；
- 维修间；
- 小车站 / 接力路线；
- 温室 / 花园；
- 档案室 / 书店；
- 厨房 / 烘焙台；
- 桌面小剧场。

如果上一张已经是“输入 → 机器 → 输出”，下一张优先换世界、换镜头或换物理关系。

### 4. 选择构图

读 `references/composition-patterns.md`，优先从以下模式中选一个：

- Workflow 工坊流程；
- Central Device 中央装置；
- Repair Scene 修补现场；
- Sorting Table 分拣桌；
- Handoff Path 接力路径；
- Before / After 双世界；
- Calibration Bench 校准台；
- Growth System 培育系统。

一张图只选一个主结构。连续两张不要同构。

### 5. 让 Tiny Maker 承担核心动作

Tiny Maker 是默认弱重复原创角色，不要求每张出现。

出现时必须在做事：搬、推、接、贴、筛、修、调、浇、分拣、装配、交付等。

判断方法：

- 角色在改变什么？
- 动作能否替代一部分文字解释？
- 去掉角色后，核心机制是否完全不受影响？

如果最后一个答案是“是”，角色太装饰，重做。

### 6. 控制文字

图内文字优先：

- 0–1 个短标题；
- 0–5 个短标签；
- 每个标签尽量 2–8 个中文字；
- 少量箭头、圈线、星号或手写强调。

不要塞长段正文。如果中文准确性比视觉更重要，宁可做无字版，再后期排字。

### 7. 选择画布

用户未指定时：

- 公众号 / 博客正文图：`4:3`；
- 横版解释图：`16:9`；
- 小红书轮播：`3:4`；
- Instagram / 通用社媒：`4:5`。

同一组比例必须一致。

### 8. Shot list 模式

用户说“先规划 / 分析配图 / 不要生图”时，默认输出 4–8 张：

- 放在哪段后；
- 核心判断；
- 小世界场景；
- 核心物理动作；
- Tiny Maker 在做什么；
- 关键物件；
- 图内短标签；
- 构图类型。

文章很短时 1–3 张即可；不要把正文做成画册。

### 9. 直接生成模式

用户明确要求“生成 / 画 / 做图 / 输出图片”时，不要停在审美建议；直接调用图像生成能力，每张单独生成，不先拼九宫格。

单张提示词至少包含：

- warm cream / off-white textured paper
- cute gouache + crayon + colored-pencil illustration
- visible dry-brush, waxy grain, slightly imperfect outlines
- pastel teal, peach pink, butter yellow, coral orange, lavender accents
- rounded friendly handmade shapes
- Tiny Maker actively performing the core action when a character is needed
- cozy low-tech miniature world
- sparse handwritten labels
- one clear physical metaphor
- editorial storybook explainer feeling
- charming but not childish
- generous breathing room

同时排除：

- glossy 3D / CGI / plastic toy
- vector corporate illustration
- anime rendering
- tech dashboard / app UI
- PPT infographic
- photorealistic scene
- excessive candy colors
- dense typography
- mascot standing idle

具体模板见 `references/prompt-template.md`。

### 10. 首张先做风格锚点

系列生成建议：

1. 先做最能代表风格的一张；
2. 检查纸张、色板、笔触、角色比例、可爱程度；
3. 通过后再扩展剩余页面；
4. 每一页重新发明物理隐喻，不复制首张构图；
5. 最后统一 QA。

必要时低频查看 `assets/examples/`，只校准视觉密度和材质，不抄物件组合。

### 11. 一组图统一“世界”，不要统一“模板”

固定：

- 暖奶油纸张；
- 粉彩青绿 / 蜜桃 / 奶黄 / 珊瑚橙主色系；
- 相近蜡笔水粉颗粒；
- 相近 Tiny Maker 角色语言；
- 相近手写字气质。

变化：

- 场景类型；
- 主物件；
- 角色动作；
- 镜头远近；
- 构图方向；
- 隐喻方式。

### 12. 不要复制参考图

参考图只能提取：材质、色板、留白、角色比例、可爱程度、场景叙事和信息密度。

默认禁止照搬：

- 具体角色长相；
- “MESSY IDEAS → 青绿色机器 → 输送带”完整场景；
- 同一台机器、同一只猫、同一堆便签；
- 原文案；
- 精确物件位置和动作。

**借语法，不抄场景；借可爱，不复制角色。**

### 13. QA + benchmark

生成后跑 `references/qa-checklist.md`。

公开示例建议达到 18/20；低于 16/20 不直接交付。

优先修复顺序：

1. 塑料 3D / 错材质；
2. 主动作不清；
3. 角色只是装饰；
4. PPT / UI 感；
5. 构图拥挤；
6. 色板漂移；
7. 中文错字；
8. 最后才修小装饰。

### 14. 保存交付

在 workspace 内工作时，默认保存到：

```text
assets/<article-slug>-cute-gouache/
```

命名：

```text
01-cover.png
02-core-idea.png
03-mechanism.png
04-contrast.png
...
```

不要覆盖旧图片，除非用户明确要求。

## 输出口径

只做规划时：直接给 shot list，少讲美术理论。

直接生成后：说明生成了几张、每张解释什么、哪张最适合作首图、哪些图需要二次修字或构图，以及保存路径。让图片承担主要表达。
