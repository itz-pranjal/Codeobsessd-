# PRODUCTION.md — Bug Check & Deploy Checklist

## Project: CodeObsessed
## Maintainers: Pranjal Bhatt & Shivansh Bansal
## GitHub: https://github.com/itz-pranjal/codeobsessed

Run through this entire list before every push to GitHub.

## Local Check
- [ ] Run: npm run dev
- [ ] Homepage loads at localhost:4321
- [ ] All 11 article cards visible on homepage
- [ ] Card grid gap looks correct (not too tight)
- [ ] Logo glitch animation plays
- [ ] Click at least 2 article cards — confirm they open
- [ ] Cover image loads correctly on article page
- [ ] Quick Answer box appears below image
- [ ] Roadmap page loads at /roadmap
- [ ] Articles list page loads at /articles
- [ ] Filter buttons work (All / Beginner / Intermediate)
- [ ] About section visible in footer
- [ ] Footer shows team names and contact email
- [ ] Mobile view looks correct (resize browser to 375px wide)

## Build Check
- [ ] Run: npm run build
- [ ] Zero errors in terminal output
- [ ] Run: npm run preview
- [ ] Confirm site works in preview mode before pushing

## Git Push Steps
- [ ] git add .
- [ ] git commit -m "describe what changed"
- [ ] git push origin main
- [ ] Open Netlify dashboard — confirm deploy status is green
- [ ] Visit live URL and spot check homepage + one article
