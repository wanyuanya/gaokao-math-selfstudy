# Gaokao Math Self-Study System (China National New Gaokao I)

> A **self-study system for high school math** that anyone can understand, with clear prerequisites and a continuous learning path.
> Learn from the **old textbooks** (2004 curriculum, illustrated and detailed), align with the **new textbooks** (PEP A Edition 2019, the scope of New Gaokao I), and validate with **real exam papers** (2020–2025 New Gaokao I).

🌐 **中文版**：[README.zh-CN.md](README.zh-CN.md) · **English**: this page

## ⚠️ Disclaimer (read first)

- **This repository is AI-assisted in generation and organization.** Despite multiple rounds of manual and independent review, **errors may still exist** (layout, OCR recognition, individual problem statements, or typos in solutions).
- **Official sources prevail**: textbook content follows the official PEP publications; exam questions and answers follow the official papers and scoring standards of provincial examination authorities; formulas follow textbooks and authoritative references.
- This repository **does not constitute any teaching commitment**, does not replace textbooks, school courses, or professional teachers; it is for personal learning and research.
- **Found an error?** Please open an Issue / PR (see "Feedback & Contribution" below) — we will keep revising.

## Quick Start

1. **For daily study, open `电子书分章\index.html`** — a **chapter-per-file edition** (guide + 19 chapters + appendix, each chapter a separate HTML page). Every page holds only one chapter, so it opens and expands answers **instantly, even on weak machines**. Click any chapter card to enter; navigate chapters with the `← 上一章 | 目录 | 下一章 →` bar at the top.
2. **Also available**: `电子书\高中数学自学系统电子版.html` — the single-file edition with the whole book in one page, including **cross-chapter full-text search**; use it when you want to search the entire book at once.
3. Every chapter page / the single file offers: **font-size control, serif/sans toggle, night mode, in-page search, collapsible answers** (answers hidden by default, labeled by **prerequisite self-test / A / B / C groups**), and **three separate print modes from the top bar** (current chapter only, never the whole book):
   - **打印讲义** (Print Lecture) — the chapter's teaching text, **with all problems and answers removed**;
   - **打印题目** (Print Problems) — a **clean worksheet**: prerequisite self-test + exit check + A/B/C exercises, **no answers**;
   - **打印答案** (Print Answers) — the **answer sheet**: self-test answers + A/B/C group answers only.
4. Follow the "six-step loop" in Chapter 00 for each chapter: **prerequisite self-test → learning goals → main text (with "plain-language" annotations) → A/B/C tiered exercises → formula quick-lookup → advanced methods → answers**.
5. Each chapter has "chapter materials" links at the top plus a "what if I don't understand" guide; if stuck over 30 minutes, mark and skip, then return later.
6. Want an AI assistant to answer questions / generate problems / verify progress with the same method? Install the skill package `技能包\gaokao-math-selfstudy\` (see `系统文档\技能包安装说明.md`).

## Sources of Content

| Category | Specific Source | Purpose |
|---|---|---|
| New textbooks | PEP A Edition 2019: Compulsory 1–2, Selective Compulsory 1–3 (5 volumes) | Scope alignment |
| Old textbooks | 2004 curriculum PEP A Edition: Compulsory 1–5, Elective 1-1/1-2, 2-1/2-2/2-3, 3-4, 4-1/4-4/4-5 (14 volumes) | Detailed reading (clearest illustrations, reliable formulas) |
| Exam papers | 2020–2025 National New Gaokao I real papers (incl. 2020 Shandong paper) | Chapter exit checks & stage validation |
| Methods book | Suzhou Teaching & Research "High School Math Problem-Solving Methods and Skills Reference" (60 topics, 208 pp.) | Method examples & techniques (cited in text as "Suzhou R&D · Topic N, p. XX") |
| Formula handbook | "Common High School Math Formulas" (18 pp.) | Appendix formula quick-lookup (419 cards) |
| Advanced methods | 7 handouts on advanced topics (extremum-point shifting, hidden zeros, homogenization, point-difference method, scaling, etc., all within syllabus) | Methods for final problems (embedded in chapters + appendix) |
| Curriculum | "General High School Mathematics Curriculum Standard" & New Gaokao I exam description | Chapter scope & requirement levels |

> Textbooks and exam papers are **third-party copyrighted materials and are NOT distributed with this repository.** Obtain them locally per `系统文档\00_素材清单与来源.md` (personal study and research only). Paths like `数学自学系统素材\...` in the text are the author's local study directories, for provenance only.

## Directory Structure

```
├── 电子书/
│   ├── 高中数学自学系统电子版.html    # Main e-book (guide+19 chapters+appendix, single file, cross-chapter search)
│   └── assets/                       # Figures (52 images, referenced by the e-book)
├── 电子书分章/                        # Chapter-per-file edition (recommended for daily study, instant & light)
│   ├── index.html                    # Home: 20 chapter cards + how-to-use
│   └── ch-00.html … ch-20.html       # One chapter per page (guide 00 … appendix 20)
├── 公式/
│   ├── 高中数学常用公式·修订版.html/.md  # Full formulas by 15 sections (with memory tips)
│   ├── 高中数学公式速查手册.html       # Quick lookup in chapter order 01–19
│   └── 不超纲高级方法手册.html         # Advanced methods (cards + search + TOC)
├── 系统文档/
│   ├── 高中数学自学系统.md            # System main document (8 stages + method card index)
│   ├── 00_素材清单与来源.md           # Full list of textbooks/exams and download sources
│   ├── 不超纲高级方法手册.md          # Advanced methods handbook source
│   ├── 技能包安装说明.md              # Skill installation guide
│   └── 三轮迭代要求.md                # Quality acceptance criteria of this project
└── 技能包/
    └── gaokao-math-selfstudy/        # Installable Skill (5 method cards + 20 chapter cards + formula lookup)
