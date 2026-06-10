# reading-fast
The skill of judging the value of texts, improving reading efficiency, and engaging in deep reading
> 渐进式、三层筛选的深度文章/报告总结 Skill — 融合 Adler 主动阅读方法，助你每天高效筛选与深度阅读大量材料。

---

## 这是什么？

是一个帮助阅读的prompt，我做成了skill。
刚开始是我需要阅读长文，但直接交给ai让它帮我总结的话ai做出来的东西过于浅显，我不喜欢，所以做了一个自己想要的效果。
我把整个阅读总结分成了三个渐进式的部分。
-  **第一部分**：判断一篇文章值不值得深读，这个是判断文章的价值。
-  **第二部分**：确定阅读后，就是提升阅读的效率，这部分是用来帮助理解文本，辅助阅读。
-  **第三部分**：这部分实在阅读后能够帮助做一个总结，以及发散思维去联想有没有什么关联的事情，把文本读宽读深。


---

## 三层筛选架构

```
┌─────────────────────────────────────────────────────┐
│  /first  快速筛查（300-400 字）                        │
│  一句话核心总结 + 基本背景 + 核心观点 + 阅读价值判断       │
│  → 30 秒判断：值得深读吗？                              │
├─────────────────────────────────────────────────────┤
│  /second  阅读建议                                     │
│  文章结构与展开逻辑 + 内容如何服务观点 + 作者的问题链      │
│  + 引导性阅读问题 ×5                                   │
│  → 带着问题框架去阅读                                  │
├─────────────────────────────────────────────────────┤
│  /third  深层分析                                      │
│  隐含假设 + 外部关联 + 举一反三 + 批判性洞见              │
│  + 个人与组织行动建议                                  │
│  → 变成你自己的知识                                    │
└─────────────────────────────────────────────────────┘
```

---

## 命令速查

| 命令 | 功能 | 适用时机 |
|------|------|----------|
| `/first` | 快速筛查总结 | 拿到文章先跑这个，决定要不要继续 |
| `/second` | 阅读建议 | 确认值得读后，获取阅读框架 |
| `/third` | 深层分析 | 深度挖掘，形成自己的洞见 |

> 支持直接跳转：你可以直接 `/second` 或 `/third`，不必按顺序执行。

---

## 各步骤详解

### Step 1 — `/first` 快速筛查总结

用 300-400 字帮你快速回答：「这篇文章在讲什么？对我有用吗？」

输出包含：
- **一句话核心总结**（Adler 式统一性总结）
- **基本背景**：研究的问题/现象、面向对象、影响群体
- **核心观点与分论点**（每个观点紧跟主要证据/案例）
- **阅读价值**：对哪些群体有价值 + 对你的个人价值 + 是否值得深读
- **关键名词解释**（3-4 个专有名词，≤150 字）

### Step 2 — `/second` 阅读建议

帮你建立主动阅读框架，输出包含：
- **文章结构与展开逻辑**（含思维导图形式）
- **内容如何服务观点**（带原文引用 + 解释）
- **作者的问题链**：提出了哪些重要问题？如何依次回答？
- **引导性阅读问题**（~5 个，帮你主动思考和验证理解）

### Step 3 — `/third` 深层分析

从「读懂」到「为我所用」，输出包含：
- **深层思想与隐含假设**
- **外部关联信息与最新发展**
- **举一反三与启示**
- **批判性洞见**：优势、局限、风险
- **个人与组织行动建议**

---



## 适用场景

- 📊 每天需要快速筛选大量行业报告 / 研报
- 📄 阅读学术论文需要结构化理解
- 📰 长文/深度报道需要提炼要点
- 🧠 任何需要「读了还要用起来」的深度阅读场景

---

## 安装与使用

1.下载.md文件
2.让ai或agent加载它
3.按需要输入/first,/second,/third
---


## 版本历史

| 版本 | 更新内容 |
|------|----------|
| 1.4 | 当前版本：三层渐进式架构 + Adler 方法融入 + 自动适应文章类型 |


