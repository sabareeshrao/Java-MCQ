# Java-MCQ — Transcript-Grounded Sequenced Q&A

A standalone Java question bank grounded in the original uploaded course transcript. Target reader: **a recent CSE graduate with academic CS fundamentals but no industry experience**.

## Completed sections

| Section | Original video range | Q&A count | File |
|---|---|---:|---|
| CH01-S01 — Java Course Introduction and Project Overview | 00:00:00–00:00:32 | 4 | [Section 1.1](chapter-01/section-01-01.md) |
| CH01-S02 — JDK, Compiler, Bytecode, and IDE | 00:00:32–00:00:58 | 6 | [Section 1.2](chapter-01/section-01-02.md) |

The [question index](question-index.json) contains current section IDs, timestamp ranges, question counts, and question IDs.

## Format

Each section contains its chapter and section ID, original timestamp range, **standalone context**, and a **single progressively ordered question-and-answer sequence**. Every answer appears immediately beneath its question.

Use IDs like `CH01-S01-Q01`, `CH01-S01-Q02`, etc. Questions should progressively establish concepts and their relationships, then use source-demonstrated examples and applied reasoning when those are present. Never split questions into predefined difficulty categories.

## Question count must be dynamic

There is **no quota, minimum, or maximum** for a section. Use as many distinct questions as the original material genuinely supports. Rich instructional sections may justify **more than 15** (for example, 20–30+); short introductory material may justify much fewer. Never pad with repeated or paraphrased questions just to hit a target.

Keep the academic rigor suitable for a CSE graduate, without assuming industry experience. Preserve source terminology, demonstrated code, practical steps, checks, and the chronological learning progression.

## Strict source grounding

The **uploaded video transcript is the only content source** for questions, context, examples, and answers. Stay within the exact section timestamps, and do not bring forward later topics, inject outside technologies, or add unrelated knowledge. Acknowledge details that have not yet been established rather than guessing. Write independent educational prose; do not refer to an instructor or narrator.

## Duplicate-free updates

Before committing, read the current [question index](question-index.json) and existing sections. Compare both the literal wording and the meaning of proposed questions across the repository; eliminate semantic repeats. Keep one file per section. Reuse stable question IDs whenever the underlying concept stays the same; if restructuring the full sequence, change the section and index together. Skip commits when content has not changed. Maintain answers directly under questions.

The `main` branch is the canonical current question bank.
