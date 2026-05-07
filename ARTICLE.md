# ARTICLE.md — How to Write and Publish a New Article

## Who uses this file
Pranjal Bhatt, Shivansh Bansal, or any AI session
working on CodeObsessed content.

## Step 1 — Create the file
Go to: src/content/articles/
Create a new file. Name it with dashes, no spaces, no capitals.
Example: understanding-apis.md

## Step 2 — Add frontmatter at the very top
Copy this block exactly and fill in your values:

---
title: "Your Article Title Here"
description: "One sentence that summarizes what this article answers."
difficulty: "Beginner"
date: "2025-06-01"
coverImage: "https://images.unsplash.com/photo-XXXXXXXXX?w=800"
related: ["which-language-to-start", "what-is-linux"]
---

## Difficulty options (pick one exactly):
- "Beginner"
- "Intermediate"
- "Both"

## Step 3 — Write the article body
Below the frontmatter write in plain Markdown.

Use ## for section headings
Use **bold** for important terms
Use - for bullet point lists
Use > Quick Answer: your answer here
  (this renders as the highlighted Quick Answer box)

## Step 4 — Find a cover image
1. Go to https://unsplash.com
2. Search for something related to your article topic
3. Click the image you want
4. Copy the URL from your browser address bar
5. Add ?w=800 to the end
6. Paste it into the coverImage field in frontmatter

## Step 5 — Link related articles
In the related field, add the slugs (filenames without .md)
of 1 to 3 articles that are relevant.
Example: related: ["what-is-linux", "why-so-many-languages"]

## Step 6 — Preview and publish
1. Save the file
2. Run: npm run dev
3. Go to localhost:4321 and check your article appears
4. Click into it and verify image, Quick Answer, and body look right
5. When ready, follow PRODUCTION.md checklist to push live
