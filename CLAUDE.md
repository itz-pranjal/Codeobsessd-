# CLAUDE.md — AI Session Context File

Paste this entire file into any AI coding session before
asking for help. This gives the AI full project context.

## Project
Name: CodeObsessed
Type: Static blog site, documentation style
Mission: Honest answers for every coder, beginner to pro.

## Team
Pranjal Bhatt — Co-founder (GitHub: itz-pranjal)
Shivansh Bansal — Co-founder
Contact: pranjalbhatt2008@gmail.com
Location: India

## Stack
Framework: Astro (static, no SSR)
Styling: Vanilla CSS, CSS custom properties (variables)
Content: Markdown files with frontmatter
Fonts: Playfair Display (headings) + Inter (body)
        loaded from Google Fonts in BaseLayout.astro
Hosting: Netlify via GitHub auto-deploy
No TypeScript. No CSS frameworks. No backend.

## Key CSS Variables (defined in BaseLayout.astro :root)
--accent         main accent color
--accent-dim     dim version for backgrounds
--bg-base        page background
--bg-card        card background
--text-primary   main text
--text-muted     secondary text

## Theme and Font System
Themes and fonts are client-side only using localStorage.
Keys: "co-theme" and "co-font"
Applied in BaseLayout.astro before paint to prevent flash.
Settings page at /settings handles user selection.
Each device has its own independent preference.

## Folder Structure
src/components/    reusable .astro components
src/layouts/       BaseLayout.astro, ArticleLayout.astro
src/pages/         index, articles, roadmap, settings
src/content/articles/  all article .md files

## Article Frontmatter Fields
title, description, difficulty, date, author,
coverImage, related, featured

## Adding Articles
Drop a new .md file in src/content/articles/
Correct frontmatter is all that is needed.
Site picks it up automatically with no code changes.

## DO NOT ask the AI to run npm run dev
The development server is always started manually.
The AI can suggest build and preview commands but
should never instruct anyone to start the dev server.

## Current Article Slugs
which-language-to-start
what-software-do-devs-use
how-do-coders-share-code
how-much-maths-for-coding
will-ai-take-our-jobs
future-programming-language
why-so-many-languages
what-is-linux
is-leetcode-a-must
degree-vs-experience
how-to-study-roadmap
