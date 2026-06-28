# 伏羲 🐉

> 女娲造人，伏羲画八卦——给混沌以符号，给无序以结构。
> — Keith Spicer《驻足思考》方法论，被伏羲注入了秩序

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Claude Code Skill](https://img.shields.io/badge/Claude%20Code-Skill-blue)](https://claude.ai/code)

一套让你在**没有任何讲稿**的情况下，也能有条理、有说服力、有魅力地张嘴就说的完整操作系统。

源自 Keith Spicer 经典著作《Think on Your Feet》(1986) 和《Winging It》(1982)，蒸馏为可被 AI（Claude Code）直接执行的沟通教练 Skill。

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
# 克隆到 Claude Code 技能目录
git clone https://github.com/ylq123/fuxi-skill.git ~/.claude/skills/fuxi-skill/
```

无需额外配置，Claude Code 自动发现并注册。

### 使用

直接在对话框描述你的沟通困境：

```
"帮我为明天的季度汇报设计一个三桩子结构，听众是挑剔的 CFO"
"用驻足思考的 AIR 法则，分析我刚才被客户质问时哪里出了问题"
"我要给非技术团队讲这个技术方案，帮我用图景辅助框架设计类比"
```

或使用斜杠命令：

```
/think-on-your-feet 帮我设计一个10分钟的晋升答辩演讲结构
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
think-on-your-feet-framework/
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
ln -s ~/.claude/skills/think-on-your-feet-framework/modules/audience-analysis-message-design ~/.claude/skills/
ln -s ~/.claude/skills/think-on-your-feet-framework/modules/speech-structure-logic-design ~/.claude/skills/
ln -s ~/.claude/skills/think-on-your-feet-framework/modules/impromptu-delivery-qa-handling ~/.claude/skills/
ln -s ~/.claude/skills/think-on-your-feet-framework/modules/strategic-expression-frameworks ~/.claude/skills/
```

---

## 🌟 特色

- **零依赖**：纯 Markdown 文本，Claude Code 原生支持
- **即刻激活**：描述问题即触发，无需记忆复杂命令
- **模块化**：5 个 Skill 可按需整体使用或拆分
- **一手源材料**：方法论直接蒸馏自 Keith Spicer 原书
- **中英双语**：核心概念双语呈现，适应不同思维习惯

---

## 📚 致谢

- 源材料：《Think on Your Feet》(1986) 和《Winging It》(1982) by Keith Spicer (1934–2023)
- 创建者：[花叔](https://x.com/AlchainHust)

---

## 📄 License

MIT — 自由使用、修改、分发。
