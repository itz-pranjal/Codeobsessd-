# MASTER.md — CodeObsessed Project Controller

## What This File Does
MASTER.md is the single entry point for managing this project.
It tells you which file to open for each task.
Read this first. Then open the file you need.

## Project Identity
- Name: CodeObsessed
- Mission: Honest answers for every coder, beginner to pro.
- Founders: Pranjal Bhatt & Shivansh Bansal
- Based in: India
- Contact: pranjalbhatt2008@gmail.com
- GitHub: https://github.com/itz-pranjal/codeobsessed
- Live URL: (add after first Netlify deploy)

## Tech Stack
- Framework: Astro (static site)
- Styling: Vanilla CSS with CSS variables
- Content: Markdown (.md) files in src/content/articles/
- Hosting: Netlify (auto-deploys from GitHub main branch)

## File Directory
| File | Purpose | Open when... |
|------|---------|-------------|
| ARTICLE.md | Writing new articles | You want to publish something |
| PRODUCTION.md | Bug checks and deploy | Before pushing to GitHub |
| CLAUDE.md | AI context file | Starting an AI coding session |
| MASTER.md | This file | You need to find anything |

## Workflows At a Glance
Writing a new article → follow ARTICLE.md
Fixing a bug with AI help → open CLAUDE.md, paste into AI
Ready to go live → follow PRODUCTION.md
Forgot where something is → read MASTER.md (here)

## Important Rules
- Never run npm run dev from these files — do that yourself
- All articles live in src/content/articles/ as .md files
- All styling uses CSS variables defined in BaseLayout.astro
- Theme and font choices are saved per-device in localStorage
- MatrixRain animation color reads from CSS variable --accent

## Current Articles (15)
which-language-to-start, what-software-do-devs-use,
how-do-coders-share-code, how-much-maths-for-coding,
will-ai-take-our-jobs, future-programming-language,
why-so-many-languages, what-is-linux, is-leetcode-a-must,
degree-vs-experience, how-to-study-roadmap,
what-projects-to-build, tutorial-hell-to-projects,
recursion-vs-iteration, demotivated-after-leetcode

## Adding a New Article
See ARTICLE.md for full instructions.
Short version: create a .md file in src/content/articles/
with correct frontmatter. The site picks it up automatically.
