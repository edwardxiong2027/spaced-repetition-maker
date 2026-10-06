---
name: spaced-repetition-maker
description: Convert trusted notes into compact recall cards that test one idea without giving away the answer. Use when: You need a study deck from class notes, a book, or a technical guide.
license: MIT
metadata:
  author: Edward Xiong
  version: 1.0.0
---

# Spaced Repetition Maker

Convert trusted notes into compact recall cards that test one idea without giving away the answer.

## When to use

You need a study deck from class notes, a book, or a technical guide.

## Workflow

1. Keep cards grounded in the provided material.
2. Test a single distinction or retrieval cue per card.
3. Add a source pointer and answer rationale.
4. Mark ambiguous cards for revision.

## Output

Return a usable result for the user’s actual task. State assumptions, evidence, and uncertainty where they affect the result. Keep the output format suited to the job: working HTML, a storyboard, a decision brief, a draft, code, or a short answer. Do not claim that a result was tested, published, or verified unless that action was completed.

## Starter prompt

> Turn these notes into [number] high-value spaced-retrieval cards. Use the supplied notes only. Each card must test one idea, have a short answer, and include a source heading/page if available. Mix recall, explain-why, and compare/contrast. Avoid trivia and cloze cards that reveal the answer. Add a one-line rationale and tag each card by topic. Mark any card whose answer is ambiguous or unsupported; do not silently guess.

## Quality check

Before delivery, check that the result answers the stated need, follows the requested format, and makes any important limitation visible. Invite the user to adjust the result when taste or judgment belongs to them.