##English version
# Adaptive Deep Summarizer

> A progressive, three-tier deep article/report summarization Skill — infused with the Adler active reading method, helping you efficiently filter and deeply read large volumes of material every day.

---

## What Is This?

It's a reading-assistance prompt that I packaged as a skill.

I started this because I needed to read long-form articles, but simply handing them to an AI for summarization produced results that were too shallow for my taste. So I built something that delivers the effect I wanted.

I broke the entire reading-and-summarization process into three progressive stages:

- **Stage 1** — Determine whether an article is worth deep reading. This is about judging the article's value.
- **Stage 2** — Once you decide to read, improve reading efficiency. This part helps with understanding the text and serves as a reading aid.
- **Stage 3** — After reading, help produce a summary and expand your thinking by drawing connections to related ideas — reading the text both broader and deeper.

---

## Three-Tier Architecture

```
┌─────────────────────────────────────────────────────┐
│  /first  Quick Screening (~300–400 words)            │
│  One-sentence core summary + Background + Key ideas  │
│  + Reading value assessment                          │
│  → 30 seconds to decide: worth a deep read?          │
├─────────────────────────────────────────────────────┤
│  /second  Reading Guide                              │
│  Article structure & logic + How content serves      │
│  arguments + Author's question chain                 │
│  + 5 guided reading questions                        │
│  → Read with a question framework                    │
├─────────────────────────────────────────────────────┤
│  /third  Deep Analysis                               │
│  Implicit assumptions + External connections         │
│  + Cross-application & insights + Critical analysis  │
│  + Personal & organizational action suggestions      │
│  → Turn it into your own knowledge                   │
└─────────────────────────────────────────────────────┘
```

---

## Command Reference

| Command   | Function               | When to Use                                       |
|-----------|------------------------|---------------------------------------------------|
| `/first`  | Quick screening summary | Run this first when you get an article, to decide whether to continue |
| `/second` | Reading guide           | Once confirmed worth reading, get a reading framework |
| `/third`  | Deep analysis           | Dig deeper and form your own insights             |

> Direct jumps are supported: you can go straight to `/second` or `/third` without following the order.

---

## Step Details

### Step 1 — `/first` Quick Screening Summary

Uses 300–400 words to quickly answer: "What is this article about? Is it useful to me?"

Output includes:
- **One-sentence core summary** (Adler-style unity summary)
- **Basic background**: the problem/phenomenon studied, target audience, affected groups
- **Core arguments & sub-arguments** (each with supporting evidence/examples following immediately)
- **Reading value**: value for different groups + personal value to you + whether it's worth a deep read
- **Key term explanations** (3–4 specialized terms, ≤150 words)

### Step 2 — `/second` Reading Guide

Helps you establish an active reading framework. Output includes:
- **Article structure & development logic** (with mind-map style representation)
- **How content serves the arguments** (with original text quotes + explanations)
- **Author's question chain**: what key questions does the author raise? How are they answered in sequence?
- **Guided reading questions** (~5, to help with active thinking and verifying understanding)

### Step 3 — `/third` Deep Analysis

From "understood" to "made my own." Output includes:
- **Deep ideas & implicit assumptions**
- **External connections & latest developments**
- **Cross-application & insights**
- **Critical insights**: strengths, limitations, risks
- **Personal & organizational action suggestions**

---

## Use Cases

- 📊 Need to rapidly filter large volumes of industry reports / research papers daily
- 📄 Need structured understanding when reading academic papers
- 📰 Need to extract key points from long-form articles / in-depth reports
- 🧠 Any deep reading scenario where you need to "read and then use it"

---

## Installation & Usage

1. Download the `.md` file
2. Have your AI or agent load it
3. Use `/first`, `/second`, `/third` as needed

---

## Version History

| Version | Changes                                                              |
|---------|----------------------------------------------------------------------|
| 1.4     | Current version: three-tier progressive architecture + Adler method integration + auto-adaptation to article types |

