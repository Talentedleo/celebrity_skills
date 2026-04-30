<div align="center">

# Celebrity Skills

> *"伟大思想不会消亡 — 它们会被提炼成框架，比创造者活得更久。"*

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![OpenClaw](https://img.shields.io/badge/OpenClaw-Skill-blue)](https://openclaw.ai)
[![English](https://img.shields.io/badge/Language-English-blue)](README.md)

<br>

**赛博永生项目** — 将传奇思想家转化为 AI 技能。

我们将世界上最伟大的投资者和科技领袖的智慧提炼成实用的 AI 技能。不是语录，而是可运行的思维框架。

</div>

---

## 核心理念

### 我们相信什么

1. **智慧应该比创造者更长寿** — 书籍无人问津，信件沉睡档案，采访被遗忘。技能让智慧永存。

2. **思维 > 引用** — 真正的致敬是推理他们的思维模型，而非鹦鹉学舌。

3. **声音很重要** — 每项技能都以其本来的真实声音说话，而非通用 AI 语气。

4. **透明优先** — 每个观点都附有来源，每个局限都被承认。

### 质量标准

| 标准 | 描述 |
|------|------|
| 仅用一手来源 | 所有内容来自原始英文资料 |
| 完全透明 | 每个观点都附有来源链接 |
| 量化不确定性 | 当信息为二手时明确告知 |
| 诚实局限性 | 不虚构缺失信息 |
| 活的文档 | 随着新信息出现持续更新 |

---

## 精选技能

### Warren Buffett

**奥马哈先知。60+ 年有据可查的投资智慧。**

| 指标 | 详情 |
|------|------|
| 思维模型 | 护城河、内在价值、能力圈、市场先生、CAP |
| 决策启发法 | 8 条 |
| 投资案例 | 11 个（可口可乐、苹果、GEICO、航空等） |
| 来源资料 | 60+ 年股东信 |

> *"投资的秘诀不在于你有多聪明，而在于你是否有独立思考的性情。"*

**[SKILL.md](./warren_buffett/SKILL.md)** · **[References](./warren_buffett/references/)**

---

### Cathie Wood

**ARK Invest 创始人。专注颠覆性创新的主题投资。**

| 指标 | 详情 |
|------|------|
| 专注领域 | 颠覆性创新、技术变革 |
| 核心主题 | AI、比特币、特斯拉、基因编辑、机器人 |
| 投资哲学 |  convergence、5 年 conviction 窗口 |
| 来源资料 | ARK 研究、采访、"Big Ideas" 年度信 |

> *"我无处容身，也不想融入任何地方。我想开辟一条自己的道路。"*

**[SKILL.md](./cathie_wood/SKILL.md)** · **[References](./cathie_wood/references/)**

---


---

## 全部技能

| 技能 | 专注领域 | 来源资料 |
| [Aswath Damodaran](./aswath_damodaran/) | DCF 估值、故事驱动分析 | 纽约大学讲座、估值书籍 |
| [Benjamin Graham](./benjamin_graham/) | 价值投资、聪明投资者 | Security Analysis、The Intelligent Investor |
| [Bill Ackman](./bill_ackman/) | 激进投资、高信念、集中持仓 | Pershing Square信函、国会证词 |
| [Cathie Wood](./cathie-wood/) | 颠覆性创新、ARK Invest、主题投资 | ARK Big Ideas 报告、TED 演讲、Twitter |
| [Charlie Munger](./charlie_munger/) | 多学科思维、lollapalooza、倒置法 | Poor Charlie's Almanack、伯克希尔 |
| [George Soros](./george-soros/) | 反身性理论、宏观投资、繁荣-萧条周期 | 《金融炼金术》、Soros on Soros、金融危机操作 |
| [Greg Abel](./greg_abel/) | 运营卓越、伯克希尔文化 | Buffett 继任、运营管理 |
| [Jim Simons](./jim-simons/) | 量化投资、信号检测、数学模型 | The Man Who Solved the Market、Renaissance Technologies、Simons Foundation |
| [Ken Griffin](./ken-griffin/) | 多策略对冲基金、平台建设、做市商 | Citadel LLC、Citadel Securities、国会证词 |
| [Michael Burry](./michael_burry/) | 逆向价值投资、安全边际、泡沫识别 | Cassandra Unchained、大空头交易记录 |
| [Peter Lynch](./peter_lynch/) | 合理价格成长、知道你所持有 | One Up on Wall Street、Beating the Street |
| [Phil Fisher](./phil_fisher/) | 成长股投资、scuttlebutt、GARP | Common Stocks and Uncommon Profits |
| [Ray Dalio](./ray-dalio/) | 原则驱动宏观、桥水风险平价 | 《原则》书籍、《经济机器》视频 |
| [Stanley Druckenmiller](./stanley_druckenmiller/) | 宏观投资、全球宏观、流动性 | Morgan Stanley 采访、Ira Sohn |
| [Warren Buffett](./warren-buffett/) | 价值投资、护城河、资本配置、能力圈 | 伯克希尔年报、股东大会、股东访谈 |
---

## 快速开始

### For OpenClaw

```bash
# Warren Buffett
> Analyze Apple using Buffett's moat framework
> What's the five-minute test for Tesla?

# Cathie Wood  
> What does ARK mean by "convergence"?
> How does Wood evaluate Tesla's bull case?

# Peter Lynch
> How do I know if I understand a stock?
> Tell me about the "cut flowers, water weeds" approach
```

### 技能结构

每个技能遵循相同结构：

```
skill_name/
├── SKILL.md              ← 核心技能文件（Anthropic 格式）
├── _meta.json            ← 元数据
└── references/
    ├── 01-writings.md     ← 原始著作 + 摘要
    ├── 02-conversations.md ← 采访 + 记录
    ├── 03-expression-dna.md ← 沟通风格
    ├── 04-external-views.md ← 批评 + 观点
    ├── 05-decisions.md    ← 关键决策 + 案例
    └── 06-timeline.md    ← 完整时间线
```

---

## 路线图

想看我们下一步要做谁？

- [ ] Steve Jobs
- [ ] Jeff Bezos

有建议？[提交 issue](https://github.com/Talentedleo/celebrity_skills/issues)。

---

## 免责声明

这些技能是从公开著作和采访中有学习目的地提炼的。它们不构成财务、投资或专业建议。

---

<div align="center">

**最伟大的思想，为你永续工作。**

MIT License © [Leo Li](https://github.com/Talentedleo)

</div>
