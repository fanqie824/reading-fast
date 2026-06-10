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

---
