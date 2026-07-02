# FRCA MTF Quiz — 1000 Primary & Final FRCA MCQs

A self-contained, single-file quiz web app rebuilt from the source PDF
*1000 Practice MTF MCQs for the Primary and Final FRCA*.

## Files
- **index.html** — the entire app (HTML + CSS + JS + all 1000 questions embedded). No server or build step needed; open it directly or host it.
- **questions_data.json** — the extracted question data (for reference / reuse). Not required by index.html (data is already embedded).

## What it contains
- **1000 questions**, each with a stem, 5 True/False statements, the answer key, and **one full explanation block** (the book's real "Answers" text — not duplicated per option, not truncated).
- Physiology (150), Anatomy (150), Pharmacology (150), Physics & Equipment (150), Clinical Anaesthesia (400).

## Structure
- **Physiology / Anatomy / Pharmacology / Physics** → thematic subtopics → sets of 10 questions.
- **Clinical Anaesthesia** → 20 batches of 20 questions (Batch 1 = Q1–20 … Batch 20 = Q381–400).
- Extras: Random 20 (mixed), Review incorrect, Bookmarks, per-question progress saved in the browser (localStorage).

## Deploy to GitHub Pages (your existing repo gopitherobot/frca_quiz)
1. Replace the old `index.html` in the repo with this `index.html`.
2. Commit & push to the `main` branch.
3. Pages will update at https://gopitherobot.github.io/frca_quiz/ within a minute.

(You can drag-drop the file in GitHub's web UI: open the repo → click `index.html` → the pencil/⋯ → *Upload files* / *Edit* → paste or replace → Commit.)
