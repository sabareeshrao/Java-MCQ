# Java MCQ — Transcript-Grounded Question Bank

This repository is the reference for independent Java section assessments based on the uploaded Java course transcript.

## Structure

- `chapter-01/section-01-01.md` — Chapter 1, Section 1.1
- `chapter-01/section-01-02.md` — Chapter 1, Section 1.2
- `question-index.json` — Completed sections, stable question IDs, and question-bank rules

## Section format

Every section contains its original transcript timestamp range, standalone context and 15 **answered** questions: 5 Easy, 5 Medium, 5 Hard. Each answer is placed immediately beneath its question. Easy still demands technical understanding at CSE graduate level.

The content is independent study material for recent CSE graduates without industry experience. No narrator or instructor framing is used. Every question has an **answer immediately below it**. Both questions and answers must remain strictly within the scope of the corresponding transcript section, without importing outside explanations or concepts. If the source does not establish a point, state that limit instead of guessing.

## Updating without duplicates

Before generating a new section, inspect `question-index.json` and the existing section files. Compare proposed questions by both exact wording and meaning, including questions in different sections. Retain the same stable question IDs on revisions. Update a section file in place when needed; do not create duplicate section files or commit unchanged content.

Question ID pattern: `CH01-S01-E01`, `CH01-S01-M01`, `CH01-S01-H01`.
