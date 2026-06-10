---
name: adaptive-deep-summarizer
version: 1.4
description: A progressive, three-tier deep article/report summarization Skill. Infused with the Adler active reading method, supporting efficient daily filtering and deep reading of large volumes of material.
---

# Adaptive Deep Summarizer

## Commands
- `/first` → Execute Step 1 (Quick Screening Summary)
- `/second` → Execute Step 2 (Reading Guide)
- `/third` → Execute Step 3 (Deep Analysis)

## Usage Rules
1. Run `/first` by default initially.
2. Strictly trigger the corresponding step based on user command; direct jumps are supported.
3. Remember the article context currently being analyzed.
4. Automatically adapt to different article types (industry reports, academic papers, commentary, etc.).

## Step 1: Quick Screening Summary (300–400 words)
- **One-sentence core summary** (Adler-style unity summary): Capture the article's core in one sentence.
- **Basic background**: The problem/phenomenon studied, target audience, potentially affected groups.
- **Core arguments & sub-arguments**: Main argument + key sub-arguments (each immediately followed by primary evidence/examples).
- **Reading value**: Value for different audiences + personal value to the user + whether it's worth a deep read.
- **Key term explanations**: 3–4 most important specialized terms (≤150 words, placed at the end).

## Step 2: Reading Guide
1. **Article structure & development logic** (with mind-map style representation).
2. **How content serves the arguments** (with original text quotes + explanations).
3. **The author's questions**: What key questions does the author raise? How are they answered in sequence?
4. **Guided reading questions** (~5, to help with active thinking and verifying understanding).

## Step 3: Deep Analysis
- Deep ideas & implicit assumptions.
- External connections & latest developments.
- Cross-application & insights.
- Critical insights (strengths, limitations, risks).
- Personal & organizational action suggestions.

## Output Principles
- Clear structure using headings and subsections.
- Tight coupling of arguments and evidence; avoid listing examples in isolation.
- Professional, neutral, and practical language.
- Emphasize actionability and personal takeaways.

## Adler Method Integration
- Step 1: One-sentence core summary + how the main parts serve the whole.
- Steps 2 & 3: Incorporate the active reading question framework.

**Use Case**: For users who read large volumes of articles/reports daily and need rapid filtering + structured understanding + deep thinking.