```

## How to Learn (in one sentence)

- **One main thread**: 19 chapters ordered by dependencies; each chapter tells you "what you must know before, what you can do after, how to prove you pass".
- **Prerequisite control**: each chapter starts with a prerequisite self-test (remedy prerequisites if failing) and ends with an exit check (unlock the next chapter only when passing).
- **Three tiers**: understand (old-textbook diagrams + plain-language annotations) → can solve (method cards) → solve correctly (tiered real-exam problems A/B/C).
- **Essence-first**: each chapter opens with "the essence in one sentence + why it is useful", then a general skeleton — solve one problem type and you can solve the whole family; knowledge combines across chapters (extend from one to many).

## Quality & Fidelity

- All content went through **three rounds of iteration + independent blind review** (independent reviewers actually executed tests with verifiable records; verbal claims rejected), acceptance criteria in `系统文档\三轮迭代要求.md`.
- **Anti-hallucination red lines**: formulas, conclusions, and exam answers all have sources (textbooks / exam papers / verified facts); nothing fabricated; every method example cites its source (Suzhou R&D · Topic N / Advanced Methods Handbook · X.Y).
- Verified anchor examples: 2025 T4=2tan(x−π/3)/B; 2025 T16 recurrence proving arithmetic (common difference 1 of {n·aₙ}); 2024 T7=6; 2023 T1=complex numbers; χ²=50/3; aₙ=4n−3; ellipse eccentricity; permutation-combination counts; expectation/variance; stratified sampling — all verified against real papers / recomputation.
- **Unverified items (honestly disclosed)**: page-level word-by-word comparison of some 2021/2022 problems, not every self-authored exercise number recomputed (spot-checked), dark-mode mobile contrast not item-by-item verified — you are welcome to point out issues.

## Copyright & License

- **This repository contains only original content** (e-book, formula compilation, methods handbook, system documents, skill package), open-sourced under the **MIT License** (see LICENSE). Copyright belongs to the author, **wanyuanya**.
- Textbooks and exam papers (third-party copyrighted materials) are **not distributed** in this repository; rights belong to their original owners; obtain them yourself for personal study and research only.

## Feedback & Contribution

Issues / PRs are welcome. Please follow the project's acceptance criteria: **no hallucination, no fabrication, no deviation from sources**; every change must carry verifiable evidence (source / recomputation / screenshot); changes involving real exam problems must be checked against the official papers.


## Materials (Important)

- **Included in this repo**: the e-book content (single-file + per-chapter versions), the Formula Quick-Reference, and the Non-Out-of-Syllabus Advanced Methods Handbook — all original works by the author.
- **Not distributed here**: textbooks and past exam papers are third-party copyrighted materials for personal study only. Please obtain them yourself:
  - Old textbooks: PEP High School Math A (2004 syllabus) Volumes 1–5 and Electives 2-1 / 2-2 / 2-3, etc. Each chapter's "Materials" chips show the **exact book title and edition**.
  - New textbooks: PEP A (2019 syllabus) Compulsory 1–2 and Selective Compulsory 1–3.
  - Past papers: 2020–2025 National New Gaokao I (official versions are free on NEEA / provincial exam authority websites).
- **Desktop client**: Windows installer / portable builds are on GitHub Releases; for personal study only, **commercial use is strictly prohibited** (see LICENSE).
- Contact: QQ 1064752335
