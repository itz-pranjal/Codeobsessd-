# PRODUCTION.md — Bug Check and Deploy Checklist

Managed by MASTER.md. Run through this before every push.

## Before You Start
Make sure you have already previewed the site manually.
This file does NOT start the dev server.
Start it yourself, check everything, then use this checklist.

## Visual Checklist (check in browser manually)

### Homepage
- [ ] Search bar visible and centered in hero
- [ ] Typing in search bar filters article cards live
- [ ] Hashtag pills visible above footer
- [ ] Clicking a hashtag fills search and filters cards
- [ ] MatrixRain canvas visible on desktop hero
- [ ] MatrixRain hidden on mobile view
- [ ] "LATEST ARTICLES" section shows all article cards
- [ ] Article card images all load (no broken images)
- [ ] Fallback placeholder shows if an image fails

### Navigation
- [ ] Logo shows "codeobsessed_" with glitch animation
- [ ] Underscore in logo blinks
- [ ] All nav links work: Home Articles Roadmap Settings
- [ ] Subscribe button opens email client correctly
- [ ] Mobile hamburger menu appears under 640px width
- [ ] Hamburger menu opens and closes correctly

### Articles
- [ ] /articles page loads with full card grid
- [ ] Filter buttons work: All Beginner Intermediate
- [ ] Clicking a card opens the correct article
- [ ] Cover image loads on each article page
- [ ] Quick Answer box appears below image
- [ ] Reading progress bar fills as you scroll
- [ ] Related articles section shows at bottom
- [ ] Prev/Next buttons navigate correctly
- [ ] Back to top button appears after scrolling down

### Settings
- [ ] All 4 theme options shown as cards
- [ ] Clicking a theme changes colors site-wide immediately
- [ ] Theme choice persists after page reload
- [ ] Theme is device-local only (not shared across devices)
- [ ] All font options shown
- [ ] Clicking a font changes body font immediately
- [ ] Font choice persists after page reload

### Other Pages
- [ ] /roadmap loads and step cards display correctly
- [ ] Footer shows team names and contact email
- [ ] About section visible in footer

## Build Check (run these commands yourself)
  npm run build
  (check terminal for zero errors)
  npm run preview
  (spot check homepage and one article in preview)

## Git Push Steps (run these yourself)
  git add .
  git commit -m "brief description of what changed"
  git push origin main

## After Push
- [ ] Open Netlify dashboard
- [ ] Confirm deploy status shows as published (green)
- [ ] Visit live URL
- [ ] Check homepage and one article on live site
