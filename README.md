# 伏羲 🐉

> 女娲造人，伏羲画八卦——给混沌以符号，给无序以结构。
> — Keith Spicer《伏羲》方法论，被伏羲注入了秩序

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Claude Code Skill](https://img.shields.io/badge/Claude%20Code-Skill-blue)](https://claude.ai/code)

一套让你在**没有任何讲稿**的情况下，也能有条理、有说服力、有魅力地张嘴就说的完整操作系统。

源自 Keith Spicer 经典著作《伏羲》(1986) 和《Winging It》(1982)，基于纯 Markdown 的 AI Skill 格式，可直接被 Claude Code、OpenCode、OpenClaw 等主流 AI 编程工具加载使用。

---

## 📖 适用场景

| 场景 | 示例 |
|------|------|
| 🎤 正式演讲/汇报 | 季度汇报、项目提案、年会发言 |
| ⚡ 即兴发言 | 会议被点名、电梯碰到老板、临时分享 |
| ❓ Q&A 应对 | 演讲后提问、媒体采访、客户质疑 |
| 🔥 困难对话 | 传达坏消息、处理愤怒听众、推翻同事方案 |
| 🧠 复杂概念解释 | 给非技术人员讲技术、给老板讲细节 |

---

## 🚀 快速开始

### 安装

```bash
# 克隆到 AI 工具的技能目录（以 Claude Code 为例）
git clone https://github.com/lipeionline/fuxi-skill.git ~/.claude/skills/fuxi-skill/
```

放置到对应工具的 skills 目录后即可自动加载，无需额外配置。

### 使用

直接在对话框描述你的沟通困境：

```
"帮我为明天的季度汇报设计一个三桩子结构，听众是挑剔的 CFO"
"用伏羲的 AIR 法则，分析我刚才被客户质问时哪里出了问题"
"我要给非技术团队讲这个技术方案，帮我用图景辅助框架设计类比"
"面试官问我'你在学校和男生关系好还是女生关系好'，帮我用钟摆计划组织回答"
```

**示例：面试陷阱题的伏羲式拆解**

> 面试官问：「你在学校和同学关系怎么样？和男生好还是和女生好？」
>
> **真实意图**：考察跨性别职场协作能力与边界感（不是八卦）。
>
> **推荐策略**——钟摆计划：
> - 摆到 A 端：「和男生相处，我学到最宝贵的是直接——不绕弯子，把事情说清楚」
> - 摆到 B 端：「和女生相处，我学到最宝贵的是细腻——关注到人的状态和细节」
> - 落在中间：「两边我都受益。进了团队，不管跟谁配合，该直接时不磨叽，该关注人的时候不迟钝——**跟谁都能配合，看事不看人**」

或使用斜杠命令：

```
/fuxi 帮我设计一个10分钟的晋升答辩演讲结构
```

---

## 🧠 核心方法论

```
大脑扫描(3min) → 核心信息(≤7词) → 逻辑结构(6种计划) → 三桩子脱稿 → AIR问答应对
```

### 五步工作流

| 步骤 | 工具 | 产出 |
|------|------|------|
| **1. 大脑扫描** | 3分钟三列表 | 听众画像：知道什么/想要什么/怕什么 |
| **2. 核心信息** | 标题编写法则 | ≤7词、主动语态、具体名词动词 |
| **3. 逻辑结构** | 6种计划 + 双重测试 | 通过电影测试+结论测试的框架 |
| **4. 脱稿表达** | 三桩子法 | 左脑搭骨架，右脑自由跳舞 |
| **5. Q&A应对** | AIR法则 | 认可→询问→调整 |

### 三桩子法（即兴脱稿核心）

```
左脑立三个关键词桩子 → 大声宣布数字 → 右脑逐桩展开细节 → 回到左脑收尾
```

### AIR 法则（问答应对）

- **A**cknowledge（认可）—— 先接住情绪
- **I**nquire（询问）—— 澄清真正的问题
- **R**espond/Adjust（调整回答）—— 引导到你能解决的轨道

### 六种逻辑计划

| 计划 | 适用 | 例子 |
|------|------|------|
| 🔺 三角 | 并列维度 | 可行性/风险/建议 |
| 🕐 时钟 | 时间序列 | 过去/现在/未来 |
| ⏳ 钟摆 | 对比论证 | A极端→B极端→中间C |
| 📍 地点 | 空间维度 | 本地/全国/全球 |
| 🔍 变焦镜 | 层次切换 | 个人→部门→公司→行业 |
| 💰 收益 | 利益罗列 | 对个人/对团队/对公司 |

---

## 📁 目录结构

```
fuxi-skill/
├── README.md                          # 你在这儿
├── LICENSE                            # MIT
├── SKILL.md                           # 完整方法论（主技能）
├── index.md                           # 技能集总览
├── .gitignore
├── modules/                           # 子技能模块（可独立使用）
│   ├── audience-analysis-message-design/
│   │   ├── SKILL.md                   # 听众分析与核心信息设计
│   │   └── references/
│   ├── speech-structure-logic-design/
│   │   ├── SKILL.md                   # 演讲逻辑结构设计
│   │   └── references/
│   ├── impromptu-delivery-qa-handling/
│   │   ├── SKILL.md                   # 即兴表达与问答应对
│   │   └── references/
│   └── strategic-expression-frameworks/
│       ├── SKILL.md                   # 高级表达框架（变焦镜/钟摆/图景）
│       └── references/
└── references/
```

### 高级用户：拆分安装子模块

如果需要将 4 个子技能拆分为独立 Skill：

```bash
ln -s ~/.claude/skills/fuxi-skill/modules/audience-analysis-message-design ~/.claude/skills/
ln -s ~/.claude/skills/fuxi-skill/modules/speech-structure-logic-design ~/.claude/skills/
ln -s ~/.claude/skills/fuxi-skill/modules/impromptu-delivery-qa-handling ~/.claude/skills/
ln -s ~/.claude/skills/fuxi-skill/modules/strategic-expression-frameworks ~/.claude/skills/
```

---

## 🌟 特色

- **零依赖，跨平台**：纯 Markdown 文本，兼容 Claude Code、OpenCode、OpenClaw 等主流 AI 编程工具
- **即刻激活**：描述问题即触发，无需记忆复杂命令
- **模块化**：5 个 Skill 可按需整体使用或拆分
- **一手源材料**：方法论直接蒸馏自 Keith Spicer 原书
- **中英双语**：核心概念双语呈现，适应不同思维习惯

---

## 📚 致谢

- 源材料：《伏羲》(1986) 和《Winging It》(1982) by Keith Spicer (1934–2023)
- 创建者：[李培](https://x.com/AlchainHust)

---

## 📄 License

MIT — 自由使用、修改、分发。
