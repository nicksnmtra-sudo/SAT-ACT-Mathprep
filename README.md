# Graphite Math: ACT & SAT Math Prep

A single-page, no-build website for ACT and SAT Math practice.

## Features
- SAT / ACT mode and target score level (questions adapt to the level)
- 12 topic sections, each with a worked example and 3 solving approaches (algebra, Desmos, test the choices)
- 5 full practice tests per exam (SAT: 54 questions, ACT: 60 questions), easy to hard
- Endless question bank generated from templates
- Desmos Lab: regression guide plus a small line-of-best-fit calculator
- Rule-based tutor tab

## Project structure
- `index.html`: the whole app (HTML, CSS, JavaScript)
- `netlify.toml`: Netlify settings
- `.gitignore`

## Run locally
Open `index.html` in a browser. No install needed.

## Deploy on Netlify
1. Push this repo to GitHub.
2. In Netlify: Add new site, Import an existing project, pick this repo.
3. Build command: leave empty. Publish directory: `.`
4. Every `git push` redeploys the site.

## Add questions or topics
In `index.html`, find the `G` object. Each topic is one block, for example `Linear:{...}`.
Copy a block, rename it, and change the numbers and wording. New topics appear automatically in Topics and Question Bank.

## Notes
- Questions are original, generated from templates. Do not paste copyrighted workbook questions into this repo.
- Not affiliated with College Board, ACT, or Desmos.
