# 论文 PDF 转 LaTeX 精读流程

目标不是先总结论文，而是先把论文转成结构清楚、可长期复习的中英文对照 LaTeX 版本。

## 核心原则

先复刻论文，再翻译论文。

结构必须先于理解，完整性必须先于总结。

## 标准流程

### 1. 提取论文结构

先从 PDF 中确认：

- Title
- Abstract
- Section
- Subsection
- Subsubsection
- Equations
- Figures / Tables
- References

### 2. 建立英文原文章节

用 LaTeX 保留完整英文原文和原论文结构：

```latex
\chapter{Paper Title}

\section{Abstract}

English abstract.

\section{Introduction}

English introduction.

\subsection{Subsection Title}

English subsection text.
```

要求：

- 原文结构完整
- section / subsection 层级清楚
- 公式尽量保留原样
- 图表标题和关键说明保留
- 不随意改写原文

### 3. 建立中文翻译章节

在英文原文后建立对应中文版：

```latex
\chapter{《Paper Title》中文版}

\section{摘要}

中文摘要翻译。

\section{引言}

中文引言翻译。

\subsection{小节标题翻译}

中文小节翻译。
```

要求：

- 中文章节与英文章节一一对应
- 标题层级保持一致
- 段落顺序保持一致
- 公式保留原样或等价重排
- 专有名词首次出现保留英文括注

### 4. 核对完整性

完成后检查：

- 英文原文是否完整
- 中文翻译是否完整
- 英文 section 与中文 section 是否对应
- 公式、符号、编号是否遗漏
- 图表说明是否保留
- LaTeX 是否能编译

## 推荐 LaTeX 排布

优先使用“两章式”结构：

```text
\chapter{Paper Title}
英文原文

\chapter{《Paper Title》中文版}
中文翻译
```

不要优先使用“英文一段、中文一段”的穿插式结构，除非论文很短或特别适合逐段对照。

## 最终标准

一篇论文转成 LaTeX 后，应该做到：

```text
英文原文完整
论文结构完整
中文翻译完整
中英章节对应
公式图表不丢
```

