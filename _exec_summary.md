# DAMA DMBOK Interactive Course — Executive Summary

## Overview

Interactive self-study course for business analysts based on DAMA DMBOK. Single HTML file, fully offline, no backend.

## Architecture

### Modules (6)
| Module | DAMA Chapter | Bank Size | Test Size |
|--------|-------------|-----------|-----------|
| Data Management | Chapter 1 | 70 | 50 |
| Data Governance | Chapter 3 | 70 | 50 |
| Data Architecture | Chapter 4 | 60 | 50 |
| Data Modeling & Design | Chapter 5 | 60 | 50 |
| Data Storage & Operations | Chapter 6 | 60 | 50 |
| Data Integration & Interoperability | Chapter 8 | 60 | 50 |

### Final Assessment
- **Bank size:** 130 questions (cross-module)
- **Test size:** 100 questions per attempt

### Total Questions: 544
- Question banks for dynamic quiz generation: 380 (module banks) + 130 (final bank)
- Inline section checks: 34 (across 19 sections)
- Question types: single choice (430), true/false (62), fill-in (41), matching (8), multiple choice (3)

## Key Features

### Dynamic Quiz Generation
- Each test attempt randomly selects a subset from the question bank
- Balanced topic coverage: questions are tagged by topic and selected proportionally
- Both question order and answer option order are randomized
- Multiple attempts generate different question sets, supporting retakes with variation

### Question Design
- CDMP exam-style patterns: "Which BEST describes...", "The PRIMARY purpose...", scenario-based, concept distinction
- Original questions inspired by professional certification exam standards
- Mix of conceptual understanding, terminology, and applied scenarios
- Bilingual terminology coverage (Russian/English)

### UI
- Modern design with indigo/cyan accent palette
- Clean sidebar with English-only module names (no chapter numbers)
- Progress tracking with visual indicators
- Attempt history for each module test
- Responsive layout (desktop + mobile)

### Learning Mode
- Immediate explanations after each answer
- Correct/incorrect visual feedback
- Explanations reinforce understanding, not just correctness

### Progress & Export
- `localStorage` persistence across sessions
- Export formats: JSON, CSV, Markdown
- Export includes: learner name, per-module scores, attempt history with IDs, final test results, timestamps
- Each attempt is tracked with a unique ID and the set of question IDs used
- Reset button clears all progress

### Pass Threshold
- 80% on each module test and final assessment

## Files
| File | Description |
|------|-------------|
| `course.html` | Complete interactive course (single file, ~211KB) |
| `_exec_summary.md` | This document |
