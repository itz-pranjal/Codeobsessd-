# ARTICLE.md — Writing and Publishing Articles

Managed by MASTER.md. Follow every step in order.

## Step 1 — Create the File
Go to: src/content/articles/
Create a new file. Use only lowercase letters and dashes.
No spaces. No capital letters.
Good example: understanding-apis.md
Bad example: Understanding APIs.md

## Step 2 — Copy This Frontmatter Template

---
title: "Your Article Title"
description: "One sentence that answers the question directly."
difficulty: "Beginner"
date: "2025-06-01"
author: "Pranjal Bhatt"
coverImage: "https://images.unsplash.com/photo-XXXXX?w=800&auto=format&fit=crop"
related: ["which-language-to-start", "what-is-linux"]
featured: false
---

## Difficulty Values (copy exactly, spelling matters)
"Beginner" or "Intermediate" or "Both"

## Author Values
"Pranjal Bhatt" or "Shivansh Bansal"

## Step 3 — Find a Cover Image
1. Visit https://unsplash.com
2. Search a topic related to your article
3. Click any image
4. Copy the URL from the browser address bar
5. Add ?w=800&auto=format&fit=crop to the end
6. Paste into coverImage in the frontmatter

## Step 4 — Write the Article Body
Write below the closing --- of the frontmatter.
Use standard Markdown syntax only.

> Quick Answer: Write your one-paragraph direct answer here.
This becomes the highlighted Quick Answer box on the page.

## for section headings
**bold** for important terms
- bullet lists for steps or comparisons

## Step 5 — Add Related Articles
In the related field, add 1 to 3 article slugs.
A slug is the filename without .md
Example: related: ["what-is-linux", "degree-vs-experience"]

## Step 6 — Preview (Manual Step)
Start the dev server yourself, then check:
  - Article appears in the /articles list
  - Article card shows correct image
  - Clicking the card opens the article
  - Quick Answer box appears
  - Related articles show at bottom
  - Reading time looks correct

## Step 7 — Publish
When preview looks correct, follow PRODUCTION.md.
