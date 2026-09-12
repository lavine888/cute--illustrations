<div align="center">

# Cute Gouache Illustrations

**把抽象观点，画成一座可爱、温暖、会运转的小小创意世界。**

中文内容 → 认知锚点 → 可爱叙事场景 → 蜡笔 × 水粉插画

![Codex Skill](https://img.shields.io/badge/Codex-Skill-111111?style=flat-square)
![Chinese First](https://img.shields.io/badge/Chinese-First-EA7F73?style=flat-square)
![Cute Gouache](https://img.shields.io/badge/Style-Cute%20Gouache-79AFA5?style=flat-square)
![MIT License](https://img.shields.io/badge/License-MIT-6E63A8?style=flat-square)

</div>

---

## 这个 Skill 是什么？

**Cute Gouache Illustrations** 是一个面向中文内容创作的 Codex Skill。

它会先理解文章里的观点、转折、机制和情绪，再把它们翻译成一张张像“可爱绘本里的小小工作坊”一样的解释图：暖白纸张、蜡笔与水粉混合笔触、粉彩配色、圆润角色、真实动作、少量手写标注，以及一个正在发生事情的完整场景。

它不是把内容做成 PPT 信息图，也不是只给文章塞一只萌宠。

核心原则是：

> **可爱负责让人愿意看，场景负责把观点讲明白。**

---

## 和另外两个 Skill 的区别

| Skill | 核心视觉语言 | 最擅长 |
|---|---|---|
| `crayon-doodle-illustrations` | 彩铅讲义 / 知识卡 | 判断、概念拆解、轮播 |
| `ian-xiaohei-illustrations` | 白底黑线 / 怪诞小黑 | 正文解释图、流程和隐喻 |
| **`cute-gouache-illustrations`** | **可爱水粉绘本 / 小世界叙事** | **让复杂内容变得亲切、温暖、好传播** |

第三个 Skill 不追求“更萌的知识卡”，而是把观点变成一个**正在运转的小世界**。

---

## 视觉 DNA

| 维度 | 默认规则 |
|---|---|
| **Background** | 暖白 / 奶油色纸张，有轻微纸纤维纹理 |
| **Material** | 蜡笔 + 水粉 + 彩铅混合，干刷、颗粒、轻微不均匀 |
| **Palette** | 青绿色、蜜桃粉、奶油黄、珊瑚橙、薰衣草紫 |
| **Character** | 圆润、软乎、表情简单；角色必须参与核心动作 |
| **World** | 纸箱、机器、输送带、书本、植物、工具、便签等“低科技小世界” |
| **Typography** | 少量手写字，像马克笔 / 蜡笔；短词优先 |
| **Composition** | 一张图一个动作或机制，场景完整但不拥挤 |
| **Mood** | 温暖、聪明、俏皮，不幼稚，不糖果过量 |

### 明确不要

`商业扁平插画` · `PPT 信息图` · `3D 塑料玩具` · `动漫厚涂` · `纯儿童绘本` · `复杂 UI` · `霓虹科技感` · `满屏文字` · `只站着卖萌的吉祥物`

---

## 最适合拿来画什么？

- AI / Agent / 工作流 / 产品 / 创业
- 职场与学习方法
- 观点型公众号文章
- 小红书 5–9 页轮播
- 博客 / Notion 正文配图
- “复杂但不想画得太硬”的流程、机制和因果关系
- 想让技术内容更有亲和力的解释图

尤其适合：**内容本身有点硬，但你不想再画一张冷冰冰的技术图。**

---

## 30 秒开始用

```bash
git clone https://github.com/lavine888/cute--illustrations.git
cd cute--illustrations

mkdir -p "${CODEX_HOME:-$HOME/.codex}/skills"
cp -R ./cute-gouache-illustrations "${CODEX_HOME:-$HOME/.codex}/skills/"
```

然后：

```text
Use $cute-gouache-illustrations 把下面这篇文章做成 6 张可爱水粉绘本风配图。
每张图只讲一个核心认知动作，角色必须真的参与场景。

<粘贴文章>
```

---

## 默认工作流

```text
原始文章 / 观点
      ↓
找认知锚点
      ↓
把抽象关系变成真实动作
      ↓
设计一个“可爱小世界”场景
      ↓
安排角色、物件和少量手写标注
      ↓
生成蜡笔 × 水粉插画
      ↓
QA：可爱但不幼稚 / 清楚但不 PPT / 系列一致
```

### 例子

观点：

> AI 不是替你思考，而是把你的判断放大。

不要画：机器人 + 大脑 + 向上箭头。

可以画成：

**一只小创客站在巨大的调音台前，把一颗很小的“判断种子”接进机器；机器不会生成新的种子，只会把原本那颗种子的声音、光和影响放大。**

这就是这个 Skill 的核心：**把抽象观点变成一个可爱的、具体的、正在发生的动作。**

---

## 常用调用方式

### 一篇文章 → 一组正文配图

```text
Use $cute-gouache-illustrations 为下面文章生成 5 张正文配图。
先提炼 5 个真正值得画的认知锚点，再分别设计小世界场景并生成。
保持整组纸张、角色语言、色板和材质一致。

<文章>
```

### 一篇文章 → 小红书轮播

```text
Use $cute-gouache-illustrations 把下面内容拆成 7 页 3:4 轮播。
可爱，但不要儿童绘本感；每页一个判断，一个场景，一个核心动作。

<内容>
```

### 一个观点 → 单张图

```text
Use $cute-gouache-illustrations 为这句话生成一张 4:3 正文插图：

“真正稀缺的不是工具，而是判断。”

不要直接画天平、灯泡或奖杯，重新发明一个可爱的物理隐喻。
```

### 只规划，不生图

```text
Use $cute-gouache-illustrations 先不要生成图片。
把下面文章拆成 6 个 shot，并输出：核心判断 / 场景隐喻 / 角色动作 / 关键物件 / 手写标注 / 构图。
```

更多见 [`examples/prompts.md`](examples/prompts.md)。

---

## Skill 结构

```text
cute-gouache-illustrations/
├── SKILL.md
├── agents/
│   └── openai.yaml
└── references/
    ├── style-dna.md
    ├── scene-language.md
    ├── prompt-template.md
    └── qa-checklist.md
```

真正需要安装的是 `cute-gouache-illustrations/` 子目录。

---

## 设计边界

本项目从参考图里抽取的是**通用视觉语法**：暖色纸张、蜡笔与水粉质感、圆润角色、粉彩色板、小世界场景、手写标注和叙事方法。

生成新内容时，不应机械复刻某张参考图里的角色造型、机器结构、文案、物件摆放或精确构图。

**借语法，不抄场景；借可爱，不复制角色。**

---

## About

Made by [Lavine](https://github.com/lavine888) for turning serious ideas into tiny worlds people actually want to look at.

MIT License · See [`LICENSE`](LICENSE) and [`NOTICE.md`](NOTICE.md).
