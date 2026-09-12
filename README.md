<div align="center">

# Cute Gouache Illustrations

**把抽象观点，画成一座可爱、温暖、会运转的小小创意世界。**

中文内容 → 认知锚点 → 物理动作 → 小世界叙事 → 蜡笔 × 水粉插画

![Codex Skill](https://img.shields.io/badge/Codex-Skill-111111?style=flat-square)
![Chinese First](https://img.shields.io/badge/Chinese-First-EA7F73?style=flat-square)
![Cute Gouache](https://img.shields.io/badge/Style-Cute%20Gouache-79AFA5?style=flat-square)
![MIT License](https://img.shields.io/badge/License-MIT-6E63A8?style=flat-square)

</div>

---

## 先看效果

<p align="center">
  <img src="examples/images/01-creative-workflow-reference.jpg" width="88%" alt="Cute Gouache visual reference">
</p>

这张图只作为**视觉校准基准**：奶油纸、水粉蜡笔颗粒、粉彩色板、圆润角色、小世界叙事、少量手写批注。

真正使用 Skill 时，不应该一直复刻“左边乱想法 → 中间机器 → 右边输出”的同一构图。每个新主题都要重新发明场景和物理隐喻。

> **统一的是视觉语言，不是模板。**

---

## 这个 Skill 到底做什么？

**Cute Gouache Illustrations** 是一个面向中文内容创作的 Codex Skill。

它不会直接把一段文章“配一张可爱图”。它会先判断文章里什么最值得画，再把抽象关系变成一个真实物理动作，最后把这个动作放进一个温暖、可爱、会运转的小世界。

```text
原始文章 / 观点
      ↓
找真正值得画的认知锚点
      ↓
把抽象关系换成物理动作
      ↓
选择工坊 / 邮局 / 维修间 / 车站 / 温室等小世界
      ↓
安排 Tiny Maker 承担核心动作
      ↓
生成蜡笔 × 水粉解释图
      ↓
QA：材质 / 隐喻 / 角色 / 构图 / 中文 / 系列一致性
```

所以它更像一个**视觉解释 Agent 的工作方法**，而不是一句 `cute gouache style` prompt。

核心原则只有一句：

> **可爱负责让人愿意看，场景负责把观点讲明白。**

---

## 和另外两个 Skill 的区别

| Skill | 核心视觉语言 | 最擅长 |
|---|---|---|
| `crayon-doodle-illustrations` | 彩铅讲义 / 知识卡 | 判断、概念拆解、轮播 |
| `ian-xiaohei-illustrations` | 白底黑线 / 怪诞小黑 | 正文解释图、流程和隐喻 |
| **`cute-gouache-illustrations`** | **可爱水粉绘本 / 小世界叙事** | **让偏硬内容变得亲切、温暖、好传播** |

它不是“更萌的知识卡”，而是把观点变成一个**正在发生事情的小世界**。

---

## 视觉 DNA

| 维度 | 默认规则 |
|---|---|
| **Background** | 暖白 / 奶油色纸张，有轻微纸纤维纹理 |
| **Material** | 水粉 + 蜡笔 + 彩铅，干刷、颗粒、露纸、轻微不均匀 |
| **Palette** | 青绿色、蜜桃粉、奶油黄、珊瑚橙、薰衣草紫 |
| **Character** | Tiny Maker / 小芽创客；圆润但不幼儿化，必须参与核心动作 |
| **World** | 工坊、邮局、维修间、车站、温室、档案室、厨房、桌面小剧场 |
| **Typography** | 少量手写字，像马克笔 / 蜡笔；短词优先 |
| **Composition** | 一张图一个动作或机制，完整但不拥挤 |
| **Mood** | 温暖、聪明、俏皮，有一点尺度反差和冷幽默 |

### 明确不要

`商业扁平插画` · `PPT 信息图` · `塑料 3D / CGI` · `动漫厚涂` · `幼儿园贴纸` · `复杂 UI` · `霓虹科技感` · `满屏文字` · `只站着卖萌的吉祥物`

---

## Tiny Maker：不是吉祥物，是执行者

默认弱重复角色叫 **Tiny Maker / 小芽创客**。

它可以有小叶芽、围裙、工具袋或帽子，但不锁死为某种动物，也不要求每张出现。

出现时必须真的在做事：

- 堵住漏信息的水管；
- 给混乱输入贴标签；
- 把任务递给下一站；
- 调校一个判断旋钮；
- 修补断掉的桥；
- 把反馈送回起点。

如果把角色删掉以后，画面逻辑完全没变化，那它只是装饰。

详细规则见 [`tiny-maker-ip.md`](cute-gouache-illustrations/references/tiny-maker-ip.md)。

---

## 8 种常用构图，不再每张都画“创意机器”

Skill 内置了几类高复用结构：

- Workflow 工坊流程
- Central Device 中央装置
- Repair Scene 修补现场
- Sorting Table 分拣桌
- Handoff Path 接力路径
- Before / After 双世界
- Calibration Bench 校准台
- Growth System 培育系统

连续系列要求换镜头、换场景、换动作、换构图方向。具体见 [`composition-patterns.md`](cute-gouache-illustrations/references/composition-patterns.md)。

---

## 最适合拿来画什么？

特别适合那些“内容有点硬，但不想画得冷冰冰”的主题：

- AI / Agent / Harness / 工作流
- 产品 / 创业 / 商业机制
- 职场与学习方法
- 观点型公众号文章
- 小红书 5–9 页轮播
- 博客 / Notion 正文配图
- 流程、断点、反馈、协作、判断、优先级等抽象机制

不推荐拿它做严格统计图、复杂技术拓扑、真实产品 UI、高端摄影 KV 或精确复刻已有 IP。

---

## 30 秒开始用

```bash
git clone https://github.com/lavine888/cute--illustrations.git
cd cute--illustrations

mkdir -p "${CODEX_HOME:-$HOME/.codex}/skills"
cp -R ./cute-gouache-illustrations "${CODEX_HOME:-$HOME/.codex}/skills/"
```

然后直接丢文章：

```text
Use $cute-gouache-illustrations 为下面文章生成 5 张 4:3 正文配图。

先提炼真正值得画的认知锚点，再为每张重新发明一个小世界和物理动作。
保持整组纸张、色板、Tiny Maker 角色语言和蜡笔×水粉材质一致。
不要连续使用同一种“输入→机器→输出”构图。

<文章>
```

---

## 常用调用方式

### 一个观点 → 一张解释图

```text
Use $cute-gouache-illustrations 为这句话生成一张 4:3 正文插图：

“AI 会放大你的判断，不会替你拥有判断。”

不要画机器人、大脑、灯泡或上升箭头。
先把“放大但不创造判断”翻译成一个原创物理动作，再生成。
```

### 一篇文章 → 小红书轮播

```text
Use $cute-gouache-illustrations 把下面内容拆成 7 页 3:4 轮播。
每页一个判断、一个主动作、一个小世界。
整组统一视觉语言，但连续两页不能同构。

<内容>
```

### 只规划，不生图

```text
Use $cute-gouache-illustrations 先不要生成图片。
从下面文章里挑 6 个最值得画的认知锚点。
每个输出：核心判断 / 小世界 / 物理动作 / Tiny Maker 职责 / 关键道具 / 短标签 / 构图类型。

<文章>
```

### 修掉 3D 感

```text
Use $cute-gouache-illustrations 编辑这张图。
保留构图和核心机制，把塑料 CGI 材质改成奶油纸上的水粉 + 蜡笔：去掉镜面高光、真实景深和数字渲染感，增加干刷、颗粒、露纸和不规则边缘。
```

更多见 [`examples/prompts.md`](examples/prompts.md)。

---

## Skill 结构

```text
.
├── README.md
├── LICENSE
├── NOTICE.md
├── examples/
│   ├── images/
│   │   └── 01-creative-workflow-reference.jpg
│   └── prompts.md
└── cute-gouache-illustrations/
    ├── SKILL.md
    ├── agents/
    │   └── openai.yaml
    ├── assets/
    │   └── examples/
    │       └── 01-creative-workflow-reference.jpg
    └── references/
        ├── style-dna.md
        ├── tiny-maker-ip.md
        ├── scene-language.md
        ├── composition-patterns.md
        ├── prompt-template.md
        └── qa-checklist.md
```

真正需要安装到 Codex 的是 `cute-gouache-illustrations/` 子目录。

`assets/examples/` 只用于低频视觉校准，不应该成为默认检索上下文，更不能当构图模板直接照抄。

---

## QA Benchmark

每张公开图按 20 分快速评分：纸张与材质、色板、可爱但不幼稚、核心隐喻、角色动作、构图留白、文字克制、原创场景、系列一致性、第一眼传播力，每项 0–2 分。

- **18–20**：可以作为公开示例
- **16–17**：可用，但建议再修一次
- **<16**：不要直接交付

完整清单见 [`qa-checklist.md`](cute-gouache-illustrations/references/qa-checklist.md)。

---

## 设计边界

这个项目抽取的是一种通用视觉语法：暖色纸张、蜡笔与水粉质感、圆润角色、粉彩色板、小世界场景、短手写批注和“用真实动作解释抽象关系”的方法。

生成新内容时，不应机械复刻参考图里的角色造型、机器结构、文案、猫、便签、物件摆放或精确构图。

**借语法，不抄场景；借可爱，不复制角色。**

---

## About

Made by [Lavine](https://github.com/lavine888) for turning serious ideas into tiny worlds people actually want to look at.

MIT License · See [`LICENSE`](LICENSE) and [`NOTICE.md`](NOTICE.md).
